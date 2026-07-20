---
type: document
subtype: relazione_tecnica
gara: "Procedura aperta telematica per l'affidamento dell'appalto dei lavori di \"Intervento di efficientamento energetico dell'Istituto Comprensivo 'De Luca Picione Caravita' sito alla Via Nuova\""
date: 2026-07-19
ai-first: true
codice: "R.05"
file: "sub_1033190081364072797_R.05 - RELAZIONE IMPIANTO FOTOVOLTAICO.pdf"
section: "02"
version_group: "R.05"
is_latest: true
status: estratto
extracted_md: "01_extracted/text/sub_1033190081364072797_R.05 - RELAZIONE IMPIANTO FOTOVOLTAICO.md"
confidence: verificato
supports_criteria:
  - { criterion: "[[C3]]", priority: alta, reason: "Relazione tecnico specialistica interamente dedicata all'impianto fotovoltaico oggetto del criterio C3 — potenza, produzione, componentistica, schemi elettrici." }
related_documents:
  - { doc: "[[R.01_Relazione_Generale_e_Tecnica_Illustrativa]]", type: references, reason: "R.05 cita R.01 §7.6 per la sintesi dell'impianto FV nel contesto generale del progetto" }
  - { doc: "[[R.04_Relazione_Energetica_Ex_L10]]", type: references, reason: "R.05 cita R.04 per il dimensionamento e la copertura del fabbisogno energetico tramite FV" }
  - { doc: "[[S.04_Piano_Sicurezza_Coordinamento]]", type: references, reason: "R.05 cita la fase di lavorazione 'realizzazione impianto solare fotovoltaico' descritta nel PSC" }
  - { doc: "[[R.01_Relazione_Generale_e_Tecnica_Illustrativa]]", type: referenced_by, reason: "R.01 cita R.05 per il dettaglio dell'impianto fotovoltaico (arco reciproco)" }
  - { doc: "[[R.02_Relazione_CAM]]", type: referenced_by, reason: "R.02 cita R.05 per la coerenza dell'impianto fotovoltaico (36 kW)" }
  - { doc: "[[R.03_Attestato_di_Prestazione_Energetica]]", type: referenced_by, reason: "R.03 cita R.05 per il dettaglio della produzione dell'impianto fotovoltaico" }
  - { doc: "[[R.04_Relazione_Energetica_Ex_L10]]", type: referenced_by, reason: "R.04 cita R.05 per il dettaglio dell'impianto fotovoltaico (arco reciproco)" }
---

## Per Claude futuro

Questa è la Relazione Tecnico Specialistica dell'Impianto Fotovoltaico (R.05), estratta in questa fase
via pdftotext (priorità alta, precedentemente non estratta). Descrive esclusivamente il NUOVO impianto
FV da 36,00 kW, aggiuntivo rispetto all'esistente (24,00 kWp, non oggetto di questo elaborato). È il
documento tecnico primario per il criterio C3. Confidence: verificato (46/46 pagine lette).

## Contenuto chiave

- Nuovo impianto: 36,00 kW (72 moduli JA Solar DeepBlue 4.0 X JAM60S40-500/LR, 159,48 m², 2 campi da
  18,00 kW), 2 inverter Each Energy Technology PHT4-20KW-M1
- Producibilità: 43.515,24 kWh/anno primo anno (1.208,76 kWh/kW specifico), perdita efficienza 0,90%/anno
- Tilt 15,0°, Azimut 0,0° (Sud), coefficiente ombreggiamento 1,00, riflettanza 0,20, BOS 74,97%
- Irradiazione: 5.425,20 MJ/m² (piano orizzontale, UNI 10349:2016 Airola), 1.610,56 kWh/m² (piano moduli)
- Sistema di accumulo: nessuno
- Benefici ambientali a 20 anni: 149,56 TEP risparmiate, 379.087,46 kg CO2 evitati
- Potenze bilanciate per fase: L1=L2=L3=12,00 kW (sbilanciamento 0,00 kW)
- Protezioni: interruttori magnetotermici differenziali Gewiss GW94050 su tutti i quadri

## Nota — possibile discrepanza Tilt/Azimut vs R.04

Questo elaborato riporta per il calcolo elettrico dei campi fotovoltaici Tilt=15,0° e Azimut=0,0° (Sud),
mentre `[[R.04_Relazione_Energetica_Ex_L10]]` riporta per la stessa falda nuova inclinazione 30° e
orientamento SUD_OVEST. Possibile spiegazione: dato di progetto architettonico/energetico (R.04) vs
ipotesi cautelativa di calcolo elettrico (R.05) — non necessariamente una contraddizione, ma segnalata
per verifica. Non risolvibile senza lettura delle tavole EG.05.2 (Pianta Copertura Stato di Progetto) o
EG.07 (Sezioni Stato di Progetto).

## Coerenza con altri elaborati

Potenza nuovo impianto (36,00 kW) coerente con R.01 §7.6 e R.04 (Falda 2). Potenza complessiva
(24,00+36,00=60,00 kW) coerente con R.01 e R.03 (APE dichiara PV installato 60,00 kW).

## Riferimenti a altri elaborati (per Fase D — archi)
- Impianto FV descritto in sintesi → R.01 §7.6
- Dimensionamento e copertura fabbisogno FV → R.04
- Fase di lavorazione "realizzazione impianto solare fotovoltaico" → S.04
