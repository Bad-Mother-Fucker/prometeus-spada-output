---
type: index
gara: "Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)"
date: 2026-10-03
ai-first: true
generato: "graph-builder invocazione 8 (Fasi 4-5) — rebuild completo, non accodato"
confidence: verificato
nodi: 53                      # confidence: verificato — file in 02_graph/nodes/
nodi_estratti: 23              # confidence: verificato — status: estratto
nodi_non_estratti: 30          # confidence: verificato — tavole, status: non_estratto
sintesi: 11                   # confidence: verificato — file in 02_graph/synthesis/
archi_doc_criterio: 114       # confidence: verificato — supports_criteria = supported_by
archi_doc_doc: 253            # confidence: verificato — related_documents
orfani: 3                     # confidence: verificato — supports_criteria: []
contraddizioni_irrisolte: 7   # confidence: verificato — economic_framework «Per l'index»
contraddizioni_risolte: 5     # confidence: verificato — D1, D7, D15, D17, D19 (gerarchia delle fonti)
quesiti_sa: 5                 # confidence: verificato — economic_framework §10.1
---

# Index — Knowledge graph della gara Cineteatro «Sala Polifunzionale Periz», Castello di Bella (PZ)

## Per Claude futuro

Questo è il catalogo del knowledge graph della gara «Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)» (CIG BCF01395AF), **rigenerato per intero il 2026-10-03** dall'invocazione 8 di graph-builder, dopo le Fasi 0-2 (censimento ed estrazione), A-C (pagine nodo, pagine speciali, sintesi) e D-F (archi, contraddizioni, criteri). È **il file da leggere per primo**. Contiene 53 pagine nodo (una per elaborato: 23 con testo estratto, 30 tavole non estratte), 11 pagine di sintesi tematiche, le pagine speciali [[scope]] ed [[economic_framework]], 114 archi documento→criterio e 253 archi documento→documento.

Percorso per analizzare un criterio Cx: (1) §3 di questo index → documenti `alta` del sottocriterio; (2) frontmatter `supported_by` di `03_criteria/criteria/criterion_Cx.md` (sottocriteri e confidence per arco); (3) pagina di sintesi del tema (§4); (4) pagine nodo e loro archi `related_documents`; (5) [[scope]] §2 (baseline di progetto per sottocriterio) e §6 (limiti di modifica), [[economic_framework]] §10 (registro contraddizioni D1-D19) e §10.1 (quesiti alla SA). **Prima di usare un valore numerico controlla la §7**: 7 contraddizioni sono irrisolte e quattro toccano le baseline dei sottocriteri C1.2, C2.3, C4.1, C4.2. Le 30 tavole hanno archi verso i criteri solo `inferito` (tranne PI-00a → C2, verificato sul disciplinare): leggerle con `drawing-reader` prima di citarle come evidenza. 3 documenti sono orfani (§6), da decidere con `/resolve_orphan`. Mai riportare prezzi o importi di questo grafo nell'offerta tecnica (pena l'esclusione, disciplinare art. 16). Confidence: verificato (conteggi letti dai frontmatter; esito del lint in §9).

## 1. Gara

| Voce | Valore | Fonte | Confidence |
|---|---|---|---|
| Gara | Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ) | `PROJECT_CONFIG.json` | verificato |
| CIG / CUP | BCF01395AF / D63I23000230009 | `PROJECT_CONFIG.json` | verificato |
| Stazione appaltante | Comune di Bella (PZ), Area III Lavori Pubblici; procedura su PAD ASMECOMM | `PROJECT_CONFIG.json` | verificato |
| Importo | 381.364,99 € soggetti a ribasso (di cui manodopera 47.849,85 €) + 13.005,47 € sicurezza = **394.370,46 €** IVA esclusa | [[economic_framework]] §1 | verificato |
| Punteggi | tecnica 90 (80 discrezionali C1-C4 + 10 tabellari C5-C7), economica 10; soglia di sbarramento 50/90 | `PROJECT_CONFIG.json`, `03_criteria/criteria_matrix.md` | verificato |
| Durata lavori | 150 giorni naturali e consecutivi, comprese forniture e posa | disciplinare art. 3.1 | verificato |
| Scadenze | richiesta sopralluogo **obbligatorio** 05/10/2026 ore 12:00 · quesiti 06/10/2026 ore 12:00 · offerta 14/10/2026 ore 12:00 | `PROJECT_CONFIG.json` | verificato |
| Offerta tecnica | relazione max 30 facciate A4 + computo metrico **non estimativo** + cronoprogramma; nessun elemento economico, pena esclusione | disciplinare art. 16 | verificato |
| Stato del grafo | completo: Fasi 0-2, A, B, C, D, E, F, 4-5 eseguite il 2026-10-03 | [log.md](log.md) | verificato |

## 2. Pagine speciali

| Pagina | Contenuto | Confidence |
|---|---|---|
| [[scope]] | Perimetro dei lavori: tutte le 139 voci del computo [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] (§4), voci NP (§5), **baseline di progetto per sottocriterio** con «cosa NON è previsto» (§2), limiti di modifica dalle pagine criterio (§6), regola d'uso per gli agenti | verificato (colonne SOA e baseline: inferito) |
| [[economic_framework]] | Cornice economica dalle sole versioni `is_latest`: importi (§1), verifica dei riferimenti del disciplinare (§2), incidenze (§3), SOA (§4), super-categorie (§5), QE (§7), sicurezza (§8), **registro contraddizioni D1-D19 (§10)**, **quesiti alla SA Q1-Q5 (§10.1)**, TBD (§13) | verificato |
| [log.md](log.md) | Registro append-only di tutte le operazioni sul grafo (Fasi 0-2, A-F, 4-5, lint) | — |
| [_census.md](_census.md) | Censimento dei 56 file di `00_input/`, liste ECONOMICI / TESTUALI / TAVOLE / ALTRO, riconciliazione con manifest ed elenco elaborati, gruppi di versione | verificato |

Numeri chiave (da [[economic_framework]]):

| Dato | Valore | Confidence |
|---|---|---|
| Lavori soggetti a ribasso | 381.364,99 € (= QE A1 = computo G-04-ESEC-02) | verificato |
| Oneri della sicurezza | 13.005,47 € = 3,410% dei lavori (SIC-03 = QE A4 = copia PSC: nessuna discordanza) | verificato |
| Manodopera dichiarata | 47.849,85 € = 12,547% (G-05; sottostimata di almeno 13.708,57 € sulle voci NP, D4) | verificato (valore), inferito (sottostima) |
| Forniture di arredo | 55.296,43 € = 14,5% (poltrone, palco e allestimento, 100% NP) | verificato |
| Quota a nuovi prezzi | 37,67% (143.667,94 €, 19 codici NP, 14 senza analisi) | verificato |
| Costo complessivo di progetto | 520.000,00 € (QE G-01-ESEC-02) | verificato |
| Confronto con prezzario regionale | **rinviato**: tariffa Basilicata non in cache, edizione non dichiarata (TBD) | TBD |

## 3. Criteri e documenti collegati

Fonte: frontmatter `supported_by` di `03_criteria/criteria/criterion_C1…C7.md` (Fase F), identico all'inverso dei `supports_criteria` delle pagine nodo (114 archi). «(inf.)» = arco `confidence: inferito` (tavola non letta o collegamento dedotto). «superato» = versione `is_latest: false`, solo per confronto, mai baseline. «trasversale» = cornice economica / verifica di anomalia (art. 23).

| Criterio | Titolo | Punti | Natura | Sottocriteri (pt) | Documenti collegati (alta / media / bassa) | Sintesi | Evidenza |
|---|---|---|---|---|---|---|---|
| [[C1]] | Involucro, Poltrone ed Efficientamento Acustico | 25 | D | C1.1 (10), C1.2 (7), C1.3 (8) | 29 (4 / 9 / 16) | [sala_e_poltrone](synthesis/sala_e_poltrone.md), [acustica_sala](synthesis/acustica_sala.md), [serramenti_e_ponti_termici](synthesis/serramenti_e_ponti_termici.md), [tutela_castello_e_impatto_visivo](synthesis/tutela_castello_e_impatto_visivo.md), [antincendio](synthesis/antincendio.md) | debole su C1.1, C1.2, C1.3 (§8) |
| [[C2]] | Energie Rinnovabili e Sistemi di Sicurezza | 30 | D | C2.1 (15), C2.2 (8), C2.3 (7) | 31 (6 / 10 / 15) | [fotovoltaico_e_accumulo](synthesis/fotovoltaico_e_accumulo.md), [tutela_castello_e_impatto_visivo](synthesis/tutela_castello_e_impatto_visivo.md), [copertura_terrazzi_e_cupola](synthesis/copertura_terrazzi_e_cupola.md), [antincendio](synthesis/antincendio.md) | debole su C2.1, C2.2, C2.3 (§8) |
| [[C3]] | Logistica Cantieri e Dotazioni Cinematografiche | 15 | D | C3.1 (5), C3.2 (5), C3.3 (5) | 30 (7 / 6 / 17) | [copertura_terrazzi_e_cupola](synthesis/copertura_terrazzi_e_cupola.md), [dotazioni_audio_video_scena](synthesis/dotazioni_audio_video_scena.md), [logistica_cantiere](synthesis/logistica_cantiere.md), [tutela_castello_e_impatto_visivo](synthesis/tutela_castello_e_impatto_visivo.md), [antincendio](synthesis/antincendio.md) | debole su C3.1, C3.2, C3.3 (§8) |
| [[C4]] | Accessibilità Universale e Criteri CAM | 10 | D | C4.1 (5), C4.2 (5) | 22 (5 / 7 / 10) | [ascensore](synthesis/ascensore.md), [cam_ed_economia_circolare](synthesis/cam_ed_economia_circolare.md), [logistica_cantiere](synthesis/logistica_cantiere.md), [serramenti_e_ponti_termici](synthesis/serramenti_e_ponti_termici.md) | debole su C4.1, C4.2 (§8) |
| [[C5]] | Esperienza specifica pregressa | 6 | T | C5.1 (6) | 2 (0 / 0 / 2) | — | atteso: curriculum dell'impresa |
| [[C6]] | Criteri premiali art. 57 e Allegato II.3 del D. Lgs. 36/2023 | 2 | T | C6.1 (2) | 0 (0 / 0 / 0) | — | atteso: status dell'impresa (L. 68/1999) |
| [[C7]] | Criteri premiali 108 co.7 del D. Lgs. 36/2023 | 2 | T | C7.1 (2) | 0 (0 / 0 / 0) | — | atteso: certificazione UNI/PdR 125:2022 |

### C1 — Involucro, Poltrone ed Efficientamento Acustico (25 pt, discrezionale)

| Sottocriterio | Pt | Documenti (di cui alta) | Documenti `alta` (punto di partenza per pdf-reader / drawing-reader) |
|---|---|---|---|
| C1.1 — Qualità, quantità ed efficientamento nodi dei nuovi infissi | 10 | 17 (4) | [[G-02-ESEC-01_ELENCO_PREZZI]], [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]], [[G-08-ESEC-01_RELAZIONE_GENERALE]], [[RS-03-ESEC-01_RELAZIONE_ACUSTICA]] |
| C1.2 — Fornitura quantitativa e qualità delle nuove poltrone | 7 | 13 (4) | [[G-02-ESEC-01_ELENCO_PREZZI]], [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]], [[G-08-ESEC-01_RELAZIONE_GENERALE]], [[RS-03-ESEC-01_RELAZIONE_ACUSTICA]] |
| C1.3 — Efficientamento e risanamento acustico dei materiali interni | 8 | 19 (4) | [[G-02-ESEC-01_ELENCO_PREZZI]], [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]], [[G-08-ESEC-01_RELAZIONE_GENERALE]], [[RS-03-ESEC-01_RELAZIONE_ACUSTICA]] |

- **alta** (4): [[G-02-ESEC-01_ELENCO_PREZZI]] (C1.1, C1.2, C1.3) · [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] (C1.1, C1.2, C1.3) · [[G-08-ESEC-01_RELAZIONE_GENERALE]] (C1.1, C1.2, C1.3) · [[RS-03-ESEC-01_RELAZIONE_ACUSTICA]] (C1.1, C1.2, C1.3)
- **media** (9): [[COM-PZ.REGISTRO-UFFICIALE.2026.0007341_Marcato]] (C1.1, C1.2, C1.3) · [[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]] (C1.1) · [[G-09-ESEC-01_RELAZIONE_CAM]] (C1.1, C1.3) · [[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]] (C1.1, C1.2) · [[SIC-01-ESEC-01_CRONOPROGRAMMA]] (C1.1, C1.2, C1.3) · [[G-07-ESEC-01_RELAZIONE_FOTOGRAFICA]] (C1.1, C1.2, C1.3; parziale) · [[PA-00-ESEC-01_PIANTE_stato_di_progetto]] (C1.1, C1.2, C1.3; inferito) · [[PA-01-ESEC-01_PROSPETTI_stato_di_progetto]] (C1.1; inferito) · [[PI-02-ESEC-01_PROGETTO_CON_INDICAZIONE_CLASSI_RESISTENZA_AL_FUOCO]] (C1.3; inferito)
- **bassa** (16): [[G-00-ESEC-01_ELENCO_ELABORATI]] (C1.1, C1.2, C1.3) · [[G-01-ESEC-01_QUADRO_ECONOMICO]] (trasversale; superato) · [[G-01-ESEC-02_QUADRO_ECONOMICO]] (trasversale) · [[G-04-ESEC-01_COMPUTO_METRICO_ESTIMATIVO]] (C1.1, C1.2, C1.3; superato) · [[G-05-ESEC-01_QUADRO_INCIDENZA_MANODOPERA]] (trasversale) · [[G-06-ESEC-01_CAPITOLATO_SPECIALE_D_APPALTO]] (C1.1; superato) · [[G-10-ESEC-01_PIANO_DI_MANUTENZIONE]] (C1.3) · [[G-11-ESEC-01_SCHEMA_DI_CONTRATTO]] (C1.2) · [[PA-02-ESEC-01_SEZIONI_stato_di_progetto]] (C1.3; inferito) · [[RIL-01-ESEC-01_PIANTE_stato_di_fatto]] (C1.1; inferito) · [[RIL-02-ESEC-01_PROSPETTI_stato_di_fatto]] (C1.1; inferito) · [[RS-02-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_IDRICO_ANTINCENDIO]] (C1.2, C1.3; inferito) · [[VVF-PI-02-00_PIANTA_PIANO_TERRA]] (C1.3; inferito) · [[VVF-PI-03-00_PIANTA_PIANO_PRIMO]] (C1.3; inferito) · [[VVF-PI-04-00_PIANTA_PIANO_SECONDO]] (C1.3; inferito) · [[VVF-PI-05-00_PIANTA_PIANO_TERZO]] (C1.3; inferito)
- Sintesi: [sala_e_poltrone](synthesis/sala_e_poltrone.md), [acustica_sala](synthesis/acustica_sala.md), [serramenti_e_ponti_termici](synthesis/serramenti_e_ponti_termici.md), [tutela_castello_e_impatto_visivo](synthesis/tutela_castello_e_impatto_visivo.md), [antincendio](synthesis/antincendio.md)

### C2 — Energie Rinnovabili e Sistemi di Sicurezza (30 pt, discrezionale)

| Sottocriterio | Pt | Documenti (di cui alta) | Documenti `alta` (punto di partenza per pdf-reader / drawing-reader) |
|---|---|---|---|
| C2.1 — Integrazione architettonica dell'impianto fotovoltaico (BIPV) | 15 | 21 (6) | [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]], [[G-08-ESEC-01_RELAZIONE_GENERALE]], [[PI-00a-ESEC-01_PLANIMETRIA_DI_INSIEME_CON_FOTOVOLTAICO_INTEGRATO_E_FOTOINSERIMENTI]], [[RS-00-ESEC-01_RELAZIONE_TECNICA_IMPIANTI]], [[RS-01-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_FOTOVOLTAICO]], [[PI-00-ESEC-01_PROGETTO_IMPIANTO_FOTOVOLTAICO]] (inf.) |
| C2.2 — Sistemi antintrusione e videosorveglianza | 8 | 12 (3) | [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]], [[G-08-ESEC-01_RELAZIONE_GENERALE]], [[RS-00-ESEC-01_RELAZIONE_TECNICA_IMPIANTI]] |
| C2.3 — Sistemi di accumulo e Building Automation | 7 | 21 (5) | [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]], [[G-08-ESEC-01_RELAZIONE_GENERALE]], [[RS-00-ESEC-01_RELAZIONE_TECNICA_IMPIANTI]], [[RS-01-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_FOTOVOLTAICO]], [[PI-00-ESEC-01_PROGETTO_IMPIANTO_FOTOVOLTAICO]] (inf.) |

- **alta** (6): [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] (C2.1, C2.2, C2.3) · [[G-08-ESEC-01_RELAZIONE_GENERALE]] (C2.1, C2.2, C2.3) · [[PI-00a-ESEC-01_PLANIMETRIA_DI_INSIEME_CON_FOTOVOLTAICO_INTEGRATO_E_FOTOINSERIMENTI]] (C2.1) · [[RS-00-ESEC-01_RELAZIONE_TECNICA_IMPIANTI]] (C2.1, C2.2, C2.3) · [[RS-01-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_FOTOVOLTAICO]] (C2.1, C2.3; parziale) · [[PI-00-ESEC-01_PROGETTO_IMPIANTO_FOTOVOLTAICO]] (C2.1, C2.3; inferito)
- **media** (10): [[G-02-ESEC-01_ELENCO_PREZZI]] (C2.1, C2.3) · [[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]] (C2.1, C2.2, C2.3) · [[G-09-ESEC-01_RELAZIONE_CAM]] (C2.3) · [[G-10-ESEC-01_PIANO_DI_MANUTENZIONE]] (C2.1, C2.2, C2.3) · [[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]] (C2.1, C2.3) · [[SIC-01-ESEC-01_CRONOPROGRAMMA]] (C2.1, C2.2, C2.3) · [[G-07-ESEC-01_RELAZIONE_FOTOGRAFICA]] (C2.1, C2.2; parziale) · [[PI-04-ESEC-01_INTERVENTI_TERMICI]] (C2.3; inferito) · [[PI-05-ESEC-01_INTERVENTI_ELETTRICI]] (C2.2, C2.3; inferito) · [[VVF-PI-08-00_AREE_A_RISCHIO_SPECIFICO]] (C2.3; inferito)
- **bassa** (15): [[G-00-ESEC-01_ELENCO_ELABORATI]] (C2.1) · [[G-01-ESEC-01_QUADRO_ECONOMICO]] (trasversale; superato) · [[G-01-ESEC-02_QUADRO_ECONOMICO]] (trasversale) · [[G-03-ESEC-01_ANALISI_NUOVI_PREZZI]] (C2.3) · [[G-04-ESEC-01_COMPUTO_METRICO_ESTIMATIVO]] (C2.1, C2.3; superato) · [[G-05-ESEC-01_QUADRO_INCIDENZA_MANODOPERA]] (trasversale) · [[G-06-ESEC-01_CAPITOLATO_SPECIALE_D_APPALTO]] (C2.1, C2.2, C2.3; superato) · [[RS-03-ESEC-01_RELAZIONE_ACUSTICA]] (C2.3) · [[COM-PZ.REGISTRO-UFFICIALE.2026.0007341_Marcato]] (C2.1, C2.2, C2.3; inferito) · [[IT-02-ESEC-00_INQUADRAMENTO_SU_ORTOFOTO]] (C2.1; inferito) · [[IT-03-ESEC-00_INQUADRAMENTO_SU_DTM_CURVE_DI_LIVELLO]] (C2.1; inferito) · [[PA-01-ESEC-01_PROSPETTI_stato_di_progetto]] (C2.1, C2.2; inferito) · [[PI-01-ESEC-01_SISTEMA_EVACUAZIONE_FUMI_FORZATO]] (C2.1, C2.3; inferito) · [[PI-03-ESEC-01_PROGETTO_IMPIANTO_IRAI]] (C2.2, C2.3; inferito) · [[VVF-PI-06-00_COPERTURA]] (C2.1; inferito)
- Sintesi: [fotovoltaico_e_accumulo](synthesis/fotovoltaico_e_accumulo.md), [tutela_castello_e_impatto_visivo](synthesis/tutela_castello_e_impatto_visivo.md), [copertura_terrazzi_e_cupola](synthesis/copertura_terrazzi_e_cupola.md), [antincendio](synthesis/antincendio.md)

### C3 — Logistica Cantieri e Dotazioni Cinematografiche (15 pt, discrezionale)

| Sottocriterio | Pt | Documenti (di cui alta) | Documenti `alta` (punto di partenza per pdf-reader / drawing-reader) |
|---|---|---|---|
| C3.1 — Risoluzione delle carenze termiche su terrazzi e cupola | 5 | 19 (6) | [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]], [[G-08-ESEC-01_RELAZIONE_GENERALE]], [[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]], [[SIC-01-ESEC-01_CRONOPROGRAMMA]], [[G-07-ESEC-01_RELAZIONE_FOTOGRAFICA]], [[PA-05-ESEC-01_cupola_e_impermeabilizzazione]] (inf.) |
| C3.2 — Attrezzature o arredi cinematografici migliorativi/aggiuntivi | 5 | 6 (2) | [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]], [[G-07-ESEC-01_RELAZIONE_FOTOGRAFICA]] |
| C3.3 — Logistica e piano di protezione delle attrezzature esistenti | 5 | 17 (6) | [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]], [[G-08-ESEC-01_RELAZIONE_GENERALE]], [[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]], [[SIC-01-ESEC-01_CRONOPROGRAMMA]], [[G-07-ESEC-01_RELAZIONE_FOTOGRAFICA]], [[SIC-02-ESEC-01_LAYOUT_DI_CANTIERE]] (inf.) |

- **alta** (7): [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] (C3.1, C3.2, C3.3) · [[G-08-ESEC-01_RELAZIONE_GENERALE]] (C3.1, C3.3) · [[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]] (C3.1, C3.3) · [[SIC-01-ESEC-01_CRONOPROGRAMMA]] (C3.1, C3.3) · [[G-07-ESEC-01_RELAZIONE_FOTOGRAFICA]] (C3.1, C3.2, C3.3; parziale) · [[PA-05-ESEC-01_cupola_e_impermeabilizzazione]] (C3.1; inferito) · [[SIC-02-ESEC-01_LAYOUT_DI_CANTIERE]] (C3.3; inferito)
- **media** (6): [[G-02-ESEC-01_ELENCO_PREZZI]] (C3.1, C3.2) · [[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]] (C3.1, C3.3) · [[G-09-ESEC-01_RELAZIONE_CAM]] (C3.1) · [[SIC-03-ESEC-01_COSTI_PER_LA_SICUREZZA]] (C3.3) · [[PA-02-ESEC-01_SEZIONI_stato_di_progetto]] (C3.1; inferito) · [[RIL-01-ESEC-01_PIANTE_stato_di_fatto]] (C3.1, C3.3; inferito)
- **bassa** (17): [[G-00-ESEC-01_ELENCO_ELABORATI]] (C3.1, C3.3) · [[G-01-ESEC-01_QUADRO_ECONOMICO]] (trasversale; superato) · [[G-01-ESEC-02_QUADRO_ECONOMICO]] (trasversale) · [[G-03-ESEC-01_ANALISI_NUOVI_PREZZI]] (C3.3) · [[G-04-ESEC-01_COMPUTO_METRICO_ESTIMATIVO]] (C3.1, C3.2; superato) · [[G-05-ESEC-01_QUADRO_INCIDENZA_MANODOPERA]] (C3.3) · [[G-06-ESEC-01_CAPITOLATO_SPECIALE_D_APPALTO]] (C3.1, C3.3; superato) · [[COM-PZ.REGISTRO-UFFICIALE.2026.0007341_Marcato]] (C3.2; inferito) · [[IT-01-ESEC-00_INQUADRAMENTO_SU_CTR]] (C3.3; inferito) · [[PA-00-ESEC-01_PIANTE_stato_di_progetto]] (C3.2, C3.3; inferito) · [[PI-00-ESEC-01_PROGETTO_IMPIANTO_FOTOVOLTAICO]] (C3.1; inferito) · [[PI-01-ESEC-01_SISTEMA_EVACUAZIONE_FUMI_FORZATO]] (C3.1; inferito) · [[RIL-00-ESEC-01_PLANIMETRIA_stato_di_fatto]] (C3.3; inferito) · [[RIL-02-ESEC-01_PROSPETTI_stato_di_fatto]] (C3.1; inferito) · [[RS-02-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_IDRICO_ANTINCENDIO]] (C3.3; inferito) · [[VVF-PI-06-00_COPERTURA]] (C3.1; inferito) · [[VVF-PI-07-00_PROSPETTO_E_SEZIONE]] (C3.1; inferito)
- Sintesi: [copertura_terrazzi_e_cupola](synthesis/copertura_terrazzi_e_cupola.md), [dotazioni_audio_video_scena](synthesis/dotazioni_audio_video_scena.md), [logistica_cantiere](synthesis/logistica_cantiere.md), [tutela_castello_e_impatto_visivo](synthesis/tutela_castello_e_impatto_visivo.md), [antincendio](synthesis/antincendio.md)

### C4 — Accessibilità Universale e Criteri CAM (10 pt, discrezionale)

| Sottocriterio | Pt | Documenti (di cui alta) | Documenti `alta` (punto di partenza per pdf-reader / drawing-reader) |
|---|---|---|---|
| C4.1 — Integrazioni tecnologiche e comfort dell'ascensore | 5 | 16 (5) | [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]], [[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]], [[G-08-ESEC-01_RELAZIONE_GENERALE]], [[G-09-ESEC-01_RELAZIONE_CAM]], [[PA-03-ESEC-01_PARTICOLARI_COSTRUTTIVI_scala_e_ascensore]] (inf.) |
| C4.2 — Criteri CAM avanzati, certificazioni di filiera ed economia circolare | 5 | 16 (4) | [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]], [[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]], [[G-09-ESEC-01_RELAZIONE_CAM]], [[PA-03-ESEC-01_PARTICOLARI_COSTRUTTIVI_scala_e_ascensore]] (inf.) |

- **alta** (5): [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] (C4.1, C4.2) · [[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]] (C4.1, C4.2) · [[G-08-ESEC-01_RELAZIONE_GENERALE]] (C4.1) · [[G-09-ESEC-01_RELAZIONE_CAM]] (C4.1, C4.2) · [[PA-03-ESEC-01_PARTICOLARI_COSTRUTTIVI_scala_e_ascensore]] (C4.1, C4.2; inferito)
- **media** (7): [[G-02-ESEC-01_ELENCO_PREZZI]] (C4.1, C4.2) · [[G-10-ESEC-01_PIANO_DI_MANUTENZIONE]] (C4.1, C4.2) · [[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]] (C4.1, C4.2) · [[SIC-01-ESEC-01_CRONOPROGRAMMA]] (C4.1, C4.2) · [[G-07-ESEC-01_RELAZIONE_FOTOGRAFICA]] (C4.1, C4.2; parziale) · [[PA-04-ESEC-01_PARTICOLARI_COSTRUTTIVI_collegamenti_verticali]] (C4.1; inferito) · [[PI-02-ESEC-01_PROGETTO_CON_INDICAZIONE_CLASSI_RESISTENZA_AL_FUOCO]] (C4.2; inferito)
- **bassa** (10): [[G-00-ESEC-01_ELENCO_ELABORATI]] (C4.1, C4.2) · [[G-01-ESEC-01_QUADRO_ECONOMICO]] (trasversale; superato) · [[G-01-ESEC-02_QUADRO_ECONOMICO]] (trasversale) · [[G-04-ESEC-01_COMPUTO_METRICO_ESTIMATIVO]] (C4.1, C4.2; superato) · [[G-05-ESEC-01_QUADRO_INCIDENZA_MANODOPERA]] (trasversale) · [[G-06-ESEC-01_CAPITOLATO_SPECIALE_D_APPALTO]] (C4.1, C4.2; superato) · [[SIC-03-ESEC-01_COSTI_PER_LA_SICUREZZA]] (C4.2) · [[PA-00-ESEC-01_PIANTE_stato_di_progetto]] (C4.1, C4.2; inferito) · [[PA-02-ESEC-01_SEZIONI_stato_di_progetto]] (C4.1; inferito) · [[SIC-02-ESEC-01_LAYOUT_DI_CANTIERE]] (C4.2; inferito)
- Sintesi: [ascensore](synthesis/ascensore.md), [cam_ed_economia_circolare](synthesis/cam_ed_economia_circolare.md), [logistica_cantiere](synthesis/logistica_cantiere.md), [serramenti_e_ponti_termici](synthesis/serramenti_e_ponti_termici.md)

### C5 — Esperienza specifica pregressa (6 pt, tabellare)

| Sottocriterio | Pt | Documenti (di cui alta) | Documenti `alta` (punto di partenza per pdf-reader / drawing-reader) |
|---|---|---|---|
| C5.1 — Esperienza pregressa di realizzazione di interventi analoghi su immobili destinati a cinema, teatro, cineteatri o altri edifici destinati prevalentemente ad attività di spettacolo e intrattenimento aperti al pubblico | 6 | 2 (0) | — |

- **bassa** (2): [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] (C5.1) · [[G-08-ESEC-01_RELAZIONE_GENERALE]] (C5.1)
- Sintesi: —

### C6 — Criteri premiali art. 57 e Allegato II.3 del D. Lgs. 36/2023 (2 pt, tabellare)

Nessun elaborato collegato (`supported_by: []` in `03_criteria/criteria/criterion_C6.md`). **Atteso**: criterio tabellare, il punteggio dipende dallo status dell'impresa e non dagli elaborati di progetto. Sottocriterio: C6.1 — Clausole sociali e meccanismi premiali per realizzare le pari opportunità generazionali e di genere e per promuovere l'inclusione lavorativa delle persone con disabilità o persone svantaggiate (2 pt).

### C7 — Criteri premiali 108 co.7 del D. Lgs. 36/2023 (2 pt, tabellare)

Nessun elaborato collegato (`supported_by: []` in `03_criteria/criteria/criterion_C7.md`). **Atteso**: criterio tabellare, il punteggio dipende dallo status dell'impresa e non dagli elaborati di progetto. Sottocriterio: C7.1 — Adozione di politiche tese al raggiungimento della parità di genere (2 pt).

**Tavole `alta` non ancora lette** (priorità per `drawing-reader`): [[PI-00a-ESEC-01_PLANIMETRIA_DI_INSIEME_CON_FOTOVOLTAICO_INTEGRATO_E_FOTOINSERIMENTI]] e [[PI-00-ESEC-01_PROGETTO_IMPIANTO_FOTOVOLTAICO]] (C2.1, 15 pt), [[PA-05-ESEC-01_cupola_e_impermeabilizzazione]] (C3.1), [[SIC-02-ESEC-01_LAYOUT_DI_CANTIERE]] (C3.3), [[PA-03-ESEC-01_PARTICOLARI_COSTRUTTIVI_scala_e_ascensore]] (C4.1).

## 4. Pagine di sintesi

11 pagine in `02_graph/synthesis/` (synthesis hook: tema trattato da tre o più elaborati). Linkate come percorso e non come wikilink perché `graph_lint.js` risolve solo `nodes/`, criteri e pagine speciali. Ogni sintesi ha nel frontmatter `criteri` e la lista `documenti` (wikilink ai nodi).

| Sintesi | Tema | Sottocriteri | Documenti collegati | Fatto chiave |
|---|---|---|---|---|
| [acustica_sala](synthesis/acustica_sala.md) | Acustica della sala: tempo di riverbero, materiali di finitura, poltrone | C1.3, C1.2 | 11 | Unica fonte numerica RS-03: T60 di Sabine 0,79 s a 500 Hz, V = 986 m³; STI, C50, C80 non calcolati |
| [antincendio](synthesis/antincendio.md) | Prevenzione incendi: rete naspi, compartimentazioni, evacuazione fumi, parere VV.F. | vincolo per C1, C2, C3 | 22 | Nessun sub premia l'antincendio. Sprinkler inesistenti (D15); 4 naspi DN25 (RS-02, PI-06) vs cassette UNI 45 (computo voce 122); parere VV.F. favorevole 20/04/2026 |
| [ascensore](synthesis/ascensore.md) | Ascensore per l'abbattimento delle barriere architettoniche (vano circolare) | C4.1 | 11 | Dati non coerenti (D14: idraulico vs «elettrico a fune»; 6 pers./3 fermate vs 8 pers./6 fermate); nessun telecontrollo, sintesi vocale o isolamento acustico della cabina |
| [cam_ed_economia_circolare](synthesis/cam_ed_economia_circolare.md) | Criteri Ambientali Minimi (CAM), certificazioni di filiera ed economia circolare dei rifiuti di cantiere | C4.2 | 13 | Tre edizioni dei CAM negli elaborati, nessuna è il D.M. 24.11.2025 del disciplinare (D11); relazione CAM G-09 solo dichiarativa |
| [copertura_terrazzi_e_cupola](synthesis/copertura_terrazzi_e_cupola.md) | Copertura piana, terrazzi e cupola in acciaio e vetro | C3.1, C2.1 | 17 | Impermeabilizzazione poliureica, fori di evacuazione fumi e pellicola antisolare sulla cupola; nessun isolamento termico della copertura |
| [dotazioni_audio_video_scena](synthesis/dotazioni_audio_video_scena.md) | Dotazioni cinematografiche, audio-video e di scena: esistenti e di progetto | C3.2, C3.3 | 16 | Configurazione base solo scenica (NP 07 palco e allestimento); nessun censimento di audio, proiettori e schermo esistenti; i «proiettori» della voce 58 sono plafoniere LED |
| [fotovoltaico_e_accumulo](synthesis/fotovoltaico_e_accumulo.md) | Impianto fotovoltaico, accumulo e gestione energetica | C2.1, C2.3 (C2.2) | 16 | 5,85 kWp su staffe inclinate (non integrato); accumulo 15 kWh (computo) vs 20 kWh (G-08) — D13 |
| [logistica_cantiere](synthesis/logistica_cantiere.md) | Logistica di cantiere in centro storico, fasi, stoccaggi e protezione dell'esistente | C3.3, C4.2 | 11 | PSC, cronoprogramma, layout e costi della sicurezza; nessun elaborato tratta le attrezzature cinematografiche esistenti |
| [sala_e_poltrone](synthesis/sala_e_poltrone.md) | Sala, poltrone e posti a sedere | C1.2, C1.3 | 20 | 134 poltrone «Operapulia art. 310 Social», nessuna scorta né garanzia di prodotto; posti 134 vs 128 della pratica VV.F. (D18) |
| [serramenti_e_ponti_termici](synthesis/serramenti_e_ponti_termici.md) | Serramenti esterni, nodi di posa e ponti termici | C1.1, C4.2 | 16 | Unico dato prestazionale: G-02 Nr. 24 (Uw 0,90-1,09 W/m²K, Uf ≤ 1,4, Rw ≤ 37 dB); relazione ex L. 10/91 e abaco serramenti assenti; fattore solare 50-60% vs 0,35 |
| [tutela_castello_e_impatto_visivo](synthesis/tutela_castello_e_impatto_visivo.md) | Tutela del Castello Aragonese e impatto visivo degli interventi in copertura e in facciata | C2.1, C1.1, C3.1 | 20 | Nessun elaborato riporta indirizzi, pareri o prescrizioni della Soprintendenza; impatto visivo solo da foto G-07 e tavole di contesto |

### Mappa criterio → sintesi

Fonte: mappa della Fase F (log, 6 sintesi della Fase B) integrata con il campo `criteri` delle 5 sintesi create dalla Fase D. Le pagine criterio non hanno un campo per le sintesi (non previsto dallo schema `criterion`): questa mappa vive solo nell'index.

| Criterio | Sintesi da leggere (in ordine) | Note |
|---|---|---|
| [[C1]] | [sala_e_poltrone](synthesis/sala_e_poltrone.md) (C1.2, C1.3) · [acustica_sala](synthesis/acustica_sala.md) (C1.3) · [serramenti_e_ponti_termici](synthesis/serramenti_e_ponti_termici.md) (C1.1) · [tutela_castello_e_impatto_visivo](synthesis/tutela_castello_e_impatto_visivo.md) (C1.1, vincolo) · [antincendio](synthesis/antincendio.md) (vincolo) | reazione al fuoco di MDF e poltrone: vincolo da `antincendio` |
| [[C2]] | [fotovoltaico_e_accumulo](synthesis/fotovoltaico_e_accumulo.md) (C2.1, C2.3) · [tutela_castello_e_impatto_visivo](synthesis/tutela_castello_e_impatto_visivo.md) (C2.1) · [copertura_terrazzi_e_cupola](synthesis/copertura_terrazzi_e_cupola.md) (C2.1, supporto fisico) · [antincendio](synthesis/antincendio.md) (vincolo C2.1, C2.3) | C2.2 (antintrusione / TVCC, 8 pt) **non ha una sintesi**: il tema è assente da tutti gli elaborati (nessuna voce di computo) |
| [[C3]] | [copertura_terrazzi_e_cupola](synthesis/copertura_terrazzi_e_cupola.md) (C3.1) · [dotazioni_audio_video_scena](synthesis/dotazioni_audio_video_scena.md) (C3.2, C3.3) · [logistica_cantiere](synthesis/logistica_cantiere.md) (C3.3) · [tutela_castello_e_impatto_visivo](synthesis/tutela_castello_e_impatto_visivo.md) (C3.1, vincolo) · [antincendio](synthesis/antincendio.md) (vincolo C3.1-C3.3) | |
| [[C4]] | [ascensore](synthesis/ascensore.md) (C4.1) · [cam_ed_economia_circolare](synthesis/cam_ed_economia_circolare.md) (C4.2) · [logistica_cantiere](synthesis/logistica_cantiere.md) (C4.2, polveri e vibrazioni) · [serramenti_e_ponti_termici](synthesis/serramenti_e_ponti_termici.md) (C4.2, CAM serramenti) | |
| [[C5]], [[C6]], [[C7]] | — | criteri tabellari: nessuna sintesi pertinente |

## 5. Documenti per sezione

53 pagine nodo in `02_graph/nodes/`. Sezione = prefisso del codice elaborato (convenzione di questo progetto, vedi [_census.md](_census.md)). Colonna «Criteri»: archi `supports_criteria` della pagina con priorità; «(inf.)» = arco inferito. «Archi doc-doc» = numero di voci `related_documents`. Non hanno pagina nodo, per scelta della Fase 1: il disciplinare e il bando (fonte di `03_criteria/`) e `norme.tecniche` (norme d'uso della piattaforma, non pertinenti).

### G — Documenti generali, economici e contrattuali (15)

| Documento | Descrizione | Subtype | Estrazione · confidence | Criteri (priorità) | Archi doc-doc |
|---|---|---|---|---|---|
| [[G-00-ESEC-01_ELENCO_ELABORATI]] | Elenco Elaborati | altro | estratto · verificato | C1 bassa · C2 bassa · C3 bassa · C4 bassa | 39 |
| [[G-01-ESEC-01_QUADRO_ECONOMICO]] | Quadro economico (revisione aprile 2026, SUPERATA) — **superato** da [[G-01-ESEC-02_QUADRO_ECONOMICO]] (`is_latest: false`) | quadro_economico | estratto · verificato | C1 bassa · C2 bassa · C3 bassa · C4 bassa | 2 |
| [[G-01-ESEC-02_QUADRO_ECONOMICO]] | Quadro economico (revisione maggio 2026) | quadro_economico | estratto · verificato | C1 bassa · C2 bassa · C3 bassa · C4 bassa | 3 |
| [[G-02-ESEC-01_ELENCO_PREZZI]] | Elenco prezzi unitari | elenco_prezzi | estratto · verificato | C1 alta · C2 media · C3 media · C4 media | 5 |
| [[G-03-ESEC-01_ANALISI_NUOVI_PREZZI]] | Analisi nuovi prezzi | elenco_prezzi | estratto · verificato | C2 bassa · C3 bassa | 3 |
| [[G-04-ESEC-01_COMPUTO_METRICO_ESTIMATIVO]] | Computo metrico estimativo (revisione aprile 2026, SUPERATA) — **superato** da [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] (`is_latest: false`) | computo_metrico | estratto · verificato | C1 bassa · C2 bassa · C3 bassa · C4 bassa | 2 |
| [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] | Computo metrico estimativo (revisione maggio 2026) | computo_metrico | estratto · verificato | C1 alta · C2 alta · C3 alta · C4 alta · C5 bassa | 7 |
| [[G-05-ESEC-01_QUADRO_INCIDENZA_MANODOPERA]] | Quadro incidenza manodopera | quadro_manodopera | estratto · verificato | C1 bassa · C2 bassa · C3 bassa · C4 bassa | 3 |
| [[G-06-ESEC-01_CAPITOLATO_SPECIALE_D_APPALTO]] | Capitolato Speciale d'Appalto (revisione aprile 2026, SUPERATA) — **superato** da [[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]] (`is_latest: false`) | capitolato | estratto · verificato | C1 bassa · C2 bassa · C3 bassa · C4 bassa | 7 |
| [[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]] | Capitolato Speciale d'Appalto (revisione maggio 2026) | capitolato | estratto · verificato | C1 media · C2 media · C3 media · C4 alta | 9 |
| [[G-07-ESEC-01_RELAZIONE_FOTOGRAFICA]] | Relazione Fotografica | relazione_tecnica | estratto · parziale | C1 media · C2 media · C3 alta · C4 media | 9 |
| [[G-08-ESEC-01_RELAZIONE_GENERALE]] | Relazione Generale | relazione_generale | estratto · verificato | C1 alta · C2 alta · C3 alta · C4 alta · C5 bassa | 17 |
| [[G-09-ESEC-01_RELAZIONE_CAM]] | Relazione CAM (Criteri Ambientali Minimi) | relazione_tecnica | estratto · verificato | C4 alta · C1 media · C3 media · C2 media | 8 |
| [[G-10-ESEC-01_PIANO_DI_MANUTENZIONE]] | Piano di manutenzione | relazione_tecnica | estratto · verificato | C2 media · C4 media · C1 bassa | 2 |
| [[G-11-ESEC-01_SCHEMA_DI_CONTRATTO]] | Schema di Contratto | altro | estratto · verificato | C1 bassa | 5 |

### RS — Relazioni specialistiche (4)

| Documento | Descrizione | Subtype | Estrazione · confidence | Criteri (priorità) | Archi doc-doc |
|---|---|---|---|---|---|
| [[RS-00-ESEC-01_RELAZIONE_TECNICA_IMPIANTI]] | Relazione tecnica impianti | relazione_tecnica | estratto · verificato | C2 alta | 8 |
| [[RS-01-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_FOTOVOLTAICO]] | Relazione tecnica impianto fotovoltaico | relazione_tecnica | estratto · parziale | C2 alta | 6 |
| [[RS-02-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_IDRICO_ANTINCENDIO]] | Relazione tecnica impianto idrico antincendio | relazione_tecnica | estratto · verificato | C1 bassa · C3 bassa | 12 |
| [[RS-03-ESEC-01_RELAZIONE_ACUSTICA]] | Relazione acustica | relazione_tecnica | estratto · verificato | C1 alta · C2 bassa | 4 |

### SIC — Sicurezza e cantiere (4)

| Documento | Descrizione | Subtype | Estrazione · confidence | Criteri (priorità) | Archi doc-doc |
|---|---|---|---|---|---|
| [[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]] | Piano di Sicurezza e Coordinamento (PSC) | PSC | estratto · verificato | C3 alta · C4 media · C2 media · C1 media | 9 |
| [[SIC-01-ESEC-01_CRONOPROGRAMMA]] | Cronoprogramma | cronoprogramma | estratto · verificato | C3 alta · C1 media · C2 media · C4 media | 7 |
| [[SIC-02-ESEC-01_LAYOUT_DI_CANTIERE]] | Layout di cantiere | tavola | non estratto · inferito | C3 alta (inf.) · C4 bassa (inf.) | 5 |
| [[SIC-03-ESEC-01_COSTI_PER_LA_SICUREZZA]] | Costi per la sicurezza | stima_sicurezza | estratto · verificato | C3 media · C4 bassa | 4 |

### IT — Inquadramento territoriale (tavole) (4)

| Documento | Descrizione | Subtype | Estrazione · confidence | Criteri (priorità) | Archi doc-doc |
|---|---|---|---|---|---|
| [[IT-00-ESEC-01_INQUADRAMENTO_SU_IGM]] | Inquadramento su IGM | tavola | non estratto · inferito | — **ORFANO** (§6) | 3 |
| [[IT-01-ESEC-00_INQUADRAMENTO_SU_CTR]] | Inquadramento su CTR | tavola | non estratto · inferito | C3 bassa (inf.) | 3 |
| [[IT-02-ESEC-00_INQUADRAMENTO_SU_ORTOFOTO]] | Inquadramento su ortofoto | tavola | non estratto · inferito | C2 bassa (inf.) | 3 |
| [[IT-03-ESEC-00_INQUADRAMENTO_SU_DTM_CURVE_DI_LIVELLO]] | Inquadramento su DTM e curve di livello | tavola | non estratto · inferito | C2 bassa (inf.) | 3 |

### RIL — Rilievo dello stato di fatto (tavole) (3)

| Documento | Descrizione | Subtype | Estrazione · confidence | Criteri (priorità) | Archi doc-doc |
|---|---|---|---|---|---|
| [[RIL-00-ESEC-01_PLANIMETRIA_stato_di_fatto]] | Planimetria, stato di fatto | tavola | non estratto · inferito | C3 bassa (inf.) | 3 |
| [[RIL-01-ESEC-01_PIANTE_stato_di_fatto]] | Piante, stato di fatto | tavola | non estratto · inferito | C3 media (inf.) · C1 bassa (inf.) | 3 |
| [[RIL-02-ESEC-01_PROSPETTI_stato_di_fatto]] | Prospetti, stato di fatto | tavola | non estratto · inferito | C1 bassa (inf.) · C3 bassa (inf.) | 3 |

### PA — Progetto architettonico (tavole) (6)

| Documento | Descrizione | Subtype | Estrazione · confidence | Criteri (priorità) | Archi doc-doc |
|---|---|---|---|---|---|
| [[PA-00-ESEC-01_PIANTE_stato_di_progetto]] | Piante, stato di progetto | tavola | non estratto · inferito | C1 media (inf.) · C3 bassa (inf.) · C4 bassa (inf.) | 3 |
| [[PA-01-ESEC-01_PROSPETTI_stato_di_progetto]] | Prospetti, stato di progetto | tavola | non estratto · inferito | C1 media (inf.) · C2 bassa (inf.) | 2 |
| [[PA-02-ESEC-01_SEZIONI_stato_di_progetto]] | Sezioni, stato di progetto | tavola | non estratto · inferito | C3 media (inf.) · C1 bassa (inf.) · C4 bassa (inf.) | 3 |
| [[PA-03-ESEC-01_PARTICOLARI_COSTRUTTIVI_scala_e_ascensore]] | Particolari costruttivi: corpo scala e ascensore | tavola | non estratto · inferito | C4 alta (inf.) | 2 |
| [[PA-04-ESEC-01_PARTICOLARI_COSTRUTTIVI_collegamenti_verticali]] | Particolari costruttivi: collegamenti verticali con il palco | tavola | non estratto · inferito | C4 media (inf.) | 2 |
| [[PA-05-ESEC-01_cupola_e_impermeabilizzazione]] | Particolari costruttivi: cupola e impermeabilizzazione | tavola | non estratto · inferito | C3 alta (inf.) | 2 |

### PI — Progetto impianti (tavole) (8)

| Documento | Descrizione | Subtype | Estrazione · confidence | Criteri (priorità) | Archi doc-doc |
|---|---|---|---|---|---|
| [[PI-00-ESEC-01_PROGETTO_IMPIANTO_FOTOVOLTAICO]] | Progetto impianto fotovoltaico | tavola | non estratto · inferito | C2 alta (inf.) · C3 bassa (inf.) | 4 |
| [[PI-00a-ESEC-01_PLANIMETRIA_DI_INSIEME_CON_FOTOVOLTAICO_INTEGRATO_E_FOTOINSERIMENTI]] | Planimetria di insieme con fotovoltaico integrato e fotoinserimenti | tavola | non estratto · inferito | C2 alta | 1 |
| [[PI-01-ESEC-01_SISTEMA_EVACUAZIONE_FUMI_FORZATO]] | Sistema di evacuazione fumi forzato | tavola | non estratto · inferito | C3 bassa (inf.) · C2 bassa (inf.) | 2 |
| [[PI-02-ESEC-01_PROGETTO_CON_INDICAZIONE_CLASSI_RESISTENZA_AL_FUOCO]] | Progetto con indicazione delle classi di reazione (o resistenza) al fuoco | tavola | non estratto · inferito | C1 media (inf.) · C4 media (inf.) | 2 |
| [[PI-03-ESEC-01_PROGETTO_IMPIANTO_IRAI]] | Progetto impianto IRAI | tavola | non estratto · inferito | C2 bassa (inf.) | 2 |
| [[PI-04-ESEC-01_INTERVENTI_TERMICI]] | Interventi termici | tavola | non estratto · inferito | C2 media (inf.) | 2 |
| [[PI-05-ESEC-01_INTERVENTI_ELETTRICI]] | Interventi elettrici | tavola | non estratto · inferito | C2 media (inf.) | 2 |
| [[PI-06-ESEC-01_IMPIANTO_IDRICO_ANTINCENDIO]] | Impianto idrico antincendio | tavola | non estratto · inferito | — **ORFANO** (§6) | 3 |

### VVF-PI — Pratica di prevenzione incendi VV.F. 21079 (tavole, fuori elenco elaborati) (8)

| Documento | Descrizione | Subtype | Estrazione · confidence | Criteri (priorità) | Archi doc-doc |
|---|---|---|---|---|---|
| [[VVF-PI-01-00_PLANIMETRIA_GENERALE]] | Pratica VV.F. 21079: planimetria generale | tavola | non estratto · inferito | — **ORFANO** (§6) | 2 |
| [[VVF-PI-02-00_PIANTA_PIANO_TERRA]] | Pratica VV.F. 21079: pianta piano terra | tavola | non estratto · inferito | C1 bassa (inf.) | 2 |
| [[VVF-PI-03-00_PIANTA_PIANO_PRIMO]] | Pratica VV.F. 21079: pianta piano primo | tavola | non estratto · inferito | C1 bassa (inf.) | 2 |
| [[VVF-PI-04-00_PIANTA_PIANO_SECONDO]] | Pratica VV.F. 21079: pianta piano secondo | tavola | non estratto · inferito | C1 bassa (inf.) | 2 |
| [[VVF-PI-05-00_PIANTA_PIANO_TERZO]] | Pratica VV.F. 21079: pianta piano terzo | tavola | non estratto · inferito | C1 bassa (inf.) | 2 |
| [[VVF-PI-06-00_COPERTURA]] | Pratica VV.F. 21079: copertura | tavola | non estratto · inferito | C2 bassa (inf.) · C3 bassa (inf.) | 2 |
| [[VVF-PI-07-00_PROSPETTO_E_SEZIONE]] | Pratica VV.F. 21079: prospetto e sezione | tavola | non estratto · inferito | C3 bassa (inf.) | 2 |
| [[VVF-PI-08-00_AREE_A_RISCHIO_SPECIFICO]] | Pratica VV.F. 21079: aree a rischio specifico | tavola | non estratto · inferito | C2 media (inf.) | 2 |

### COM-PZ — Parere del Comando VV.F. di Potenza (fuori elenco elaborati) (1)

| Documento | Descrizione | Subtype | Estrazione · confidence | Criteri (priorità) | Archi doc-doc |
|---|---|---|---|---|---|
| [[COM-PZ.REGISTRO-UFFICIALE.2026.0007341_Marcato]] | Parere favorevole VV.F., Pratica PI 21079 | altro | estratto · verificato | C1 media · C2 bassa · C3 bassa | 8 |

## 6. Orfani — ALERT

> ALERT — 3 documenti senza alcun arco verso un criterio (`supports_criteria: []`): [[IT-00-ESEC-01_INQUADRAMENTO_SU_IGM]], [[PI-06-ESEC-01_IMPIANTO_IDRICO_ANTINCENDIO]], [[VVF-PI-01-00_PLANIMETRIA_GENERALE]]. Restano raggiungibili dagli archi `related_documents` e dalle sintesi, ma **nessuna analisi di criterio li aprirà**. Non sono stati collegati d'iniziativa: la decisione spetta al professionista con `/resolve_orphan`. Già segnalati come «orfani potenziali» dalla Fase C e confermati dalla Fase F.

| Documento | Cosa rappresenta | Valutazione | Proposta motivata per `/resolve_orphan` |
|---|---|---|---|
| [[IT-00-ESEC-01_INQUADRAMENTO_SU_IGM]] | Inquadramento territoriale su cartografia IGM 1:25000 (1 foglio A1, apr. 2026) | **Orfano giustificato**: puro contesto geografico, nessun sottocriterio riguarda la scala territoriale. Il contesto paesaggistico utile a C2.1 è già coperto da IT-02 (ortofoto) e IT-03 (DTM), collegate a C2 bassa, e dalla sintesi [tutela_castello_e_impatto_visivo](synthesis/tutela_castello_e_impatto_visivo.md), che lo cita | **Lasciare orfano** (confermare la giustificazione). Alternativa minima, sconsigliata: C2 bassa, sub C2.1, `confidence: inferito`, reason «contesto paesaggistico del Castello a scala territoriale» |
| [[PI-06-ESEC-01_IMPIANTO_IDRICO_ANTINCENDIO]] | Rete idrica antincendio: 4 naspi DN25 UNI EN 671-1 (3 fogli A1, 1:100) | **Orfano non giustificato del tutto**: nessun sottocriterio premia l'antincendio, ma la tavola è un **vincolo fisico** per due migliorie. La sua relazione [[RS-02-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_IDRICO_ANTINCENDIO]] è già collegata a C1 bassa (C1.2, C1.3) e C3 bassa (C3.3) con lo stesso ragionamento; la sintesi [antincendio](synthesis/antincendio.md) lo esplicita. La Fase E (D15) segnala il residuo naspi DN25 (RS-02, PI-06) vs cassette UNI 45 (computo voce 122): solo la tavola dice dove stanno i terminali | **Collegare come vincolo**: C1 bassa, sub C1.3, `confidence: inferito`, reason «posizione di naspi / cassette UNI 45: pannelli MDF e rivestimenti acustici non devono coprirli né ridurne lo spazio di manovra»; C3 bassa, sub C3.3, `confidence: inferito`, reason «depositi temporanei delle attrezzature smontate e percorsi di cantiere senza ostacolare naspi e vie d'esodo» |
| [[VVF-PI-01-00_PLANIMETRIA_GENERALE]] | Planimetria generale della pratica VV.F. 21079 (accessi, area esterna, idrante esterno, attacco motopompa), parere favorevole COM-PZ 20/04/2026 | **Orfano in gran parte giustificato**: nessun sottocriterio riguarda la prevenzione incendi; unico uso plausibile è la logistica esterna di C3.3 (accessi e punti VV.F. da lasciare liberi). Le altre 7 tavole VVF-PI sono collegate (C1, C2, C3 bassa, inferito) | **Facoltativo**: C3 bassa, sub C3.3, `confidence: inferito`, reason «accessi, idrante esterno e attacco motopompa da mantenere liberi durante il cantiere e lo stoccaggio delle attrezzature»; altrimenti lasciare orfano giustificato |

## 7. Contraddizioni rilevate

Registro completo con valori, pagine e fonte prevalente: [[economic_framework]] §10 (D1-D19, verificato in Fase E). Sezioni «Contraddizioni rilevate» nelle pagine [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]], [[G-01-ESEC-02_QUADRO_ECONOMICO]], [[G-05-ESEC-01_QUADRO_INCIDENZA_MANODOPERA]], [[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]]; note `# ATTENZIONE` nelle pagine meno autorevoli.

### 7.1 Irrisolte — verifica manuale richiesta (7)

- CONTRADDIZIONE: capacità di accumulo di progetto 15 kWh ([[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] voce 78, RS-01 p. 7, RS-00 p. 11, tavola PI-00) vs 20 kWh / 4 batterie ([[G-08-ESEC-01_RELAZIONE_GENERALE]] p. 15, PSC p. 9, RS-03 p. 9, G-09 pp. 14, 16); lettura della soglia «>20 kWh» del sub C2.3 (D13, quesito Q1) — verifica manuale richiesta
- CONTRADDIZIONE: CAM di riferimento D.M. 24.11.2025 (disciplinare p. 3, «Elaborato B3» inesistente) vs D.M. 23/06/2022 ([[G-09-ESEC-01_RELAZIONE_CAM]], [[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]] Cap. 5) vs DM 11/10/2017 ([[G-02-ESEC-01_ELENCO_PREZZI]], capitolato p. 183); «minimi CAM» del sub C4.2 indeterminati (D11, quesito Q2) — verifica manuale richiesta
- CONTRADDIZIONE: ascensore 8 persone / 6 fermate / corsa 18 m (computo voce 96, elenco prezzi Nr. 87) vs 6 persone / 3 fermate / corsa 9 m (G-08 p. 17, PSC p. 10); «elettrico a fune» ([[SIC-01-ESEC-01_CRONOPROGRAMMA]] p. 2, PSC p. 48) vs idraulico (disciplinare sub 4.1, computo) — baseline sub C4.1 (D14, quesito Q3) — verifica manuale richiesta
- CONTRADDIZIONE: numero di poltrone 134 (computo voce 102, G-08, PSC, RS-03) vs 128 (tavole VV.F. approvate [[VVF-PI-03-00_PIANTA_PIANO_PRIMO]] + [[VVF-PI-04-00_PIANTA_PIANO_SECONDO]]) / 129 (PI-03) / 130 (PI-05) — baseline sub C1.2 (D18, quesito Q4) — verifica manuale richiesta
- CONTRADDIZIONE: manodopera 0,00 su tutte le voci NP in [[G-05-ESEC-01_QUADRO_INCIDENZA_MANODOPERA]] vs ≥ 13.708,57 € in [[G-03-ESEC-01_ANALISI_NUOVI_PREZZI]] e NP 16 (PSC: 773 uomini-giorno) (D4, quesito Q5 facoltativo) — verifica manuale richiesta
- CONTRADDIZIONE: IVA sui lavori 59.428,23 € dichiarata «al 22%» (= 15,07% di A) in [[G-01-ESEC-02_QUADRO_ECONOMICO]]; causa non ricostruibile, nessun impatto sull'offerta (D2) — verifica manuale richiesta
- CONTRADDIZIONE: importo presunto dei lavori 391.795,41 € nel PSC [[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]] p. 2 vs 381.364,99 / 394.370,46 € del QE; origine non ricostruibile, nessun impatto sull'offerta (D16) — verifica manuale richiesta

### 7.2 Risolte per gerarchia delle fonti (5) — nessuna verifica manuale

Gerarchia: disciplinare > capitolato/contratto > elenco prezzi > computo/QE > relazioni > tavole; tra versioni prevale `is_latest: true`.

- **D1** — Tabella 1 del disciplinare: righe 339.074,03 + 55.296,43 totalizzate «A) 381.364,99» → il ribasso si applica a 381.364,99 (testo art. 3).
- **D7** — Premio di accelerazione: 0,5%/giorno e tetto 10% (disciplinare) vs 0,3‰/giorno e tetto 5% (capitolato art. 2.14) → prevale il disciplinare; tetto effettivo = imprevisti QE B3 7.386,68 €.
- **D15** — Sprinkler citati da G-08, RS-03, G-09: inesistenti in computo, RS-02 e tavole; «idranti a colonna» di G-10 smentiti (protezione esterna a computo). Residuo naspi DN25 / cassette UNI 45 da chiarire con la DL in esecuzione (rilevante per l'orfano PI-06, §6).
- **D17** — «6 kWh» e «pompe di calore» (G-08 p. 24, RS-03, G-09) → prevale il computo: 5,85 kWp + inverter 6 kW, caldaia a condensazione.
- **D19** — Categoria «OG2» su tutti i 40 elaborati dell'elenco G-00 → prevale OG1 del disciplinare e del capitolato; quesito sconsigliato senza valutazione del professionista.

### 7.3 Anomalie interne senza impatto sull'offerta (7)

D3 IVA B9 h) del QE · D5 14 NP senza analisi (80.266,19 €) · D6 numerazione NP ambigua · D8 voce 37 a quantità nulla · D9 codice anomalo E.00050 · D10 riferimenti al vecchio codice nel QE · D12 refuso in lettere nel capitolato art. 1.3. Dettaglio in [[economic_framework]] §10.

### 7.4 Quesiti proposti alla stazione appaltante — entro il 06/10/2026 ore 12:00

Testi pronti in [[economic_framework]] §10.1 «Quesiti proposti alla stazione appaltante» (nessuno contiene elementi dell'offerta). D14 e D18 vanno verificati anche al **sopralluogo obbligatorio** (richiesta entro il 05/10/2026 ore 12:00).

| Quesito | Priorità | Contraddizione | Sottocriterio che ne dipende |
|---|---|---|---|
| Q1 — Capacità di accumulo di progetto e lettura della soglia «>20 kWh» | alta | D13 | C2.3 (7 pt) |
| Q2 — Versione dei CAM e «minimi CAM» (Elaborato B3 inesistente) | alta | D11 | C4.2 (5 pt) |
| Q3 — Tipologia, portata, fermate e corsa dell'ascensore | media | D14 | C4.1 (5 pt) |
| Q4 — Numero di poltrone e configurazione della sala (134 vs 128) | media | D18 | C1.2 (7 pt) |
| Q5 — Manodopera sulle voci a nuovo prezzo | bassa, facoltativo | D4 | trasversale (anomalia, art. 23) |

### 7.5 Altre anomalie documentali (non numeriche)

Rilevate nelle Fasi 0-2, B, C; dettaglio nelle pagine nodo e in [log.md](log.md).

- Documenti richiamati ma assenti da `00_input/` (`find` negativo): relazione tecnica ex L. 10/91 e abaco serramenti (rinvio del capitolato, baseline C1.1), «preventivo allegato» delle poltrone (G-08, PSC), «Elaborato B3» del disciplinare, «elaborato C1» di G-08.
- [[PI-00a-ESEC-01_PLANIMETRIA_DI_INSIEME_CON_FOTOVOLTAICO_INTEGRATO_E_FOTOINSERIMENTI]]: non firmata, fuori elenco elaborati, cartiglio «Agosto 2026»; è comunque l'elaborato a cui il disciplinare rinvia per C2.1.
- Refusi di cartiglio: [[PI-01-ESEC-01_SISTEMA_EVACUAZIONE_FUMI_FORZATO]] riporta il codice PI-00, [[PI-03-ESEC-01_PROGETTO_IMPIANTO_IRAI]] il codice PI-02; [[PA-04-ESEC-01_PARTICOLARI_COSTRUTTIVI_collegamenti_verticali]] ha il titolo di PA-03; [[PI-02-ESEC-01_PROGETTO_CON_INDICAZIONE_CLASSI_RESISTENZA_AL_FUOCO]] «reazione» (elenco) vs «resistenza» (nome file); IT-01/02/03 ESEC-00 nel nome file, ESEC-01 in elenco e cartiglio.
- [[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]]: 103 segnaposto `$MANUAL$` non compilati (FV, accumulo, antincendio), indice «edilizia scolastica»; [[G-11-ESEC-01_SCHEMA_DI_CONTRATTO]]: rinvii ad articoli del capitolato inesistenti e residui di altri appalti; [[SIC-01-ESEC-01_CRONOPROGRAMMA]]: nessuna fase per infissi, MDF, cupola, naspi, IRAI, BA, accumulo.

## 8. Sottocriteri con evidenza debole (Fase F)

Fonte: [log.md](log.md), voce `ingest-fase-F`, e commenti YAML nel frontmatter di `criterion_C1…C5.md`. Ogni sottocriterio discrezionale ha almeno un documento `alta` non inferito, ma l'evidenza sull'elemento premiante è debole nei casi seguenti. «Documenti (alta)» ricalcolato dai `supported_by`.

| Sub | Pt | Documenti (alta) | Evidenza debole | Azione che la rafforza |
|---|---|---|---|---|
| C1.1 | 10 | 17 (4) | Uw/Uf/Rw di progetto solo come range della voce Nr. 24 di G-02 (computo voce 35); relazione ex L. 10/91 e abaco serramenti assenti; geometria e partiture solo da tavole inferite (PA-01, RIL-01, RIL-02) | `drawing-reader` su PA-01, RIL-02; baseline prestazionale = G-02 Nr. 24 |
| C1.2 | 7 | 13 (4) | Garanzia solo da G-11 (contrattuale); scorta assente nel computo; «preventivo allegato» delle poltrone assente; numero di poltrone 134 vs 128 (D18) | quesito Q4 + sopralluogo |
| C1.3 | 8 | 19 (4) | Reazione al fuoco di finiture e MDF solo da tavole inferite (PI-02, VVF-PI-02…05) e RTV15 generica (COM-PZ); unico indice calcolato T60 (RS-03) | `drawing-reader` su PI-02 e VVF-PI-03 |
| C2.1 | 15 | 21 (6) | PI-00a (rinvio espresso del disciplinare) e PI-00 non lette; indirizzi di tutela della Soprintendenza assenti da tutti gli elaborati; impatto visivo e riflettanza solo da foto G-07 (parziale) e tavole di contesto inferite | **`drawing-reader` su PI-00a e PI-00 (priorità massima: 15 pt)** |
| C2.2 | 8 | 12 (3) | Archi `alta` solo di assenza (G-04-ESEC-02, G-08, RS-00); predisposizioni elettriche solo da tavole inferite (PI-05, PI-03) | `drawing-reader` su PI-05 |
| C2.3 | 7 | 21 (5) | Baseline accumulo in contraddizione: 15 kWh (computo, RS-00, RS-01, PI-00) vs 20 kWh (G-08, PSC, G-09, RS-03) — D13 | quesito Q1 |
| C3.1 | 5 | 19 (6) | Torrini di estrazione fumi sulla cupola solo da tavole inferite (VVF-PI-07, PI-01); PA-05 (alta) non letta | `drawing-reader` su PA-05, VVF-PI-07 |
| C3.2 | 5 | 6 (2) | Copertura minima tra i sottocriteri discrezionali; unica baseline verificata NP 07 palco e allestimento; configurazione base multimediale e cinematografica non descritta da alcun elaborato | sopralluogo (dotazioni esistenti) |
| C3.3 | 5 | 17 (6) | Nessun censimento di impianto audio, proiettori e schermo esistenti (solo foto G-07); archi `alta` di sola assenza (PSC, cronoprogramma, computo) | sopralluogo; `drawing-reader` su SIC-02 |
| C4.1 | 5 | 16 (5) | Isolamento acustico della cabina (dB) assente ovunque; dati ascensore in contraddizione (D14); PA-03 (alta) non letta | quesito Q3; `drawing-reader` su PA-03 |
| C4.2 | 5 | 16 (4) | «Minimi CAM» di progetto riferiti al DM 23/06/2022 (G-06-ESEC-02, G-09) e al DM 11/10/2017 (G-02), non al D.M. 24.11.2025 del disciplinare; nessuna percentuale né EPD in G-09 (D11) | quesito Q2 |
| C5.1 | 6 | 2 (0) | Atteso: criterio tabellare; i 2 archi `bassa` servono solo a definire l'«intervento analogo» | curriculum dell'impresa |
| C6.1, C7.1 | 2 + 2 | 0 | Atteso: nessun elaborato; il punteggio dipende dallo status dell'impresa | documentazione dell'impresa |

## 9. Salute del grafo (lint del 2026-10-03)

Check meccanici: `node scripts/graph/graph_lint.js` → **3 ERROR, 26 WARN** su 53 nodi, 7 criteri, 0 proposte. Valutazione di merito secondo `.claude/skills/graph-lint/SKILL.md`.

| Esito | Check | N. | Valutazione |
|---|---|---|---|
| ERROR | orfano | 3 | attesi: IT-00, PI-06, VVF-PI-01 (§6), decisione con `/resolve_orphan` |
| WARN | archi-solo-ereditati | 26 | attesi: tavole collegate per argomento (titolo, cartiglio, sezione), contenuto grafico non letto |
| OK | arco-senza-reason, frontmatter, subtype, confidence, wikilink, index ↔ nodi, copertura estrazione | 0 | nessun rilievo |

**WARN `archi-solo-ereditati` (26 tavole).** IT 3 · PA 6 · PI 6 · RIL 3 · SIC 1 · VVF-PI 7. Sono tutte le tavole tranne [[PI-00a-ESEC-01_PLANIMETRIA_DI_INSIEME_CON_FOTOVOLTAICO_INTEGRATO_E_FOTOINSERIMENTI]] (arco verificato sul rinvio del disciplinare) e le 3 orfane. Giudizio: il collegamento è plausibile ma **non verificato**; non va usato come evidenza finché `drawing-reader` non ha letto la tavola. Le 4 con priorità `alta` (PI-00, PA-03, PA-05, SIC-02) sono le prime da leggere (§3); le altre restano `media`/`bassa` di contesto.

Check di merito (skill graph-lint):

- **Check 1 — Orfani**: 3, valutati uno per uno in §6 (IT-00 giustificato, PI-06 da collegare come vincolo, VVF-PI-01 facoltativo).
- **Check 2 — Dati economici**: oneri della sicurezza 13.005,47 € identici in [[economic_framework]], [[SIC-03-ESEC-01_COSTI_PER_LA_SICUREZZA]], QE A4 e copia nel PSC (12/12 voci); importo lavori 381.364,99 € = somma delle categorie SOA (OG1 + OS3 + OS4 + OG9 + OS30). Nessuna contraddizione su questi due valori; le contraddizioni del registro sono in §7.
- **Check 3 — Archi doc→doc**: tutte le 30 tavole hanno almeno un arco `tavola_di`, tutte le relazioni delle sezioni con tavole hanno `relazione_di`. [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] ha `computo_di` → G-08; [[G-04-ESEC-01_COMPUTO_METRICO_ESTIMATIVO]] non ne ha: **giustificato**, è la versione superata e punta a ESEC-02 con `versione_successiva`. Il legame QE A4 = SIC-03 non ha un tipo d'arco ammesso (sezioni diverse, nessuna citazione): documentato solo nei corpi e in [[economic_framework]].
- **Check 4 — Versioni**: G-01, G-04, G-06 hanno esattamente un `is_latest: true` (ESEC-02); archi `versione_precedente` / `versione_successiva` presenti (3 + 3).
- **Check 5 — Pagine speciali**: [[scope]] e [[economic_framework]] presenti, `confidence: verificato`, nessun campo chiave a TBD (TBD residui elencati in economic_framework §13 e scope §7).
- **Check 6 — Copertura estrazione**: 0 documenti economici non estratti; 0 testuali non estratti. Estrazione **parziale e bloccata alla fonte** (pagine immagine, vincolo permanente, non in coda): RS-01 pp. 3-5 (PVGIS) e G-07 (fotografie), entrambe lette visivamente. `norme.tecniche` non estratto e senza nodo: non pertinente al progetto.
- **Controlli aggiuntivi** (fuori dallo script, che non legge `synthesis/`, `scope.md`, `economic_framework.md`): wikilink di sintesi, pagine speciali, nodi, criteri e index tutti risolti; frontmatter YAML valido su tutte le pagine (nodi, sintesi, pagine speciali, criteri, index); nessun campo vuoto. Eccezione formale: il metadato `pagine` (numero di pagine del PDF, da pdfinfo) non porta commento di confidence sui 53 nodi — non è un dato di progetto, lasciato invariato. Nessuna correzione meccanica necessaria in questa invocazione.

## 10. Statistiche

| Voce | Valore | Dettaglio |
|---|---|---|
| File in `00_input/` | 56 | 53 con pagina nodo + 3 senza (disciplinare, bando, norme.tecniche) — vedi [_census.md](_census.md) |
| Pagine nodo | 53 | tavola 30 · relazione_tecnica 7 · altro 3 · quadro_economico 2 · elenco_prezzi 2 · computo_metrico 2 · capitolato 2 · quadro_manodopera 1 · relazione_generale 1 · PSC 1 · cronoprogramma 1 · stima_sicurezza 1 |
| Testo estratto | 23 | confidence: verificato 21, parziale 2 (RS-01 pp. 3-5 immagini, G-07 fotografie) |
| Non estratti | 30 | tutte tavole (`status: non_estratto`, `confidence: inferito`) — lettura on-demand con `drawing-reader` |
| Gruppi di versione | 3 | G-01, G-04, G-06: `is_latest: true` su ESEC-02, `false` su ESEC-01 |
| Pagine di sintesi | 11 | §4 |
| Pagine speciali | 2 | [[scope]], [[economic_framework]] |
| Archi documento → criterio | 114 | alta 22 · media 32 · bassa 60; verificato 67 · parziale 5 · inferito 42; 12 su versioni superate |
| Archi documento → documento | 253 | references 74 · referenced_by 74 · relazione_di 40 · tavola_di 40 · stesso_lotto 18 · versione_successiva 3 · versione_precedente 3 · computo_di 1; verificato 159 · inferito 94 |
| **Archi totali** | **367** | 114 + 253 |
| Orfani | 3 | §6 |
| Contraddizioni | 7 irrisolte · 5 risolte · 7 anomalie interne | registro D1-D19, §7 |
| Quesiti alla SA | 5 | Q1-Q5, §7.4 |
