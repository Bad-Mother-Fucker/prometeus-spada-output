---
type: document
subtype: relazione_tecnica
gara: "Procedura aperta telematica per l'affidamento dell'appalto dei lavori di \"Intervento di efficientamento energetico dell'Istituto Comprensivo 'De Luca Picione Caravita' sito alla Via Nuova\""
date: 2026-07-19
ai-first: true
codice: "R.06"
file: "sub_1389663786756837900_R.06 - RELAZIONE CALCOLO ILLUMINOTECNICO.pdf"
section: "02"
version_group: "R.06"
is_latest: true
status: non_estratto
extracted_md: TBD
confidence: inferito
supports_criteria:
  - { criterion: "[[C1]]", priority: media, reason: "La sostituzione dei corpi illuminanti con LED (§7.5 di R.01) è un'opera di efficientamento energetico rientrante in C1; questa relazione ne descrive presumibilmente il dimensionamento illuminotecnico, ma il contenuto non è stato verificato per volume del documento (743 pagine, 55 MB)." }
related_documents:
  - { doc: "[[R.01_Relazione_Generale_e_Tecnica_Illustrativa]]", type: referenced_by, reason: "R.01 §7.5 cita R.06 per il dettaglio dell'intervento di relamping LED e del calcolo illuminotecnico" }
---

## Per Claude futuro

Questa è la Relazione Tecnico Specialistica di Calcolo Illuminotecnico (R.06). **Non estratta** in
questa fase: il PDF ha 743 pagine (55 MB), verosimilmente un export di calcolo fotometrico
punto-punto (tipico di software come DIALux/Relux), volume incompatibile con l'estrazione nel contesto
di Fase B. Confermata solo la pagina di copertina (identificazione documento). Confidence: inferito
(da nome file + copertina, non da lettura del contenuto).

## Cosa si sa con certezza (da altri elaborati verificati)

Da `[[R.01_Relazione_Generale_e_Tecnica_Illustrativa]]` §7.5: sostituzione di 216 plafoniere esistenti
(fluorescenti/LED miste, 11,196 kW installati) con nuove plafoniere LED, potenza post-operam dichiarata
7,301 kW — risparmio ~35%. Questo elaborato (R.06) presumibilmente contiene il calcolo illuminotecnico
di dettaglio (livelli di illuminamento, UNI EN 12464-1) a supporto di questa scelta, ma il dato
quantitativo sopra proviene da R.01, non da questo documento.

## Contenuto — TBD

Tutti i contenuti specifici (schema apparecchi, calcoli lux, layout corpi illuminanti) sono `TBD` — non
estratti. **Non inventare dati**: se necessario per l'analisi del criterio C1, richiedere lettura
mirata a `pdf-reader` on-demand in Fase 2, con estrazione parziale mirata (es. solo indice e riepilogo
finale, non le 743 pagine di calcolo).

## Riferimenti a altri elaborati (per Fase D — archi)
- Sostituzione plafoniere LED (dato quantitativo) → R.01 §7.5
- CAM impianti illuminazione (UNI EN 12464-1, LED ≥50.000h) → R.02

## Confidence
`inferito` — solo pagina di copertina letta (identificazione TAVOLA: R.06, progettista, oggetto).
Contenuto tecnico interamente `status: non_estratto`.
