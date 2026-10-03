---
type: document
subtype: quadro_economico
gara: "Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)"
date: 2026-10-03
ai-first: true
codice: "G-01-ESEC-02"
file: "G-01-ESEC-02_QUADRO_ECONOMICO.pdf"
file_originale: "00_input/p7m/progetto.esecutivo.a.base.di.gara/Progetto esecutivo_Integrazione 2026/G_01_ESEC_02-_QUADRO ECONOMICO.pdf.p7m"
section: "G"
version_group: "G-01"
is_latest: true
status: estratto
extracted_md: "01_extracted/text/G-01-ESEC-02_QUADRO_ECONOMICO.md"
pagine: 2
data_elaborato: "maggio 2026 (cartiglio)"
copertura_lettura: "integrale (testo estratto) + verifica visiva della tabella sul PDF p. 2"
confidence: verificato
cost_summary:
  totale_eur: 520000.00                 # confidence: verificato, «COSTO COMPLESSIVO PROGETTO (A + B + C)» p. 2
  lavori_a_misura_eur: 381364.99        # confidence: verificato, A1 = importo a base di gara
  oneri_sicurezza_eur: 13005.47         # confidence: verificato, A4
  totale_lavori_eur: 394370.46          # confidence: verificato, «TOTALE LAVORI (1+2+3+4)»
  somme_a_disposizione_eur: 125629.54   # confidence: verificato, «TOTALE SOMME A DISPOSIZIONI (somma da 1 a 12)»
  iva_lavori_eur: 59428.23              # confidence: verificato (valore letto); aliquota dichiarata 22% NON coerente, vedi corpo
  forniture_C_eur: 0.00                 # confidence: verificato, sezione C) — le forniture di arredo (55.296,43 €) sono dentro A1
  voci_count: TBD                       # confidence: TBD — non pertinente al quadro economico
supports_criteria:
  - { criterion: "[[C1]]", priority: bassa, reason: "Cornice economica (base di gara 381.364,99 € + sicurezza 13.005,47 €) rispetto alla quale la commissione valuta la sostenibilità economica delle migliorie in sede di anomalia (art. 23 disciplinare, richiamato nei modification_limits di C1)" }
  - { criterion: "[[C2]]", priority: bassa, reason: "Cornice economica per la verifica di anomalia delle migliorie C2 (art. 23); nessuna voce di forniture separate in C) per FV o accumulo" }
  - { criterion: "[[C3]]", priority: bassa, reason: "Cornice economica per la verifica di anomalia delle migliorie C3 (art. 23); B3 imprevisti 7.386,68 € è anche il tetto del premio di accelerazione (disciplinare p. 8), rilevante per il cronoprogramma integrato" }
  - { criterion: "[[C4]]", priority: bassa, reason: "Cornice economica per la verifica di anomalia delle migliorie C4 (art. 23)" }
related_documents:
  - { doc: "[[G-01-ESEC-01_QUADRO_ECONOMICO]]", type: versione_precedente, confidence: verificato, reason: "Revisione aprile 2026 superata (is_latest: false): stessa parte A, costo complessivo 513.811,73 €" }
  - { doc: "[[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]]", type: referenced_by, confidence: verificato, reason: "Il capitolato G-06-ESEC-02 rinvia alle somme per imprevisti del quadro economico per il premio di accelerazione (Art. 2.14, p. 25)" }
  - { doc: "[[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]]", type: stesso_lotto, confidence: verificato, reason: "Sezione G, quadro economico / computo: la riga A1 (381.364,99 €) e' il totale del computo; B6 5.000 € legato all'Allegato I revisione prezzi del computo" }
---

# G-01-ESEC-02 — Quadro economico (revisione maggio 2026)

## Per Claude futuro

Questo è il quadro economico G-01-ESEC-02 della gara «Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)» (CIG BCF01395AF). Descrizione ufficiale: «QUADRO ECONOMICO» (voce G-01-ESEC-01 di [[G-00-ESEC-01_ELENCO_ELABORATI]]; la revisione ESEC-02 è successiva all'elenco, cartella «Integrazione 2026»). **Aggiorna [[G-01-ESEC-01_QUADRO_ECONOMICO]] (is_latest: false).** Modifiche rispetto alla versione precedente: la parte A (lavori) è invariata; nelle somme a disposizione aumentano gli imprevisti (5.982,30 → 7.386,68 €, ora «comprensivi di IVA 22%»), compare l'accantonamento per adeguamento prezzi (0 → 5.000,00 €) e cambia l'IVA sulle altre somme (1.839,34 → 1.623,23 €); il costo complessivo sale da 513.811,73 a **520.000,00 €**. Contiene: importo lavori, oneri sicurezza, somme a disposizione della SA. È la **fonte QE di [[economic_framework]]**. Confidence: verificato (tabella controllata anche sul PDF).

## Contenuto chiave

### A) Lavori

| Riga | Voce | Importo € | Confidence |
|---|---|---|---|
| A1 | lavori a misura | 381.364,99 | verificato |
| A2 | lavori a corpo | 0,00 | verificato |
| A3 | lavori in economia | 0,00 | verificato |
| — | Importo dei lavori a base di gara («(2+2+3)», refuso per 1+2+3) | 381.364,99 | verificato |
| A4 | oneri della sicurezza, non soggetti a ribasso | 13.005,47 | verificato |
| — | adeguamento prezzi (riga senza importo) | — | verificato |
| — | **TOTALE LAVORI (1+2+3+4)** | **394.370,46** | verificato |

### B) Somme a disposizione della stazione appaltante

| Riga | Voce | Importo € | Confidence |
|---|---|---|---|
| B1 | Lavori in economia esclusi dall'appalto, rimborsi previa fattura | 2.000,00 | verificato |
| B2 | Allacciamenti ai pubblici servizi | 0,00 | verificato |
| B3 | Imprevisti comprensivi di IVA 22% | 7.386,68 | verificato |
| B4 | Acquisizione aree o immobili | 0,00 | verificato |
| B5 | Espropriazioni | 0,00 | verificato |
| B6 | Accantonamento art. 133 cc. 3-4 del codice (adeguamento prezzi) | 5.000,00 | verificato |
| B7 | Pubblicità e opere artistiche | 378,32 | verificato |
| B8 | Spese artt. 90 c. 5 e 92 c. 7-bis del codice | 0,00 | verificato |
| B9 a) | Rilievi, accertamenti, indagini, prove di laboratorio (IVA compresa) | 1.000,00 | verificato |
| B9 b) | Spese tecniche (progettazione, CSP, DL, CSE, contabilità, collaudi; cassa 4% e IVA 22% incluse) | 40.373,79 | verificato |
| B9 c) | Incentivo art. 113 del codice | 4.322,05 | verificato |
| B9 d) | Attività tecnico-amministrative, supporto RUP, verifica e validazione | 2.000,00 | verificato |
| B9 e) | Commissioni giudicatrici | 500,00 | verificato |
| B9 f) | Verifiche tecniche da capitolato | 0,00 | verificato |
| B9 g) | Collaudi | 0,00 | verificato |
| B9 h) | IVA sulle spese B9 («22% delle voci a, c, e, f, g») | 1.492,00 | verificato (valore) |
| B9 | Totale spese connesse (a+…+h) | 49.687,84 | verificato |
| B10 | IVA sui lavori «al 22%» | 59.428,23 | verificato (valore) |
| B11 | IVA su B1, B6 | 1.623,23 | verificato (valore) |
| B12 | Altre imposte e contributi | 125,24 | verificato |
| — | **TOTALE SOMME A DISPOSIZIONE (1-12)** | **125.629,54** | verificato (ricalcolato: somma esatta) |

### C) Forniture e D) Ribasso

- C1 Forniture 0,00 €; C2 IVA forniture 0,00 €; totale C 0,00 € (verificato). Le forniture di poltrone, palco e allestimento (55.296,43 €, super-categoria ARREDO del computo) sono **comprese in A1**, coerentemente con la Tabella 1 del disciplinare che le tratta come prestazione secondaria dell'appalto.
- **COSTO COMPLESSIVO PROGETTO (A+B+C) = 520.000,00 €** (verificato; 394.370,46 + 125.629,54).
- D) Ribasso d'asta: riga vuota.

### Incoerenze interne rilevate

| # | Incoerenza | Dettaglio | Confidence |
|---|---|---|---|
| 1 | IVA sui lavori «al 22%» | 59.428,23 € ≠ 22% × 394.370,46 € = 86.761,50 €; il valore riportato è il 15,07% di A (base implicita al 22% = 270.128,32 €, non riconducibile a nessun importo del progetto). Riga identica in ESEC-01. Verificato sul PDF p. 2 | verificato (valore), causa TBD |
| 2 | B9 h) IVA sulle spese | 1.492,00 € ≠ 22% × (a+c+e+f+g = 5.822,05 €) = 1.280,85 € | verificato (valore), causa TBD |
| 3 | B11 «IVA su B1, B6» | 1.623,23 € = 22% × 7.378,32 € = 22% × (B1 + B6 + B7): l'etichetta omette B7 | inferito (ricostruzione aritmetica esatta) |
| 4 | Riferimenti normativi | B6 «art. 133 del codice», B8 «artt. 90 e 92», B9 c) «art. 113», B9 a)/f) «DPR 207/2010»: rinvii al vecchio codice, mentre la relazione di revisione prezzi in [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] cita art. 60 D.Lgs. 36/2023 | verificato |

Le incoerenze riguardano solo le somme a disposizione della SA: non modificano la base di gara né gli oneri della sicurezza (approfondite in Fase E, sotto).

## Contraddizioni rilevate (Fase E, 2026-10-03)

Questo QE (`is_latest: true`) è la fonte prevalente per gli importi tra le pagine coinvolte (sopra di esso solo il disciplinare, che non ha pagina nodo). Registro completo in [[economic_framework]] §10.

| # | Tema | Valore in questo QE | Valore in conflitto (fonte, pag.) | Prevale | Stato |
|---|---|---|---|---|---|
| D16 | Importo dei lavori | A1 381.364,99 €; totale A 394.370,46 € (p. 2) | «Importo presunto dei Lavori: 391´795,41 euro»: [[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]] p. 2 (+10.430,42 € su A1, −2.575,05 € su A; nessuna relazione aritmetica con gli importi di progetto) | questo QE + disciplinare art. 3 p. 7 | origine TBD; nessun impatto sull'offerta, nessun quesito |
| D1 | Tabella 1 del disciplinare | A1 381.364,99 = lavori 326.068,56 + forniture di arredo 55.296,43 (computo p. 24) | disciplinare Tab. 1 p. 7: righe 339.074,03 + 55.296,43 = 394.370,46 totalizzate «A) Importo a base di gara 381.364,99» | disciplinare (testo art. 3: ribasso su 381.364,99) + questo QE | risolta: la riga 1 della Tabella include la sicurezza |
| D2 | IVA sui lavori | B10 59.428,23 € «al 22%» (= 15,07% di A) | aliquota dichiarata: 22% × 394.370,46 = 86.761,50 €; riga identica in [[G-01-ESEC-01_QUADRO_ECONOMICO]] | — (somme della SA) | causa TBD: nessuna combinazione di aliquote 4/10/22% per super-categoria ricostruisce il valore; nessun impatto sull'offerta |
| D3 | IVA B9 h) | 1.492,00 € | 22% di (a+c+e+f+g) = 1.280,85 € | — | causa TBD; nessun impatto |

Nessuna contraddizione sugli oneri della sicurezza: A4 = [[SIC-03-ESEC-01_COSTI_PER_LA_SICUREZZA]] = copia nel PSC (12/12 voci identiche) = disciplinare = capitolato.

## Riferimenti a altri elaborati

- Nessun codice di altro elaborato citato nel testo. Cartiglio: G-01-ESEC-00 febbraio 2025 (non presente in `00_input`), G-01-ESEC-01 aprile 2026, G-01-ESEC-02 maggio 2026.
- Per Fase D: stesso `version_group` «G-01» di [[G-01-ESEC-01_QUADRO_ECONOMICO]]; A1 = totale di [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]]; A4 = totale di [[SIC-03-ESEC-01_COSTI_PER_LA_SICUREZZA]]; B6 giustificato dall'Allegato I del computo ESEC-02.
