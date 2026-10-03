---
type: document
subtype: computo_metrico
gara: "Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)"
date: 2026-10-03
ai-first: true
codice: "G-04-ESEC-01"
file: "G-04-ESEC-01_COMPUTO_METRICO_ESTIMATIVO.pdf"
file_originale: "00_input/p7m/progetto.esecutivo.a.base.di.gara/pdf firmati/G_04_ESEC_01_COMPUTO METRICO ESTIMATIVO.PDF.p7m"
section: "G"
version_group: "G-04"
is_latest: false
status: estratto
extracted_md: "01_extracted/text/G-04-ESEC-01_COMPUTO_METRICO_ESTIMATIVO.md"
pagine: 25
data_elaborato: "aprile 2026 (cartiglio); computo datato 22/04/2026 (p. 25)"
copertura_lettura: "integrale; 139 voci estratte con lo stesso parser di G-04-ESEC-02 e confrontate voce per voce (codice, u.m., quantità, prezzo, importo, misure, categoria)"
confidence: verificato
cost_summary:
  totale_eur: 381364.99        # confidence: verificato, p. 23 e riepiloghi pp. 24-25 — identico a G-04-ESEC-02
  voci_count: 139              # confidence: verificato
  codici_distinti: 123         # confidence: verificato
supports_criteria:
  - { criterion: "[[C1]]", priority: bassa, reason: "Versione superata (is_latest: false) con voci identiche a G-04-ESEC-02 per C1 (serramenti voce 35, poltrone voce 102, pannelli voce 103): da usare solo per confronto tra versioni, mai come baseline" }
  - { criterion: "[[C2]]", priority: bassa, reason: "Versione superata: FV, accumulo 15 kWh e Building Automation identici a G-04-ESEC-02; solo confronto tra versioni" }
  - { criterion: "[[C3]]", priority: bassa, reason: "Versione superata: impermeabilizzazioni, pellicola cupola e allestimento palco identici a G-04-ESEC-02; solo confronto tra versioni" }
  - { criterion: "[[C4]]", priority: bassa, reason: "Versione superata: ascensore, cartongesso/silicati e taglio solaio identici a G-04-ESEC-02; solo confronto tra versioni" }
related_documents:
  - { doc: "[[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]]", type: versione_successiva, confidence: verificato, reason: "Revisione maggio 2026 che aggiorna questa: stesse 139 voci e totale 381.364,99 €, voce 37 a quantita' zero, aggiunti riepiloghi TOL/SOA e Allegato I revisione prezzi" }
  - { doc: "[[G-00-ESEC-01_ELENCO_ELABORATI]]", type: referenced_by, confidence: verificato, reason: "L'elenco elaborati G-00-ESEC-01 lo elenca per codice (p. 2) come «COMPUTO METRICO ESTIMATIVO»: fonte della descrizione ufficiale" }
---

# G-04-ESEC-01 — Computo metrico estimativo (revisione aprile 2026, SUPERATA)

> **# ATTENZIONE: valore aggiornato in [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]]** — questa versione ha `is_latest: false`. [[scope]] ed [[economic_framework]] leggono solo da G-04-ESEC-02.

## Per Claude futuro

Questo è il computo metrico estimativo G-04-ESEC-01 della gara «Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)». Descrizione ufficiale: «COMPUTO METRICO ESTIMATIVO» (voce G-04-ESEC-01 di [[G-00-ESEC-01_ELENCO_ELABORATI]]). È **superato** da [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] (maggio 2026). Il confronto voce per voce mostra che le due versioni hanno le stesse 139 voci, gli stessi prezzi e lo stesso totale (381.364,99 €); cambia solo la quantità della voce 37 (a importo nullo) e ESEC-02 aggiunge tre riepiloghi/allegati. Serve alla Fase E (contraddizioni tra versioni). Confidence: verificato.

## Contenuto chiave

| Dato | G-04-ESEC-01 | G-04-ESEC-02 | Esito | Confidence |
|---|---|---|---|---|
| Totale lavori a misura | 381.364,99 € | 381.364,99 € | identico | verificato |
| N. voci / codici | 139 / 123 | 139 / 123 | identico | verificato |
| Super-categorie (6) e categorie (19) | importi pp. 24-25 | importi pp. 24-25 | identici al centesimo | verificato |
| Voce 37 B.18.071.10 (PVC bicolore 60,96%) | q.tà 11,40 × 0,00 € = 0,00 € | q.tà 0,00 × 0,00 € = 0,00 € | quantità azzerata, nessun effetto economico | verificato |
| Altre 138 voci | — | — | identiche (codice, u.m., quantità, prezzo, importo, righe di misura) | verificato |
| Riepilogo sub-categorie TOL | assente | p. 26 | aggiunto in ESEC-02 | verificato |
| Riepilogo categorie SOA | assente | p. 27 | aggiunto in ESEC-02 | verificato |
| Allegato I «Relazione tecnica di revisione ed aggiornamento prezzi» | assente | pp. 28-35 | aggiunto in ESEC-02 | verificato |
| Data | 22/04/2026 | 14/05/2026 | — | verificato |
| Pagine | 25 | 35 | +10 pp. (allegati) | verificato |

Per il dettaglio delle voci (uguali) vedi [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] e la tabella completa in [[scope]].

## Riferimenti a altri elaborati

- Nessun codice di altro elaborato citato nel testo (solo «Vedi voce n° 12», interno). Cartiglio: G-04-ESEC-00 febbraio 2025 (non presente in `00_input`), G-04-ESEC-01 aprile 2026.
- Per Fase D: stesso `version_group` «G-04» di [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] → arco `versione_successiva`.
