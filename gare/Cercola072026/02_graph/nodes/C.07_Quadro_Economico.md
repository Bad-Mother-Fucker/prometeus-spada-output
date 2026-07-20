---
type: document
subtype: quadro_economico
gara: "Procedura aperta telematica per l'affidamento dell'appalto dei lavori di \"Intervento di efficientamento energetico dell'Istituto Comprensivo 'De Luca Picione Caravita' sito alla Via Nuova\""
date: 2026-07-19
ai-first: true
codice: "C.07"
file: "sub_2623727743680319868_C.07 - QUADRO ECONOMICO.pdf"
section: "08"
version_group: "C.07"
is_latest: true
status: estratto
extracted_md: "01_extracted/text/sub_2623727743680319868_C.07 - QUADRO ECONOMICO.md"
confidence: verificato
supports_criteria: []
related_documents:
  - { doc: "[[C.01_Computo_Metrico_Estimativo]]", type: references, reason: "C.07 riporta coincidenza esatta con la voce A.1 del computo metrico" }
  - { doc: "[[C.04_Stima_Incidenza_Manodopera]]", type: references, reason: "C.07 riporta coincidenza esatta con la voce A.2 (manodopera)" }
  - { doc: "[[C.05_Computo_Metrico_Sicurezza]]", type: references, reason: "C.07 riporta coincidenza esatta con la voce A.3 (oneri sicurezza)" }
  - { doc: "[[C.06_Elenco_Prezzi_Sicurezza]]", type: references, reason: "C.07 riporta coincidenza esatta con la voce A.3 (oneri sicurezza)" }
  - { doc: "[[C.04_Stima_Incidenza_Manodopera]]", type: referenced_by, reason: "C.04 cita C.07 per la coincidenza del totale manodopera (arco reciproco)" }
  - { doc: "[[C.05_Computo_Metrico_Sicurezza]]", type: referenced_by, reason: "C.05 cita C.07 per la coincidenza del totale oneri sicurezza (arco reciproco)" }
  - { doc: "[[C.06_Elenco_Prezzi_Sicurezza]]", type: referenced_by, reason: "C.06 cita C.07 per la coincidenza del totale oneri sicurezza (arco reciproco)" }
  - { doc: "[[R.01_Relazione_Generale_e_Tecnica_Illustrativa]]", type: referenced_by, reason: "R.01 cita C.07 come fonte degli importi complessivi dell'intervento" }
cost_summary:
  totale_eur: 1367150.00          # confidence: verificato — TOTALE GENERALE QUADRO ECONOMICO
  voci_count: 15                   # confidence: verificato — righe A.1-A.3 + B.1.1-B.7
---

## Per Claude futuro

Questo e' il quadro_economico C.07 della gara "efficientamento energetico Istituto Comprensivo De Luca Picione Caravita" (Cercola, NA). E' il Quadro Tecnico
Economico (2 pagine, PriMus/tabella), non datato esplicitamente nel cartiglio. Fonte primaria di
`02_graph/economic_framework.md`. Confidence: verificato — dati letti direttamente dal PDF
tabellare. **`supports_criteria` intenzionalmente vuoto**: questo documento e' la cornice economica
generale dell'appalto (non evidenza di merito tecnico per uno specifico criterio C1-C6) — la sua
funzione e' alimentare `02_graph/economic_framework.md` e supportare l'audit di sostenibilita' economica
delle proposte migliorative (non un singolo criterio). Non lo si considera un "orfano" nel senso
negativo del termine: e' un documento strutturale, come chiarito in `02_graph/index.md`.

## Contenuto chiave

### A — LAVORI A BASE DI APPALTO

| Voce | Descrizione | Importo (€) |
|---|---|---|
| A.1 | Lavori, forniture e oneri per la manodopera soggetti a ribasso | 915.809,83 |
| A.2 | Costi per la manodopera non soggetti a ribasso | 180.457,45 |
| A.3 (nel PDF originale etichettata "A.2", refuso di battitura) | Oneri per la sicurezza, non soggetti a ribasso | 39.073,96 |
| **Totale lavori a base di appalto** | | **954.883,79** |

Questo importo (954.883,79 €) coincide esattamente con `PROJECT_CONFIG.json → gara.importo_base_asta`.

### B — SOMME A DISPOSIZIONE

| Voce | Descrizione | Importo (€) |
|---|---|---|
| B.1.1 | Progettazione esecutiva, CSP, Direzione Lavori, CRE | 111.739,32 |
| B.1.2 | Coordinatore Sicurezza Esecuzione (CSE) | 16.960,68 |
| B.1.3 | Collaudo tecnico amministrativo e statico | 0,00 |
| B.1.4 | Supporto al RUP come consulenza esecutiva | 14.000,00 |
| B.1.5 | Incentivi per funzioni tecniche (art. 45 D.Lgs 36/2023) | 15.278,14 |
| B.1.6 | Consulenza Energetica Energy Manager | 25.000,00 |
| B.1.7 | APE & Diagnosi Energetica | 4.260,00 |
| **Totale B.1 Prestazioni Tecniche** | | **187.238,14** |
| B.2.1 | Imprevisti sui lavori | 57.166,84 |
| B.3.1–B.3.6 | Previdenza CNPAIA — contributi EPAP (varie) | 6.878,40 |
| B.4 | Forniture | 0,00 |
| B.5.1 | Oneri della discarica ("Codici vari") | 25.000,00 |
| B.6 | Altro (spese gara CUC, economie post gara, contributo GSE, spese ANAC) | 1.150,00 |
| B.7 | IVA (varie aliquote 10%/22%) | 134.832,83 |

**TOTALE GENERALE QUADRO ECONOMICO: € 1.367.150,00** (954.883,79 lavori + 412.266,21 somme a
disposizione — quadratura verificata).

## Nota file gemello (fonte amministrativa non estratta)

`00_input/elaborati/QUADRO ECONOMICO.xlsx` e' verosimilmente la sorgente xlsx da cui e' esportato
questo PDF (stesso titolo, stessa sezione 08). Non e' stato estratto (formato xlsx, non prioritario
per Fase A): se in futuro estratto e discordante da questo PDF, va segnalata contraddizione. Allo
stato attuale nessun confronto e' possibile — TBD.

## Riferimenti a altri elaborati
- [[C.01_Computo_Metrico_Estimativo]] — coincidenza esatta voce A.1
- [[C.04_Stima_Incidenza_Manodopera]] — coincidenza esatta voce A.2
- [[C.05_Computo_Metrico_Sicurezza]], [[C.06_Elenco_Prezzi_Sicurezza]] — coincidenza esatta voce A.3 (oneri sicurezza)
