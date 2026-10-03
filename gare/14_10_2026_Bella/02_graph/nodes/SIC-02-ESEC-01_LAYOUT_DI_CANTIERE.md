---
type: document
subtype: tavola
gara: "Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)"
date: 2026-10-03
ai-first: true
codice: "SIC-02-ESEC-01"
file: "SIC-02-ESEC-01_LAYOUT DI CANTIERE.pdf.p7m"
file_originale: "00_input/p7m/progetto.esecutivo.a.base.di.gara/pdf firmati/SIC-02-ESEC-01_LAYOUT DI CANTIERE.pdf.p7m"
pdf_leggibile: "01_extracted/p7m_extracted/SIC-02-ESEC-01_LAYOUT_DI_CANTIERE.pdf"
section: "SIC"
version_group: "SIC-02"
is_latest: true
status: non_estratto
extracted_md: "nessuno — tavola grafica, non estratta per regola (lettura on-demand via drawing-reader)"
confidence: inferito
descrizione_ufficiale: "LAYOUT DI CANTIERE"  # fonte: elenco elaborati G-00-ESEC-01 — confidence: inferito
in_elenco_elaborati: true
firmato: true  # firma CMS Martone Carmen 2026-04-24 (manifest)
pagine: 2
formato: "A1"
supports_criteria:
  - { criterion: "[[C3]]", priority: alta, confidence: inferito, reason: "C3.3 logistica e protezione delle attrezzature esistenti: il layout di cantiere e' la base per accessi, aree di deposito/stoccaggio e movimentazione, condizioni che il disciplinare indica come peculiari (art. 11, pp. 16-17) e che la checklist C3 chiede di ricavare. Inferito dal titolo, contenuto grafico non letto" }
  - { criterion: "[[C4]]", priority: bassa, confidence: inferito, reason: "C4.2 piano di economia circolare dei detriti con monitoraggio polveri/vibrazioni: le aree di cantiere per deposito e selezione dei rifiuti sono verosimilmente indicate nel layout. Inferito dal titolo, da verificare" }
related_documents:
  - { doc: "[[G-00-ESEC-01_ELENCO_ELABORATI]]", type: referenced_by, confidence: verificato, reason: "L'elenco elaborati G-00-ESEC-01 lo elenca per codice (p. 2) come «LAYOUT DI CANTIERE»: fonte della descrizione ufficiale" }
  - { doc: "[[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]]", type: referenced_by, confidence: verificato, reason: "Il PSC SIC-00 lo elenca tra gli allegati (p. 83) e ne contiene una copia alle pp. 259-260 (cartiglio SIC-02-ESEC-01)" }
  - { doc: "[[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]]", type: tavola_di, confidence: verificato, reason: "Layout di cantiere allegato al PSC (p. 83) e riprodotto alle pp. 259-260: aree esterne, ponteggio Nord-Est, stoccaggi interni per piano" }
  - { doc: "[[SIC-01-ESEC-01_CRONOPROGRAMMA]]", type: stesso_lotto, confidence: verificato, reason: "Sezione SIC, layout / cronoprogramma: le aree del layout servono le fasi di allestimento (12 g) e smobilizzo (8 g); entrambi copiati nel PSC" }
  - { doc: "[[SIC-03-ESEC-01_COSTI_PER_LA_SICUREZZA]]", type: stesso_lotto, confidence: verificato, reason: "Sezione SIC, layout / costi sicurezza: ponteggio 195 mq (15 × 13 m) e recinzione dei costi da riscontrare sul layout (ponteggio fisso sul prospetto Nord-Est nella copia del PSC)" }
---

# SIC-02-ESEC-01 — Layout di cantiere

## Per Claude futuro
Questa e' la tavola SIC-02-ESEC-01 della gara Cineteatro «Sala Polifunzionale Periz» — Castello di Bella (PZ), CIG BCF01395AF.
Rappresenta il layout di cantiere (organizzazione delle aree, accessi, ingombri) per la sezione SIC (progetto sicurezza).
Lettura approfondita differita a drawing-reader on-demand. Confidence: inferito (descrizione da elenco elaborati e cartiglio; contenuto grafico non letto).

## Identificazione

| Campo | Valore | Fonte | Confidence |
|---|---|---|---|
| Descrizione ufficiale | LAYOUT DI CANTIERE | [[G-00-ESEC-01_ELENCO_ELABORATI]] | inferito |
| Titolo nel cartiglio | LAYOUT DI CANTIERE — SIC-02-ESEC-01 | cartiglio, pdftotext p. 1 | verificato |
| Revisioni nel cartiglio | ESEC-00 febbraio 2025; ESEC-01 aprile 2026 | cartiglio | verificato |
| Scala | 1:100 | cartiglio | verificato |
| Fogli / formato | 2 / A1 | pdfinfo | verificato |

## Criteri collegati
- [[C3]] — priorita' alta, arco inferito — sub C3.3 (logistica, stoccaggio, protezione attrezzature esistenti).
- [[C4]] — priorita' bassa, arco inferito — sub C4.2 (gestione detriti, monitoraggio polveri/vibrazioni).

## Cosa cercare con drawing-reader
- Aree di stoccaggio protetto disponibili per impianto audio, proiettori e schermo smontati (C3.3).
- Accessi, percorsi mezzi e pedonali, aree di carico/scarico nel contesto del Castello (C3.3).
- Aree per deposito e selezione rifiuti/detriti (C4.2).
- Ponteggi: il testo grafico cita «INGOMBRO PONTEGGIO PROSPETTO NORD_EST» (segnale non verificato) — interferenze con lavorazioni in copertura (C2.1, C3.1).

## Note
- Verosimile copia interna nel PSC `SIC-00-ESEC-01` pp. 259-260 (testo grafico «AREA MOVIMENTAZIONE MEZZI», «percorso pedonale», da `02_graph/_census.md`): da confrontare.
- Elaborati correlati probabili (archi da creare in Fase D): `SIC-00-ESEC-01` (PSC), `SIC-01-ESEC-01` (cronoprogramma), `SIC-03-ESEC-01` (costi sicurezza).

Lettura approfondita disponibile on-demand via `drawing-reader`.
