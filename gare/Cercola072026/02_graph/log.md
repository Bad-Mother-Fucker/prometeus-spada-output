# Log — graph-builder

Registro append-only delle operazioni di ingest/re-ingest sul knowledge graph.

## [2026-07-19] ingest-start | Intervento di efficientamento energetico Istituto Comprensivo "De Luca Picione Caravita" (Cercola) | elenco elaborati: trovato

ELENCO ELABORATI.xlsx letto con successo (parsing diretto XML del formato xlsx, senza libreria esterna).
Mappa codice→descrizione ufficiale costruita per 35 elaborati elencati (R.xx, EG.xx, IT.xx, C.xx, S.xx).
5 elaborati elencati risultano MANCANTI dal filesystem: EG.08, EG.08.1, EG.09, IT.01, IT.02 — segnalati
come `missing`, non processabili, da NON inventare.

Censimento filesystem: 48 file in 00_input/ (elaborati + disciplinare + p7m vuoto). Riconciliazione con
`00_input/_manifest_input.md` (già completo): nessun file orfano rispetto al manifest. 7 gruppi di
duplicati identificati e verificati per contenuto (non solo dimensione): disciplinare di gara, verbale
validazione, verbale verifica → duplicati puri (MD5 identico); C.01, C.05, COMPUTO OPERE OPZIONALI →
stessa dimensione ma MD5 diverso, contenuto testuale verificato IDENTICO (doppio export, non revisione).

Classificazione in 4 liste (dettaglio completo in `00_input/_manifest_input.md` sezione "Aggiornamento
graph-builder Fase 0-2"): ECONOMICI (9 doc, incl. COMPUTO OPERE OPZIONALI senza codice), TESTUALI (12 doc),
TAVOLE (14 presenti su 17 elencate), ALTRO (8 doc amministrativi).

Estrazione testi eseguita direttamente (Read tool su PDF, non document-preprocessor — invocazione diretta
non prevede sub-agenti): 15 documenti estratti in `01_extracted/text/` con status verificato/parziale
(vedi `01_extracted/extraction_log.md` per dettaglio pagina-per-pagina). Documenti economici (C.01-C.07,
COMPUTO OPERE OPZIONALI) tutti processati almeno parzialmente. Testuali: R.01, R.03, R.04 completi;
S.03, S.05 completi; S.04 parziale (20/51 pag.). R.02, R.02.1, R.05, R.06, S.01, S.02 non ancora estratti
(disponibili per estrazione nei round successivi o on-demand via pdf-reader in Fase 2 criteri).

2 contraddizioni rilevate in questa fase (dettaglio in manifest e nei file estratti):
1. Importi C4/C5 (criteria_matrix.md: 67.000/46.000 €) vs somma voci computo opere opzionali (73.000/40.000 €).
2. EPgl,nren stato di progetto: R.01 dichiara 19,9614 kWh/m²anno, R.03 (APE) dichiara 25,8212 kWh/m²anno.

Prezzario di riferimento dedotto dai codici tariffa (`CAM25_...`): Regione Campania 2025. Da riportare in
PROJECT_CONFIG.json (campo attualmente vuoto).

Struttura cartelle 02_graph/ creata: nodes/, synthesis/, proposals/. Nessuna pagina nodo scritta in questa
invocazione (riservato alle Fasi A/B/C successive).

## [2026-07-19] contraddizioni (Fase E) | Intervento di efficientamento energetico Istituto Comprensivo "De Luca Picione Caravita" (Cercola)

Fase E eseguita sulle pagine nodo scritte dalle Fasi A/B (round 1). 5 contraddizioni confermate e
documentate su tutte le pagine pertinenti (2 gia' complete dal round 1, verificate; 2 completate in
questa fase con nota simmetrica mancante; 1 gia' completa). Nessuna nuova contraddizione economica
rilevata: incrocio C.01/C.02/C.03/C.04/C.05/C.06/C.07 tutto coerente (importo lavori, manodopera,
oneri sicurezza coincidono esattamente su tutti i documenti economici). Azioni di questa fase:
aggiunta sezione "ATTENZIONE — Contraddizione: esclusione caldaie a gas" a
`[[R.01_Relazione_Generale_e_Tecnica_Illustrativa]]` (mancava, presente solo su R.02.1/R.04/S.04);
aggiunta sezione "ATTENZIONE — Contraddizione: Tilt/Azimut" a
`[[R.04_Relazione_Energetica_Ex_L10]]` (mancava, presente solo su R.05) per rendere simmetrico il
cross-reference.

Righe da includere nella sezione "Orfani e contraddizioni" di `02_graph/index.md` (invocazione 8):

CONTRADDIZIONE: Ripartizione opere opzionali C4/C5 — `03_criteria/criteria_matrix.md` e
`PROJECT_CONFIG.json` dichiarano C4 (B1, voci 01,02,04) = € 67.000,00 e C5 (B2, voci 03,05,06,07,08)
= € 46.000,00; [[COMPUTO_OPERE_OPZIONALI]] (fonte contabile verificata voce per voce) da' invece
C4 = € 73.000,00 e C5 = € 40.000,00 (il totale € 113.000,00 coincide in entrambi i casi — la
contraddizione riguarda solo la ripartizione, non il totale). Dettaglio in
[[COMPUTO_OPERE_OPZIONALI]] ed `economic_framework.md`. — verifica manuale richiesta prima
dell'analisi dei criteri C4/C5

CONTRADDIZIONE: EPgl,nren stato di progetto — [[R.01_Relazione_Generale_e_Tecnica_Illustrativa]] §8
dichiara EPgl,nren post-operam = 19,9614 kWh/m²anno (superficie 2.723,5 mq); [[R.03_Attestato_di_Prestazione_Energetica]]
(APE) dichiara per lo stesso stato di progetto EPgl,nren = 25,8212 kWh/m²anno (superficie 2.643,38
mq) — differenza ~30% relativa, entrambi classe A4/nZEB, entrambi `confidence: verificato`.
Dettaglio in `02_graph/synthesis/prestazione_energetica_e_contraddizioni.md`. — verifica manuale
richiesta prima di formulare proposte quantitative sul risparmio energetico nel criterio C1

CONTRADDIZIONE: Esclusione caldaie a gas — [[R.02.1_Relazione_DNSH]] dichiara nella checklist
Art.5 Item 0 "e' stata verificata l'esclusione dall'intervento delle caldaie a gas? → SI", ma
[[R.01_Relazione_Generale_e_Tecnica_Illustrativa]] (2 caldaie a condensazione ~33,80 kW cad.),
[[R.04_Relazione_Energetica_Ex_L10]] (caldaia a metano 194,80 kW) e
[[S.04_Piano_Sicurezza_Coordinamento]] (fase "installazione caldaia per impianto termico")
confermano indipendentemente la presenza di caldaie nell'impianto di progetto. Rilevante per
l'ammissibilita' PNRR (Regime 1). Dettaglio in `02_graph/synthesis/prestazione_energetica_e_contraddizioni.md`.
— verifica manuale richiesta

CONTRADDIZIONE: CIG frontespizio difforme — [[R.02_Relazione_CAM]] e [[R.02.1_Relazione_DNSH]]
riportano in frontespizio CIG B9C7EAF75F, diverso dal CIG di gara BC3ECFAA55 in
`PROJECT_CONFIG.json` (stesso CUP G13C25000920001 su entrambi). Non altera l'oggetto tecnico delle
relazioni. — verifica manuale richiesta con la stazione appaltante

CONTRADDIZIONE: Tilt/Azimut falda fotovoltaica nuova — [[R.04_Relazione_Energetica_Ex_L10]]
dichiara Tilt 30°/Azimut SUD_OVEST per la falda nuova (36,00 kWp), [[R.05_Relazione_Impianto_Fotovoltaico]]
dichiara Tilt 15,0°/Azimut 0,0° (Sud) per la stessa falda (potenza e superficie coerenti tra i due
documenti). Discrepanza minore, non bloccante per C3 secondo `02_graph/synthesis/impianto_fotovoltaico.md`.
— verifica manuale raccomandata (lettura tavole EG.05.2/EG.07 o chiarimento progettista)

Nessuna contraddizione economica aggiuntiva rilevata oltre a quella C4/C5 gia' nota: i cinque
documenti economici (C.01, C.04, C.05, C.06, C.07) sono stati confrontati incrociando i tre importi
chiave (lavori € 915.809,83, manodopera € 180.457,45, oneri sicurezza € 39.073,96) e coincidono
esattamente su tutte le fonti.

## [2026-07-19] ingest | Intervento di efficientamento energetico Istituto Comprensivo "De Luca Picione Caravita" (Cercola) — 43 create, 6 riscritte, 12 orfani, 5 contraddizioni

Fasi 4-5 (invocazione 8/8, round 2 completato). Riepilogo cumulativo dell'intera build (prima
costruzione del grafo — 02_graph/ gitignored, ricreato da zero):

- **43 pagine create** (prima ingestione, non re-ingest): 39 pagine nodo documento
  (`02_graph/nodes/`), `02_graph/scope.md`, `02_graph/economic_framework.md`, 2 pagine di sintesi
  (`02_graph/synthesis/impianto_fotovoltaico.md`, `02_graph/synthesis/prestazione_energetica_e_contraddizioni.md`).
- **6 pagine riscritte** (arricchimento frontmatter, non creazione): `03_criteria/criteria/criterion_C1.md`
  … `criterion_C6.md`, campo `supported_by` popolato da Fase F con incrocio su tutte le 39 pagine
  nodo; `modification_limits`/`fuori_scope_risks` presenti dove gia' compilati da `disciplinare-analyst`,
  altrimenti `[]` con commento `# da compilare`.
- **12 orfani** (`supports_criteria` vuoto): 7 legittimi/intenzionali (C.05, C.06, C.07, R.02.1,
  S.03, S.04, S.05 — motivazione per documento in `02_graph/index.md` sezione "Orfani e
  contraddizioni") + 5 non risolvibili per file assente dal filesystem (EG.08, EG.08.1, EG.09,
  IT.01, IT.02 — elencati nell'elenco elaborati ma mai caricati in `00_input/`).
- **5 contraddizioni** documentate (Fase E, dettaglio completo gia' appeso all'entry precedente di
  questo log): ripartizione opere opzionali C4/C5, EPgl,nren R.01 vs R.03, esclusione caldaie gas
  R.02.1 vs R.01/R.04/S.04, CIG difforme R.02/R.02.1, tilt/azimut fotovoltaico R.04 vs R.05.
- **124 archi documento-documento** (`related_documents`) su tutte le 39 pagine nodo (Fase D).
- **index.md rigenerato per intero** (non accodato): sezioni pagine speciali, pagine di sintesi,
  criteri e documenti collegati (con warning espliciti su C4/C5 supporto minimo e C6 zero
  documenti), documenti per sezione, orfani e contraddizioni, problemi di lint aperti,
  correzioni testuali applicate, statistiche.
- **Retry di questa invocazione**: il tentativo precedente si era interrotto a meta' della
  correzione dei wikilink in `scope.md`. Verifica in questa invocazione: `scope.md` ed
  `economic_framework.md` risultavano gia' completamente corretti (nessun placeholder
  `PROJECT_CONFIG.gara.nome` residuo, nessun wikilink malformato verso `economic_framework`,
  nessun wikilink abbreviato non risolto). L'unico lavoro residuo era in `index.md` stesso: la
  sezione "Correzioni testuali applicate" del tentativo precedente documentava le forme errate
  usando la sintassi `[[...]]`, generando 4 falsi positivi `index-nodo-fantasma` nel lint —
  riscritta in questa invocazione senza doppie parentesi quadre sulle forme errate.

## [2026-07-19] lint | 12 orfani, 5 contraddizioni, 0 archi mancanti, 0 errori versione

`node scripts/graph/graph_lint.js` eseguito dopo il rebuild di index.md: 26 ERROR, 14 WARN,
exit code 1. Scomposizione e giudizio di merito:

- 12 ERROR `orfano` — tutti motivati (vedi entry ingest sopra e `02_graph/index.md`): nessuna
  azione correttiva necessaria.
- 6 ERROR `frontmatter-campo` (campo `type` mancante su `criterion_C1.md`…`criterion_C6.md`) —
  fuori mandato di `graph-builder` (pagine di `disciplinare-analyst`, tocca solo i campi previsti
  dallo schema). Segnalato per manutenzione futura.
- 8 ERROR `index-nodo-fantasma` — falsi positivi accertati: `scripts/graph/graph_lint.js` (Check 5)
  risolve i wikilink dell'index solo contro `02_graph/nodes/` e non copre il prefisso `criterion_`
  ne' `02_graph/synthesis/`. Verificato manualmente: i file target
  (`criterion_C1.md`…`criterion_C6.md`, `impianto_fotovoltaico.md`,
  `prestazione_energetica_e_contraddizioni.md`) esistono tutti. Nessuna correzione al grafo;
  segnalato come limite dello script condiviso, non modificato in questa invocazione (fuori
  mandato Fasi 4-5).
- 14 WARN `archi-solo-ereditati` — tutte le 14 tavole gia' segnalate in `02_graph/index.md`, sola
  eredita' di sezione senza lettura del contenuto grafico: coerente con la policy di Fase C, da
  riaprire on-demand via `drawing-reader` in fase di analisi criteri.
- Check 3 (archi doc→doc mancanti sospetti): 0 — verificato che tutte le 39 pagine nodo hanno
  almeno una riga `related_documents` popolata (Fase D, 124 archi totali).
- Check 4 (versioni multiple senza `is_latest`): 0 — ogni `version_group` e' un singleton con
  `is_latest: true`; nessuna revisione multipla rilevata (i 3 gruppi di file "gemelli" — C.01,
  C.05, COMPUTO_OPERE_OPZIONALI — sono duplicati di export PDF a MD5 diverso ma contenuto
  identico, non versioni: la regola `version_group` non si applica, documentato nei rispettivi
  nodi).
- Check 5 (scope.md/economic_framework.md): entrambe presenti, `confidence: parziale` e
  `verificato` rispettivamente, nessun campo interamente `TBD`.

Nessun ERROR residuo rappresenta un difetto reale non motivato del grafo.

## [2026-07-20] re-ingest | C.01 Computo Metrico Estimativo + C.02 Elenco Prezzi Unitari — 2 pagine nodo riscritte, 0 create, 0 contraddizioni nuove

Re-ingest mirato, non ricostruzione del grafo. Innesco: riestrazione integrale dei due elaborati
economici, prima disponibili solo parzialmente.

- `01_extracted/text/sub_15175049978810242486_C.01 - COMPUTO METRICO ESTIMATIVO.md` — da pag. 1-3+24-25 a 26/26 pagine, 101 voci
- `01_extracted/text/sub_12901568693736854610_C.02 - ELENCO PREZZI UNITARI.md` — da pag. 1-2 a 10/10 pagine, 98 voci

Pagine nodo riscritte (rewrite-not-append, nessun altro nodo toccato):

- `02_graph/nodes/C.01_Computo_Metrico_Estimativo.md` — `status: estratto` + `estrazione: integrale`;
  `confidence` da `parziale` a `verificato`; `cost_summary.voci_count` da TBD a 101 (0 senza codice,
  0 non parsate, 98 codici distinti, 3 usati due volte); totale ricostruito € 915.809,83 = totale
  stampato, scostamento € 0,00. Aggiunti al frontmatter il blocco `famiglie_codice` e, nel corpo, la
  tripartizione dei codici, la tabella completa dei 12 nuovi prezzi, gli aggregati per capitolo su
  infissi/isolamento/fotovoltaico e le 10 voci di maggiore importo (69,7% dell'importo lavori).
- `02_graph/nodes/C.02_Elenco_Prezzi_Unitari.md` — `status: estratto` + `estrazione: integrale`;
  `confidence` da `parziale` a `verificato`; `voci_count` da TBD a 98 (98/98 con codice e prezzo);
  `prezzario_riferimento: Regione Campania 2025` esplicitato nel frontmatter. Priorita' verso C1/C2/C3
  alzata da `bassa` a `media` con `confidence: verificato` (la motivazione precedente era
  "estrazione parziale", non piu' vera).

Verifiche incrociate (esito: nessuna contraddizione):

- C.01 totale € 915.809,83 = voce A.1 di C.07 Quadro Economico = `importo_lavori_eur` in
  `02_graph/economic_framework.md`. Invariato rispetto al round precedente.
- C.02 → C.01: i 98 codici sono tutti usati nel computo e i 98 prezzi unitari coincidono uno a uno,
  0 scostamenti.
- Riconciliazioni aritmetiche esatte sulle sottocategorie dei criteri: 001 isolamento verticale
  € 109.542,62, 002 isolamento orizzontale € 165.770,44, 003 infissi € 158.811,91, 006 fotovoltaico
  € 57.139,96. Marcate come riconciliazione aritmetica, NON come attribuzione di categoria stampata
  (PriMus non stampa la categoria per singola voce nel corpo del computo).

Dato strutturale nuovo registrato in entrambe le pagine e in `02_graph/index.md` — tripartizione dei
codici tariffa, perimetro del price-gap check: `CAM25_*` 73 righe / € 608.462,99 / 66,44%
(confrontabili col Prezzario Campania 2025); `NP.01`-`NP.12` 12 righe / € 260.184,34 / 28,41% (non
confrontabili, rimandano a C.03); codici a sei cifre + lettera 16 righe / € 47.162,50 / 5,15% (fuori
schema regionale, listino di provenienza TBD).

Archi: +6 righe `related_documents` (124 → 130). Su C.01: `references` verso C.02 (coincidenza 1:1
dei 98 prezzi) e verso C.03 (le 12 voci NP riportano "(VEDI ANALISI DEI PREZZI)"). Su C.02:
`referenced_by` da C.01, `references` verso C.03, `stesso_lotto` verso C.06 e C.07. Reciproci sui
nodi C.03/C.06/C.07 NON scritti: fuori dal mandato del re-ingest mirato (C.03 e C.04 citavano gia'
C.01/C.02 nel corpo).

Aperto / non fatto in questa invocazione (fuori mandato):

- `02_graph/scope.md` — la riga "dettaglio voce-per-voce ~90+ voci: TBD da estrarre" non e' piu' vera.
  Segnalato in `02_graph/index.md`, file non riscritto.
- `03_criteria/criteria/criterion_C1|C2|C3.md` — `supported_by` elenca ancora C.02 a `priority: bassa`
  con motivazione "estrazione parziale". Da riallineare con una prossima Fase F.
- `PROJECT_CONFIG.json → gara.prezzario_riferimento` — ancora non compilato; il valore verificato e'
  `{ regione: "Campania", anno: "2025" }`.
