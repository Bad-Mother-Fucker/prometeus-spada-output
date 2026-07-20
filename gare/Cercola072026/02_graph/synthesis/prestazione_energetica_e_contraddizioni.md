---
type: synthesis
gara: "Procedura aperta telematica per l'affidamento dell'appalto dei lavori di \"Intervento di efficientamento energetico dell'Istituto Comprensivo 'De Luca Picione Caravita' sito alla Via Nuova\""
date: 2026-07-19
ai-first: true
tema: "Prestazione energetica post-operam e contraddizioni tra elaborati"
documenti_collegati:
  - "[[R.01_Relazione_Generale_e_Tecnica_Illustrativa]]"
  - "[[R.03_Attestato_di_Prestazione_Energetica]]"
  - "[[R.04_Relazione_Energetica_Ex_L10]]"
  - "[[R.02.1_Relazione_DNSH]]"
  - "[[S.04_Piano_Sicurezza_Coordinamento]]"
confidence: verificato
---

## Per Claude futuro

Pagina di sintesi generata dal synthesis hook di graph-builder: quattro documenti tecnici (R.01, R.03,
R.04, R.02.1) e un quinto di conferma indipendente (S.04) descrivono lo stesso oggetto — la prestazione
energetica post-operam dell'edificio e l'impianto termico di progetto — con **due contraddizioni
numeriche/dichiarative distinte** che vanno lette insieme prima di formulare proposte quantitative sul
criterio C1. Usa questa pagina come punto di ingresso invece di ricostruire il confronto da zero.

## Contraddizione 1 — EPgl,nren stato di progetto (R.01 vs R.03)

| Fonte | Valore EPgl,nren post-operam | Superficie di calcolo | Confidence |
|---|---|---|---|
| R.01 §8 | 19,9614 kWh/m²anno | 2.723,5 mq | verificato |
| R.03 (APE) | 25,8212 kWh/m²anno | 2.643,38 mq | verificato |

Differenza ~30% in termini relativi. Entrambi classe A4/nZEB. Possibili spiegazioni non verificabili dal
testo: perimetro di calcolo diverso (79,88 mq di scarto tra le due superfici dichiarate), versione di
calcolo diversa, o R.03 include voci aggiuntive. **Non risolvibile senza chiarimento del progettista.**

Nota aggiuntiva: R.04 riporta un terzo indicatore, EPgl,tot = 73,11 kWh/m²anno, che NON è comparabile
numericamente ai due EPgl,nren sopra (include quota rinnovabile e non rinnovabile) — non è una terza
contraddizione, solo un indicatore diverso riferito allo stesso stato di progetto.

## Contraddizione 2 — Esclusione caldaie a gas (R.02.1 vs R.01/R.04/S.04)

`[[R.02.1_Relazione_DNSH]]` dichiara nella checklist Art.5 Item 0: "È stata verificata l'esclusione
dall'intervento delle caldaie a gas? → **SI**".

Tre elaborati indipendenti descrivono invece la presenza di generatori a caldaia nell'impianto ibrido:

| Fonte | Descrizione caldaia |
|---|---|
| R.01 §7.4 | 2 caldaie a condensazione da ~33,80 kW cad. |
| R.04 | Caldaia a metano, 194,80 kW utile, rendimento 97,90%/106,70% |
| S.04 | Fase di lavorazione "Installazione di caldaia per impianto termico (autonomo)" |

Possibile spiegazione non verificabile: la stessa Relazione DNSH prevede una deroga per caldaie a gas
che rientrano in un più ampio programma di efficientamento con riduzione significativa delle emissioni,
costo ≤20% del programma complessivo, e accompagnate da investimenti in rinnovabili — condizioni che
l'impianto ibrido PdC+caldaia+FV di progetto potrebbe soddisfare, ma la relazione non lo esplicita in
corrispondenza dell'Item 0 della checklist. **Non risolvibile senza chiarimento del progettista.**
Rilevante per l'ammissibilità PNRR del progetto (Regime 1, contributo sostanziale alla mitigazione
climatica), non solo come nota tecnica minore.

## Implicazioni per l'analisi del criterio C1

- Non usare acriticamente il valore 19,9614 né 25,8212 kWh/m²anno come base di calcolo per il
  miglioramento percentuale proposto in offerta senza segnalare la duplice fonte al professionista.
- Se una proposta migliorativa tocca l'impianto termico (es. sostituzione ulteriore di generatori),
  verificare la compatibilità con la dichiarazione DNSH di esclusione caldaie a gas prima di
  presentarla come coerente con i vincoli di finanziamento PNRR.
- Entrambe le contraddizioni sono gia' riportate nelle pagine nodo dei singoli documenti coinvolti
  (`[[R.01_Relazione_Generale_e_Tecnica_Illustrativa]]`, `[[R.03_Attestato_di_Prestazione_Energetica]]`,
  `[[R.02.1_Relazione_DNSH]]`); questa pagina le riunisce per una lettura d'insieme.
