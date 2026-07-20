---
type: document
subtype: capitolato
gara: "Procedura aperta telematica per l'affidamento dell'appalto dei lavori di \"Intervento di efficientamento energetico dell'Istituto Comprensivo 'De Luca Picione Caravita' sito alla Via Nuova\""
date: 2026-07-19
ai-first: true
codice: "S.01"
file: "sub_13100082949839379961_S.01 - SCHEMA DI CONTRATTO E CAPITOLATO SPECIALE D_APPALTO.pdf"
section: "08"
version_group: "S.01"
is_latest: true
status: non_estratto
extracted_md: TBD
confidence: parziale
supports_criteria:
  - { criterion: "[[C1]]", priority: bassa, reason: "Definisce le specifiche tecniche contrattuali di base per le opere di efficientamento energetico; riferimento per valutare cosa è già incluso nel progetto base rispetto alle proposte migliorative — contenuto non ancora estratto." }
  - { criterion: "[[C2]]", priority: bassa, reason: "Definisce presumibilmente le specifiche tecniche di base per infissi e serramenti; riferimento per proposte migliorative — contenuto non ancora estratto." }
  - { criterion: "[[C3]]", priority: bassa, reason: "Definisce presumibilmente le specifiche tecniche di base per l'impianto fotovoltaico; riferimento per proposte migliorative — contenuto non ancora estratto." }
related_documents:
  - { doc: "[[R.02_Relazione_CAM]]", type: referenced_by, reason: "R.02 rimanda a S.01 per le modalita' di verifica dei CAM in fase esecutiva" }
  - { doc: "[[C.02_Elenco_Prezzi_Unitari]]", type: stesso_lotto, reason: "Stessa sezione economico-contrattuale (08); nessun riferimento testuale diretto individuato, discipline documentali diverse (capitolato vs elenco_prezzi)" }
  - { doc: "[[C.03_Analisi_dei_Prezzi]]", type: stesso_lotto, reason: "Stessa sezione economico-contrattuale (08); nessun riferimento testuale diretto individuato, discipline documentali diverse (capitolato vs analisi_prezzi/altro)" }
  - { doc: "[[COMPUTO_OPERE_OPZIONALI]]", type: stesso_lotto, reason: "Stessa sezione economico-contrattuale (08); nessun riferimento testuale diretto individuato, discipline documentali diverse (capitolato vs computo_metrico)" }
---

## Per Claude futuro

Questo è lo Schema di Contratto e Capitolato Speciale d'Appalto (S.01), 188 pagine. **Non estratto
integralmente** in questa fase (volume incompatibile con il contesto di Fase B): lette solo le prime 4
pagine (copertina + Capitolo 1, artt. 1-4). Confidence: parziale.

## Contenuto verificato (dalle prime 4 pagine)

- Oggetto: lavori di efficientamento energetico, nessuna suddivisione in lotti ("per la complessità dei
  lavori, unitari ed interagenti")
- Forma: procedura aperta, offerta economicamente più vantaggiosa
- **Quadro economico di sintesi (Art. 4)** — riportato qui per completezza, ma la fonte primaria per
  `economic_framework.md` resta C.07/QUADRO ECONOMICO (dominio Fase A):
  - Lavori a base d'appalto: € 954.883,79 (di cui € 915.809,83 soggetti a ribasso, € 180.457,45 costi
    manodopera non soggetti a ribasso, € 39.073,96 oneri sicurezza non soggetti a ribasso) — **coerente
    con PROJECT_CONFIG.json**
  - Somme a disposizione: prestazioni tecniche € 187.238,14, imprevisti € 57.166,84, oneri
    previdenziali € 6.878,40, oneri discarica € 25.000,00 (voce "Codici vari")
  - Nessun CIG riportato nel testo (campo vuoto "_________" all'art. 1) — diversamente dalle anomalie
    CIG riscontrate in R.02/R.02.1, qui il campo è semplicemente non compilato nel testo del capitolato,
    non un valore diverso

## Contenuto NON estratto — TBD

Il corpo tecnico del capitolato (specifiche materiali, modalità di esecuzione, norme di misurazione e
contabilizzazione, articoli su cappotto/infissi/impianti/fotovoltaico) è `TBD`. Se necessario per
l'analisi dei criteri C1/C2/C3 (per stabilire la baseline contrattuale rispetto a cui le proposte
migliorative devono aggiungere valore), richiedere lettura mirata a `pdf-reader` on-demand in Fase 2,
con estrazione per sezioni tematiche (non le 188 pagine intere in un colpo solo).

## Riferimenti a altri elaborati (per Fase D — archi)
- Quadro economico (coerenza importi) → C.07
