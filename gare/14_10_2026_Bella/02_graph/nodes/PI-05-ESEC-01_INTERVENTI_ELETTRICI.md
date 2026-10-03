---
type: document
subtype: tavola
gara: "Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)"
date: 2026-10-03
ai-first: true
codice: "PI-05-ESEC-01"
file: "PI_05_ESEC_01_INTERVENTI ELETTRICI.pdf.p7m"
file_originale: "00_input/p7m/progetto.esecutivo.a.base.di.gara/pdf firmati/PI_05_ESEC_01_INTERVENTI ELETTRICI.pdf.p7m"
pdf_leggibile: "01_extracted/p7m_extracted/PI-05-ESEC-01_INTERVENTI_ELETTRICI.pdf"
section: "PI"
version_group: "PI-05"
is_latest: true
status: non_estratto
extracted_md: "nessuno — tavola grafica, non estratta per regola (lettura on-demand via drawing-reader)"
confidence: inferito
descrizione_ufficiale: "INTERVENTI ELETTRICI"  # fonte: elenco elaborati G-00-ESEC-01 — confidence: inferito
in_elenco_elaborati: true
firmato: true  # firma CMS Martone Carmen 2026-04-24 (manifest)
pagine: 1
formato: "A1"
supports_criteria:
  - { criterion: "[[C2]]", priority: media, confidence: inferito, reason: "C2.2 antintrusione/TVCC: alimentazioni e predisposizioni elettriche di progetto (checklist C2 «verificare se il progetto prevede gia' impianti antintrusione/TVCC o predisposizioni»); C2.3 accumulo e Building Automation: quadri e distribuzione su cui integrare batterie e supervisione. Inferito dal titolo" }
related_documents:
  - { doc: "[[G-00-ESEC-01_ELENCO_ELABORATI]]", type: referenced_by, confidence: verificato, reason: "L'elenco elaborati G-00-ESEC-01 lo elenca per codice (p. 2) come «INTERVENTI ELETTRICI»: fonte della descrizione ufficiale" }
  - { doc: "[[RS-00-ESEC-01_RELAZIONE_TECNICA_IMPIANTI]]", type: tavola_di, confidence: inferito, reason: "Tavola degli interventi elettrici descritti nella relazione: controsoffitto per cavidotti, LED, sostituzione cavi, revisione quadro (pp. 9, 12-13) — abbinamento per disciplina, contenuto grafico non letto" }
---

# PI-05-ESEC-01 — Interventi elettrici

> **# ATTENZIONE (Fase E, 2026-10-03):** il livello di testo della tavola (pdftotext, confidence parziale) riporta «54 posti a sedere» + «49 posti a sedere» in platea e «27 posti a sedere» in galleria (= 130), contro 134 poltrone del computo [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] voce 102 (platea 53 + 54 in [[G-08-ESEC-01_RELAZIONE_GENERALE]] p. 20) e 128 della pratica VV.F. [[VVF-PI-03-00_PIANTA_PIANO_PRIMO]] (D18, quesito SA Q4). Vedi [[economic_framework]] §10.

## Per Claude futuro
Questa e' la tavola PI-05-ESEC-01 della gara Cineteatro «Sala Polifunzionale Periz» — Castello di Bella (PZ), CIG BCF01395AF.
Rappresenta gli interventi sull'impianto elettrico (planimetrie piano terra +0,15, primo +3,05, secondo +7,19; scala 1:100) per la sezione PI (progetto impianti).
Lettura approfondita differita a drawing-reader on-demand. Confidence: inferito (descrizione da elenco elaborati e cartiglio; contenuto grafico non letto).

## Identificazione

| Campo | Valore | Fonte | Confidence |
|---|---|---|---|
| Descrizione ufficiale | INTERVENTI ELETTRICI | [[G-00-ESEC-01_ELENCO_ELABORATI]] | inferito |
| Titolo nel cartiglio | INTERVENTI ELETTRICI — PI-05-ESEC-01 aprile 2026 | cartiglio, pdftotext p. 1 | verificato |
| Scala | 1:100 | cartiglio | verificato |
| Fogli / formato | 1 / A1 | pdfinfo | verificato |

## Criteri collegati
- [[C2]] — priorita' media, arco inferito — sub C2.2, C2.3.

## Cosa cercare con drawing-reader
- Presenza o assenza di impianti/predisposizioni antintrusione e TVCC (baseline C2.2).
- Quadri, linee dedicate a FV/accumulo e sistemi di supervisione (baseline C2.3).
- Il testo grafico cita «n. 14 plafoniere da sostituire» (dato non verificato).

## Note
- Elaborati correlati probabili (Fase D): `RS-00-ESEC-01`, `RS-01-ESEC-01`, [[PI-00-ESEC-01_PROGETTO_IMPIANTO_FOTOVOLTAICO]].

Lettura approfondita disponibile on-demand via `drawing-reader`.
