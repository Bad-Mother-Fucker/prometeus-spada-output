---
type: document
subtype: altro
gara: "Procedura aperta telematica per l'affidamento dell'appalto dei lavori di \"Intervento di efficientamento energetico dell'Istituto Comprensivo 'De Luca Picione Caravita' sito alla Via Nuova\""
date: 2026-07-19
ai-first: true
codice: "S.05"
file: "sub_15959735490678831121_S.05 - LAYOUT DI CANTIERE.pdf"
section: "09"
version_group: "S.05"
is_latest: true
status: parziale
extracted_md: "01_extracted/text/sub_15959735490678831121_S.05 - LAYOUT DI CANTIERE.md"
confidence: parziale
supports_criteria: []
# Nessun criterio agganciato: layout logistico di cantiere, non tecnico-migliorativo. Documento a
# prevalente contenuto grafico (planimetria), status parziale — solo legenda testuale estratta.
related_documents:
  - { doc: "[[S.04_Piano_Sicurezza_Coordinamento]]", type: referenced_by, reason: "S.04 rimanda a S.05 per aree e viabilita' di cantiere" }
  - { doc: "[[S.03_Cronoprogramma_Lavori]]", type: stesso_lotto, reason: "Stessa sezione sicurezza/cronoprogramma (09); nessun riferimento testuale diretto individuato, discipline documentali diverse (layout_cantiere/altro vs cronoprogramma)" }
---

## Per Claude futuro

Questo è il Layout di Cantiere (S.05), 1 pagina, nonostante il codice "S.xx" è essenzialmente una
**tavola grafica** (planimetria su base aerofotogrammetrica), non un documento testuale come gli altri
elaborati della Lista TESTUALI. Contiene però una legenda testuale interamente leggibile, già estratta.
Non supporta direttamente alcun criterio C1-C6. Rilevante per l'audit strategico "viabilità cantiere"
(vedi `03_criteria/strategy_audit.md`, dominio strategy-auditor). Confidence: parziale (legenda
verificata, planimetria non estratta).

## Contenuto chiave (legenda testuale)

- Aree identificate: area di cantiere, viabilità interna/esterna, ingresso cantiere, deposito/stoccaggio
  materiali, deposito/stoccaggio rifiuti, baraccamento, servizi igienici
- Ingresso cantiere: su Via Nuova, lato nord dell'area
- Aree deposito/stoccaggio: adiacenti al fabbricato aule, lato est
- Recinzione delimita l'area a ridosso del fabbricato aule e del refettorio
- Segnaletica: divieto accesso non addetti, limite velocità 30 km/h, attenzione carichi sospesi/caduta
  materiali, obbligo DPI (guanti, casco, scarpe)
- Nessun dato quantitativo aggiuntivo rispetto a `[[S.04_Piano_Sicurezza_Coordinamento]]` e
  `[[S.03_Cronoprogramma_Lavori]]`

## Contenuto grafico — non estratto

La planimetria vera e propria (disposizione grafica di aree/percorsi) resta `status: non_estratto` —
lettura approfondita disponibile on-demand via `drawing-reader`, se necessaria per l'analisi della
viabilità di cantiere nell'audit strategico o nell'analisi criteri.

## Riferimenti a altri elaborati (per Fase D — archi)
- Fasi di lavorazione, contesto cantiere → S.04
- Durata cantiere → S.03
