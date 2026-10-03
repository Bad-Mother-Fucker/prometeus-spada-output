---
type: document
subtype: tavola
gara: "Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)"
date: 2026-10-03
ai-first: true
codice: "PI-03-ESEC-01"
file: "PI_03_ESEC_01_PROGETTO IMPIANTO IRAI.pdf.p7m"
file_originale: "00_input/p7m/progetto.esecutivo.a.base.di.gara/pdf firmati/PI_03_ESEC_01_PROGETTO IMPIANTO IRAI.pdf.p7m"
pdf_leggibile: "01_extracted/p7m_extracted/PI-03-ESEC-01_PROGETTO_IMPIANTO_IRAI.pdf"
section: "PI"
version_group: "PI-03"
is_latest: true
status: non_estratto
extracted_md: "nessuno — tavola grafica, non estratta per regola (lettura on-demand via drawing-reader)"
confidence: inferito
descrizione_ufficiale: "PROGETTO IMPIANTO IRAI"  # fonte: elenco elaborati G-00-ESEC-01 — confidence: inferito
in_elenco_elaborati: true
firmato: true  # firma CMS Martone Carmen 2026-04-24 (manifest)
pagine: 4
formato: "A1"
supports_criteria:
  - { criterion: "[[C2]]", priority: bassa, confidence: inferito, reason: "C2.2/C2.3: impianto IRAI (rivelazione e allarme incendio) e centrale antincendio di progetto — riferimento per integrare antintrusione/TVCC e supervisione remota senza interferire con il sistema di sicurezza approvato. Inferito dal titolo" }
related_documents:
  - { doc: "[[G-00-ESEC-01_ELENCO_ELABORATI]]", type: referenced_by, confidence: verificato, reason: "L'elenco elaborati G-00-ESEC-01 lo elenca per codice (p. 2) come «PROGETTO IMPIANTO IRAI»: fonte della descrizione ufficiale" }
  - { doc: "[[RS-00-ESEC-01_RELAZIONE_TECNICA_IMPIANTI]]", type: tavola_di, confidence: inferito, reason: "Tavola impiantistica abbinata alla relazione tecnica impianti; RS-00 NON descrive l'IRAI (nessuna relazione testuale dedicata) — abbinamento per disciplina, contenuto grafico non letto" }
---

# PI-03-ESEC-01 — Progetto impianto IRAI

> **# ATTENZIONE (Fase E, 2026-10-03):** il livello di testo della tavola (pdftotext, confidence parziale) riporta «PLANIMETRIA PIANO PRIMO +3.05 — TOTALE POSTI A SEDERE PLATEA: 102, DI CUI 2 PER DISABILI» (+ 27 in galleria = 129), contro platea 53 + 54 = 107 di [[G-08-ESEC-01_RELAZIONE_GENERALE]] p. 20, 134 poltrone del computo [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] voce 102 e 53 + 48 della pratica VV.F. [[VVF-PI-03-00_PIANTA_PIANO_PRIMO]] (D18, quesito SA Q4). Vedi [[economic_framework]] §10.

## Per Claude futuro
Questa e' la tavola PI-03-ESEC-01 della gara Cineteatro «Sala Polifunzionale Periz» — Castello di Bella (PZ), CIG BCF01395AF.
Rappresenta il progetto dell'impianto IRAI (rivelazione automatica e allarme incendio, con centrale antincendio; 4 fogli, scala 1:50) per la sezione PI (progetto impianti).
Lettura approfondita differita a drawing-reader on-demand. Confidence: inferito (descrizione da elenco elaborati e cartiglio; contenuto grafico non letto).

## Identificazione

| Campo | Valore | Fonte | Confidence |
|---|---|---|---|
| Descrizione ufficiale | PROGETTO IMPIANTO IRAI | [[G-00-ESEC-01_ELENCO_ELABORATI]] | inferito |
| Titolo nel cartiglio | PROGETTO IMPIANTO IRAI — aprile 2026 | cartiglio, pdftotext p. 1 | verificato |
| Codice nel cartiglio | **PI-02-ESEC-01** (refuso: atteso PI-03-ESEC-01) | cartiglio | verificato |
| Scala | 1:50 | cartiglio | verificato |
| Fogli / formato | 4 / A1 | pdfinfo | verificato |

## Criteri collegati
- [[C2]] — priorita' bassa, arco inferito — sub C2.2, C2.3.

## Anomalie
- **Codice errato nel cartiglio:** il cartiglio riporta `PI-02-ESEC-01`. Nome file ed elenco concordano su PI-03: il nodo usa PI-03.

## Note
- Il testo grafico di [[VVF-PI-03-00_PIANTA_PIANO_PRIMO]] cita un'azione «in automatico comandata dal sistema IRAI» (oggetto non letto): l'IRAI e' verosimilmente interfacciato con altri impianti, elemento da considerare per la Building Automation di C2.3.
- Elaborati correlati probabili (Fase D): `RS-00-ESEC-01`, [[PI-01-ESEC-01_SISTEMA_EVACUAZIONE_FUMI_FORZATO]].

Lettura approfondita disponibile on-demand via `drawing-reader`.
