---
type: document
subtype: tavola
gara: "Procedura aperta telematica per l'affidamento dell'appalto dei lavori di \"Intervento di efficientamento energetico dell'Istituto Comprensivo 'De Luca Picione Caravita' sito alla Via Nuova\""
date: 2026-07-19
ai-first: true
codice: "EG.05.2"
file: "sub_1834350179827911924_EG.05.2 - PIANTA COPERTURA - STATO DI PROGETTO.pdf"
section: "03"
version_group: "EG.05.2"
is_latest: true
status: non_estratto
confidence: inferito
supports_criteria:
  - { criterion: "[[C1]]", priority: media, confidence: inferito, reason: "Pianta di copertura allo stato di progetto: rappresenta l'esito dell'intervento 'Isolamento solaio tetto piano' (XPS 12 cm, U post = 0,2010 W/m²K) descritto in [[R.01_Relazione_Generale_e_Tecnica_Illustrativa]] §7.2 — corrispondenza tematica dedotta dal titolo." }
  - { criterion: "[[C3]]", priority: media, confidence: inferito, reason: "Pianta di copertura allo stato di progetto: rappresenta presumibilmente la nuova falda fotovoltaica aggiuntiva (SUD_OVEST, 144 mq, 36,00 kWp, per un totale di 60,00 kWp con l'esistente) descritta in [[R.01_Relazione_Generale_e_Tecnica_Illustrativa]] §7.6 — tavola potenzialmente la piu' direttamente rilevante per il criterio C3 tra le tavole disponibili, ma resta a confidence inferito in assenza di lettura del contenuto grafico." }
related_documents:
  - { doc: "[[R.01_Relazione_Generale_e_Tecnica_Illustrativa]]", type: tavola_di, reason: "R.01 descrive gli interventi di progetto sulla copertura (isolamento tetto, falda FV) rappresentati in questa pianta — arco strutturale, non verificato da lettura del contenuto grafico (confidence: inferito)" }
---

## Per Claude futuro

Questa e' la tavola EG.05.2 (Pianta Copertura — Stato di Progetto) della gara di
efficientamento energetico dell'Istituto Comprensivo "De Luca Picione Caravita"
(Cercola). E' la tavola che, per titolo e oggetto (copertura, stato di progetto),
dovrebbe rappresentare sia l'isolamento del solaio (C1) sia la nuova falda
fotovoltaica aggiuntiva (C3, 36,00 kWp secondo [[R.01_Relazione_Generale_e_Tecnica_Illustrativa]]
§7.6). Nessuna lettura del contenuto grafico e' stata eseguita: massima priorita'
tematica per C3 tra le tavole della gara, ma resta comunque `priority: media` e
`confidence: inferito` per policy (le tavole non vengono mai estratte). Lettura
approfondita raccomandata via `drawing-reader` in fase di analisi del criterio C3.

## Contenuto (da titolo/elenco elaborati, non verificato graficamente)

- Descrizione ufficiale: "Pianta Copertura — Stato di Progetto"
- Sezione di raggruppamento: 03
- Interventi di riferimento (da [[R.01_Relazione_Generale_e_Tecnica_Illustrativa]], non
  dalla tavola): isolamento solaio XPS 12 cm; nuovo impianto fotovoltaico 36,00 kWp su
  falda SUD_OVEST 144 mq (esistente 24,00 kWp + nuovo 36,00 kWp = 60,00 kWp totali)
  <!-- confidence: inferito --> — dettaglio impiantistico completo atteso in
  [[R.05_Relazione_Impianto_Fotovoltaico]] (Relazione impianto fotovoltaico)

## Nota

Lettura approfondita disponibile on-demand via `drawing-reader`. Raccomandata priorita'
alta per il criterio C3 data la diretta pertinenza tematica.
