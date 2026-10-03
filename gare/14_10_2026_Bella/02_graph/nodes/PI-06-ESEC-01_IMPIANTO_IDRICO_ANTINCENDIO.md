---
type: document
subtype: tavola
gara: "Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)"
date: 2026-10-03
ai-first: true
codice: "PI-06-ESEC-01"
file: "PI_06_ESEC_01_IMPIANTO IDRICO ANTINCENDIO.pdf.p7m"
file_originale: "00_input/p7m/progetto.esecutivo.a.base.di.gara/pdf firmati/PI_06_ESEC_01_IMPIANTO IDRICO ANTINCENDIO.pdf.p7m"
pdf_leggibile: "01_extracted/p7m_extracted/PI-06-ESEC-01_IMPIANTO_IDRICO_ANTINCENDIO.pdf"
section: "PI"
version_group: "PI-06"
is_latest: true
status: non_estratto
extracted_md: "nessuno — tavola grafica, non estratta per regola (lettura on-demand via drawing-reader)"
confidence: inferito
descrizione_ufficiale: "IM PIANTO IDRICO ANTINCENDIO"  # fonte: elenco elaborati G-00-ESEC-01 (refuso «IM PIANTO») — confidence: inferito
in_elenco_elaborati: true
firmato: true  # firma CMS Martone Carmen 2026-04-24 (manifest)
pagine: 3
formato: "A1"
# ORFANO POTENZIALE: l'adeguamento antincendio e' nell'oggetto dell'appalto ma nessun sottocriterio C1-C7 lo premia. Decidere con /resolve_orphan.
supports_criteria: []
related_documents:
  - { doc: "[[G-00-ESEC-01_ELENCO_ELABORATI]]", type: referenced_by, confidence: verificato, reason: "L'elenco elaborati G-00-ESEC-01 lo elenca per codice (p. 2) come «IM PIANTO IDRICO ANTINCENDIO»: fonte della descrizione ufficiale" }
  - { doc: "[[RS-02-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_IDRICO_ANTINCENDIO]]", type: referenced_by, confidence: inferito, reason: "La relazione RS-02 rinvia agli «elaborati grafici allegati» della rete naspi (p. 6): rinvio implicito senza codice" }
  - { doc: "[[RS-02-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_IDRICO_ANTINCENDIO]]", type: tavola_di, confidence: inferito, reason: "Tavola della rete idrica antincendio (4 naspi DN25, UNI 10779) descritta e calcolata nella relazione (pp. 6-22) — abbinamento per disciplina, contenuto grafico non letto" }
---

# PI-06-ESEC-01 — Impianto idrico antincendio

## Per Claude futuro
Questa e' la tavola PI-06-ESEC-01 della gara Cineteatro «Sala Polifunzionale Periz» — Castello di Bella (PZ), CIG BCF01395AF.
Rappresenta l'impianto idrico antincendio (3 fogli, scala 1:100) per la sezione PI (progetto impianti) — componente dell'adeguamento antincendio.
Lettura approfondita differita a drawing-reader on-demand. Confidence: inferito (descrizione da elenco elaborati e cartiglio; contenuto grafico non letto).

## Identificazione

| Campo | Valore | Fonte | Confidence |
|---|---|---|---|
| Descrizione ufficiale | IM PIANTO IDRICO ANTINCENDIO (refuso dell'elenco) | [[G-00-ESEC-01_ELENCO_ELABORATI]] | inferito |
| Titolo nel cartiglio | IMPIANTO IDRICO ANTINCENDIO — PI-06-ESEC-01 aprile 2026 | cartiglio, pdftotext p. 1 | verificato |
| Scala | 1:100 | cartiglio | verificato |
| Fogli / formato | 3 / A1 | pdfinfo | verificato |

## Criteri collegati
Nessuno — **orfano potenziale**. La rete idrica antincendio fa parte dell'oggetto dell'appalto (adeguamento antincendio, Premesse p. 3) ma nessun sottocriterio della tabella art. 18.1 la premia. Ha valore di **vincolo** per le migliorie: per esempio rivestimenti acustici C1.3 su pareti con idranti/naspi, o supervisione degli impianti in C2.3. Collegamenti deboli, non sufficienti per un arco: da confermare o collegare con `/resolve_orphan`.

## Note
- Elaborati correlati probabili (Fase D): `RS-02-ESEC-01` (relazione tecnica impianto idrico antincendio), serie VVF-PI.

Lettura approfondita disponibile on-demand via `drawing-reader`.
