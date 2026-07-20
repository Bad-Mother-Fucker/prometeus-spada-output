---
type: document
subtype: relazione_tecnica
gara: "Procedura aperta telematica per l'affidamento dell'appalto dei lavori di \"Intervento di efficientamento energetico dell'Istituto Comprensivo 'De Luca Picione Caravita' sito alla Via Nuova\""
date: 2026-07-19
ai-first: true
codice: "R.04"
file: "sub_9175526598134801674_R.04 -RELAZIONE ENERGETICA (EX LEGGE 10).pdf"
section: "02"
version_group: "R.04"
is_latest: true
status: estratto
extracted_md: "01_extracted/text/sub_9175526598134801674_R.04 -RELAZIONE ENERGETICA (EX LEGGE 10).md"
confidence: verificato
supports_criteria:
  - { criterion: "[[C1]]", priority: alta, reason: "Allegato tecnico obbligatorio richiesto per la valutazione del criterio, art. 16 lett. m del disciplinare (\"Relazione energetica ex L.10 + APE post operam\"). Contiene la tabella completa trasmittanze ante/post e le verifiche di legge." }
  - { criterion: "[[C2]]", priority: alta, reason: "Stesso allegato tecnico obbligatorio richiesto anche per C2 ex art. 16 lett. m — le trasmittanze post-operam includono l'effetto della sostituzione infissi." }
  - { criterion: "[[C3]]", priority: alta, reason: "Stesso allegato tecnico obbligatorio richiesto anche per C3 ex art. 16 lett. m — riporta il dimensionamento e la copertura del fabbisogno da FV (40,99%)." }
related_documents:
  - { doc: "[[R.01_Relazione_Generale_e_Tecnica_Illustrativa]]", type: references, reason: "R.04 cita R.01 per la simulazione energetica dello stato di progetto (EPgl,nren)" }
  - { doc: "[[R.03_Attestato_di_Prestazione_Energetica]]", type: references, reason: "R.04 cita R.03 per l'APE post-operam, EPgl,ren, energia esportata (valori coerenti)" }
  - { doc: "[[R.05_Relazione_Impianto_Fotovoltaico]]", type: references, reason: "R.04 cita R.05 per il dettaglio dell'impianto fotovoltaico" }
  - { doc: "[[S.04_Piano_Sicurezza_Coordinamento]]", type: references, reason: "R.04 cita S.04 come conferma indipendente della presenza delle caldaie a gas nell'impianto termico ibrido" }
  - { doc: "[[R.01_Relazione_Generale_e_Tecnica_Illustrativa]]", type: referenced_by, reason: "R.01 cita R.04 per le verifiche di legge (arco reciproco)" }
  - { doc: "[[R.02_Relazione_CAM]]", type: referenced_by, reason: "R.02 cita R.04 per la coerenza dell'impianto fotovoltaico e della diagnosi energetica" }
  - { doc: "[[R.03_Attestato_di_Prestazione_Energetica]]", type: referenced_by, reason: "R.03 cita R.04 per il confronto EPgl,tot (arco reciproco)" }
  - { doc: "[[R.05_Relazione_Impianto_Fotovoltaico]]", type: referenced_by, reason: "R.05 cita R.04 per il dimensionamento e la copertura del fabbisogno FV (arco reciproco)" }
  - { doc: "[[S.04_Piano_Sicurezza_Coordinamento]]", type: referenced_by, reason: "S.04 cita R.04 nella nota sulla contraddizione relativa alle caldaie a gas (arco reciproco, motivazione diversa da quella sopra)" }
---

## Per Claude futuro

Questa è la Relazione Tecnica ex L.10/91 e D.Lgs 192/05 (R.04), software TerMus (ACCA), richiesta
Permesso di Costruire n.01/2025 del 16/07/2025. Come `[[R.03_Attestato_di_Prestazione_Energetica]]`, è
esplicitamente citata nel disciplinare (art. 16 lett. m) come **allegato tecnico obbligatorio per tutti
e tre i criteri qualitativi C1, C2, C3**. Contiene le verifiche di legge sull'involucro e sugli impianti,
tutte dichiarate positive. Confidence: verificato (14/14 pagine lette).

## Contenuto chiave

- Gradi giorno: 1.105 GG — Volume riscaldato 13.387,15 m³ — Superficie disperdente 7.095,72 m² — S/V 0,53
- Superficie utile riscaldata 2.643,38 mq (coerente con R.03)
- Nessuna climatizzazione estiva prevista

**Impianti termici stato di progetto**:
- Zona vecchia: PdC aria-acqua (91,20 kW utile, COP 3,09) + **caldaia a metano** (194,80 kW utile,
  rendimento 97,90%/106,70%) — vedi nota contraddizione in `[[R.02.1_Relazione_DNSH]]`
- Zona nuova: PdC aria-acqua (129,00 kW utile, COP 3,17)
- Terminali: 42 ventilconvettori, potenza nominale totale 101,186 kW

**Verifiche di legge** (tutte VERIFICATE): H'T = 0,25 < 0,60 W/m²K; ηH = 0,66 > 0,58; ηW = 0,81 > 0,59.

**Impianto fotovoltaico** (coerente con R.01/R.05): falda esistente 140 mq/24,00 kWp + falda nuova
144 mq/36,00 kWp SUD_OVEST 30° = 60,00 kW totali. Copertura fabbisogno annuo da FV: 40,99%.

**Bilancio energetico complessivo**: Edel = 69.362,76 kWh/anno; EPgl,ren = 47,29 kWh/m²anno (coerente
con R.03); energia esportata 43.774,75 kWh/anno (coerente con R.03); **EPgl,tot = 73,11 kWh/m²anno**
(indicatore diverso da EPgl,nren di R.01/R.03 — include quota rinnovabile e non rinnovabile, non
direttamente confrontabile in valore assoluto).

Nessuna deroga a norme richiesta (§7).

## ATTENZIONE — Contraddizione: Tilt/Azimut falda fotovoltaica nuova vs R.05

Questa relazione riporta per la falda nuova del fotovoltaico (36,00 kWp) inclinazione **30°** e
orientamento **SUD_OVEST**. `[[R.05_Relazione_Impianto_Fotovoltaico]]` — documento tecnico
specialistico dedicato, dati di calcolo elettrico — riporta invece per la stessa falda **Tilt 15,0°,
Azimut 0,0° (Sud)**. Potenza (36,00 kW) e superficie coerenti tra i due documenti: la discrepanza
riguarda solo l'angolo di inclinazione e l'orientamento. Possibile spiegazione non verificabile:
dato di progetto architettonico/energetico (questo documento) vs ipotesi cautelativa di calcolo
elettrico (R.05). **Non risolvibile senza lettura delle tavole EG.05.2 (Pianta Copertura Stato di
Progetto) o EG.07 (Sezioni Stato di Progetto)** o chiarimento del progettista. Da segnalare prima di
formulare proposte quantitative sulla producibilita' del fotovoltaico nel criterio [[C3]].

## Nota metodologica — tre indicatori energetici non comparabili tra loro

I tre valori 19,9614 (R.01, EPgl,nren), 25,8212 (R.03, EPgl,nren) e 73,11 (R.04, EPgl,tot) kWh/m²anno
riguardano tutti lo stesso edificio post-operam ma con metriche diverse: i primi due sono direttamente
confrontabili (stessa metrica EPgl,nren) e quindi generano la contraddizione segnalata in R.01/R.03; il
terzo (EPgl,tot) non è comparabile numericamente ai primi due. Non trattare come una terza
contraddizione — segnalato solo per chiarezza terminologica.

## Riferimenti a altri elaborati (per Fase D — archi)
- Simulazione energetica stato di progetto, EPgl,nren → R.01
- APE post-operam, EPgl,ren, energia esportata (valori coerenti) → R.03
- Impianto fotovoltaico (dettaglio) → R.05
- Conferma indipendente presenza caldaie → S.04
