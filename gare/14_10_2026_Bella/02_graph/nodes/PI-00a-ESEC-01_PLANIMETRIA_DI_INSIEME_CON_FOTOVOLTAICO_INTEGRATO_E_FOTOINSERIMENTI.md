---
type: document
subtype: tavola
gara: "Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)"
date: 2026-10-03
ai-first: true
codice: "PI-00a-ESEC-01"
file: "PI-00a-ESEC-01_PLANIMETRIA  DI INSIEME CON FOTOVOLTAICO INTEGRATO E FOTOINSERIMENTI -- dettaglio offerta tecnica.pdf"
file_originale: "00_input/p7m/progetto.esecutivo.a.base.di.gara/PI-00a-ESEC-01_PLANIMETRIA  DI INSIEME CON FOTOVOLTAICO INTEGRATO E FOTOINSERIMENTI -- dettaglio offerta tecnica.pdf"
pdf_leggibile: "00_input/p7m/progetto.esecutivo.a.base.di.gara/PI-00a-ESEC-01_PLANIMETRIA  DI INSIEME CON FOTOVOLTAICO INTEGRATO E FOTOINSERIMENTI -- dettaglio offerta tecnica.pdf"
section: "PI"
version_group: "PI-00a"
is_latest: true
status: non_estratto
extracted_md: "nessuno — tavola grafica, non estratta per regola (lettura on-demand via drawing-reader)"
confidence: inferito
descrizione_ufficiale: "TBD — non presente nell'Elenco Elaborati G-00-ESEC-01; titolo dal nome file e dal disciplinare"
in_elenco_elaborati: false
firmato: false  # PDF semplice, non .p7m (manifest)
pagine: 1
formato: "A0"
supports_criteria:
  - { criterion: "[[C2]]", priority: alta, confidence: verificato, reason: "C2.1 BIPV (15 pt, sub-criterio piu' pesante della gara): il disciplinare rinvia espressamente a questo elaborato «ai fini della formulazione della miglioria» (art. 18.1 sub 2.1, p. 28; testo in 01_extracted/text/disciplinare.di.gara.md). Arco verificato sul testo del disciplinare; il contenuto della tavola non e' stato letto" }
related_documents:
  - { doc: "[[RS-01-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_FOTOVOLTAICO]]", type: tavola_di, confidence: inferito, reason: "FV integrato con fotoinserimenti (agosto 2026, non firmata, fuori elenco): stesso impianto della relazione in configurazione integrata, riferimento della miglioria C2.1 — la relazione prevede moduli su staffe a 30° — abbinamento per disciplina, contenuto grafico non letto" }
---

# PI-00a-ESEC-01 — Planimetria di insieme con fotovoltaico integrato e fotoinserimenti

## Per Claude futuro
Questa e' la tavola PI-00a-ESEC-01 della gara Cineteatro «Sala Polifunzionale Periz» — Castello di Bella (PZ), CIG BCF01395AF.
Rappresenta la planimetria di insieme con fotovoltaico integrato e i fotoinserimenti del FV (scala 1:100, formato A0) per la sezione PI (progetto impianti); il nome file la qualifica «dettaglio offerta tecnica».
E' l'elaborato a cui il disciplinare rinvia per il sub-criterio C2.1 (BIPV, 15 punti): leggerlo per primo quando si analizza [[C2]]. Lettura approfondita differita a drawing-reader on-demand. Confidence della pagina: inferito (contenuto grafico non letto); l'arco verso C2 e' verificato sul disciplinare.

## Identificazione

| Campo | Valore | Fonte | Confidence |
|---|---|---|---|
| Descrizione ufficiale | — non in Elenco Elaborati | [[G-00-ESEC-01_ELENCO_ELABORATI]] | verificato (assenza riscontrata in census) |
| Titolo nel cartiglio | PLANIMETRIA DI INSIEME CON FOTOVOLTAICO INTEGRATO E FOTOINSERIMENTI — PI-00a-ESEC-01 | cartiglio, pdftotext p. 1 | verificato |
| Data nel cartiglio | Agosto 2026 | cartiglio | verificato |
| Viste citate nel testo grafico | fotovoltaico integrato (scala 1:100); fotoinserimenti del fotovoltaico integrato | testo grafico p. 1 | parziale |
| Fogli / formato | 1 / A0 (3370 x 2384 pt) | pdfinfo | verificato |
| Firma digitale | assente (PDF semplice in `00_input/p7m/…/`, non `.p7m`) | manifest | verificato |
| Richiamo nel disciplinare | art. 18.1, sub 2.1, p. 28 | disciplinare | verificato |

## Criteri collegati
- [[C2]] — priorita' alta, arco **verificato** sul disciplinare — sub C2.1.

## Anomalie e cautele
- **Non firmato:** a differenza delle tavole del progetto esecutivo (firma CMS Martone Carmen 24/04/2026), questo PDF non ha firma digitale.
- **Non in Elenco Elaborati:** assente da `G-00-ESEC-01` (40 elaborati); presente in `00_input` e richiamato dal disciplinare per il sub-criterio 2.1. Nel census e' registrato come `orphan_input` rispetto all'elenco.
- **Data successiva al progetto:** cartiglio «Agosto 2026», posteriore alle revisioni firmate di aprile/maggio 2026; preparato verosimilmente per la gara («dettaglio offerta tecnica»).
- **Rischio:** se il suo contenuto differisce da [[PI-00-ESEC-01_PROGETTO_IMPIANTO_FOTOVOLTAICO]] (elaborato firmato), non e' chiaro quale faccia da baseline per C2.1. Confrontare le due tavole con drawing-reader; se divergono, valutare un chiarimento alla stazione appaltante entro il 06/10/2026 ore 12:00.

## Cosa cercare con drawing-reader
- Soluzione FV integrata proposta come riferimento (posizione, tipologia, superficie) e fotoinserimenti: punto di partenza per impatto visivo, riflettanza e tutela (parametri di giudizio del sub 2.1).
- Differenze rispetto al FV di PI-00 (6 kWp trifase secondo il testo grafico di PI-00, dato non verificato).

Lettura approfondita disponibile on-demand via `drawing-reader`.
