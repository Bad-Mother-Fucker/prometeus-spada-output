---
type: document
subtype: computo_metrico
gara: "Procedura aperta telematica per l'affidamento dell'appalto dei lavori di \"Intervento di efficientamento energetico dell'Istituto Comprensivo 'De Luca Picione Caravita' sito alla Via Nuova\""
date: 2026-07-20
ai-first: true
codice: "C.01"
file: "sub_15175049978810242486_C.01 - COMPUTO METRICO ESTIMATIVO.PDF"
section: "08"
version_group: "C.01"
is_latest: true
status: estratto
estrazione: integrale          # 26/26 pagine, re-ingest 2026-07-20 (prima: parziale, pag. 1-3 + 24-25)
extracted_md: "01_extracted/text/sub_15175049978810242486_C.01 - COMPUTO METRICO ESTIMATIVO.md"
confidence: verificato
supports_criteria:
  - { criterion: "[[C1]]", priority: alta, confidence: verificato, reason: "Base quantitativa a progetto per le migliorie di efficientamento: isolamento verticale a cappotto (voce 21, CAM25_E10.040.040.E(CAM), 1.357,84 mq x 80,46 €/mq = € 109.251,81), isolamento orizzontale in copertura (voce 24, NP.02, 762,00 mq x 146,44 €/mq = € 111.587,28) e impianti termico/elettrico/illuminazione. Con l'estrazione integrale sono ora disponibili codice tariffa, quantita' e prezzo unitario di ogni voce: il confronto prezzi e il dimensionamento economico di una miglioria sono verificabili voce per voce" }
  - { criterion: "[[C2]]", priority: alta, confidence: verificato, reason: "Sottocategoria 003 'Sostituzione Chiusure Trasparenti' € 158.811,91 (17,341%). Ora scomponibile: 4 voci di nuovi infissi per € 155.754,25 (CAM25_E18.090.012.B/C/D in PVC + NP.10) su 195,49 mq totali, con prezzi unitari 635,39 / 650,75 / 875,72 / 481,47 €/mq — base diretta per quantificare l'extra-costo di una miglioria sugli infissi" }
  - { criterion: "[[C3]]", priority: alta, confidence: verificato, reason: "Sottocategoria 006 'Impianto Fotovoltaico' € 57.139,96 (6,239%), ora scomposta nelle 23 voci del capitolo omonimo (moduli 105062a/105062b per 36.000 W complessivi a 1,01 e 0,93 €/W, inverter NP.09, strutture NP.08, cablaggi e protezioni) — base diretta per valutare l'incremento di potenza o di qualita' dei componenti" }
related_documents:
  - { doc: "[[R.01_Relazione_Generale_e_Tecnica_Illustrativa]]", type: computo_di, reason: "Il computo metrico misura le opere descritte nella relazione generale R.01" }
  - { doc: "[[R.01_Relazione_Generale_e_Tecnica_Illustrativa]]", type: referenced_by, reason: "R.01 rimanda a C.01 come fonte degli importi delle voci di progetto descritte" }
  - { doc: "[[C.02_Elenco_Prezzi_Unitari]]", type: references, reason: "Tutti i 98 codici tariffa distinti usati nelle 101 righe del computo sono elencati in C.02, e i 98 prezzi unitari coincidono uno a uno (0 scostamenti verificati in estrazione integrale il 2026-07-20)" }
  - { doc: "[[C.03_Analisi_dei_Prezzi]]", type: references, reason: "Le 12 voci a nuovo prezzo NP.01-NP.12 usate nel computo (€ 260.184,34, 28,41% del totale) rimandano esplicitamente all'analisi prezzi: la descrizione di ciascuna riporta '(VEDI ANALISI DEI PREZZI)'" }
  - { doc: "[[C.04_Stima_Incidenza_Manodopera]]", type: referenced_by, reason: "C.04 replica la struttura di voci e categorie di C.01 aggiungendo la colonna costo manodopera" }
  - { doc: "[[C.07_Quadro_Economico]]", type: referenced_by, reason: "C.07 riporta coincidenza esatta con la voce A.1 di C.01 (€ 915.809,83)" }
  - { doc: "[[COMPUTO_OPERE_OPZIONALI]]", type: referenced_by, reason: "Il computo delle opere opzionali richiama C.01 per collegamento concettuale di metodologia (stessa tecnica PriMus, opere fuori dal computo a base d'appalto)" }
cost_summary:
  totale_eur: 915809.83         # confidence: verificato — somma ricostruita delle 101 righe SOMMANO = totale stampato, scostamento € 0,00
  voci_count: 101               # confidence: verificato — N. 1-101, nessuna mancante, nessuna duplicata, 0 non parsate
  codici_tariffa_distinti: 98   # confidence: verificato — 3 codici usati due volte
  voci_senza_codice: 0          # confidence: verificato
famiglie_codice:                # confidence: verificato — tripartizione che definisce il perimetro del price-gap check
  - { famiglia: "CAM25_*", descrizione: "Prezzario Regione Campania 2025", righe: 73, codici_distinti: 70, importo_eur: 608462.99, pct: 66.44, confrontabile_con_prezzario: true }
  - { famiglia: "NP.01-NP.12", descrizione: "Nuovi prezzi — analisi in C.03", righe: 12, codici_distinti: 12, importo_eur: 260184.34, pct: 28.41, confrontabile_con_prezzario: false }
  - { famiglia: "sei cifre + lettera", descrizione: "Codici fuori dallo schema regionale (es. 015008c, 105062a, 205015e_)", righe: 16, codici_distinti: 16, importo_eur: 47162.50, pct: 5.15, confrontabile_con_prezzario: false }
---

## Per Claude futuro

Questo e' il computo_metrico C.01 della gara "efficientamento energetico Istituto Comprensivo
De Luca Picione Caravita" (Cercola, NA): il Computo Metrico Estimativo del progetto a base
d'appalto (26 pagine, stampa PriMus, World Building Engineering S.r.l. — Ing. Martino Rango,
31/03/2026).

**Re-ingest 2026-07-20 — estrazione ora INTEGRALE (26/26 pagine).** La versione precedente di
questa pagina si basava su un'estrazione parziale (solo pag. 1-3 e 24-25) e portava
`confidence: parziale` con `voci_count: TBD`. Ora sono disponibili **tutte le 101 voci** con
**codice tariffa, unita' di misura, quantita', prezzo unitario e importo**, piu' i blocchi
dimensionali di misura (par.ug./lung./larg./H-peso) nella sezione "Dettaglio voci e misure" del
file estratto. Il totale ricostruito sommando le 101 righe `SOMMANO` da **€ 915.809,83**, identico
al totale stampato: **quadratura esatta, scostamento € 0,00**. Confidence della pagina: `verificato`.

Cosa cambia per gli agenti a valle: non serve piu' riaprire il PDF con `pdf-reader` per conoscere
il prezzo unitario o la quantita' di una lavorazione. Il confronto tra il prezzo di progetto e il
prezzario regionale, il dimensionamento economico di una miglioria e il calcolo dell'incidenza di
una singola voce sul totale sono ora eseguibili direttamente dal file estratto
`01_extracted/text/sub_15175049978810242486_C.01 - COMPUTO METRICO ESTIMATIVO.md`.

## Tripartizione dei codici tariffa — perimetro del price-gap check

**Questa e' l'informazione operativa piu' importante della pagina.** Le 101 voci si dividono in
tre famiglie di codice e **solo la prima e' confrontabile con il prezzario regionale**:

| Famiglia | Cosa e' | Righe | Codici distinti | Importo (€) | % del totale | Confrontabile col prezzario |
|---|---|---:|---:|---:|---:|---|
| `CAM25_*` | Prezzario Regione Campania 2025 | 73 | 70 | 608.462,99 | 66,44% | **SI** |
| `NP.01`–`NP.12` | Nuovi prezzi, analisi in [[C.03_Analisi_dei_Prezzi]] | 12 | 12 | 260.184,34 | 28,41% | **NO — per definizione assenti dal prezzario** |
| sei cifre + lettera | Fuori dallo schema di codifica regionale | 16 | 16 | 47.162,50 | 5,15% | **NO — non riconducibili al prezzario Campania 2025** |

Confidence: `verificato` — conteggi e somme ricavati dalle 101 righe estratte, il totale delle tre
famiglie ricompone € 915.809,83.

**Conseguenza operativa:** un price-gap check contro il Prezzario Campania 2025 puo' coprire al
massimo il **66,44%** dell'importo lavori. Il restante **33,56%** (€ 307.346,84) non e'
confrontabile con il prezzario e va valutato per altra via — per i nuovi prezzi attraverso
[[C.03_Analisi_dei_Prezzi]], per i codici a sei cifre risalendo al listino di provenienza (non
dichiarato nel documento: **TBD**, non inferire).

### Nuovi prezzi NP.01-NP.12 — pesano il 28,41% dell'importo

Nessuno di questi ha un riscontro nel prezzario regionale: la loro congruita' si valuta solo
leggendo [[C.03_Analisi_dei_Prezzi]]. Sono l'area di maggiore discrezionalita' del progettista e
quindi il terreno piu' promettente — e piu' rischioso — per una proposta migliorativa.

| Codice | Descrizione sintetica | Capitolo (gruppo di misura) | U.M. | Q.ta' | Prezzo unit. (€) | Importo (€) |
|---|---|---|---|---:|---:|---:|
| `NP.02` | Isolamento orizzontale su manto di copertura | Isolamento Termico Orizzontale | mq | 762,00 | 146,44 | 111.587,28 |
| `NP.06` | Nuovo impianto termico "factory made" (generatore a condensazione + pompa di calore) | Nuovo Impianto Termico | cad | 1,00 | 73.911,60 | 73.911,60 |
| `NP.05` | Nuova rete di distribuzione impianto termico | Impianto Termico | cad | 1,00 | 27.192,69 | 27.192,69 |
| `NP.04` | Manutenzione e adeguamento impianto elettrico ai nuovi carichi | Impianto Elettrico | cad | 1,00 | 23.401,78 | 23.401,78 |
| `NP.09` | Inverter trifase 20 kW | Impianto Fotovoltaico | cad | 2,00 | 3.016,62 | 6.033,24 |
| `NP.08` | Struttura di sostegno fotovoltaico con zavorre | Impianto Fotovoltaico | cad | 38,00 | 141,06 | 5.360,28 |
| `NP.03` | Profilo perimetrale di ritenzione ghiaia | Interventi in Copertura | ml | 95,00 | 32,14 | 3.053,30 |
| `NP.07` | Sistema di controllo e regolazione caldaia/pompa di calore | Impianto Termico | cad | 1,00 | 2.921,94 | 2.921,94 |
| `NP.10` | Infisso PVC 4 ante a vasistas, zona climatica C | Nuovi Infissi | mq | 6,00 | 481,47 | 2.888,82 |
| `NP.12` | Allacci lavabo e docce, multistrato PN 10 Ø16 | Impianto Idrico Sanitario | cad | 27,00 | 98,51 | 2.659,77 |
| `NP.11` | Allacci vasi WC, multistrato PN 10 Ø16 | Impianto Idrico Sanitario | cad | 13,00 | 67,91 | 882,83 |
| `NP.01` | Rimozione accessori da pareti interne ed esterne | Rimozione Accessori | cad | 1,00 | 290,81 | 290,81 |
| | **Totale NP** | | | | | **260.184,34** |

Confidence: `verificato` (tutti i valori letti dal computo estratto).

### Codici a sei cifre + lettera (16 voci, € 47.162,50)

`015008c`, `015032d`, `015041c`, `025165c`, `025236c`, `025237a`, `035060d`, `035217f`, `035404n`,
`105025`, `105028`, `105046d`, `105046e`, `105062a`, `105062b`, `205015e_`.

Sono concentrati sull'impianto fotovoltaico (moduli, cavi, protezioni) e sull'impianto idrico.
Il documento non dichiara da quale listino provengano: **TBD — non attribuire al prezzario
Campania 2025**. Nota: `205015e_` ha l'underscore finale esattamente come stampato nel PDF.

## Avvertenze di matching (da tramandare a chi fa lookup sui codici)

1. **Suffisso `(CAM)`** — es. `CAM25_R02.090.060.A(CAM)`: e' il marcatore PriMus di voce conforme
   ai Criteri Ambientali Minimi, **non fa parte del codice di prezzario**. Per il lookup usare la
   radice senza suffisso (`CAM25_R02.090.060.A`).
2. **`205015e_`** — l'underscore finale e' stampato cosi' nel PDF, non e' un artefatto di parsing.
3. **Categoria/sottocategoria per singola voce: NON stampata nel corpo del computo.** PriMus la
   espone solo nei riepiloghi finali (pp. 23-25). La colonna "Capitolo (gruppo di misura)" del file
   estratto riporta l'etichetta di raggruppamento realmente stampata sopra le misure della voce
   (es. "Impianto Fotovoltaico", "Nuovi Infissi"): **nessuna attribuzione di categoria e' stata
   inferita**. Non trattare il capitolo come se fosse la categoria OG del riepilogo.
4. **Artefatti tipografici PriMus**: parole spezzate da uno spazio ("p osa", "Imp ianto",
   "cop p ie"). Testo lasciato verbatim nel file estratto: tenerne conto nelle ricerche full-text.
5. **Descrizioni troncate**: nel corpo del computo PriMus tronca con " ... ". Il file estratto
   riporta nella colonna Descrizione la versione integrale della stessa voce presa da
   [[C.02_Elenco_Prezzi_Unitari]] (corrispondenza 1:1 sul codice, verificata su tutte le 101 righe),
   e conserva la stampa verbatim di C.01 nella sezione "Dettaglio voci e misure".
6. **3 codici compaiono due volte** nel computo (`CAM25_E01.015.010.A`, `CAM25_L02.010.260.I`,
   `CAM25_R02.060.018.A(CAM)`): due righe distinte con quantita' diverse e stesso prezzo unitario.
   Non deduplicare sommando erroneamente.

## Riepilogo per categorie (fonte: pp. 23-25, verbatim)

| Codice | Categoria / Sottocategoria | Importo (€) | Incid. % | Confidence |
|---|---|---:|---:|---|
| `M:001.001` | **OG 1 — Edifici Civili e Industriali** | 601.249,40 | 65,652 | verificato |
| `M:001.001.001` | Isolamento Termico Superfici Opache Verticali | 109.542,62 | 11,961 | verificato |
| `M:001.001.002` | Isolamento Termico Superfici Opache Orizzontali | 165.770,44 | 18,101 | verificato |
| `M:001.001.003` | Sostituzione Chiusure Trasparenti (infissi) | 158.811,91 | 17,341 | verificato |
| `M:001.001.008` | Finiture di Opere Generali | 159.846,43 | 17,454 | verificato |
| `M:001.001.010` | Rifiuti | 7.278,00 | 0,795 | verificato |
| `M:001.002` | **OG 9 — Impianti Produzione Energia Elettrica** | 82.954,99 | 9,058 | verificato |
| `M:001.002.004` | Impianto Elettrico | 23.401,78 | 2,555 | verificato |
| `M:001.002.005` | Impianto Termico (quota OG9) | 2.413,25 | 0,264 | verificato |
| `M:001.002.006` | Impianto Fotovoltaico | 57.139,96 | 6,239 | verificato |
| `M:001.003` | **OG 11 — Impianti Tecnologici** | 231.605,44 | 25,290 | verificato |
| `M:001.003.005` | Impianto Termico (quota OG11) | 119.521,32 | 13,051 | verificato |
| `M:001.003.007` | Impianto Idro-Sanitario | 57.639,89 | 6,294 | verificato |
| `M:001.003.009` | Illuminazione | 54.444,23 | 5,945 | verificato |
| | **TOTALE LAVORI A MISURA** | **915.809,83** | 100,000 | verificato |

L'importo € 915.809,83 coincide esattamente con la voce A.1 del Quadro Economico
[[C.07_Quadro_Economico]] e con `importo_lavori_eur` in `02_graph/economic_framework.md`.
**Nessuna contraddizione economica rilevata dopo l'estrazione integrale.**

## Aggregati per capitolo, sui temi dei criteri C1/C2/C3

Aggregazione delle 101 voci per etichetta di raggruppamento stampata. Confidence: `verificato`
sui singoli importi; l'aggregazione e' aritmetica sulle righe estratte.

### Infissi — criterio [[C2]] (€ 158.811,91, sottocategoria 003)

| N. | Codice | Descrizione | U.M. | Q.ta' | Prezzo unit. (€) | Importo (€) |
|---:|---|---|---|---:|---:|---:|
| 56 | `CAM25_E18.090.012.B` | Infisso PVC, zona climatica C-D | mq | 5,68 | 635,39 | 3.609,02 |
| 57 | `CAM25_E18.090.012.C` | Infisso PVC a 2 ante a battente | mq | 52,05 | 650,75 | 33.871,54 |
| 58 | `CAM25_E18.090.012.D` | Infisso PVC scorrevole complanare 2 ante | mq | 131,76 | 875,72 | 115.384,87 |
| 59 | `NP.10` | Infisso PVC 4 ante a vasistas | mq | 6,00 | 481,47 | 2.888,82 |
| | **Nuovi infissi** | | **mq** | **195,49** | | **155.754,25** |
| 3-5 | `CAM25_R02.025.050.A/B/C(CAM)` | Rimozione infissi in ferro/alluminio | mq | 206,49 | 10,91 / 8,72 / 7,27 | 1.715,01 |

Nota di riconciliazione (aritmetica, non stampata nel documento): 155.754,25 + 1.715,01 +
1.342,65 (voce 22, canali di gronda, capitolo "Opere di Lattoneria") = **158.811,91**, cioe'
esattamente la sottocategoria 003. E' una **ipotesi di riconciliazione verificata sul totale**,
non un'attribuzione di categoria stampata nel computo: il documento non dichiara a quale
sottocategoria appartenga ciascuna voce (vedi avvertenza 3).

**Il 74% dell'importo infissi sta in una sola voce** (`CAM25_E18.090.012.D`, scorrevole complanare,
875,72 €/mq su 131,76 mq): e' li' che una miglioria sugli infissi produce il maggiore impatto
economico, ed e' una voce `CAM25_*`, quindi confrontabile col prezzario.

### Isolamento termico — criterio [[C1]]

| Sottocategoria | Voci | Importo (€) | Composizione |
|---|---|---:|---|
| 001 — Opache verticali | voce 21 `CAM25_E10.040.040.E(CAM)` cappotto EPS con grafite, 1.357,84 mq x 80,46 €/mq = 109.251,81; + voce 2 `NP.01` 290,81 | 109.542,62 | riconciliazione aritmetica esatta |
| 002 — Opache orizzontali | voce 24 `NP.02` 762,00 mq x 146,44 €/mq = 111.587,28; + capitolo "Interventi in Copertura" (voci 17, 18, 23, 25) = 54.183,16 | 165.770,44 | riconciliazione aritmetica esatta |

Il cappotto verticale e' una voce `CAM25_*` (confrontabile col prezzario); l'isolamento orizzontale
e' `NP.02`, nuovo prezzo (**non** confrontabile: va letto in [[C.03_Analisi_dei_Prezzi]]).

### Impianto fotovoltaico — criterio [[C3]] (€ 57.139,96, sottocategoria 006)

23 voci nel capitolo "Impianto Fotovoltaico", il cui totale coincide **esattamente** con la
sottocategoria 006. Voci principali:

| N. | Codice | Descrizione | U.M. | Q.ta' | Prezzo unit. (€) | Importo (€) |
|---:|---|---|---|---:|---:|---:|
| 34 | `105062a` | Modulo FV silicio monocristallino, fino a 20 kW | W | 20.000,00 | 1,01 | 20.200,00 |
| 35 | `105062b` | Modulo FV, quota oltre i 20 kW (20-100 kW) | W | 16.000,00 | 0,93 | 14.880,00 |
| 36 | `NP.09` | Inverter trifase 20 kW | cad | 2,00 | 3.016,62 | 6.033,24 |
| 33 | `NP.08` | Struttura di sostegno con zavorre | cad | 38,00 | 141,06 | 5.360,28 |
| 42 | `035060d` | Modulo differenziale tripolare | cad | 13,00 | 175,29 | 2.278,77 |
| 47 | `105028` | Protezione di interfaccia CEI 0-21 | cad | 1,00 | 1.534,42 | 1.534,42 |
| 41 | `035404n` | Interruttore magnetotermico 4,5 kA curva C | cad | 13,00 | 113,38 | 1.473,94 |
| 37 | `CAM25_L02.030.220.F` | Canale portacavi 120x80 IP40 | cad | 15,00 | 87,49 | 1.312,35 |
| — | (altre 15 voci: cavi, tubi, scavi, pozzetto, dispersore, contattore, rele') | | | | | 4.067,96 |
| | **Totale capitolo Impianto Fotovoltaico** | | | | | **57.139,96** |

Potenza computata: **36.000 W** (20.000 W a 1,01 €/W + 16.000 W a 0,93 €/W). I moduli sono codici a
sei cifre, **non** confrontabili col prezzario regionale; inverter e strutture sono nuovi prezzi.
Di conseguenza il price-gap check su C3 e' possibile solo su cavi, canaline e opere edili
accessorie (voci `CAM25_*`), che pesano poco piu' del 5% del capitolo.

## Le dieci voci di maggiore importo (concentrazione della spesa)

| N. | Codice | Importo (€) | % del totale | Capitolo |
|---:|---|---:|---:|---|
| 58 | `CAM25_E18.090.012.D` | 115.384,87 | 12,60% | Nuovi Infissi |
| 24 | `NP.02` | 111.587,28 | 12,18% | Isolamento Termico Orizzontale |
| 21 | `CAM25_E10.040.040.E(CAM)` | 109.251,81 | 11,93% | Isolamento Termico |
| 28 | `NP.06` | 73.911,60 | 8,07% | Nuovo Impianto Termico |
| 93 | `CAM25_L03.100.030.J(CAM)` | 49.708,56 | 5,43% | Nuovi Apparecchi Illuminanti |
| 87 | `CAM25_E13.015.010.B(CAM)` | 49.698,00 | 5,43% | Nuova Pavimentazione (esclusi WC) |
| 23 | `CAM25_E07.005.040.A(CAM)` | 41.656,25 | 4,55% | Interventi in Copertura |
| 57 | `CAM25_E18.090.012.C` | 33.871,54 | 3,70% | Nuovi Infissi |
| 27 | `NP.05` | 27.192,69 | 2,97% | Impianto Termico |
| 94 | `CAM25_E18.020.010.A` | 25.918,91 | 2,83% | Porte Interne |

Le prime 10 voci su 101 valgono **€ 638.181,51, il 69,7% dell'importo lavori**. Confidence:
`verificato`.

## Nota file gemello

Esiste un secondo file con contenuto identico: `sub_9238062272237864872_C.01 - COMPUTO METRICO
ESTIMATIVO.PDF` — 26 pagine, stessi metadati PriMus (CreationDate 01/04/2026 11:17:59), differisce
solo la ModDate. Duplicato di export PDF, non revisione: non si applica la regola
`version_group`/`is_latest`. Questo nodo rappresenta il file canonico `sub_15175049978810242486`,
che e' quello estratto integralmente.

## Riferimenti a altri elaborati

- [[C.02_Elenco_Prezzi_Unitari]] — listino dei 98 codici usati qui; prezzi verificati coincidenti 1:1
- [[C.03_Analisi_dei_Prezzi]] — analisi delle 12 voci NP.01-NP.12 (28,41% dell'importo)
- [[C.04_Stima_Incidenza_Manodopera]] — stessa struttura di voci/categorie con colonna manodopera
- [[C.07_Quadro_Economico]] — voce A.1 coincidente (€ 915.809,83)
- [[R.01_Relazione_Generale_e_Tecnica_Illustrativa]] — descrizione delle opere qui misurate
- Nessun rimando testuale esplicito ad altri codici elaborato nel corpo del computo (documento
  tabellare PriMus, non narrativo): gli archi sopra sono strutturali o basati sulla dicitura
  "(VEDI ANALISI DEI PREZZI)" delle voci NP.
