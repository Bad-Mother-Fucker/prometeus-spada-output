---
type: document
subtype: tavola
gara: "Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)"
date: 2026-10-03
ai-first: true
codice: "PI-00-ESEC-01"
file: "PI_00_ESEC_01_PROGETTO IMPIANTO FOTOVOLTAICO.pdf.p7m"
file_originale: "00_input/p7m/progetto.esecutivo.a.base.di.gara/pdf firmati/PI_00_ESEC_01_PROGETTO IMPIANTO FOTOVOLTAICO.pdf.p7m"
pdf_leggibile: "01_extracted/p7m_extracted/PI-00-ESEC-01_PROGETTO_IMPIANTO_FOTOVOLTAICO.pdf"
section: "PI"
version_group: "PI-00"
is_latest: true
status: non_estratto
extracted_md: "nessuno — tavola grafica, non estratta per regola (lettura on-demand via drawing-reader)"
confidence: inferito
descrizione_ufficiale: "PROGETTO IMPIANTO FOTOVOLTAICO"  # fonte: elenco elaborati G-00-ESEC-01 — confidence: inferito
in_elenco_elaborati: true
firmato: true  # firma CMS Martone Carmen 2026-04-24 (manifest)
pagine: 1
formato: "A1"
supports_criteria:
  - { criterion: "[[C2]]", priority: alta, confidence: inferito, reason: "C2.1 BIPV: progetto FV di base in copertura (layout, configurazione, integrazione) — baseline su cui si misura la miglioria; C2.3 accumulo: verosimile indicazione di inverter/batterie di progetto, necessaria per interpretare la soglia «>20 kWh». Inferito dal titolo, contenuto grafico non letto" }
  - { criterion: "[[C3]]", priority: bassa, confidence: inferito, reason: "C3.1: planimetria coperture con il campo FV — verificare interferenze tra FV e inserimento dell'isolamento sulla copertura piana. Inferito dal titolo" }
related_documents:
  - { doc: "[[G-00-ESEC-01_ELENCO_ELABORATI]]", type: referenced_by, confidence: verificato, reason: "L'elenco elaborati G-00-ESEC-01 lo elenca per codice (p. 2) come «PROGETTO IMPIANTO FOTOVOLTAICO»: fonte della descrizione ufficiale" }
  - { doc: "[[G-08-ESEC-01_RELAZIONE_GENERALE]]", type: referenced_by, confidence: inferito, reason: "La relazione generale G-08 ne riproduce il contenuto nella Figura 12 «Pianta coperture con impianto fotovoltaico» (p. 16); rinvio per figura, non per codice" }
  - { doc: "[[RS-00-ESEC-01_RELAZIONE_TECNICA_IMPIANTI]]", type: tavola_di, confidence: inferito, reason: "Tavola del FV 6 kW su staffe e dell'accumulo descritti nella relazione impianti (p. 11) — abbinamento per disciplina, contenuto grafico non letto" }
  - { doc: "[[RS-01-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_FOTOVOLTAICO]]", type: tavola_di, confidence: inferito, reason: "Tavola del FV di progetto descritto nella relazione (6 kWp, moduli su staffe inclinate 30°, pp. 2-3); il testo grafico della tavola parla di impianto «integrato»: da confrontare — abbinamento per disciplina, contenuto grafico non letto" }
---

# PI-00-ESEC-01 — Progetto impianto fotovoltaico

## Per Claude futuro
Questa e' la tavola PI-00-ESEC-01 della gara Cineteatro «Sala Polifunzionale Periz» — Castello di Bella (PZ), CIG BCF01395AF.
Rappresenta il progetto dell'impianto fotovoltaico di base (planimetria coperture e layout FV, scala 1:100) per la sezione PI (progetto impianti).
Lettura approfondita differita a drawing-reader on-demand. Confidence: inferito (descrizione da elenco elaborati e cartiglio; contenuto grafico non letto).

## Identificazione

| Campo | Valore | Fonte | Confidence |
|---|---|---|---|
| Descrizione ufficiale | PROGETTO IMPIANTO FOTOVOLTAICO | [[G-00-ESEC-01_ELENCO_ELABORATI]] | inferito |
| Titolo nel cartiglio | PROGETTO IMPIANTO FOTOVOLTAICO — PI-00-ESEC-01 aprile 2026 | cartiglio, pdftotext p. 1 | verificato |
| Viste citate nel testo grafico | planimetria coperture +14,57; layout impianto fotovoltaico | testo grafico p. 1 | parziale |
| Titolo grafico dell'impianto | «IMPIANTO FOTOVOLTAICO DA 6 KWp TRIFASE INTEGRATO» | testo grafico p. 1 | parziale |
| Scala | 1:100 | cartiglio | verificato |
| Fogli / formato | 1 / A1 | pdfinfo | verificato |

## Criteri collegati
- [[C2]] — priorita' alta, arco inferito — sub C2.1 (baseline FV), C2.3 (accumulo di progetto).
- [[C3]] — priorita' bassa, arco inferito — sub C3.1 (interferenze in copertura).

## Cosa cercare con drawing-reader
- Potenza, numero/tipo di moduli, superficie e posizione del campo FV; il testo grafico riporta 6 kWp trifase «integrato» (dato non verificato: confrontare con `RS-01-ESEC-01` e computo).
- Presenza e capacita' di accumulo di progetto (interpretazione della soglia «>20 kWh» di C2.3, nota N5).
- Differenze con [[PI-00a-ESEC-01_PLANIMETRIA_DI_INSIEME_CON_FOTOVOLTAICO_INTEGRATO_E_FOTOINSERIMENTI]], l'elaborato a cui il disciplinare rinvia per C2.1.

## Note
- Elaborati correlati probabili (Fase D): `RS-01-ESEC-01` (relazione tecnica FV), `RS-00-ESEC-01` (relazione impianti), [[PI-05-ESEC-01_INTERVENTI_ELETTRICI]].

Lettura approfondita disponibile on-demand via `drawing-reader`.
