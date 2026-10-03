---
type: document
subtype: tavola
gara: "Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)"
date: 2026-10-03
ai-first: true
codice: "PI-01-ESEC-01"
file: "PI_01_ESEC_01_SISTEMA EVACUAZIONE FUMI FORZATO.pdf.p7m"
file_originale: "00_input/p7m/progetto.esecutivo.a.base.di.gara/pdf firmati/PI_01_ESEC_01_SISTEMA EVACUAZIONE FUMI FORZATO.pdf.p7m"
pdf_leggibile: "01_extracted/p7m_extracted/PI-01-ESEC-01_SISTEMA_EVACUAZIONE_FUMI_FORZATO.pdf"
section: "PI"
version_group: "PI-01"
is_latest: true
status: non_estratto
extracted_md: "nessuno — tavola grafica, non estratta per regola (lettura on-demand via drawing-reader)"
confidence: inferito
descrizione_ufficiale: "PROGETTO SISTEMAZIONE EVACUAZIONE FUMI FORZATO"  # fonte: elenco elaborati G-00-ESEC-01 — confidence: inferito
in_elenco_elaborati: true
firmato: true  # firma CMS Martone Carmen 2026-04-24 (manifest)
pagine: 1
formato: "A1"
supports_criteria:
  - { criterion: "[[C3]]", priority: bassa, confidence: inferito, reason: "C3.1 cupola e copertura: il sistema di evacuazione fumi interessa verosimilmente la cupola/copertura (VVF-PI-07 cita torrini di estrazione sulla cupola) — vincolo antincendio per isolamento e schermature del sub 3.1. Inferito dal titolo" }
  - { criterion: "[[C2]]", priority: bassa, confidence: inferito, reason: "C2.1/C2.3: il testo grafico riporta il fotovoltaico in copertura (possibili interferenze con il BIPV); l'impianto di evacuazione fumi e' tra gli impianti del teatro da considerare nel controllo remoto integrato. Inferito, contenuto non letto" }
related_documents:
  - { doc: "[[G-00-ESEC-01_ELENCO_ELABORATI]]", type: referenced_by, confidence: verificato, reason: "L'elenco elaborati G-00-ESEC-01 lo elenca per codice (p. 2) come «PROGETTO SISTEMAZIONE EVACUAZIONE FUMI FORZATO»: fonte della descrizione ufficiale" }
  - { doc: "[[RS-00-ESEC-01_RELAZIONE_TECNICA_IMPIANTI]]", type: tavola_di, confidence: inferito, reason: "Tavola impiantistica abbinata alla relazione tecnica impianti; RS-00 NON descrive l'evacuazione fumi (nessuna relazione testuale dedicata: la tavola resta l'unica fonte) — abbinamento per disciplina, contenuto grafico non letto" }
---

# PI-01-ESEC-01 — Sistema di evacuazione fumi forzato

## Per Claude futuro
Questa e' la tavola PI-01-ESEC-01 della gara Cineteatro «Sala Polifunzionale Periz» — Castello di Bella (PZ), CIG BCF01395AF.
Rappresenta il progetto del sistema di evacuazione forzata dei fumi (scale 1:100 e 1:50) per la sezione PI (progetto impianti) — componente dell'adeguamento antincendio.
Lettura approfondita differita a drawing-reader on-demand. Confidence: inferito (descrizione da elenco elaborati e cartiglio; contenuto grafico non letto).

## Identificazione

| Campo | Valore | Fonte | Confidence |
|---|---|---|---|
| Descrizione ufficiale | PROGETTO SISTEMAZIONE EVACUAZIONE FUMI FORZATO | [[G-00-ESEC-01_ELENCO_ELABORATI]] | inferito |
| Titolo nel cartiglio | PROGETTO SISTEMAZIONE EVACUAZIONE FUMI FORZATO; «SISTEMA EVACUAZIONE FUMI FORZATO» aprile 2026 | cartiglio, pdftotext p. 1 | verificato |
| Codice nel cartiglio | **PI-00-ESEC-01** (refuso: atteso PI-01-ESEC-01) | cartiglio | verificato |
| Scala | 1:100 (dettagli 1:50) | cartiglio | verificato |
| Fogli / formato | 1 / A1 | pdfinfo | verificato |

## Criteri collegati
- [[C3]] — priorita' bassa, arco inferito — sub C3.1 (vincoli sulla cupola).
- [[C2]] — priorita' bassa, arco inferito — sub C2.1 (interferenze FV), C2.3 (controllo remoto).

## Anomalie
- **Codice errato nel cartiglio:** il cartiglio di questa tavola riporta `PI-00-ESEC-01` (codice della tavola FV). Nome file ed elenco concordano su PI-01: il nodo usa PI-01.
- Titolo: «PROGETTO SISTEMAZIONE…» (elenco e cartiglio) vs «SISTEMA…» (nome file).

## Note
- Elaborati correlati probabili (Fase D): [[VVF-PI-07-00_PROSPETTO_E_SEZIONE]], `RS-00-ESEC-01`, `COM-PZ.REGISTRO-UFFICIALE.2026.0007341` (parere VV.F.).

Lettura approfondita disponibile on-demand via `drawing-reader`.
