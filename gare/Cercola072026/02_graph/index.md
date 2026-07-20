---
type: index
gara: "Procedura aperta telematica per l'affidamento dell'appalto dei lavori di \"Intervento di efficientamento energetico dell'Istituto Comprensivo 'De Luca Picione Caravita' sito alla Via Nuova\""
date: 2026-07-19
ai-first: true
---

# Knowledge Graph — Indice

**Gara:** Intervento di efficientamento energetico dell'Istituto Comprensivo "De Luca Picione
Caravita" (Cercola, NA) — CIG `BC3ECFAA55` — CUP `G13C25000920001`
**Stazione appaltante:** Comune di Cercola (NA), V Settore
**Data ultima ricostruzione dell'indice:** 2026-07-19
**Ultimo aggiornamento parziale:** 2026-07-20 — re-ingest mirato di [[C.01_Computo_Metrico_Estimativo]]
e [[C.02_Elenco_Prezzi_Unitari]] (estrazione da parziale a integrale). Vedi sezione "Re-ingest"
sotto. Nessun altro nodo modificato.
**Regola per ogni agente:** leggi questa pagina PRIMA di aprire qualunque pagina nodo. Segui i
wikilink verso `02_graph/nodes/`, `02_graph/synthesis/`, `03_criteria/criteria/`.

---

## Pagine speciali

| Pagina | Stato | Confidence | Note |
|---|---|---|---|
| [[scope.md]] (`02_graph/scope.md`) | compilato | `parziale` | ⚠ **DA AGGIORNARE dopo il re-ingest 2026-07-20**: la riga "dettaglio voce-per-voce — TBD da estrarre" non e' piu' vera, le 101 voci sono ora disponibili in [[C.01_Computo_Metrico_Estimativo]]. `scope.md` non e' stato riscritto (fuori dal mandato del re-ingest mirato) |
| [[economic_framework.md]] (`02_graph/economic_framework.md`) | compilato | `verificato` | Tutti i valori chiave (importo lavori, manodopera, oneri sicurezza, QE totale) verificati e incrociati su 5 documenti indipendenti; 1 contraddizione critica documentata (ripartizione C4/C5) |

## Pagine di sintesi (`02_graph/synthesis/`)

| Pagina | Tema | Documenti collegati | Confidence |
|---|---|---|---|
| [[impianto_fotovoltaico]] | Impianto fotovoltaico — dati coerenti tra elaborati e criterio C3, 1 discrepanza minore (tilt/azimut) | R.01, R.02, R.04, R.05, S.04 | verificato |
| [[prestazione_energetica_e_contraddizioni]] | Prestazione energetica post-operam — 2 contraddizioni tra elaborati (EPgl,nren; esclusione caldaie gas) | R.01, R.03, R.04, R.02.1, S.04 | verificato |

---

## Criteri e documenti collegati

Fonte: frontmatter `supported_by` di `03_criteria/criteria/criterion_Cx.md`, arricchito da graph-builder
Fase F il 2026-07-19. Elenco completo per priorità in ogni pagina criterio; qui solo `alta`.

| Criterio | Titolo | Punti | Tipo | Documenti prioritari (`alta`) | Documenti totali collegati |
|---|---|---|---|---|---|
| [[criterion_C1]] | Proposte migliorative efficientamento energetico | 20 | qualitativo | [[C.01_Computo_Metrico_Estimativo]], [[R.01_Relazione_Generale_e_Tecnica_Illustrativa]], [[R.03_Attestato_di_Prestazione_Energetica]], [[R.04_Relazione_Energetica_Ex_L10]] | 22 |
| [[criterion_C2]] | Proposte migliorative infissi | 25 | qualitativo | [[C.01_Computo_Metrico_Estimativo]], [[R.01_Relazione_Generale_e_Tecnica_Illustrativa]], [[R.03_Attestato_di_Prestazione_Energetica]], [[R.04_Relazione_Energetica_Ex_L10]] | 17 |
| [[criterion_C3]] | Proposte migliorative impianto fotovoltaico | 20 | qualitativo | [[C.01_Computo_Metrico_Estimativo]], [[R.01_Relazione_Generale_e_Tecnica_Illustrativa]], [[R.03_Attestato_di_Prestazione_Energetica]], [[R.04_Relazione_Energetica_Ex_L10]], [[R.05_Relazione_Impianto_Fotovoltaico]] | 11 |
| [[criterion_C4]] | Barriere architettoniche (opere opzionali B1) | 13 | tabellare | [[COMPUTO_OPERE_OPZIONALI]] | 2 — ⚠ minimo, vedi warning sotto |
| [[criterion_C5]] | Sistemazione e decoro esterno (opere opzionali B2) | 10 | tabellare | [[COMPUTO_OPERE_OPZIONALI]] | 2 — ⚠ minimo, vedi warning sotto |
| [[criterion_C6]] | Certificazione UNI/PdR 125:2022 | 2 | tabellare | — | 0 — ⚠ per natura del requisito, vedi warning sotto |

**Warning C4/C5 (supporto documentale minimo):** entrambi i criteri sono collegati solo a
`COMPUTO_OPERE_OPZIONALI` (priorità alta, fonte contabile) e `EG.01_Planimetria_Area_Esterna`
(priorità media, tavola inferita). Sono criteri tabellari on/off il cui oggetto e' interamente
descritto dall'atto contabile delle opere opzionali: la scarsità di documenti collegati e' coerente
con la natura del criterio, non un difetto di ingest. Resta pero' il fatto che, se in fase di analisi
del criterio servisse evidenza aggiuntiva (es. fattibilità tecnica dell'ascensore), l'unica tavola
disponibile è a `confidence: inferito` — verificarne il contenuto reale via `drawing-reader` prima
di dare per assodata la fattibilità.

**Warning C6 (zero documenti):** nessuna pagina nodo cita `[[C6]]` in `supports_criteria`. Per
natura del requisito (possesso di una certificazione aziendale UNI/PdR 125:2022, non un elemento
progettuale) non esiste un documento di progetto che lo supporti: nessun elaborato tecnico tra
quelli in `00_input/` può dimostrare il possesso di una certificazione dell'operatore economico.
Zero documenti collegati e' quindi atteso, non un errore di ingest.

---

## Documenti per sezione

### Sezione 01 — Relazione generale (1 documento)
| Codice | Descrizione | Subtype | Status | Confidence |
|---|---|---|---|---|
| [[R.01_Relazione_Generale_e_Tecnica_Illustrativa]] | Relazione Generale e Tecnica Illustrativa | relazione_generale | estratto | verificato |

### Sezione 02 — Relazioni tecniche specialistiche (6 documenti)
| Codice | Descrizione | Subtype | Status | Confidence |
|---|---|---|---|---|
| [[R.02_Relazione_CAM]] | Relazione CAM | relazione_tecnica | estratto | verificato |
| [[R.02.1_Relazione_DNSH]] | Relazione DNSH | relazione_tecnica | estratto | parziale (10/27 pag.) |
| [[R.03_Attestato_di_Prestazione_Energetica]] | Attestato di Prestazione Energetica (APE) | relazione_tecnica | estratto | verificato |
| [[R.04_Relazione_Energetica_Ex_L10]] | Relazione Energetica ex L.10 | relazione_tecnica | estratto | verificato |
| [[R.05_Relazione_Impianto_Fotovoltaico]] | Relazione Impianto Fotovoltaico | relazione_tecnica | estratto | verificato |
| [[R.06_Relazione_Calcolo_Illuminotecnico]] | Relazione Calcolo Illuminotecnico | relazione_tecnica | non_estratto | inferito |

### Sezione 03 — Tavole grafiche (19 documenti, 14 reali + 5 stub mancanti)
| Codice | Descrizione | Subtype | Status | Confidence |
|---|---|---|---|---|
| [[EG.01_Planimetria_Area_Esterna]] | Planimetria Area Esterna | tavola | non_estratto | inferito |
| [[EG.02_Pianta_Piano_Terra_Stato_di_Fatto]] | Pianta Piano Terra — Stato di Fatto | tavola | non_estratto | inferito |
| [[EG.02.1_Pianta_Piano_Primo_Stato_di_Fatto]] | Pianta Piano Primo — Stato di Fatto | tavola | non_estratto | inferito |
| [[EG.02.2_Pianta_Copertura_Stato_di_Fatto]] | Pianta Copertura — Stato di Fatto | tavola | non_estratto | inferito |
| [[EG.03_Prospetti_Stato_di_Fatto]] | Prospetti — Stato di Fatto | tavola | non_estratto | inferito |
| [[EG.04_Sezioni_Stato_di_Fatto]] | Sezioni — Stato di Fatto | tavola | non_estratto | inferito |
| [[EG.05_Pianta_Piano_Terra_Stato_di_Progetto]] | Pianta Piano Terra — Stato di Progetto | tavola | non_estratto | inferito |
| [[EG.05.1_Pianta_Piano_Primo_Stato_di_Progetto]] | Pianta Piano Primo — Stato di Progetto | tavola | non_estratto | inferito |
| [[EG.05.2_Pianta_Copertura_Stato_di_Progetto]] | Pianta Copertura — Stato di Progetto | tavola | non_estratto | inferito |
| [[EG.06_Prospetti_Stato_di_Progetto]] | Prospetti — Stato di Progetto | tavola | non_estratto | inferito |
| [[EG.07_Sezioni_Stato_di_Progetto]] | Sezioni — Stato di Progetto | tavola | non_estratto | inferito |
| [[EG.10_Schema_Centrale_Termica]] | Schema Centrale Termica | tavola | non_estratto | inferito |
| [[EG.11_Abaco_degli_Infissi]] | Abaco degli Infissi | tavola | non_estratto | inferito |
| [[EG.12_Particolari_Costruttivi]] | Particolari Costruttivi | tavola | non_estratto | inferito |
| [[EG.08_Planimetria_Corpi_Illuminanti_ISOLUX_Piano_Terra]] | Planimetria Corpi Illuminanti ISOLUX Piano Terra | tavola | **missing — file assente** | TBD |
| [[EG.08.1_Planimetria_Corpi_Illuminanti_ISOLUX_Piano_Primo]] | Planimetria Corpi Illuminanti ISOLUX Piano Primo | tavola | **missing — file assente** | TBD |
| [[EG.09_Schema_Unifilare]] | Schema Unifilare | tavola | **missing — file assente** | TBD |
| [[IT.01_Inquadramento_Territoriale]] | Inquadramento Territoriale | tavola | **missing — file assente** | TBD |
| [[IT.02_Memoria_Fotografica]] | Memoria Fotografica | tavola | **missing — file assente** | TBD |

### Sezione 08 — Economici + capitolato (9 documenti)
| Codice | Descrizione | Subtype | Status | Confidence |
|---|---|---|---|---|
| [[C.01_Computo_Metrico_Estimativo]] | Computo Metrico Estimativo | computo_metrico | estratto — **integrale (26/26 pag.)** | **verificato** |
| [[C.02_Elenco_Prezzi_Unitari]] | Elenco Prezzi Unitari | elenco_prezzi | estratto — **integrale (10/10 pag.)** | **verificato** |
| [[C.03_Analisi_dei_Prezzi]] | Analisi dei Prezzi | altro | estratto | parziale |
| [[C.04_Stima_Incidenza_Manodopera]] | Stima Incidenza Manodopera | quadro_manodopera | estratto | verificato |
| [[C.05_Computo_Metrico_Sicurezza]] | Computo Metrico Sicurezza | stima_sicurezza | estratto | verificato |
| [[C.06_Elenco_Prezzi_Sicurezza]] | Elenco Prezzi Sicurezza | elenco_prezzi | estratto | verificato |
| [[C.07_Quadro_Economico]] | Quadro Economico | quadro_economico | estratto | verificato |
| [[COMPUTO_OPERE_OPZIONALI]] | Computo Opere Opzionali (senza codice progetto) | computo_metrico | estratto | verificato |
| [[S.01_Capitolato_Speciale_Appalto]] | Capitolato Speciale d'Appalto | capitolato | non_estratto | parziale |

### Sezione 09 — Sicurezza e cantiere (4 documenti)
| Codice | Descrizione | Subtype | Status | Confidence |
|---|---|---|---|---|
| [[S.02_Piano_Manutenzione_Opera]] | Piano di Manutenzione dell'Opera | altro | non_estratto | parziale |
| [[S.03_Cronoprogramma_Lavori]] | Cronoprogramma dei Lavori | cronoprogramma | estratto | verificato |
| [[S.04_Piano_Sicurezza_Coordinamento]] | Piano di Sicurezza e Coordinamento (PSC) | PSC | estratto | verificato |
| [[S.05_Layout_Cantiere]] | Layout di Cantiere | altro | parziale | parziale |

---

## Orfani e contraddizioni

### Orfani (12 documenti senza `supports_criteria`)

**Orfani legittimi — intenzionali, documentati nella pagina stessa (7):** questi documenti hanno
`supports_criteria: []` con un commento esplicito nel frontmatter che ne motiva l'esclusione dai
criteri C1-C6. Non sono un difetto di ingest.

| Documento | Motivo dell'esclusione |
|---|---|
| [[C.05_Computo_Metrico_Sicurezza]] | Cornice economica generale (oneri sicurezza), non evidenza di merito tecnico per un singolo criterio — alimenta `economic_framework.md` |
| [[C.06_Elenco_Prezzi_Sicurezza]] | Idem C.05 — dettaglio voce per voce degli oneri sicurezza |
| [[C.07_Quadro_Economico]] | Cornice economica generale dell'appalto, non evidenza di merito tecnico |
| [[R.02.1_Relazione_DNSH]] | Documento di compliance PNRR/DNSH — vincolo di scope, non elaborato migliorativo |
| [[S.03_Cronoprogramma_Lavori]] | Programmazione temporale — nessun criterio valuta la tempistica realizzativa |
| [[S.04_Piano_Sicurezza_Coordinamento]] | PSC descrive rischi/DPI per lavorazione, non caratteristiche tecniche migliorabili — vincolo di scope |
| [[S.05_Layout_Cantiere]] | Layout logistico di cantiere — rilevante per l'audit strategico "viabilità cantiere", non per C1-C6 |

**Orfani non risolvibili — file assente dal filesystem (5):** stub creati per wikilink, elencati
nell'`ELENCO ELABORATI.xlsx` ma assenti da `00_input/`. Segnalati come `missing` fin dalla Fase 0-2
(vedi `02_graph/log.md`, entry `ingest-start`). Non processabili, non risolvibili da graph-builder.

| Documento | Nota |
|---|---|
| [[EG.08_Planimetria_Corpi_Illuminanti_ISOLUX_Piano_Terra]] | File assente — verificare con la stazione appaltante/progettista |
| [[EG.08.1_Planimetria_Corpi_Illuminanti_ISOLUX_Piano_Primo]] | File assente |
| [[EG.09_Schema_Unifilare]] | File assente |
| [[IT.01_Inquadramento_Territoriale]] | File assente |
| [[IT.02_Memoria_Fotografica]] | File assente |

### Documenti con soli archi ereditati (14 tavole, `confidence: inferito`)

Le seguenti tavole passano il check orfani (hanno `supports_criteria` non vuoto) ma **ogni** arco
verso un criterio è stato ereditato per corrispondenza di sezione/tema con la relazione generale,
senza lettura del contenuto grafico: EG.01, EG.02, EG.02.1, EG.02.2, EG.03, EG.04, EG.05, EG.05.1,
EG.05.2, EG.06, EG.07, EG.10, EG.11, EG.12. Coerente con la policy di Fase C (le tavole non vengono
mai estratte in questa fase). Da riaprire via `drawing-reader` on-demand in fase di analisi dei
criteri C1/C2/C3, specialmente [[EG.05.2_Pianta_Copertura_Stato_di_Progetto]] (massima priorità
tematica per C3).

### Contraddizioni rilevate (5, tutte da verifica manuale — Fase E, 2026-07-19)

CONTRADDIZIONE: Ripartizione opere opzionali C4/C5 — `03_criteria/criteria_matrix.md` e
`PROJECT_CONFIG.json` dichiarano C4 (B1, voci 01,02,04) = € 67.000,00 e C5 (B2, voci
03,05,06,07,08) = € 46.000,00; [[COMPUTO_OPERE_OPZIONALI]] (fonte contabile verificata voce per
voce) da' invece C4 = € 73.000,00 e C5 = € 40.000,00 (il totale € 113.000,00 coincide in entrambi
i casi — la contraddizione riguarda solo la ripartizione, non il totale). Dettaglio in
[[COMPUTO_OPERE_OPZIONALI]] ed `economic_framework.md`. — verifica manuale richiesta prima
dell'analisi dei criteri C4/C5

CONTRADDIZIONE: EPgl,nren stato di progetto — [[R.01_Relazione_Generale_e_Tecnica_Illustrativa]] §8
dichiara EPgl,nren post-operam = 19,9614 kWh/m²anno (superficie 2.723,5 mq);
[[R.03_Attestato_di_Prestazione_Energetica]] (APE) dichiara per lo stesso stato di progetto
EPgl,nren = 25,8212 kWh/m²anno (superficie 2.643,38 mq) — differenza ~30% relativa, entrambi classe
A4/nZEB, entrambi `confidence: verificato`. Dettaglio in
`02_graph/synthesis/prestazione_energetica_e_contraddizioni.md`. — verifica manuale richiesta prima
di formulare proposte quantitative sul risparmio energetico nel criterio C1

CONTRADDIZIONE: Esclusione caldaie a gas — [[R.02.1_Relazione_DNSH]] dichiara nella checklist Art.5
Item 0 "e' stata verificata l'esclusione dall'intervento delle caldaie a gas? → SI", ma
[[R.01_Relazione_Generale_e_Tecnica_Illustrativa]] (2 caldaie a condensazione ~33,80 kW cad.),
[[R.04_Relazione_Energetica_Ex_L10]] (caldaia a metano 194,80 kW) e
[[S.04_Piano_Sicurezza_Coordinamento]] (fase "installazione caldaia per impianto termico")
confermano indipendentemente la presenza di caldaie nell'impianto di progetto. Rilevante per
l'ammissibilita' PNRR (Regime 1). Dettaglio in
`02_graph/synthesis/prestazione_energetica_e_contraddizioni.md`. — verifica manuale richiesta

CONTRADDIZIONE: CIG frontespizio difforme — [[R.02_Relazione_CAM]] e [[R.02.1_Relazione_DNSH]]
riportano in frontespizio CIG B9C7EAF75F, diverso dal CIG di gara BC3ECFAA55 in
`PROJECT_CONFIG.json` (stesso CUP G13C25000920001 su entrambi). Non altera l'oggetto tecnico delle
relazioni. — verifica manuale richiesta con la stazione appaltante

CONTRADDIZIONE: Tilt/Azimut falda fotovoltaica nuova — [[R.04_Relazione_Energetica_Ex_L10]]
dichiara Tilt 30°/Azimut SUD_OVEST per la falda nuova (36,00 kWp),
[[R.05_Relazione_Impianto_Fotovoltaico]] dichiara Tilt 15,0°/Azimut 0,0° (Sud) per la stessa falda
(potenza e superficie coerenti tra i due documenti). Discrepanza minore, non bloccante per C3
secondo `02_graph/synthesis/impianto_fotovoltaico.md`. — verifica manuale raccomandata (lettura
tavole EG.05.2/EG.07 o chiarimento progettista)

---

## Re-ingest 2026-07-20 — C.01 e C.02 da estrazione parziale a integrale

Riscritte due sole pagine nodo, nessun altro nodo toccato.

| Nodo | Prima | Dopo |
|---|---|---|
| [[C.01_Computo_Metrico_Estimativo]] | pag. 1-3 + 24-25, `confidence: parziale`, `voci_count: TBD` | 26/26 pag., `confidence: verificato`, **101 voci** con codice tariffa + quantita' + prezzo unitario + importo; totale ricostruito € 915.809,83 = totale stampato (scostamento € 0,00) |
| [[C.02_Elenco_Prezzi_Unitari]] | pag. 1-2 (sola voce NP.01), `confidence: parziale`, `voci_count: TBD` | 10/10 pag., `confidence: verificato`, **98 voci** con codice + descrizione integrale + prezzo unitario; i 98 codici sono tutti usati in C.01 e i 98 prezzi coincidono 1:1 (0 scostamenti) |

**Dato strutturale nuovo — tripartizione dei codici tariffa.** Determina il perimetro di qualunque
price-gap check contro il Prezzario Regione Campania 2025:

| Famiglia | Voci in C.02 | Righe in C.01 | Importo (€) | % importo lavori | Confrontabile col prezzario |
|---|---:|---:|---:|---:|---|
| `CAM25_*` (Campania 2025) | 70 | 73 | 608.462,99 | 66,44% | **SI** |
| `NP.01`-`NP.12` (nuovi prezzi → [[C.03_Analisi_dei_Prezzi]]) | 12 | 12 | 260.184,34 | 28,41% | **NO** |
| sei cifre + lettera (fuori schema regionale) | 16 | 16 | 47.162,50 | 5,15% | **NO** |

Conseguenza per `strategy-auditor` e per l'analisi "gap prezzi": **il confronto col prezzario puo'
coprire al massimo il 66,44% dell'importo lavori.** I nuovi prezzi pesano da soli il 28,41% e sono
concentrati su poche voci di grande importo (NP.02 isolamento orizzontale € 111.587,28; NP.06 nuovo
impianto termico € 73.911,60/cad; NP.05 € 27.192,69; NP.04 € 23.401,78).

Avvertenze di matching sui codici (dettaglio nelle due pagine nodo): il suffisso `(CAM)` e' un
marcatore PriMus di conformita' CAM e non fa parte del codice di prezzario (usare la radice);
`205015e_` ha l'underscore finale come stampato; la categoria per singola voce non e' stampata nel
corpo del computo (nessuna attribuzione inferita); artefatti tipografici PriMus lasciati verbatim.

**Nessuna contraddizione economica introdotta:** il totale € 915.809,83 continua a coincidere con
la voce A.1 di [[C.07_Quadro_Economico]] e con `importo_lavori_eur` di
`02_graph/economic_framework.md`. `economic_framework.md` non e' stato modificato.

**Disallineamento aperto (non corretto, fuori mandato):** le pagine `criterion_C1.md`,
`criterion_C2.md`, `criterion_C3.md` elencano ancora [[C.02_Elenco_Prezzi_Unitari]] a
`priority: bassa` con motivazione "estrazione parziale", mentre la pagina nodo C.02 ora dichiara
`priority: media` con evidenza verificata. Da riallineare in una prossima esecuzione della Fase F.

## Problemi di lint aperti (non corretti in questa invocazione)

Riscontrati da `node scripts/graph/graph_lint.js` il 2026-07-19, dopo le correzioni testuali già
applicate (vedi sotto). Non rientrano nel mandato di questa invocazione (rewrite di pagine
criterio/nodo) — segnalati per il professionista o per un futuro re-ingest mirato:

- **`campo type mancante`** su tutte le 6 pagine `03_criteria/criteria/criterion_Cx.md`: sono
  pagine pre-esistenti create da `disciplinare-analyst`, che non popola il campo universale `type`.
  Lo schema (`references/graph-schema.md`) prevede che graph-builder arricchisca SOLO
  `supported_by`/`modification_limits`/`fuori_scope_risks`/`graph_updated` su queste pagine, senza
  toccare il resto del frontmatter o del corpo — quindi non corretto qui. Verificare con
  `disciplinare-analyst` se aggiungere `type: criterion` in un prossimo aggiornamento.
- **`index-nodo-fantasma` — 8 falsi positivi accertati, limite dello script, non del grafo**:
  `scripts/graph/graph_lint.js` (Check 5) risolve i wikilink dell'index solo contro
  `02_graph/nodes/`, e la sua regex di esclusione (`^(PROJECT_CONFIG|C\d|scope|economic_framework|P-C)`)
  non copre ne' il prefisso `criterion_` ne' la cartella `02_graph/synthesis/`. Di conseguenza
  segnala come "fantasma" 6 wikilink verso pagine criterio realmente esistenti
  (`[[criterion_C1]]` … `[[criterion_C6]]`, file in `03_criteria/criteria/`) e 2 wikilink verso
  pagine di sintesi realmente esistenti (`[[impianto_fotovoltaico]]`,
  `[[prestazione_energetica_e_contraddizioni]]`, file in `02_graph/synthesis/`). Verificato
  manualmente in questa invocazione: tutti e 8 i file target esistono e sono corretti. Non
  rientra nel mandato di questa invocazione modificare lo script condiviso — segnalato per un
  futuro intervento di manutenzione (estendere Check 5 a `03_criteria/criteria/` e
  `02_graph/synthesis/`, o ampliare la regex di esclusione).

## Correzioni testuali applicate (round precedente + verifica di questa invocazione)

Nota di formattazione: nelle righe seguenti i riferimenti alle forme errate/abbreviate sono
riportati SENZA la sintassi a doppia parentesi quadra, per non generare wikilink fantasma nel
lint (lo script `graph_lint.js` non distingue il testo tra backtick da un wikilink reale).

- 8 pagine economiche (`C.01`-`C.07`, `COMPUTO_OPERE_OPZIONALI`): sostituito il placeholder di
  template non risolto — letteralmente `PROJECT_CONFIG.gara.nome` tra doppie parentesi quadre —
  con il nome letterale della gara. Verificato in questa invocazione: nessuna occorrenza residua
  (vedi grep `PROJECT_CONFIG.gara.nome` su `02_graph/nodes/`, 0 risultati).
- `02_graph/economic_framework.md` e `02_graph/scope.md`: stesso placeholder corretto nel
  preambolo; corretti inoltre wikilink abbreviati/errati (testo `R.01_Relazione_Generale` →
  wikilink [[R.01_Relazione_Generale_e_Tecnica_Illustrativa]], testo `R.03_APE` → wikilink
  [[R.03_Attestato_di_Prestazione_Energetica]], wikilink malformato verso la pagina economica →
  riferimento a file semplice `02_graph/economic_framework.md`). Verificato in questa invocazione:
  nessun wikilink malformato residuo in `scope.md`/`economic_framework.md`.
- [[EG.02_Pianta_Piano_Terra_Stato_di_Fatto]]: wikilink abbreviato (testo `R.01` senza suffisso
  descrittivo) normalizzato a [[R.01_Relazione_Generale_e_Tecnica_Illustrativa]].
- [[EG.05.2_Pianta_Copertura_Stato_di_Progetto]]: wikilink abbreviato (testo `R.05` senza suffisso
  descrittivo) normalizzato a [[R.05_Relazione_Impianto_Fotovoltaico]] (rimossa anche la nota "non
  ancora estratta", non più vera: R.05 risulta `status: estratto` / `confidence: verificato`).
- Questa invocazione (Fase 4-5): riscritta questa sezione stessa, che nel round precedente
  conteneva i riferimenti errati tra doppie parentesi quadre a scopo illustrativo — causando 4
  falsi positivi `index-nodo-fantasma` nel lint sui token (senza parentesi, per non ricrearli qui)
  `R.01_Relazione_Generale`, `R.03_APE`, `R.01` e `R.05` usati da soli. Nessun'altra modifica di
  contenuto: i dati di scope.md, economic_framework.md e le 39 pagine nodo erano già corretti e
  non sono stati toccati.

---

## Statistiche

| Metrica | Valore |
|---|---|
| Pagine nodo totali | 39 |
| Documenti `status: estratto` | 16 |
| Documenti `status: non_estratto` (tavole/testuali non ancora letti) | 17 |
| Documenti `status: parziale` | 1 (S.05) |
| Documenti `status: missing` (stub, file assente) | 5 |
| Pagine di sintesi | 2 |
| Criteri arricchiti (`supported_by`) | 6/6 |
| Archi documento-documento (`related_documents`, righe `{ doc: ... }`) | 130 (124 + 6 aggiunti dal re-ingest 2026-07-20: +2 su C.01, +4 su C.02) |
| Documenti economici a estrazione integrale verificata | 2 (C.01, C.02 — re-ingest 2026-07-20) |
| Orfani totali (`supports_criteria` vuoto) | 12 (7 legittimi/intenzionali + 5 file mancanti) |
| Documenti con soli archi `confidence: inferito` verso criteri | 14 (tutte tavole) |
| Contraddizioni documentate | 5 |
| Proposte in `02_graph/proposals/` | 0 (nessun feedback ancora elaborato) |
| Lint — ERROR residui | 26 — 12 orfani (già motivati sopra) + 6 frontmatter `type` mancante su pagine criterio (fuori mandato) + 8 `index-nodo-fantasma` (falsi positivi accertati, limite dello script su `criterion_*`/synthesis) |
| Lint — WARN residui | 14 (archi-solo-ereditati, giudicati legittimi) |
| Lint — eseguito `scripts/graph/graph_lint.js` | 2026-07-19, exit code 1 (solo per gli ERROR sopra motivati; nessun difetto reale di grafo non giustificato) |

---

## Come usare questo indice

1. Per ogni criterio C1-C6: apri `03_criteria/criteria/criterion_Cx.md`, leggi `supported_by`, apri
   solo i documenti `priority: alta` per la lettura approfondita.
2. Prima di qualsiasi valutazione economica: leggi `02_graph/economic_framework.md` per intero,
   incluse le sezioni CONTRADDIZIONE.
3. Prima di proporre migliorie su una lavorazione specifica: verifica il perimetro in
   `02_graph/scope.md`.
4. Per le tavole: non assumere mai che `confidence: inferito` equivalga a "verificato". Riapri con
   `drawing-reader` quando l'evidenza serve per una proposta o un gap.
5. Per C4/C5: non usare acriticamente i valori di `criteria_matrix.md` senza segnalare la
   contraddizione sulla ripartizione delle opere opzionali.
