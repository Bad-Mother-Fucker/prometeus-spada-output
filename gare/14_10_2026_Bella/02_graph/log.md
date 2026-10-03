# Log knowledge graph

Registro append-only delle operazioni di `graph-builder` sul grafo `02_graph/`.
Formato grep-able: una riga `## [YYYY-MM-DD] operazione | ...` per voce; dettagli in elenco sotto.

## [2026-10-03] ingest-start | Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ) | elenco elaborati: trovato

- Invocazione 1 di 8 (Fasi 0-2). Nessun `02_graph/index.md` preesistente: grafo costruito da zero.
- Cartelle create: `02_graph/nodes/`, `02_graph/synthesis/`, `02_graph/proposals/`.
- Elenco elaborati: `G-00-ESEC-01` «ELENCO ELABORATI (secondo il DLgs 36/2023)», rev. aprile 2026, 2 pp. — originale `00_input/p7m/progetto.esecutivo.a.base.di.gara/pdf firmati/G_00_ESEC_01_ELENCO ELABORATI.pdf.p7m`, letto da `01_extracted/p7m_extracted/G-00-ESEC-01_ELENCO_ELABORATI.pdf`. 40 elaborati in 7 gruppi (Documenti generali G-00…G-11, Relazioni specialistiche RS-00…03, Inquadramento IT-00…03, Rilievo RIL-00…02, Progetto architettonico PA-00…05, Progetto impianti PI-00…06, Progetto sicurezza SIC-00…03).
- Mappa `{codice: descrizione ufficiale}` riportata nella colonna «descrizione ufficiale» di `02_graph/_census.md`. Nodi di elaborati presenti in elenco: descrizione da elenco; nodi fuori elenco: descrizione da nome file (`confidence: inferito` per i dati presi solo dal nome file).
- Convenzione sezioni di progetto: per prefisso del codice (G, RS, SIC, IT, RIL, PA, PI, VVF-PI), non 08/09.

## [2026-10-03] census | 56 file in 00_input | ECONOMICI 8, TESTUALI 14, TAVOLE 30, ALTRO 4 | liste in 02_graph/_census.md

- `find 00_input -type f \( -iname "*.pdf" -o -iname "*.p7m" \)` → 56 file (52 `.p7m`, 4 `.pdf`).
- ECONOMICI: G-01-ESEC-01, G-01-ESEC-02, G-02-ESEC-01, G-03-ESEC-01, G-04-ESEC-01, G-04-ESEC-02, G-05-ESEC-01, SIC-03-ESEC-01
- TESTUALI: G-00-ESEC-01, G-06-ESEC-01, G-06-ESEC-02, G-07-ESEC-01, G-08-ESEC-01, G-09-ESEC-01, G-10-ESEC-01, G-11-ESEC-01, RS-00-ESEC-01, RS-01-ESEC-01, RS-02-ESEC-01, RS-03-ESEC-01, SIC-00-ESEC-01, SIC-01-ESEC-01
- TAVOLE: SIC-02-ESEC-01, IT-00-ESEC-01, IT-01-ESEC-00, IT-02-ESEC-00, IT-03-ESEC-00, RIL-00/01/02-ESEC-01, PA-00…05-ESEC-01, PI-00-ESEC-01, PI-00a-ESEC-01, PI-01…06-ESEC-01, VVF-PI-01-00 … VVF-PI-08-00
- ALTRO: COM-PZ.REGISTRO-UFFICIALE.2026.0007341, disciplinare.di.gara, bando, norme.tecniche
- Gruppi di versione: G-01, G-04, G-06 → `is_latest: true` su ESEC-02, `false` su ESEC-01 (regola 2 graph-schema: numero di revisione; confermata dal cartiglio mag. 2026 vs apr. 2026).

## [2026-10-03] reconcile-manifest | orphan_input: 0 | missing: 0

- Filesystem (56) ↔ `00_input/_manifest_input.md` (56 righe): corrispondenza completa per percorso + nome file.
- Tutti i 52 PDF sbustati indicati nel manifest esistono in `01_extracted/p7m_extracted/`.

## [2026-10-03] reconcile-elenco | orphan_input: 16 | missing: 0

- missing | nessuno — IT-01/IT-02/IT-03-ESEC-01 in elenco = file `IT_0x_ESEC_00_…` (ESEC-00 nel nome file, ESEC-01 nel cartiglio): stesso elaborato
- orphan_input | G-01-ESEC-02 | revisione mag. 2026 successiva all'elenco (cartella «Progetto esecutivo_Integrazione 2026»)
- orphan_input | G-04-ESEC-02 | revisione mag. 2026 successiva all'elenco
- orphan_input | G-06-ESEC-02 | revisione mag. 2026 successiva all'elenco
- orphan_input | PI-00a-ESEC-01 | tavola non firmata, richiamata dal disciplinare per il sub-criterio C2.1
- orphan_input | VVF-PI-01-00 … VVF-PI-08-00 | 8 tavole della Pratica VV.F. 21079 (firma Gennaro Loperfido, 04/02/2026)
- orphan_input | COM-PZ.REGISTRO-UFFICIALE.2026.0007341 | protocollo Comando VV.F. Potenza, parere favorevole 20/04/2026
- orphan_input | disciplinare.di.gara, bando, norme.tecniche | documenti di gara/piattaforma, non elaborati di progetto
- Incongruenza di denominazione: PI-02-ESEC-01 («classi di REAZIONE al fuoco» in elenco, «RESISTENZA» nel nome file).

## [2026-10-03] extract-batch | 23 estratti, 0 saltati (gia' presenti), 0 tavole saltate | errori: 0

- Estrazione Fase C (procedura document-preprocessor) eseguita da graph-builder: tutte le liste ECONOMICI e TESTUALI (comprese G-01/G-04/G-06-ESEC-01 superate) + COM-PZ…0007341.
- Output in `01_extracted/text/[codice]_[descrizione].md` con marcatori `<!-- p. N -->`; manifest aggiornato (Stato → estratto, File estratto); dettaglio per documento in `01_extracted/extraction_log.md`.
- Estrazione parziale da segnalare in Fase B: RS-01-ESEC-01 pp. 3-5 solo immagini; G-07-ESEC-01 prevalentemente foto; G-10-ESEC-01 p. 227 vuota.
- SIC-00-ESEC-01 (PSC, 260 pp.) include copie interne di cronoprogramma (pp. 85-87), costi sicurezza (pp. 256-258) e, verosimilmente, layout di cantiere (pp. 259-260): da confrontare con SIC-01/SIC-03 in Fase E.
- Testi disponibili in `01_extracted/text/`: 25 (23 nuovi + disciplinare + bando). Non estratti: 30 tavole, norme.tecniche.

## [2026-10-03] ingest-fase-C | tavole | 30 create, 0 riscritte, 3 orfani potenziali, 0 contraddizioni

- Invocazione Fase C (round 1, in parallelo con A e B). Scope: lista TAVOLE di `02_graph/_census.md` (30). Nessuna pagina tavola preesistente: tutte create. `index.md` non toccato (lo rigenera l'invocazione 8).
- Pagine leggere in `02_graph/nodes/[codice]_[descrizione].md`: `subtype: tavola`, `status: non_estratto`, `confidence: inferito`, `related_documents: []` (lo popola la Fase D), descrizione da elenco G-00 (TBD per le 9 tavole fuori elenco: PI-00a e VVF-PI-01…08). Nessuna estrazione di contenuto: solo il cartiglio (pdftotext p. 1, `-l 1`) per confermare oggetto, codice, data e scala.
- `supports_criteria` assegnato per argomento (titolo ufficiale + testo dei criteri in `03_criteria/`), un arco per criterio con sub-criteri nella `reason`. Tutti gli archi `confidence: inferito`, tranne PI-00a → C2 (`verificato`: rinvio esplicito del disciplinare art. 18.1 sub 2.1 p. 28, controllato nel testo estratto).
- Archi per criterio (alta/media/bassa): C1 0/3/7 · C2 2/3/6 · C3 2/2/8 · C4 1/2/3 · C5-C7 nessuna tavola (criteri tabellari).
- orfano-potenziale | IT-00-ESEC-01 | inquadramento IGM 1:25000, solo contesto
- orfano-potenziale | PI-06-ESEC-01 | impianto idrico antincendio: e' un vincolo per le migliorie, nessun sub-criterio lo premia
- orfano-potenziale | VVF-PI-01-00 | planimetria generale della pratica VV.F., solo contesto
- anomalia | IT-01/02/03 | ESEC-00 nel nome file, ESEC-01 in elenco e cartiglio (apr. 2026): codice del nodo dal nome file
- anomalia | PI-02-ESEC-01 | «REAZIONE» al fuoco (elenco, sottotitolo cartiglio) vs «RESISTENZA» (nome file, titolo cartiglio)
- anomalia | PI-00a-ESEC-01 | non firmato, non in elenco, cartiglio «Agosto 2026», formato A0; richiamato dal disciplinare per C2.1
- anomalia | PI-01-ESEC-01 | il cartiglio riporta il codice PI-00-ESEC-01 (refuso)
- anomalia | PI-03-ESEC-01 | il cartiglio riporta il codice PI-02-ESEC-01 (refuso)
- anomalia | PA-04-ESEC-01 | titolo del cartiglio «corpo scala e ascensore» (copiato da PA-03) vs elenco «collegamenti verticali con il palco»
- segnale | PA-05-ESEC-01 | il testo grafico cita un «filtro adesivo oscurante» sulla cupola: verificare la baseline di C3.1
- segnale | VVF-PI-07-00 / PI-01-ESEC-01 | torrini di estrazione fumi sulla cupola: vincolo per C3.1
- Wikilink `[[G-00-ESEC-01_ELENCO_ELABORATI]]` usato come fonte delle descrizioni: si risolve quando la Fase B crea la pagina con il nome previsto dal census.

## [2026-10-03] ingest-fase-B-sub1 | testuali sottoinsieme 1 | 7 create, 0 riscritte, 0 orfani, 0 contraddizioni registrate (incongruenze annotate nelle pagine)

- Invocazione Fase B, sottoinsieme 1 (round 1, in parallelo con Fase A, Fase C e Fase B sottoinsieme 2). Nessuna pagina preesistente per questi codici: tutte create. `index.md`, `scope.md`, `economic_framework.md`, `synthesis/` non toccati.
- Pagine create: `G-00-ESEC-01_ELENCO_ELABORATI` (altro, verificato), `G-06-ESEC-01_CAPITOLATO_SPECIALE_D_APPALTO` (capitolato, is_latest false, verificato), `G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO` (capitolato, is_latest true, verificato su lettura mirata + ricerca integrale), `G-07-ESEC-01_RELAZIONE_FOTOGRAFICA` (relazione_tecnica, parziale: foto lette visivamente pp. 4-13), `G-08-ESEC-01_RELAZIONE_GENERALE` (relazione_generale, verificato), `G-11-ESEC-01_SCHEMA_DI_CONTRATTO` (altro, verificato), `COM-PZ.REGISTRO-UFFICIALE.2026.0007341_Marcato` (lista ALTRO trattata in Fase B su indicazione del main loop; altro, verificato).
- `related_documents: []` su tutte (le popola la Fase D dalle sezioni «Riferimenti a altri elaborati»).
- Archi doc→criterio (alta/media/bassa): C1 1/3/3 · C2 1/2/3 · C3 2/1/3 · C4 2/1/2 · C5 0/0/1 · C6-C7 nessuno.
- version | G-06 | diff normalizzato integrale ESEC-01 → ESEC-02: penale $MANUAL$‰ → 0,3‰ (p. 25); premio accelerazione con tetto 5% (p. 25); nuovo Art. 2.17 revisione prezzi (soglia 3%, 90% eccedenza, p. 27); rinumerazione 2.17-2.27 → 2.18-2.28; indice finale troncato (260 vs 261 pp.); Capp. 3-11 tecnici identici.
- segnale | G-06-ESEC-02 | capitolato modello: 103 segnaposto $MANUAL$/$Er non compilati (FV pp. 171-175, accumulo p. 185, antincendio pp. 231-249), indice «EDILIZIA SCOLASTICA» (p. 256); nessuna occorrenza di poltrone, MDF, TVCC, building automation, cupola, kWh, Uw/Rw, Soprintendenza
- segnale | G-06-ESEC-02 | CAM citati in tre versioni: D.M. 23/06/2022 (Cap. 5), DM 11/10/2017 (FV p. 183), D.M. 24.11.2025 (disciplinare) → C4.2
- segnale | G-06-ESEC-02 | rinvio a «Relazione tecnica ex L. 10/91» e abachi serramenti per le prestazioni degli infissi (p. 158): nessun documento corrispondente in 00_input (`find` negativo) → baseline Uw/Rw di C1.1 TBD
- segnale | G-08-ESEC-01 | FV 6 kW su staffe + 4 batterie = 20 kWh (pp. 14-15): il «>20 kWh» del sub 2.3 coincide con la capacità di progetto (nota N5)
- anomalia | G-08-ESEC-01 | FV «6 kw» (p. 14) vs «6 kWh» (p. 24); caldaia a condensazione < 116 kW (p. 15) vs «pompe di calore» (p. 24); 134 poltrone (p. 18) vs platea 53 + 54 = 107 (p. 20); ascensore idraulico con «funi di trazione» (p. 17); rinvio a «elaborato C1» non esistente (p. 10); «preventivo allegato» poltrone assente (p. 18)
- anomalia | G-11-ESEC-01 | rinvii ad articoli del CSA (14, 19, 20, 27-34, 41, 47, 57, 58 …) non corrispondenti alla numerazione 1.x/2.x di G-06; durata e importi non compilati; residui di altri appalti («Prefettura di Rimini», «flusso veicolare», «lettera di invito»); offerta tecnica non elencata tra i documenti contrattuali
- anomalia | G-00-ESEC-01 | categoria «OG2» su tutti gli elaborati vs OG1 prevalente di disciplinare e capitolato; PI-00a, VVF-PI, COM-PZ e revisioni ESEC-02 fuori elenco
- Synthesis hook: temi ricorrenti segnalati al main loop (pagine di sintesi create dal sottoinsieme 2).

## [2026-10-03] ingest-fase-A | Economico — 8 pagine nodo create, 0 riscritte | economic_framework.md e scope.md creati | contraddizioni da passare alla Fase E: 13 (D1-D13)

- Invocazione Fase A (round 1, in parallelo con B e C). Nessuna pagina economica preesistente; `index.md` non toccato.
- Nodi creati (`02_graph/nodes/`): G-01-ESEC-01_QUADRO_ECONOMICO (is_latest: false), G-01-ESEC-02_QUADRO_ECONOMICO (true), G-02-ESEC-01_ELENCO_PREZZI, G-03-ESEC-01_ANALISI_NUOVI_PREZZI, G-04-ESEC-01_COMPUTO_METRICO_ESTIMATIVO (false), G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO (true), G-05-ESEC-01_QUADRO_INCIDENZA_MANODOPERA, SIC-03-ESEC-01_COSTI_PER_LA_SICUREZZA. `related_documents: []` lasciato alla Fase D.
- Metodo: parser su testi estratti (`01_extracted/text/`) per computo ESEC-01/02 (139 voci), G-05 (123 voci), G-02 e G-03 (122 prezzi); riconciliazione al centesimo con i riepiloghi dei documenti; QE ESEC-02 p. 2 verificato visivamente sul PDF.
- Numeri chiave (is_latest): lavori a misura 381.364,99 € (QE A1 = computo ESEC-02); manodopera 47.849,85 € = 12,547% (G-05); sicurezza 13.005,47 € = 3,410% (SIC-03 = QE A4); totale 394.370,46 €; forniture ARREDO 55.296,43 € (14,5%); somme a disposizione 125.629,54 €; costo complessivo 520.000,00 €. Categorie SOA OG1 185.390,73 / OS3 76.576,21 / OS4 43.512,19 / OG9 41.600,21 / OS30 34.285,65 — tutti i riferimenti del disciplinare confermati.
- scope.md: tabella completa di 139 voci (20 righe NP / 19 codici, 143.667,94 € = 37,67%; 119 righe da tariffa / 104 codici, 237.697,05 €), baseline per sub-criterio, limiti di modifica da `modification_limits`/`fuori_scope_risks` di C1-C7.
- ESEC-01 → ESEC-02: computo identico (stesse 139 voci e importi; solo voce 37 B.18.071.10 q.tà 11,40 → 0, importo 0; aggiunti riepiloghi TOL/SOA e Allegato I revisione prezzi); QE: B3 imprevisti 5.982,30 → 7.386,68, B6 accantonamento 0 → 5.000,00, B11 1.839,34 → 1.623,23, costo complessivo 513.811,73 → 520.000,00 (parte A invariata).
- contraddizione | G-01-ESEC-02 | IVA lavori «al 22%» = 59.428,23 € (15,07% di A; al 22% sarebbero 86.761,50 €) — verificata sul PDF
- contraddizione | G-05-ESEC-01 vs G-03-ESEC-01 | manodopera 0,00 su tutte le voci NP; ≥ 13.708,57 € di manodopera esplicita negli NP (analisi G-03 + NP 16)
- contraddizione | G-04-ESEC-02 vs G-08-ESEC-01 | accumulo 15 kWh (computo, RS-00, RS-01) vs 4 batterie / 20 kWh (G-08 pp. 15, 24) — baseline C2.3
- contraddizione | disciplinare Tab. 1 | righe 339.074,03 + 55.296,43 = 394.370,46 totalizzate come «A) 381.364,99» (nota N2)
- contraddizione | disciplinare p. 8 vs G-06-ESEC-02 art. 2.14 | premio di accelerazione max 10% vs max 5% (entrambi entro imprevisti 7.386,68 €)
- anomalia | G-03-ESEC-01 | analisi solo per 5 NP su 19 (80.266,19 € di NP senza analisi); numerazione NP 001-005 vs NP 03-05 ambigua; pp. 2-11 = copia di G-02
- anomalia | G-02-ESEC-01 | tariffa ed edizione non dichiarate; E.00050 codice anomalo; cartongesso con CAM DM 11/10/2017 (disciplinare: D.M. 24.11.2025)
- prezzario | tariffa Regione Basilicata non disponibile in cache: confronto prezzi rinviato (Analisi 2 strategy-auditor)
- File temporanei (parser, JSON) nella scratchpad di sessione, non nel progetto.

## [2026-10-03] ingest-fase-B-sub2 | testuali sottoinsieme 2 | 8 create, 0 riscritte, 0 orfani, 6 synthesis create | contraddizioni da passare alla Fase E: 4

- Invocazione Fase B, sottoinsieme 2 (round 1, in parallelo con Fase A, Fase C e Fase B sottoinsieme 1). Nessuna pagina preesistente per questi codici: tutte create. `index.md`, `scope.md`, `economic_framework.md`, `03_criteria/` non toccati. Unica invocazione autorizzata a scrivere in `02_graph/synthesis/`.
- Pagine nodo create: `G-09-ESEC-01_RELAZIONE_CAM` (verificato), `G-10-ESEC-01_PIANO_DI_MANUTENZIONE` (verificato; letture mirate su 227 pp.), `RS-00-ESEC-01_RELAZIONE_TECNICA_IMPIANTI` (verificato), `RS-01-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_FOTOVOLTAICO` (parziale: pp. 3-5 PVGIS lette visivamente dal PDF), `RS-02-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_IDRICO_ANTINCENDIO` (verificato), `RS-03-ESEC-01_RELAZIONE_ACUSTICA` (verificato), `SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO` (PSC, verificato; layout pp. 259-260 letto visivamente), `SIC-01-ESEC-01_CRONOPROGRAMMA` (verificato; Gantt letto visivamente per le date). `related_documents: []` (Fase D).
- Archi doc→criterio (alta/media/bassa): C1 1/3/2 · C2 2/4/1 · C3 2/1/1 · C4 1/3/0 · C5-C7 nessuno. Nessun orfano.
- Synthesis create (`02_graph/synthesis/`): `fotovoltaico_e_accumulo` (C2), `acustica_sala` (C1), `antincendio` (C1/C2/C3 vincolo), `copertura_terrazzi_e_cupola` (C3/C2), `ascensore` (C4), `logistica_cantiere` (C3/C4). Nelle pagine nodo i rinvii alle sintesi sono scritti come percorso (`02_graph/synthesis/x.md`) e non come wikilink, perche' `graph_lint.js` non risolve la cartella synthesis.
- copia-interna | SIC-00-ESEC-01 | pp. 85-87 = SIC-01 (54 righe fase/durata identiche, diff); pp. 256-258 = SIC-03 (12 voci, totale 13.005,47 €, data 23/04/2026, identico); pp. 259-260 = layout SIC-02 (cartiglio SIC-02-ESEC-01, verifica visiva)
- contraddizione | SIC-00-ESEC-01 p. 2 | importo presunto lavori 391.795,41 € vs 394.370,46 € (totale A) e 381.364,99 € (base d'asta)
- contraddizione | accumulo | 4 batt./15 kWh (RS-00 p. 11) · 3 batt./15 kWh (RS-01 p. 7) · 15 kWh litio (computo) vs 20 kWh (RS-03 p. 9, G-09 pp. 14/16, SIC-00 p. 9 «4 batterie», G-08) — baseline di C2.3 «>20 kWh»
- contraddizione | ascensore | idraulico (SIC-00 p. 10, G-10, computo) vs «impianto ascensore elettrico» (SIC-01 p. 2, SIC-00 p. 48); 6 persone/3 fermate/9 m (SIC-00, G-08) vs 8 persone/6 fermate/18 m (computo, da pagina nodo Fase A)
- contraddizione | antincendio | «sprinkler» (RS-03 p. 8, G-09 p. 14, G-08) e «idranti a colonna sottosuolo» (G-10 p. 48) vs solo 4 naspi DN25 (RS-02)
- anomalia | SIC-00-ESEC-01 | sottofase «Montaggio della gru a torre» (p. 36) assente da cronoprogramma e costi; residui «$CANCELLARE$» (p. 23), «all'interno della chiesa» (p. 23), «allegato H» (p. 24), pie' di pagina Fascicolo «impianto di smaltimento di acque meteoriche»; «preventivo allegato» poltrone (p. 11) non presente
- anomalia | SIC-01-ESEC-01 | sequenza unica Z1 di 109 gg lavorativi (≈150 gg naturali, 28/05→fine ottobre 2026 da lettura visiva); nessuna fase per infissi esterni, MDF, tenda/pellicola cupola, naspi, IRAI, BA, accumulo; pie' di pagina «ascensore esterno in edificio esistente»
- anomalia | G-09-ESEC-01 | CAM verificati su DM 23/06/2022 + DM 5/8/2024 (premessa DM 11/1/2017), nessun riferimento al DM 24.11.2025 del disciplinare ne' alla sigla «B3»; nessuna percentuale di riciclato, EPD, FSC/PEFC, classe A+ quantificata; 2.6.2 senza stima del 70%; intestazioni «FEBBRAIO 2025» da p. 7
- anomalia | G-10-ESEC-01 | piano da catalogo: mancano infissi, impianto termico, pavimenti, MDF, poltrone, impermeabilizzazioni, naspi, BA; accumulatori «al piombo acido» vs litio del computo
- segnale | C3.3 | nessun elaborato del sottoinsieme (PSC, cronoprogramma, costi) tratta smontaggio/protezione/rimontaggio di audio, proiettori e schermo esistenti
- segnale | C3.1 | G-09 p. 30: «nessun intervento ... per la coibentazione delle componenti opache»; cupola solo pellicola antisolare + tenda motorizzata + fori evacuazione fumi
- segnale | C1.3 | unica baseline numerica: T60 Sabine 0,79 s a 500 Hz, V 986 m3, sala piena 134 posti (RS-03 pp. 15-17); STI/C50/C80 non calcolati
- segnale | C2.1 | FV di progetto su staffe inclinate 30°, «limite di 6 kw imposto dallo spazio sul tetto terrazzato» (RS-01 p. 2); G-10 pp. 35-38 contempla gia' tegole/manti FV integrati per centri storici
- Lint (`node scripts/graph/graph_lint.js`, sola lettura): nessun rilievo sulle 8 pagine del sottoinsieme 2.
- File temporanei (script di ricerca, diff) nella scratchpad di sessione, non nel progetto.

## [2026-10-03] ingest-fase-F | criteri | 7 pagine criterio arricchite (solo frontmatter), 0 corpi modificati | 114 archi supported_by | 0 sottocriteri D deboli (regola meccanica), 11 elementi premianti con evidenza debole

- Invocazione Fase F (round 2, in parallelo con D ed E). Scope: `03_criteria/criteria/criterion_C1…C7.md`. Non toccati: pagine nodo, `synthesis/`, `economic_framework.md`, `scope.md`, `index.md`. `modification_limits` e `fuori_scope_risks` (disciplinare-analyst) invariati.
- Metodo: parsing manuale (PyYAML assente) dei `supports_criteria` di 53 pagine nodo → 114 archi; ricontrollo prima della scrittura: nessuna variazione degli archi durante D/E. Blocco inserito in coda al frontmatter con `# --- Aggiunto/aggiornato da graph-builder 2026-10-03 ---` e `graph_updated: 2026-10-03`. Verifiche: YAML valido (Ruby Psych 3.1.0), corpo identico (md5), wikilink 114/114 risolti in `02_graph/nodes/`, lint 0 rilievi sulle pagine criterio.
- Formato voce: `{ doc, priority, confidence, sottocriteri, [is_latest: false] }`. Estende lo schema minimo `{ doc, priority }` (graph-schema, tipo criterion) con: `confidence` = attributo d'arco gia' usato in Fase C (esplicito sull'arco; altrimenti confidence della pagina nodo; `inferito` se la reason dichiara il collegamento inferito/dedotto → 4 archi: RS-02→C1, RS-02→C3, COM-PZ→C2, COM-PZ→C3); `sottocriteri` (concetto di `sottocriterio` dello schema proposal) ricavati dalla reason, 25 assegnati a mano dove la reason li nomina in prosa, `trasversale` (11) per QE/manodopera = cornice di anomalia art. 23; `is_latest: false` sulle 3 versioni superate (G-01/G-04/G-06-ESEC-01). Ordine: alta > media > bassa, poi verificato > parziale > inferito, poi codice.
- Archi per criterio (alta/media/bassa): C1 4/9/16 (29) · C2 6/10/15 (31) · C3 7/6/17 (30) · C4 5/7/10 (22) · C5 0/0/2 · C6 0 · C7 0 (`supported_by: []`, atteso: tabellari).
- Copertura per sottocriterio (documenti / di cui alta): C1.1 17/4 · C1.2 13/4 · C1.3 19/4 · C2.1 21/6 · C2.2 12/3 · C2.3 21/5 · C3.1 19/6 · C3.2 6/2 · C3.3 17/6 · C4.1 16/5 · C4.2 16/4 · C5.1 2/0 · C6.1 0 · C7.1 0. Ogni sottocriterio discrezionale ha almeno un arco alta non inferito.
- evidenza-debole | C1.1 | Uw/Uf/Rw solo come range voce Nr. 24 di G-02 (computo voce 35); relazione ex L. 10/91 e abaco serramenti assenti da 00_input; geometria/partiture solo da tavole inferite (PA-01, RIL-01, RIL-02)
- evidenza-debole | C1.2 | garanzia: solo G-11 (bassa, contrattuale); scorta assente; «preventivo allegato» poltrone (G-08, SIC-00) non presente
- evidenza-debole | C1.3 | reazione al fuoco finiture/MDF solo da tavole inferite (PI-02, VVF-PI-02…05) + RTV15 generica (COM-PZ); unico indice calcolato T60 (RS-03)
- evidenza-debole | C2.1 (15 pt) | PI-00a (rinvio espresso del disciplinare, arco verificato solo sul testo del disciplinare) e PI-00 non lette; indirizzi di tutela Soprintendenza assenti da tutti gli elaborati; impatto visivo/riflettanza solo da foto G-07 (parziale) e tavole di contesto inferite (IT-02, IT-03, PA-01)
- evidenza-debole | C2.2 | archi alta solo di assenza (G-04-ESEC-02, G-08, RS-00); predisposizioni elettriche solo da tavole inferite (PI-05, PI-03)
- evidenza-debole | C2.3 | baseline accumulo contraddittoria 15 kWh (RS-00, RS-01, computo) vs 20 kWh (G-08, SIC-00, G-09, RS-03)
- evidenza-debole | C3.1 | torrini fumi sulla cupola solo da tavole inferite (VVF-PI-07, PI-01); PA-05 (alta) non letta
- evidenza-debole | C3.2 | copertura minima tra i D (6 documenti): unica baseline verificata NP 07 palco/allestimento (G-04-ESEC-02, G-02); configurazione base multimediale/cinematografica non descritta da alcun elaborato
- evidenza-debole | C3.3 | nessun censimento di audio, proiettori, schermo esistenti (solo foto G-07); archi alta di sola assenza (PSC, cronoprogramma, computo)
- evidenza-debole | C4.1 | isolamento acustico cabina (dB) assente ovunque; dati ascensore contraddittori (idraulico vs «elettrico»; 6/3/9 m vs 8/6/18 m); PA-03 (alta) non letta
- evidenza-debole | C4.2 | «minimi CAM» di progetto su DM 23/06/2022 (G-06-ESEC-02, G-09) e DM 11/10/2017 (G-02) invece del DM 24.11.2025 del disciplinare; nessuna percentuale/EPD in G-09
- atteso | C5.1 | 2 archi bassa (G-04-ESEC-02, G-08: definizione di «intervento analogo»); C6.1, C7.1 nessun elaborato: evidenza = status dell'impresa
- Le stesse righe di evidenza debole sono riportate come commento YAML nel frontmatter di C1-C5 (non sono campi).
- synthesis | campo non previsto dallo schema criterion: non aggiunto. Mappa per l'invocazione 8 (percorsi, non wikilink: `graph_lint.js` non risolve `synthesis/`): C1 ← `acustica_sala`, `antincendio` · C2 ← `fotovoltaico_e_accumulo`, `copertura_terrazzi_e_cupola`, `antincendio` · C3 ← `copertura_terrazzi_e_cupola`, `logistica_cantiere`, `antincendio` · C4 ← `ascensore`, `logistica_cantiere`
- orfano | IT-00-ESEC-01, PI-06-ESEC-01, VVF-PI-01-00 | `supports_criteria: []`, assenti da ogni `supported_by` (gia' segnalati in Fase C) → invocazione 8 / `/resolve_orphan`
- drawing-reader prioritario (tavole alta non lette): PI-00a e PI-00 (C2.1), PA-03 (C4.1), PA-05 (C3.1), SIC-02 (C3.3)
- Lint globale (sola lettura): 4 ERROR (3 orfano, 1 index-assente atteso fino all'invocazione 8), 26 WARN archi-solo-ereditati (tavole); 0 sulle pagine criterio.
- File temporanei (parser, blocchi YAML, validatore Ruby) nella scratchpad di sessione, non nel progetto.

## [2026-10-03] contraddizioni-fase-E | economico + trasversali | 19 voci di registro (D1-D19; 6 nuove D14-D19), 7 irrisolte, 5 quesiti SA proposti | 4 sezioni «Contraddizioni rilevate», 15 note # ATTENZIONE

- Invocazione Fase E (round 2, in parallelo con D e F). Scope: pagine economiche (G-01-ESEC-01/02, G-02, G-03, G-04-ESEC-01/02, G-05, SIC-03) + 12 contraddizioni trasversali indicate dal main loop. Ogni voce riverificata sulle fonti: testi `01_extracted/text/` con pagina (marcatori `<!-- p. N -->`), PDF sbustati, livello di testo delle tavole (`pdftotext`, confidence parziale). Gerarchia: disciplinare > capitolato/contratto > computo/QE (elenco prezzi > computo, capitolato art. 2.2) > relazioni > tavole; `is_latest`.
- Pagine nodo: solo Edit mirati nel corpo, ciascuno preceduto da rilettura (D modificava in parallelo i `related_documents`; nessun conflitto, tutte le modifiche presenti a fine fase). `index.md`, `03_criteria/`, `PROJECT_CONFIG.json`, `11_view/`, `synthesis/` non toccati.
- economic_framework.md: §10 riscritta (non duplicata) con colonne esito / fonte prevalente / impatto / quesito SA; nuova §10.1 con i testi dei quesiti Q1-Q5; §8 e §13 aggiornate; sezione finale «Per l'index» con 7 righe CONTRADDIZIONE per l'invocazione 8; frontmatter `contraddizioni_fase_e`.
- Sezioni «Contraddizioni rilevate» (pagina più autorevole coinvolta): G-04-ESEC-02 (D13, D14, D15, D17, D18) · G-01-ESEC-02 (D1, D2, D3, D16) · G-05-ESEC-01 (D4) · G-06-ESEC-02 (D7, D11, D19; il disciplinare non ha pagina nodo).
- Note `# ATTENZIONE` (pagina più vecchia o meno autorevole): G-01-ESEC-01, G-06-ESEC-01, G-02, G-03, G-00, G-08, G-09, G-10, RS-02, RS-03, SIC-00, SIC-01, VVF-PI-03-00, PI-03, PI-05. SIC-03: riscontro con la copia PSC aggiornato. scope.md: puntatori D11, D13, D14, D18 nelle righe di baseline C1.2, C2.3, C4.1, C4.2 (solo testo, nessun dato cambiato).
- confermata | D13 accumulo | 15 kWh (computo voce 78 p. 15, RS-01 p. 7, RS-00 p. 11, tavola PI-00 «3 moduli, C = 15 kWh») vs 20 kWh (G-08 p. 15/24, PSC p. 9, RS-03 p. 9, G-09 pp. 14/16); G-10 p. 30 piombo acido vs litio → quesito Q1 (alta)
- confermata | D14 ascensore | idraulico (disciplinare p. 29, computo voce 96 p. 17, G-08 p. 17, PSC p. 10) vs «elettrico a fune» (SIC-01 p. 2, PSC p. 48); 6 persone / 3 fermate / 9 m (G-08, PSC) vs 8 persone / 6 fermate / 18 m (computo, G-02 Nr. 87 p. 8 testo integrale) → quesito Q3 (media)
- parziale | D15 antincendio | sprinkler (G-08 p. 23, RS-03 p. 8, G-09 pp. 14-15) assenti da ogni fonte prevalente; «idranti a colonna» G-10 SMENTITO come errore (computo voci 118-121 + tavole VV.F.: idrante esterno e attacco motopompa); residuo naspi DN25 (RS-02, PI-06) vs cassette UNI 45 (computo voce 122) → nessun quesito
- confermata | D16 importo PSC | 391.795,41 € (p. 2) senza relazione aritmetica con QE → nessun quesito
- confermata | D17 FV/generatore | «6 kWh» e «pompe di calore» (G-08 p. 24, RS-03, G-09) vs computo (5,85 kWp + inverter 6 kW, caldaia a condensazione voce 92) → risolta per gerarchia
- parziale | D18 poltrone | 134 vs 107 SMENTITA (107 = sola platea; + galleria 27 = 134); residuo: tavole VV.F. 53 + 48 + 27 = 128, PI-03 platea 102, PI-05 54 + 49 → quesito Q4 (media)
- confermata | D4 manodopera NP | G-05 0,00 su tutti gli NP vs ≥ 13.708,57 € (G-03 + NP 16); nuovo indizio PSC p. 2 «773 uomini/giorno» (≈ 3,3 × G-05, inferito) → quesito Q5 (bassa, facoltativo)
- confermata | D2 IVA QE | 59.428,23 € «al 22%»: nessuna combinazione di aliquote 4/10/22% per super-categoria la ricostruisce → nessun quesito
- confermata | D7 premio accelerazione | divergono tasso (0,5%/g disciplinare vs 0,3‰/g capitolato) e tetto (10% vs 5%); prevale il disciplinare; tetto effettivo = imprevisti 7.386,68 € IVA compresa → nessun quesito
- confermata | D19 OG2 | G-00 p. 2 OG2 su 40 elaborati vs OG1 di disciplinare pp. 8, 11-12 e capitolato art. 1.3 → prevale OG1; quesito sconsigliato senza valutazione del professionista
- confermata | D11 CAM | D.M. 24.11.2025 (disciplinare p. 3, «Elaborato B3» inesistente) vs DM 23/06/2022 (G-09 p. 8, capitolato p. 84/257) vs DM 11/10/2017 (G-02 pp. 2-3, capitolato p. 183) vs DM 11/01/2017 (G-09 p. 4) → quesito Q2 (alta)
- confermata | D1 Tabella 1 | 339.074,03 + 55.296,43 = 394.370,46 etichettato «A) 381.364,99» → risolta (ribasso su 381.364,99 dal testo art. 3)
- chiuso-TBD | SIC-03 vs PSC pp. 256-258 | 12/12 voci identiche
- per-index | 7 righe CONTRADDIZIONE (D13, D11, D14, D18, D4, D2, D16) in `economic_framework.md` § «Per l'index»; risolte per gerarchia: D1, D7, D15, D17, D19
- Lint (sola lettura): nessun wikilink rotto introdotto; restano 4 ERROR preesistenti (3 orfani Fase C, index assente fino all'invocazione 8) e 26 WARN archi-solo-ereditati.
- File temporanei (helper di ricerca per pagina) nella scratchpad di sessione, non nel progetto.

## [2026-10-03] archi-fase-D | documento-documento | 253 archi su 53 pagine nodo (0 senza related_documents) | 5 synthesis create, 6 arricchite (+36 voci documenti)

- Invocazione Fase D (round 2, in parallelo con E e F). Scope: tutte le 53 pagine nodo + `02_graph/synthesis/`. Solo il campo `related_documents` dei nodi, sostituito con Edit mirati (`related_documents: []` → lista), ognuno preceduto da rilettura del frontmatter; verifica finale per confronto con i blocchi generati: 53/53 intatti nonostante le modifiche parallele della Fase E. `index.md`, `03_criteria/`, `PROJECT_CONFIG.json`, `11_view/`, `economic_framework.md`, `scope.md` non toccati.
- Formato arco: `{ doc, type, confidence, reason }` (confidence aggiunta sull'arco come per supports_criteria della Fase C); solo tipi del catalogo di `references/graph-schema.md`.
- Archi per tipo: references 74 · referenced_by 74 · tavola_di 40 · relazione_di 40 · stesso_lotto 18 (9 coppie) · versione_precedente 3 · versione_successiva 3 · computo_di 1 = **253**. Confidence: 159 verificato, 94 inferito (78 tavola_di/relazione_di abbinati per disciplina, cioè tutti tranne SIC-02↔SIC-00, più 16 archi da 8 rinvii con target dedotto).
- references (74): G-00 → 39 elaborati citati per codice a p. 2; COM-PZ → VVF-PI-01…08 (stesso n. di pratica 21079 nel parere e nel cartiglio); G-06-ESEC-02 → 7 (RS-01 e G-09 inferiti; SIC-01, SIC-00, G-02, G-04-ESEC-02, G-01-ESEC-02 per titolo univoco); G-06-ESEC-01 → 5; G-11 → 4; G-09 → 5 (G-08 e RS-00 inferiti); SIC-00 → SIC-01, SIC-02, SIC-03 (copie interne con codice); RS-00 → RS-01; RS-02 → PI-06 (inferito); G-08 → PI-00 (Figura 12, inferito).
- Rinvii NON trasformati in arco (target non individuabile in modo univoco o assente): G-06-ESEC-02 «grafici progettuali» del locale accumulo (PI-00 o PI-05); COM-PZ «progetto approvato» (RS-02, PI-01, PI-02, PI-03 solo possibili); relazione ex L. 10/91, abachi e schede serramenti, preventivo poltrone, «elaborato C1», APE/diagnosi energetica (non presenti in 00_input); correlazioni tematiche dichiarate «non citazioni» dalle pagine della Fase B.
- tavola_di/relazione_di (40 coppie), per disciplina come da istruzioni del main loop: PI-00 ↔ RS-01 e RS-00; PI-00a ↔ RS-01; PI-01, PI-03, PI-04, PI-05 ↔ RS-00 (RS-00 non descrive evacuazione fumi né IRAI: dichiarato nella reason); PI-06, PI-02 e VVF-PI-01…08 ↔ RS-02 (RS-02 tratta solo i naspi); PA-00…05 ↔ G-08; RIL-00…02 e IT-00…03 ↔ G-08 e G-07; PA-00, PA-02 ↔ RS-03; SIC-02 ↔ SIC-00 (verificato: allegato e copia interna).
- computo_di: G-04-ESEC-02 → G-08 (lo schema non prevede l'inverso). Versioni: G-01, G-04, G-06 (ESEC-01 versione_successiva → ESEC-02; ESEC-02 versione_precedente → ESEC-01).
- stesso_lotto con parsimonia (9 coppie, stessa sezione e subtype diversi, solo dove c'è un legame di dati): G-07↔G-08; G-04-ESEC-02 ↔ G-01-ESEC-02, G-02, G-03, G-05; G-03↔G-05 (manodopera NP, D4); SIC-01↔SIC-02, SIC-02↔SIC-03, SIC-01↔SIC-03.
- scelta | PI-02 (non elencata dal main loop) abbinata a RS-02 per disciplina antincendio; PI-00a ↔ RS-00 non creato (RS-00 descrive solo il FV su staffe).
- limite schema | QE A4 = SIC-03 (13.005,47 €): nessun tipo di arco ammesso tra sezioni diverse senza citazione → legame documentato solo in `economic_framework.md` e nei corpi delle pagine.
- synthesis create (5): `serramenti_e_ponti_termici` (C1.1, C4.2), `cam_ed_economia_circolare` (C4.2), `tutela_castello_e_impatto_visivo` (C2.1, C1.1, C3.1), `dotazioni_audio_video_scena` (C3.2, C3.3), `sala_e_poltrone` (C1.2, C1.3); allineate alle voci D11, D18, D19 della Fase E. Wikilink solo a nodi, criteri ed `economic_framework`; rinvii tra sintesi come percorso.
- synthesis arricchite (solo voci aggiunte al campo `documenti`, corpo invariato): fotovoltaico_e_accumulo +4, acustica_sala +5, antincendio +12 (tavole PI e VVF-PI già citate nel corpo), copertura_terrazzi_e_cupola +7, ascensore +4, logistica_cantiere +4. Nel corso dell'operazione la riga di chiusura `---` del frontmatter era stata omessa in queste 6 pagine; ripristinata e verificata.
- segnale | C1.1 | fattore solare del vetro: 50-60% (G-02 Nr. 24) vs 0,35 (G-09 p. 29, riferito dal CAM 2.4.8 al fattore totale vetro + schermatura) — da chiarire, annotato in `serramenti_e_ponti_termici`
- segnale | C1.2 | rimosse 120 poltrone (voce 101) vs 134 nuove (voce 102): +14 posti, oltre al residuo 134/128 di D18
- segnale | C3.3 | unico precedente di deposito protetto a computo: voce 101 NP 08 (poltrone esistenti depositate dove indica la DL, senza danni alle parti recuperabili)
- segnale | C3.2 | i «proiettori» del computo (voce 58, D3.10.019.01) sono plafoniere LED di illuminazione, non apparecchi di proiezione
- Verifica: 253/253 wikilink di `related_documents` e 355/355 wikilink delle sintesi risolvono a pagine esistenti. Lint (sola lettura): 0 arco-senza-reason, 0 wikilink-rotto; restano 4 ERROR preesistenti (3 orfani della Fase C: IT-00, PI-06, VVF-PI-01; index assente fino all'invocazione 8) e 26 WARN archi-solo-ereditati.
- File temporanei (generatore archi, blocchi YAML, verificatore) nella scratchpad di sessione, non nel progetto.

## [2026-10-03] ingest | Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ) — 67 create, 7 riscritte, 3 orfani, 7 contraddizioni

- Invocazione 8 di 8 (Fasi 4-5), sequenziale dopo il round 2 (D, E, F). Grafo costruito da zero in questa ingest (nessun `index.md` preesistente).
- Conteggio: **67 create** = 53 pagine nodo + 11 sintesi + `scope.md` + `economic_framework.md` + `index.md`; **7 riscritte** = pagine criterio C1-C7 (preesistenti, solo frontmatter arricchito dalla Fase F). Gli aggiornamenti del round 2 sulle pagine create nel round 1 (Fase D: `related_documents` di 53 nodi, 6 sintesi arricchite; Fase E: sezioni «Contraddizioni rilevate» e note `# ATTENZIONE` su 19 nodi, `economic_framework` §10/§10.1, puntatori in `scope`) sono interni alla stessa ingest e non contati come riscritture.
- `index.md` rigenerato per intero (non accodato) dai frontmatter reali di nodi, criteri e sintesi: header gara, pagine speciali e numeri chiave, criteri → documenti (sommario + dettaglio per sottocriterio e priorità), sintesi + mappa criterio → sintesi (mappa Fase F integrata con il campo `criteri` delle 5 sintesi della Fase D), documenti per sezione (9 prefissi, 53 righe), orfani ALERT con proposta motivata, contraddizioni (7 irrisolte, 5 risolte, 7 anomalie interne, quesiti Q1-Q5 con rinvio a `economic_framework` §10.1, anomalie documentali), sottocriteri con evidenza debole (Fase F) con azione suggerita, salute del grafo, statistiche. Sintesi, `log.md` e `_census.md` linkati come percorso (`graph_lint.js` non risolve wikilink fuori da `nodes/`, criteri e pagine speciali).
- Statistiche: 53 nodi (23 estratti: 21 verificato, 2 parziale; 30 tavole non estratte, inferito) · 11 sintesi · 114 archi documento → criterio (alta 22 / media 32 / bassa 60; verificato 67 / parziale 5 / inferito 42) · 253 archi documento → documento (159 verificato / 94 inferito) · **367 archi totali**.
- orfano | IT-00-ESEC-01 | giustificato (contesto IGM 1:25000) → proposta: lasciare orfano
- orfano | PI-06-ESEC-01 | non del tutto giustificato: vincolo fisico (naspi DN25 / cassette UNI 45, D15) → proposta: C1 bassa (C1.3) + C3 bassa (C3.3), `confidence: inferito`, come la relazione RS-02
- orfano | VVF-PI-01-00 | in gran parte giustificato → proposta facoltativa: C3 bassa (C3.3, accessi e punti VV.F. liberi in cantiere)
- Nessun orfano collegato d'iniziativa: decisione del professionista con `/resolve_orphan`.
- contraddizioni | 7 irrisolte riportate in index §7.1 con le righe `CONTRADDIZIONE: … — verifica manuale richiesta` di `economic_framework` «Per l'index» (D13, D11, D14, D18, D4, D2, D16); 5 risolte per gerarchia (D1, D7, D15, D17, D19); 7 anomalie interne (D3, D5, D6, D8, D9, D10, D12).
- Artifact HTML: `node scripts/render/md_to_html.js 02_graph/index.md` → `11_view/02_graph/index.html` (hook di rendering non attivo in sessione).
- Non toccati: `03_criteria/`, `PROJECT_CONFIG.json`, pagine nodo, sintesi, `scope.md`, `economic_framework.md`.
- Checklist build-knowledge-graph: tutti gli output obbligatori presenti; unico punto aperto «ogni orfano giustificato» (PI-06 in attesa di `/resolve_orphan`; IT-00 e VVF-PI-01 giustificati).
- File temporanei (generatore dell'index, verificatori di wikilink e YAML) nella scratchpad di sessione, non nel progetto.

## [2026-10-03] lint | 3 orfani, 7 contraddizioni, 0 archi mancanti, 0 errori versione

- `node scripts/graph/graph_lint.js` (con `index.md` presente): **3 ERROR** (`orfano`: IT-00, PI-06, VVF-PI-01), **26 WARN** (`archi-solo-ereditati`: tutte le tavole tranne PI-00a e le 3 orfane — IT 3, PA 6, PI 6, RIL 3, SIC 1, VVF-PI 7). Risolto l'ERROR `index-assente` delle fasi precedenti; 0 `nodo-non-indicizzato`, 0 `index-nodo-fantasma`, 0 `wikilink-rotto`, 0 `arco-senza-reason`, 0 frontmatter/subtype/confidence non validi, 0 `copertura-estrazione`.
- Merito: WARN attesi (tavole collegate per argomento, contenuto non letto); priorità `drawing-reader` sulle 4 tavole `alta` inferite (PI-00, PA-03, PA-05, SIC-02) e su PI-00a (C2.1, 15 pt). Check 2: oneri sicurezza 13.005,47 € coerenti ovunque, importo lavori = somma SOA. Check 3: 0 archi mancanti non giustificati (G-04-ESEC-01 senza `computo_di`: versione superata, giustificato). Check 4: G-01, G-04, G-06 con un solo `is_latest: true`. Check 5: pagine speciali `verificato`. Check 6: estrazione parziale bloccata alla fonte su RS-01 pp. 3-5 e G-07 (pagine immagine), vincolo permanente.
- Controlli aggiuntivi fuori script: 0 wikilink o link markdown rotti su 75 pagine (nodi, sintesi, pagine speciali, criteri, index); frontmatter YAML valido su 74/74; nessun campo vuoto; nessun dato numerico di progetto senza confidence. Unica eccezione formale: il campo metadato `pagine` (numero di pagine del PDF da pdfinfo) è senza commento di confidence su tutti i 53 nodi — non è un dato di progetto, non corretto, segnalato. Nessuna correzione meccanica necessaria (0 wikilink rotti, 0 frontmatter malformati).
