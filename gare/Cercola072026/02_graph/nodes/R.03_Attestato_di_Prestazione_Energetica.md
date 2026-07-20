---
type: document
subtype: relazione_tecnica
gara: "Procedura aperta telematica per l'affidamento dell'appalto dei lavori di \"Intervento di efficientamento energetico dell'Istituto Comprensivo 'De Luca Picione Caravita' sito alla Via Nuova\""
date: 2026-07-19
ai-first: true
codice: "R.03"
file: "sub_5937225928534581598_R.03 - ATTESTATO DI PRESTAZIONE ENERGETICA.pdf"
section: "02"
version_group: "R.03"
is_latest: true
status: estratto
extracted_md: "01_extracted/text/sub_5937225928534581598_R.03 - ATTESTATO DI PRESTAZIONE ENERGETICA.md"
confidence: verificato
supports_criteria:
  - { criterion: "[[C1]]", priority: alta, reason: "Allegato tecnico obbligatorio richiesto per la valutazione del criterio, art. 16 lett. m del disciplinare (\"Relazione energetica ex L.10 + APE post operam\"). Fornisce la prestazione energetica post-operam di riferimento." }
  - { criterion: "[[C2]]", priority: alta, reason: "Stesso allegato tecnico obbligatorio richiesto anche per C2 ai sensi dell'art. 16 lett. m del disciplinare — i miglioramenti su infissi incidono sulla prestazione energetica qui certificata." }
  - { criterion: "[[C3]]", priority: alta, reason: "Stesso allegato tecnico obbligatorio richiesto anche per C3 ai sensi dell'art. 16 lett. m del disciplinare — include il contributo energetico del fotovoltaico (24.315,42 kWh/anno prodotti)." }
related_documents:
  - { doc: "[[R.01_Relazione_Generale_e_Tecnica_Illustrativa]]", type: references, reason: "R.03 cita R.01 per lo stato di progetto e la simulazione energetica; segnalata contraddizione EPgl,nren (vedi corpo pagina)" }
  - { doc: "[[R.04_Relazione_Energetica_Ex_L10]]", type: references, reason: "R.03 cita R.04 per il confronto EPgl,tot e le verifiche di legge" }
  - { doc: "[[R.05_Relazione_Impianto_Fotovoltaico]]", type: references, reason: "R.03 cita R.05 per il dettaglio della produzione dell'impianto fotovoltaico" }
  - { doc: "[[R.02_Relazione_CAM]]", type: referenced_by, reason: "R.02 cita R.03 per la coerenza della diagnosi energetica pre/post" }
  - { doc: "[[R.01_Relazione_Generale_e_Tecnica_Illustrativa]]", type: referenced_by, reason: "R.01 cita R.03 per l'APE post-operam (arco reciproco, vedi anche references sopra)" }
  - { doc: "[[R.04_Relazione_Energetica_Ex_L10]]", type: referenced_by, reason: "R.04 cita R.03 per l'APE post-operam, EPgl,ren, energia esportata (arco reciproco)" }
---

## Per Claude futuro

Questo è l'Attestato di Prestazione Energetica post-operam (R.03), certificato da tecnico abilitato
(Ing. Martino Rango, Ordine Ingegneri Cosenza n.254), emesso 22/07/2025, validità 10 anni. È
esplicitamente citato nel disciplinare (art. 16 lett. m, vedi `criteria_matrix.md`) come **allegato
tecnico obbligatorio per la valutazione di tutti e tre i criteri qualitativi C1, C2, C3** — non solo
per C1. Contiene una **contraddizione numerica** con
`[[R.01_Relazione_Generale_e_Tecnica_Illustrativa]]` sul valore EPgl,nren. Confidence: verificato
(6/6 pagine lette).

## Contenuto chiave

- Oggetto: intero edificio, ristrutturazione importante, E7 attività scolastiche, zona climatica C
- Superficie utile riscaldata: 2.643,38 mq (nota: diversa dai 2.723,5 mq di R.01 — possibile differente
  perimetro di calcolo)
- **EPgl,nren = 25,8212 kWh/m²anno — Classe A4 (nZEB)** — vedi ATTENZIONE sotto
- EPgl,ren = 47,29 kWh/m²anno — Emissioni CO2: 5,74 kg/m²anno
- Energia elettrica da rete: 35.002,73 kWh/anno; FV prodotti: 24.315,42 kWh/anno; energia esportata:
  43.774,75 kWh/anno

**Raccomandazioni APE (interventi raccomandati e classe raggiungibile)**:

| Codice | Intervento | TR (anni) | Classe raggiungibile |
|---|---|---|---|
| REN1 | Cappotto pareti verticali | 342,0 | A1 (81,69) |
| REN1 | Isolamento tetto piano | 129,0 | A1 (77,65) |
| REN2 | Sostituzione infissi | 119,0 | A1 (73,82) |
| REN3 | Impianto termico ibrido | 6,0 | A4 (14,45) |
| REN6 | Impianto fotovoltaico | 18,0 | A2 (67,03) |
| Tutti gli interventi | — | — | A4, 8,51 kWh/m²anno |

Nota: la classe A4 "se si realizzano tutti gli interventi" (8,51 kWh/m²anno) è un TERZO valore, diverso
sia da questo APE (25,8212) sia da R.01 (19,9614) — probabile proiezione teorica di un pacchetto più
ampio di quello effettivamente a progetto.

## ATTENZIONE — Contraddizione con R.01 (EPgl,nren stato di progetto)

`[[R.01_Relazione_Generale_e_Tecnica_Illustrativa]]` §8 dichiara per lo stesso stato di
progetto/post-operam **EPgl,nren = 19,9614 kWh/m²anno**, contro i 25,8212 kWh/m²anno di questo APE.
Differenza ~30% in termini relativi (entrambi classe A4/nZEB). Entrambi i documenti sono `confidence:
verificato`. Non risolvibile senza chiarimento del progettista — vedi nota identica e più estesa nella
pagina di R.01. Da segnalare in fase di analisi C1 come dato numerico da chiarire prima di formulare
proposte quantitative sul risparmio energetico.

## Riferimenti a altri elaborati (per Fase D — archi)
- Relazione generale (stato di progetto, simulazione energetica) → R.01
- Relazione energetica ex L.10 (EPgl,tot, verifiche di legge) → R.04
- Impianto fotovoltaico (dettaglio produzione) → R.05
