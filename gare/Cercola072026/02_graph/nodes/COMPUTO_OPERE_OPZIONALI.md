---
type: document
subtype: computo_metrico
gara: "Procedura aperta telematica per l'affidamento dell'appalto dei lavori di \"Intervento di efficientamento energetico dell'Istituto Comprensivo 'De Luca Picione Caravita' sito alla Via Nuova\""
date: 2026-07-19
ai-first: true
codice: "COMPUTO OPERE OPZIONALI (nessun codice progetto in ELENCO ELABORATI.xlsx)"
file: "sub_11187281616641683157_COMPUTO DELLE OPERE OPZIONALI.PDF"
section: "08"
version_group: "COMPUTO_OPERE_OPZIONALI"
is_latest: true
status: estratto
extracted_md: "01_extracted/text/sub_11187281616641683157_COMPUTO DELLE OPERE OPZIONALI.md"
confidence: verificato
supports_criteria:
  - { criterion: "[[C4]]", priority: alta, reason: "Fonte diretta delle voci 01, 02, 04 richiamate esplicitamente dal titolo del criterio B1 come atto contabile di riferimento per l'attribuzione on/off del punteggio (art. 18.2 disciplinare)" }
  - { criterion: "[[C5]]", priority: alta, reason: "Fonte diretta delle voci 03, 05, 06, 07, 08 richiamate esplicitamente dal titolo del criterio B2 come atto contabile di riferimento per l'attribuzione on/off del punteggio (art. 18.2 disciplinare)" }
related_documents:
  - { doc: "[[C.01_Computo_Metrico_Estimativo]]", type: references, reason: "Collegamento concettuale: stessa metodologia di computo (PriMus), opere opzionali pero' fuori dal computo a base d'appalto" }
  - { doc: "[[S.01_Capitolato_Speciale_Appalto]]", type: stesso_lotto, reason: "Stessa sezione economico-contrattuale (08); nessun riferimento testuale diretto individuato, discipline documentali diverse (computo_metrico vs capitolato)" }
  - { doc: "[[C.02_Elenco_Prezzi_Unitari]]", type: stesso_lotto, reason: "Stessa sezione economico-contrattuale (08); nessun riferimento testuale diretto individuato, discipline documentali diverse (computo_metrico vs elenco_prezzi)" }
  - { doc: "[[C.03_Analisi_dei_Prezzi]]", type: stesso_lotto, reason: "Stessa sezione economico-contrattuale (08); nessun riferimento testuale diretto individuato, discipline documentali diverse (computo_metrico vs analisi_prezzi/altro)" }
cost_summary:
  totale_eur: 113000.00           # confidence: verificato
  voci_count: 8                    # confidence: verificato
---

## Per Claude futuro

Questo e' il computo_metrico "COMPUTO DELLE OPERE OPZIONALI" della gara
"efficientamento energetico Istituto Comprensivo De Luca Picione Caravita" (Cercola, NA). Non ha un codice progetto riconoscibile in ELENCO ELABORATI.xlsx (la
sezione compare come intestazione senza codice proprio, righe 54-56): l'identificatore usato e' il
filename stem, come da regola `references/graph-schema.md`. E' il documento contabile che definisce
le opzioni B1 (barriere architettoniche, criterio [[C4]]) e B2 (decoro esterno, criterio [[C5]])
richiamate dal disciplinare (art. 3.7). Cartiglio: Corigliano-Rossano, 01/04/2026. Confidence:
verificato — dati letti direttamente dal PDF tabellare.

**CONTRADDIZIONE CRITICA rilevata**: i valori economici dichiarati in `criteria_matrix.md` per C4
(€ 67.000) e C5 (€ 46.000) NON coincidono con la somma delle voci corrispondenti in questo computo
(C4 calcolato € 73.000, C5 calcolato € 40.000) — vedi sezione dedicata sotto e
`02_graph/economic_framework.md`.

## Contenuto chiave

**Voci di computo (LAVORI A MISURA):**

| N. voce | Codice | Descrizione | Importo (€) |
|---|---|---|---|
| 1 | O.OP.01 | Ascensore (impianto elevatore MRL, abbattimento barriere) | 46.000,00 |
| 2 | O.OP.02 | Rimozione scala esterna di emergenza | 8.000,00 |
| 3 | O.OP.03 | Pulizia generale aree a verde | 6.000,00 |
| 4 | O.OP.04 | Abbattimento barriere architettoniche (rampa, corrimano) | 19.000,00 |
| 5 | O.OP.05 | Pavimentazione esterna | 12.000,00 |
| 6 | O.OP.06 | Illuminazione esterna | 12.000,00 |
| 7 | O.OP.07 | Segnaletica (orizzontale e verticale) | 3.000,00 |
| 8 | O.OP.08 | Ripristini (rimozione graffiti, tinteggiatura, opere metalliche) | 7.000,00 |

**TOTALE COMPUTO OPERE OPZIONALI: € 113.000,00**

## CONTRADDIZIONE RILEVATA — valori economici C4/C5 vs somma voci

`03_criteria/criteria_matrix.md` (e `PROJECT_CONFIG.json`) dichiarano:
- [[C4]] (B1, voci 01, 02, 04) → valore economico dichiarato: **€ 67.000,00**
- [[C5]] (B2, voci 03, 05, 06, 07, 08) → valore economico dichiarato: **€ 46.000,00**

Somma effettiva delle voci corrispondenti in questo computo:
- Voci 01+02+04 (Ascensore 46.000 + Rimozione scala 8.000 + Abbattimento barriere 19.000) =
  **€ 73.000,00** (differenza di **+€ 6.000** rispetto al dichiarato 67.000)
- Voci 03+05+06+07+08 (Pulizia verde 6.000 + Pavimentazione 12.000 + Illuminazione 12.000 +
  Segnaletica 3.000 + Ripristini 7.000) = **€ 40.000,00** (differenza di **-€ 6.000** rispetto al
  dichiarato 46.000)

Il totale complessivo (€ 113.000,00) coincide in entrambi i casi (73.000+40.000 = 113.000 =
67.000+46.000): la contraddizione riguarda esclusivamente la **ripartizione tra C4 e C5**, non il
totale. Ipotesi non verificate: (a) errore di trascrizione nel disciplinare/criteria_matrix.md; (b)
le voci realmente assegnate a B1/B2 non sono esattamente 01,02,04 / 03,05,06,07,08 come riportato
nel testo del disciplinare. Poiche' C4 e C5 sono criteri tabellari on/off in cui "la proposta deve
corrispondere alle specifiche dell'atto contabile delle opzioni", questa discrepanza e'
**significativa e richiede verifica manuale** prima dell'analisi dei criteri C4/C5. Documentata
anche in `02_graph/economic_framework.md` e da riportare come CONTRADDIZIONE nell'`index.md`.

## Nota file gemello

Esiste un secondo file con contenuto identico: `sub_14753154722844715886_COMPUTO DELLE OPERE
OPZIONALI.PDF`. Verificato per confronto pagina-per-pagina (pag. 1-5): stesse 8 voci, stessi
importi, dimensione file identica (803.093 byte), MD5 diverso — duplicato di export, non revisione.
Non si applica la regola `version_group`/`is_latest`. Questo nodo rappresenta il file canonico
`sub_11187281616641683157`.

## Riferimenti a altri elaborati
- Nessun riferimento esplicito ad altri codici elaborato rilevato nel testo (documento tabellare
  PriMus). Collegamento concettuale a [[C.01_Computo_Metrico_Estimativo]] (stessa metodologia di
  computo, ma opere opzionali fuori dal computo a base d'appalto) — arco strutturale da valutare in
  Fase D.
