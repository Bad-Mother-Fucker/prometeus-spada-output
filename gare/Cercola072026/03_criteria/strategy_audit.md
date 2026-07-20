# Audit Strategico — Procedura aperta telematica per l'affidamento dell'appalto dei lavori di "Intervento di efficientamento energetico dell'Istituto Comprensivo 'De Luca Picione Caravita' sito alla Via Nuova"

**Generato il:** 2026-07-20 (rigenerazione: C.01 e C.02 estratti integralmente — perimetro di confronto esteso ai lavori a misura)
**Agente:** strategy-auditor
**Knowledge graph:** 02_graph/index.md (build del 2026-07-19; re-ingest C.01/C.02 del 2026-07-20)

---

## 1. Budget sicurezza

**Fonte:** [[C.07_Quadro_Economico]] — Quadro Economico, voce A.3 (confidence: verificato); incrociata con [[C.05_Computo_Metrico_Sicurezza]] e [[C.06_Elenco_Prezzi_Sicurezza]] (confidence: verificato)
**Importo oneri sicurezza:** € 39.073,96 (da `02_graph/economic_framework.md`, confidence: verificato)
**Importo lavori:** € 915.809,83 (voce A.1, lavori soggetti a ribasso — da `02_graph/economic_framework.md`, confidence: verificato)
**Percentuale:** 4,27% (39.073,96 / 915.809,83 × 100 — valore ricalcolato in questa invocazione, coincide con `oneri_sicurezza_pct` nel frontmatter di `economic_framework.md`)
**Classificazione:** ⚠️ BASSO

> ⚠️ ATTENZIONE: Gli oneri per la sicurezza rappresentano il 4,27% dell'importo lavori (o 4,09% se
> calcolato sulla base d'asta complessiva di € 954.883,79), sotto la soglia indicativa del 5%.

**Nota su coerenza fonti:** i tre documenti economici che riportano l'importo oneri sicurezza —
[[C.05_Computo_Metrico_Sicurezza]] (computo voce-per-voce, 12 voci di apprestamento cantiere),
[[C.06_Elenco_Prezzi_Sicurezza]] (elenco prezzi corrispondente) e [[C.07_Quadro_Economico]] (voce
A.3, etichettata "A.2" nel PDF per refuso) — coincidono esattamente sul valore € 39.073,96. Nessuna
contraddizione rilevata sulla cornice economica della sicurezza. Confidence complessiva del dato:
verificato.

---

## 2. Analisi prezzi — gap rispetto al prezzario

**Documenti prezzi del progetto usati:** [[C.01_Computo_Metrico_Estimativo]] (computo metrico, `is_latest: true`, `estrazione: integrale`, confidence: verificato — 101 righe con codice tariffa, quantità, prezzo unitario e importo; totale ricostruito € 915.809,83 = totale stampato) e [[C.02_Elenco_Prezzi_Unitari]] (elenco prezzi, `is_latest: true`, `estrazione: integrale`, confidence: verificato — 98 voci, prezzi coincidenti 1:1 con il computo, 0 scostamenti)
**Prezzario di riferimento:** Regione Campania **2026** — `/Users/michele/.spada/prezzari/Campania/2026/prezzario_campania_2026.json` (percorso da `PROJECT_CONFIG.json → gara.prezzario_riferimento.percorso`; metadata del file: "Regione Campania - Prezzario regionale dei Lavori Pubblici", `anno: 2026`, Delibera di Giunta Regionale n. 14 del 29/01/2026, 31.755 voci)
**Voci confrontate:** **73 righe di computo su 101** (70 codici tariffa distinti), pari a **€ 608.462,99 = 66,44% dell'importo lavori**. Lookup esatto su `codice_completo`: **70 codici su 70 trovati nel prezzario, 0 non trovati.**
**Gap medio aritmetico (73 righe):** **−1,41%**
**Gap medio ponderato sugli importi (perimetro confrontabile):** **−0,83%** — € 608.463,00 a computo contro € 613.546,13 ai prezzi del prezzario 2026 (delta **−€ 5.083,13**)
**Classificazione:** **BASSO** (|gap medio| < 5%)

### Perimetro del confronto — vincolo strutturale dichiarato

La tripartizione dei codici tariffa di [[C.01_Computo_Metrico_Estimativo]] (confidence: verificato)
delimita ciò che è confrontabile:

| Famiglia di codice | Righe | Importo (€) | % importo lavori | Confrontabile col prezzario |
|---|---:|---:|---:|---|
| `CAM25_*` (Prezzario Campania) | 73 | 608.462,99 | 66,44% | **SÌ — confrontate tutte** |
| `NP.01`–`NP.12` (nuovi prezzi) | 12 | 260.184,34 | 28,41% | **NO — per definizione assenti dal prezzario** (composizione in [[C.03_Analisi_dei_Prezzi]]) |
| codici a sei cifre + lettera (`015008c`, `105062a`, `205015e_`, …) | 16 | 47.162,50 | 5,15% | **NO — fuori dallo schema di codifica regionale; listino di provenienza non dichiarato: TBD** |
| **Totale non confrontabile** | **28** | **307.346,84** | **33,56%** | — |

**Le voci non confrontabili non sono state stimate.** Nessun valore è stato attribuito per
analogia, per descrizione o per estrapolazione al 33,56% dell'importo lavori.

### Trattamento del cambio di edizione 2025 → 2026

I codici a progetto hanno prefisso `CAM25_` (Prezzario Campania 2025); l'edizione disponibile in
cache è la **2026** (prefisso `CAM26_`). Il confronto è stato eseguito **sostituendo il solo
prefisso di edizione a parità di numerazione** (`CAM25_E18.090.012.D` → `CAM26_E18.090.012.D`) e
**verificando che la descrizione coincida**: per tutti e 70 i codici i campi `tipologia_famiglia`,
`capitolo` e `voce` del prezzario 2026 corrispondono alla descrizione riportata in
[[C.02_Elenco_Prezzi_Unitari]]. **Nessun codice è risultato con descrizione discordante**, quindi
nessuna voce è stata esclusa per questo motivo.

Il marcatore `(CAM)` (conformità CAM di PriMus) è stato spogliato prima del lookup, come da
avvertenza nelle pagine nodo. I 3 codici che compaiono su due righe distinte del computo
(`CAM25_E01.015.010.A`, `CAM25_L02.010.260.I`, `CAM25_R02.060.018.A(CAM)`) sono stati mantenuti
come righe separate, non deduplicati.

**Quantificazione dell'effetto edizione:** per **tutte e 70 le voci** il prezzario 2026 riporta
`scostamento_prezzo_2025_pct = 0.0` (campo letto direttamente dal JSON, confidence: verificato),
cioè prezzo 2026 identico al prezzo 2025 della medesima voce. Su questo perimetro il gap misurato
**non è attribuibile al cambio di edizione**.

### Disaggregazione del gap per le categorie che pesano sui criteri C1/C2/C3

| Categoria | Importo categoria (€) | Importo confrontato (€) | Copertura | Importo ai prezzi 2026 (€) | Gap ponderato |
|---|---:|---:|---:|---:|---:|
| **Isolamento** ([[C1]], sottocat. 001+002) | 275.313,06 | 160.381,67 | 58,3% | 162.437,15 | **−1,27%** |
| **Infissi** ([[C2]], sottocat. 003) | 158.811,91 | 155.923,09 | 98,2% | 156.351,08 | **−0,27%** |
| **Fotovoltaico** ([[C3]], sottocat. 006) | 57.139,96 | 3.488,62 | 6,1% | 3.502,37 | **−0,39%** |

Composizione (confidence: verificato sui singoli importi; l'aggregazione è aritmetica sulle righe
estratte di [[C.01_Computo_Metrico_Estimativo]]):

- **Isolamento** — confrontate: cappotto verticale `E10.040.040.E` (109.251,81), massetto copertura
  `E07.005.040.A` (41.656,25), demolizione massetto `R02.060.018.A` (8.309,61), rimozione manti
  `R02.090.070.B` (1.164,00). Fuori confronto: `NP.02` isolamento orizzontale (111.587,28),
  `NP.03` profilo perimetrale (3.053,30), `NP.01` (290,81).
- **Infissi** — confrontate: i 3 infissi in PVC `E18.090.012.B/C/D` (152.865,43), le rimozioni
  `R02.025.050.A/B/C` (1.715,01), i canali di gronda `E11.040.030.D` (1.342,65). Fuori confronto:
  `NP.10` infisso 4 ante (2.888,82). Sui soli 3 infissi nuovi il gap ponderato è **−0,23%**.
- **Fotovoltaico** — confrontabili solo cavi, canaline, tubi, scavi e dispersore (`CAM25_*`,
  € 3.488,62). Fuori confronto: moduli `105062a`/`105062b` (35.080,00), inverter `NP.09`,
  strutture `NP.08`, protezioni e interruttori a sei cifre. **Il gap −0,39% descrive il 6,1% del
  capitolo fotovoltaico, non il capitolo.**

### Tabella completa dei 73 confronti

Prezzo progetto = prezzo unitario in [[C.01_Computo_Metrico_Estimativo]] / [[C.02_Elenco_Prezzi_Unitari]]
(confidence: verificato). Prezzo prezzario = campo `prezzo` (comprensivo di S.G. 17% e U.I. 10%)
del JSON Campania 2026, lookup esatto su `codice_completo` (confidence: verificato).
Ordinamento per importo decrescente.

| # | Codice progetto | U.M. | Q.tà | Prezzo progetto | Prezzo prezzario 2026 | Gap% | Importo progetto (€) |
|---:|---|---|---:|---:|---:|---:|---:|
| 1 | CAM25_E18.090.012.D | mq | 131,76 | 875,72 | 877,60764 | −0,22% | 115.384,87 |
| 2 | CAM25_E10.040.040.E(CAM) | mq | 1.357,84 | 80,46 | 81,41266 | −1,17% | 109.251,81 |
| 3 | CAM25_L03.100.030.J(CAM) | cad | 264,00 | 188,29 | 188,40460 | −0,06% | 49.708,56 |
| 4 | CAM25_E13.015.010.B(CAM) | mq | 825,00 | 60,24 | 60,74266 | −0,83% | 49.698,00 |
| 5 | CAM25_E07.005.040.A(CAM) | mc | 76,20 | 546,67 | 552,36158 | −1,03% | 41.656,25 |
| 6 | CAM25_E18.090.012.C | mq | 52,05 | 650,75 | 652,64004 | −0,29% | 33.871,54 |
| 7 | CAM25_E18.020.010.A | cad | 65,10 | 398,14 | 398,45610 | −0,08% | 25.918,91 |
| 8 | CAM25_E21.020.055.G(CAM) | mq | 1.650,00 | 14,25 | 14,45430 | −1,41% | 23.512,50 |
| 9 | CAM25_E21.020.030.A(CAM) | mq | 2.300,00 | 7,35 | 7,51449 | −2,19% | 16.905,00 |
| 10 | CAM25_M07.010.030.E | cad | 560,00 | 26,84 | 26,84006 | −0,00% | 15.030,40 |
| 11 | CAM25_R03.040.090.A | mq | 80,00 | 139,83 | 142,85758 | −2,12% | 11.186,40 |
| 12 | CAM25_E21.010.010.A(CAM) | mq | 2.300,00 | 3,73 | 3,82908 | −2,59% | 8.579,00 |
| 13 | CAM25_R02.060.018.A(CAM) | mc | 76,20 | 109,05 | 112,83773 | −3,36% | 8.309,61 |
| 14 | CAM25_E15.080.030.A(CAM) | m | 470,00 | 17,37 | 17,49592 | −0,72% | 8.163,90 |
| 15 | CAM25_E13.030.020.D(CAM) | mq | 127,00 | 63,93 | 64,80946 | −1,36% | 8.119,11 |
| 16 | CAM25_I01.030.060.A | cad | 3,00 | 2.675,23 | 2.684,57761 | −0,35% | 8.025,69 |
| 17 | CAM25_E15.020.010.E(CAM) | mq | 105,00 | 43,56 | 44,39718 | −1,89% | 4.573,80 |
| 18 | CAM25_I01.020.060.C | cad | 17,00 | 250,10 | 251,03935 | −0,37% | 4.251,70 |
| 19 | CAM25_E18.075.045.C | cad | 13,00 | 319,23 | 320,05229 | −0,26% | 4.149,99 |
| 20 | CAM25_E08.020.010.B(CAM) | mq | 135,00 | 30,43 | 31,11336 | −2,20% | 4.108,05 |
| 21 | CAM25_T01.020.010.B | mc/5km | 600,00 | 6,58 | 6,57811 | **+0,03%** | 3.948,00 |
| 22 | CAM25_C01.070.080.F(CAM) | m | 160,00 | 23,60 | 23,68449 | −0,36% | 3.776,00 |
| 23 | CAM25_E18.090.012.B | mq | 5,68 | 635,39 | 637,28613 | −0,30% | 3.609,02 |
| 24 | CAM25_I01.020.010.A | cad | 13,00 | 273,96 | 274,80347 | −0,31% | 3.561,48 |
| 25 | CAM25_L03.100.030.I(CAM) | cad | 25,00 | 138,95 | 139,06474 | −0,08% | 3.473,75 |
| 26 | CAM25_E16.020.030.B(CAM) | mq | 135,00 | 25,56 | 26,18568 | −2,39% | 3.450,60 |
| 27 | CAM25_T01.020.010.A | mc | 75,00 | 44,40 | 44,74597 | −0,77% | 3.330,00 |
| 28 | CAM25_E18.075.040.P | cad | 2,00 | 1.634,38 | 1.635,76490 | −0,08% | 3.268,76 |
| 29 | CAM25_E21.010.005.B(CAM) | mq | 150,00 | 15,24 | 15,47420 | −1,51% | 2.286,00 |
| 30 | CAM25_E11.040.020.B | m | 80,00 | 23,95 | 24,17961 | −0,95% | 1.916,00 |
| 31 | CAM25_R02.060.032.A(CAM) | mq | 284,00 | 6,54 | 6,77027 | −3,40% | 1.857,36 |
| 32 | CAM25_I03.010.030.F(CAM) | m | 70,00 | 26,12 | 26,22972 | −0,42% | 1.828,40 |
| 33 | CAM25_I03.010.030.G(CAM) | m | 40,00 | 42,27 | 42,39396 | −0,29% | 1.690,80 |
| 34 | CAM25_E18.075.040.M | cad | 1,00 | 1.459,38 | 1.460,76673 | −0,09% | 1.459,38 |
| 35 | CAM25_R02.060.018.A(CAM) | mc | 13,00 | 109,05 | 112,83773 | −3,36% | 1.417,65 |
| 36 | CAM25_E11.040.030.D | mq | 25,95 | 51,74 | 52,14362 | −0,77% | 1.342,65 |
| 37 | CAM25_L02.030.220.F | cad | 15,00 | 87,49 | 87,82837 | −0,39% | 1.312,35 |
| 38 | CAM25_R02.090.070.B | mq | 200,00 | 5,82 | 6,01801 | −3,29% | 1.164,00 |
| 39 | CAM25_R02.050.020.B(CAM) | ml | 200,00 | 5,82 | 6,01801 | −3,29% | 1.164,00 |
| 40 | CAM25_R02.060.040.A(CAM) | mq | 130,00 | 8,72 | 9,02702 | −3,40% | 1.133,60 |
| 41 | CAM25_C01.070.080.B(CAM) | m | 70,00 | 12,06 | 12,12313 | −0,52% | 844,20 |
| 42 | CAM25_I03.010.030.C(CAM) | m | 60,00 | 13,15 | 13,23604 | −0,65% | 789,00 |
| 43 | CAM25_R02.025.050.C(CAM) | mq | 108,28 | 7,27 | 7,52252 | −3,36% | 787,20 |
| 44 | CAM25_R02.060.045.A(CAM) | ml | 470,00 | 1,45 | 1,50450 | −3,62% | 681,50 |
| 45 | CAM25_C03.010.050.H | cad | 2,00 | 312,00 | 312,88083 | −0,28% | 624,00 |
| 46 | CAM25_R02.020.030.B(CAM) | mq | 70,00 | 8,85 | 9,10275 | −2,78% | 619,50 |
| 47 | CAM25_C03.010.050.G | cad | 2,00 | 294,18 | 295,06324 | −0,30% | 588,36 |
| 48 | CAM25_R02.025.050.B(CAM) | mq | 65,60 | 8,72 | 9,02702 | −3,40% | 572,03 |
| 49 | CAM25_L02.010.260.I | m | 40,00 | 13,98 | 14,02220 | −0,30% | 559,20 |
| 50 | CAM25_R02.025.030.A(CAM) | mq | 59,85 | 8,72 | 9,02702 | −3,40% | 521,89 |
| 51 | CAM25_I03.010.030.B(CAM) | m | 40,00 | 12,12 | 12,19627 | −0,63% | 484,80 |
| 52 | CAM25_R02.090.060.A(CAM) | ml | 80,00 | 5,82 | 6,01801 | −3,29% | 465,60 |
| 53 | CAM25_L02.080.140.F | m | 25,00 | 14,90 | 14,95739 | −0,38% | 372,50 |
| 54 | CAM25_R02.025.050.A(CAM) | mq | 32,61 | 10,91 | 11,28378 | −3,31% | 355,78 |
| 55 | CAM25_L02.080.090.E | m | 25,00 | 13,74 | 13,80646 | −0,48% | 343,50 |
| 56 | CAM25_R02.050.060.C(CAM) | cad | 28,00 | 10,91 | 11,28378 | −3,31% | 305,48 |
| 57 | CAM25_L02.010.200.C | m | 30,00 | 8,82 | 8,85556 | −0,40% | 264,60 |
| 58 | CAM25_C03.010.050.E | cad | 1,00 | 260,62 | 261,44465 | −0,32% | 260,62 |
| 59 | CAM25_E01.040.020.A | mc | 19,20 | 13,22 | 13,66279 | −3,24% | 253,82 |
| 60 | CAM25_L02.010.260.G | m | 30,00 | 8,21 | 8,23780 | −0,34% | 246,30 |
| 61 | CAM25_U04.020.010.E | cad | 3,00 | 81,07 | 82,45285 | −1,68% | 243,21 |
| 62 | CAM25_L02.010.260.I | m | 15,00 | 13,98 | 14,02220 | −0,30% | 209,70 |
| 63 | CAM25_R02.050.050.D | cad | 1,00 | 127,23 | 131,64402 | −3,35% | 127,23 |
| 64 | CAM25_L05.020.010.B | cad | 1,00 | 121,99 | 122,80980 | −0,67% | 121,99 |
| 65 | CAM25_E01.015.010.A | mc | 19,20 | 5,23 | 5,27469 | −0,85% | 100,42 |
| 66 | CAM25_R02.050.010.A(CAM) | cad | 12,00 | 7,27 | 7,52252 | −3,36% | 87,24 |
| 67 | CAM25_U04.020.040.H | cad | 3,00 | 25,17 | 25,31020 | −0,55% | 75,51 |
| 68 | CAM25_I02.010.070.E | cad | 2,00 | 36,23 | 36,51146 | −0,77% | 72,46 |
| 69 | CAM25_E01.040.030.B | mc | 0,50 | 69,27 | 69,99457 | −1,04% | 34,64 |
| 70 | CAM25_R02.050.060.B(CAM) | cad | 2,00 | 8,72 | 9,02702 | −3,40% | 17,44 |
| 71 | CAM25_R02.050.060.A(CAM) | cad | 2,00 | 7,27 | 7,52252 | −3,36% | 14,54 |
| 72 | CAM25_E01.015.010.A | mc | 2,70 | 5,23 | 5,27469 | −0,85% | 14,12 |
| 73 | CAM25_E01.040.010.A | mc | 2,70 | 3,60 | 3,61981 | −0,55% | 9,72 |
| | **TOTALE perimetro confrontabile** | | | | | **−0,83%** (ponderato) | **608.463,00** |

Nota di quadratura: la somma della colonna importo (€ 608.463,00) coincide, a meno di € 0,01 di
arrotondamento, con l'importo della famiglia `CAM25_*` dichiarato in
[[C.01_Computo_Metrico_Estimativo]] (€ 608.462,99).

### Distribuzione del gap (dato, non interpretazione)

Il gap non è uniforme sulle 73 righe:

- **17 righe con gap tra −2,7% e −3,7%** (€ 30.106,55 di importo): sono tutte voci `R02.*`
  (demolizioni e rimozioni), `R03.040.090.A` (risanamento cls) e `E01.040.020.A` (rinterro a mano)
  — voci con incidenza di manodopera dichiarata dal prezzario tra 0,49 e 0,78.
- **34 righe con gap tra −0,00% e −0,50%** (€ 400.213,80 di importo): prevalentemente forniture e
  posa (infissi, corpi illuminanti, porte, sanitari, cavi), con incidenza manodopera dichiarata tra
  0,018 e 0,39.
- **1 riga con gap positivo**: `CAM25_T01.020.010.B` (+0,03%, € 3.948,00).
- Gap minimo: −3,62% (`R02.060.045.A`). Gap massimo: +0,03% (`T01.020.010.B`).

**Nota versioni:** [[C.01_Computo_Metrico_Estimativo]] e [[C.05_Computo_Metrico_Sicurezza]] hanno
ciascuno un file duplicato in `00_input/elaborati/` (contenuto identico, MD5 diverso). Non sono
versioni alternative: nessun impatto sulla scelta della voce `is_latest`.

---

## 3. Posizione e viabilita' cantiere

**Fonti:** [[R.01_Relazione_Generale_e_Tecnica_Illustrativa]] (relazione generale, confidence: verificato), [[S.04_Piano_Sicurezza_Coordinamento]] (PSC, confidence: verificato), [[S.05_Layout_Cantiere]] (layout cantiere, confidence: parziale)
**Localizzazione estratta:** Via Nuova, Cercola (NA) — catasto C495 Fg.1 Part.339 Sub.1, categoria B/5 (scuole), edificio del 1972 ([[R.01_Relazione_Generale_e_Tecnica_Illustrativa]], sez. "Edificio")
**Classificazione:** NEUTRO

**Elementi rilevati:**
- "Contesto: zona tranquilla circondata da civili abitazioni e attività commerciali, accesso
  semplice" (testo estratto di [[S.04_Piano_Sicurezza_Coordinamento]]) — zona residenziale/commerciale,
  non industriale né periferica
- "Strade: presenza strada comunale per ingresso cantiere; rischio investimento" (testo estratto di
  [[S.04_Piano_Sicurezza_Coordinamento]]) — accesso da strada comunale, non da strada provinciale o
  autostrada
- "Contesto cantiere: zona residenziale/commerciale tranquilla, scuola in esercizio durante i lavori
  (misure specifiche: riduzione orario macchine rumorose, abbattimento polveri)"
  ([[S.04_Piano_Sicurezza_Coordinamento]], sez. "Contenuto chiave") — un vincolo orario è citato,
  riferito alle macchine rumorose per la presenza della scuola in esercizio; il documento non
  specifica se derivi da ordinanza comunale o sia misura di mitigazione interna al PSC
- "Ingresso cantiere: su Via Nuova, lato nord dell'area" ([[S.05_Layout_Cantiere]]) — accesso
  diretto su strada, nessuna indicazione di occupazione di suolo pubblico aggiuntiva
- Durata cantiere 180 giorni (01/04/2026 - 27/09/2026), 17 fasi di lavorazione
  ([[S.04_Piano_Sicurezza_Coordinamento]])
- Nessuna menzione di centro storico, ZTL, larghezza delle strade di accesso o divieti espliciti di
  transito per mezzi pesanti nei testi estratti

Gli elementi rilevati non soddisfano almeno due condizioni FAVOREVOLE (zona non
industriale/periferica, accesso non da strada provinciale/autostrada, un vincolo orario è comunque
citato) né alcuna condizione SFAVOREVOLE in modo inequivocabile (nessun centro storico/ZTL, nessuna
strada dichiarata stretta, nessun divieto mezzi pesanti). Classificazione: NEUTRO.

---

## 4. Capacita' di investimento migliorativo

**Gap medio vs prezzario:** −0,83% ponderato sugli importi / −1,41% media aritmetica (da Analisi 2, confidence: verificato sul perimetro confrontabile)
**Importo lavori:** € 915.809,83 (da `02_graph/economic_framework.md`, confidence: verificato)
**Perimetro su cui il margine è misurato:** € 608.462,99 = **66,44%** dell'importo lavori
**Margine teorico misurato (perimetro confrontabile):** **−€ 5.083,13** (−0,83% su € 608.463,00)
**Classificazione:** **ASSENTE** (gap ≤ 0%)

> ⚠️ ATTENZIONE: sul 66,44% dell'importo lavori i prezzi a computo sono già inferiori al prezzario
> regionale 2026 dello 0,83% (ponderato) / 1,41% (media aritmetica). Ogni investimento aggiuntivo
> non finanziato da un delta di prezzo si traduce in una riduzione diretta del margine.

**Estensione all'intero importo lavori (estrapolazione, dichiarata come tale):** applicando il gap
ponderato −0,83% anche al 33,56% non confrontabile (€ 307.346,84 di nuovi prezzi e codici fuori
schema) si otterrebbe **−€ 7.601,22** sull'intero importo lavori. Questo secondo valore **non è
misurato**: i 12 nuovi prezzi `NP.*` (€ 260.184,34) e i 16 codici a sei cifre (€ 47.162,50) non
hanno riscontro nel prezzario e la loro congruità è verificabile solo su
[[C.03_Analisi_dei_Prezzi]] (per gli `NP.*`) o risalendo al listino di provenienza (non dichiarato:
TBD per i codici a sei cifre).

**Margine per categoria di criterio (misurato sul confrontabile):**

| Categoria | Delta misurato (€) | Gap ponderato | Copertura della categoria |
|---|---:|---:|---:|
| Isolamento ([[C1]]) | −2.055,48 | −1,27% | 58,3% |
| Infissi ([[C2]]) | −427,99 | −0,27% | 98,2% |
| Fotovoltaico ([[C3]]) | −13,75 | −0,39% | 6,1% |

**Voci con maggiore spazio di investimento (gap% più alto):**

| Voce | Gap% | Importo (€) |
|---|---:|---:|
| CAM25_T01.020.010.B — trasporto materiale di risulta oltre 5 km | +0,03% | 3.948,00 |
| CAM25_M07.010.030.E — radiatori in alluminio | −0,00% | 15.030,40 |
| CAM25_L03.100.030.J(CAM) — corpi illuminanti LED a soffitto | −0,06% | 49.708,56 |
| CAM25_E18.020.010.A — porte interne in legno | −0,08% | 25.918,91 |
| CAM25_E18.075.040.P — porta tagliafuoco REI 120 | −0,08% | 3.268,76 |

**Voci con minore spazio (gap più negativo):**

| Voce | Gap% | Importo (€) |
|---|---:|---:|
| CAM25_R02.060.045.A(CAM) — rimozione zoccolino battiscopa | −3,62% | 681,50 |
| CAM25_R02.060.032.A(CAM) — demolizione rivestimento ceramica | −3,40% | 1.857,36 |
| CAM25_R02.060.040.A(CAM) — demolizione pavimento ceramica | −3,40% | 1.133,60 |
| CAM25_R02.060.018.A(CAM) — demolizione massetto (2 righe) | −3,36% | 9.727,26 |
| CAM25_E01.040.020.A — rinterro eseguito a mano | −3,24% | 253,82 |

Nota di scala: le 5 voci a gap più negativo pesano complessivamente € 13.653,54 (2,24% del
perimetro confrontabile); le 5 a gap più alto pesano € 97.874,63 (16,09%). Sulle tre voci di
maggiore importo assoluto il gap è −0,22% (`E18.090.012.D`, € 115.384,87), −1,17%
(`E10.040.040.E`, € 109.251,81) e −0,06% (`L03.100.030.J`, € 49.708,56).

---

## Domande chiave per il professionista

1. Il budget sicurezza del 4,27% dell'importo lavori (4,09% sulla base d'asta complessiva), sotto
   la soglia indicativa del 5%, copre adeguatamente i rischi di cantiere identificati nel PSC
   (scuola in esercizio durante i lavori, 180 giorni di durata, 17 fasi di lavorazione)?
2. Il confronto col prezzario copre il 66,44% dell'importo lavori e restituisce un gap ponderato di
   −0,83%; il restante 33,56% (€ 307.346,84) è composto da 12 nuovi prezzi `NP.*` (€ 260.184,34) e
   16 codici fuori schema (€ 47.162,50), non confrontabili per costruzione: la congruità di quei
   prezzi va verificata su [[C.03_Analisi_dei_Prezzi]] prima di costruire le proposte, o si
   assume il progetto come dato?
3. Il gap non è distribuito uniformemente: le voci di demolizione/rimozione ad alta incidenza di
   manodopera stanno tra −2,8% e −3,6%, mentre le forniture e pose (infissi, illuminazione, porte,
   sanitari) stanno tra −0,00% e −0,50%: questa differenza è considerata una scelta progettuale da
   assecondare o un dato da approfondire prima di dimensionare le migliorie?
4. Le tre categorie che alimentano i criteri qualitativi mostrano gap ponderati di −1,27%
   (isolamento, coperto al 58,3%), −0,27% (infissi, coperto al 98,2%) e −0,39% (fotovoltaico,
   coperto solo al 6,1% perché moduli, inverter e strutture sono fuori prezzario): su quale delle
   tre si concentra lo sforzo migliorativo, considerato che il dato sugli infissi è quasi completo
   mentre quello sul fotovoltaico descrive un sedicesimo del capitolo?
5. I prezzi a computo sono già sotto il prezzario 2026 di € 5.083,13 sul perimetro misurato:
   l'impresa è disponibile a investire in miglioramenti tecnici attingendo direttamente al proprio
   margine e, se sì, fino a quale soglia in euro?
6. Il vincolo di "riduzione orario per macchine rumorose" citato in
   [[S.04_Piano_Sicurezza_Coordinamento]] deriva da un'ordinanza comunale sugli orari di cantiere in
   prossimità di scuole, o è una misura di mitigazione volontaria interna al PSC?

---

## Riepilogo

| Analisi | Classificazione | Alert |
|---|---|---|
| Budget sicurezza | ⚠️ BASSO | Oneri sicurezza 4,27% dell'importo lavori, sotto soglia indicativa 5% |
| Gap prezzi | BASSO | Gap ponderato −0,83% (media aritmetica −1,41%) su 73 righe / 70 codici, tutti trovati nel prezzario Campania 2026; perimetro 66,44% dell'importo lavori; 33,56% (€ 307.346,84) non confrontabile per costruzione (NP e codici fuori schema), non stimato; scostamento 2025→2026 dichiarato 0,00% su tutte le 70 voci |
| Viabilita' cantiere | NEUTRO | Nessun elemento favorevole o sfavorevole netto: zona residenziale/commerciale, accesso da strada comunale su Via Nuova, un vincolo orario citato per rumore (scuola in esercizio) |
| Investimento migliorativo | ASSENTE | Margine misurato −€ 5.083,13 (−0,83% su € 608.463,00, 66,44% dei lavori); estensione all'intero importo lavori −€ 7.601,22, dichiarata come estrapolazione sul 33,56% non confrontabile |

---

## Indicazioni strategiche del professionista

> Compilare questa sezione dopo la lettura dell'audit.
> Le indicazioni guidano l'analisi dei criteri nelle fasi successive.

### Risposte alle domande chiave

1. [risposta]
2. [risposta]
3. [risposta]
4. [risposta]
5. [risposta]
6. [risposta]

### Direttive operative

**Tono generale:** [conservativo / bilanciato / audace]

**Priorita' per criterio:**
- C1: [indicazione]
- C2: [indicazione]
- C3: [indicazione]
- C4: [indicazione]
- C5: [indicazione]
- C6: [indicazione]

**Vincoli specifici:**
- [vincolo]

**Opportunita' da valorizzare:**
- [opportunita']

**Note aggiuntive:**
[testo libero]
