---
type: document
subtype: relazione_tecnica
gara: "Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)"
date: 2026-10-03
ai-first: true
codice: "RS-01-ESEC-01"
file: "RS-01-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_FOTOVOLTAICO.pdf"
section: "RS"
version_group: "RS-01"
is_latest: true
status: estratto
extracted_md: "01_extracted/text/RS-01-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_FOTOVOLTAICO.md"
confidence: parziale
nota_confidence: "Testo delle pp. 2, 6, 7 letto integralmente (dati verificati: 6 kW, 7.964,4 kWh/anno, 3 batterie 15 kWh). Pp. 3-5 senza testo estraibile (immagini PVGIS): lette visivamente dal PDF, dati marcati 'parziale' (inclinazione 30°, perdite, mensili)."
descrizione_ufficiale: "RELAZIONE TECNICA IMPIANTO FOTOVOLTAICO (elenco elaborati G-00-ESEC-01)"
pagine: 7
data_documento: "24/04/2026 (intestazione pp. 3-5)"
supports_criteria:
  - { criterion: "[[C2]]", priority: alta, reason: "Unica relazione dimensionale del FV di progetto: 6 kWp silicio cristallino, inclinazione 30°, azimut 0°, 7.964,4 kWh/anno (PVGIS), potenza limitata dallo spazio sul tetto terrazzato (pp. 2-3) — baseline e vincolo di superficie per C2.1 BIPV; accumulo '3 batterie per 15 kwh' (p. 7) — baseline per C2.3 '>20 kWh'" }
related_documents:
  - { doc: "[[G-00-ESEC-01_ELENCO_ELABORATI]]", type: referenced_by, confidence: verificato, reason: "L'elenco elaborati G-00-ESEC-01 lo elenca per codice (p. 2) come «RELAZIONE TECNICA IMPIANTO FOTOVOLTAICO»: fonte della descrizione ufficiale" }
  - { doc: "[[G-06-ESEC-01_CAPITOLATO_SPECIALE_D_APPALTO]]", type: referenced_by, confidence: inferito, reason: "Il capitolato superato G-06-ESEC-01 rinvia alla «relazione tecnica di progetto» per le caratteristiche del FV (Art. 8.2.2.1): rinvio per tipo, corrispondenza inferita" }
  - { doc: "[[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]]", type: referenced_by, confidence: inferito, reason: "Il capitolato G-06-ESEC-02 rinvia alla «relazione tecnica di progetto» per le caratteristiche del FV (Art. 8.2.2.1): rinvio per tipo, corrispondenza inferita" }
  - { doc: "[[RS-00-ESEC-01_RELAZIONE_TECNICA_IMPIANTI]]", type: referenced_by, confidence: verificato, reason: "La relazione impianti RS-00 vi rinvia per il dettaglio del FV («si rinvia alla specifica relazione», p. 11)" }
  - { doc: "[[PI-00-ESEC-01_PROGETTO_IMPIANTO_FOTOVOLTAICO]]", type: relazione_di, confidence: inferito, reason: "Relazione dimensionale del FV rappresentato nella tavola PI-00 (6 kWp, 7.964,4 kWh/anno, accumulo 15 kWh) — abbinamento per disciplina, contenuto grafico non letto" }
  - { doc: "[[PI-00a-ESEC-01_PLANIMETRIA_DI_INSIEME_CON_FOTOVOLTAICO_INTEGRATO_E_FOTOINSERIMENTI]]", type: relazione_di, confidence: inferito, reason: "Configurazione integrata del FV (tavola richiamata dal disciplinare per C2.1): la relazione descrive invece moduli su staffe a 30° limitati dallo spazio del terrazzo (p. 2) — confrontare — abbinamento per disciplina, contenuto grafico non letto" }
---

# RS-01-ESEC-01 — Relazione tecnica impianto fotovoltaico

## Per Claude futuro

Questa e' la relazione tecnica `RS-01-ESEC-01` della gara Cineteatro "Sala Polifunzionale Periz" — Castello di Bella (PZ). Descrizione ufficiale: "RELAZIONE TECNICA IMPIANTO FOTOVOLTAICO". 7 pagine: testo alle pp. 2, 6, 7; pp. 3-5 sono schermate PVGIS (sommario, produzione mensile, profilo d'orizzonte) lette visivamente. Fissa la taglia del FV di progetto (6 kWp, moduli inclinati a 30° su staffe), la produzione attesa (7.964,4 kWh/anno), il fabbisogno stimato (6.570 kWh/anno) e l'accumulo (3 batterie, 15 kWh). E' la baseline tecnica di C2.1 (BIPV) e C2.3 (accumulo). Confidence pagina: parziale (verificato per il testo; parziale per i valori letti dalle immagini PVGIS).

## Contenuto chiave

### Impianto di progetto (p. 2)
- Potenza: **6 kW** "da installare sul tetto piano dell'edificio, mediante staffe di supporto al fine di garantire un'inclinazione tale da avere una produzione soddisfacente" <!-- confidence: verificato -->.
- **"Il limite di 6 kw e' imposto dallo spazio a disposizione sul tetto terrazzato"** <!-- confidence: verificato, p. 2 --> — vincolo di superficie rilevante per qualsiasi miglioria C2.1.
- Stima produzione con PVGIS: **7.964,4 kWh/anno** <!-- confidence: verificato, p. 2 -->.

### Simulazione PVGIS (pp. 3-5, immagini)
| Parametro | Valore | Confidence |
|---|---|---|
| Ubicazione | lat 40,757 / lon 15,537 | parziale (lettura visiva p. 3) |
| Banca dati / tecnologia | PVGIS-SARAH2 / silicio cristallino | parziale |
| Potenza installata | 6 kWp | parziale |
| Perdite di sistema | 14% | parziale |
| Inclinazione / azimut | **30°** / 0° (sud) | parziale |
| Produzione annua | 7.964,4 kWh | parziale (coincide con il testo p. 2) |
| Irraggiamento annuo sul piano | 1.772,45 kWh/m2 | parziale |
| Variabilita' interannuale | 292,70 kWh | parziale |
| Perdita totale | −25,11% (incidenza −2,8%, spettrali +0,9%, temperatura −11,21%) | parziale |
| Produzione mensile | min ~400 kWh (dicembre/gennaio), max ~940 kWh (luglio) | parziale (lettura del grafico p. 4) |
| Orizzonte | ostruzioni modeste solo a N/NE/NW (p. 5) | parziale |

### Fabbisogno e accumulo (pp. 6-7)
- Ipotesi (storico consumi non disponibile): illuminazione ~2 kWh/h + altri utilizzatori (proiettore, ausiliari riscaldamento) ~4 kWh/h = **6 kWh/h**; 3 h/giorno x 365 = **6.570 kWh/anno** → il FV "soddisfa completamente il fabbisogno" nelle condizioni di massimo utilizzo <!-- confidence: verificato, p. 6 -->.
- Energia assorbita soprattutto in ore serali/notturne → **"n. 3 batterie di accumulo per un totale di 15 kwh"** <!-- confidence: verificato, p. 7 -->.
- Tipo di batteria, inverter, numero e modello dei moduli: **non indicati** in questa relazione (TBD qui). Il computo [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] riporta 13 moduli PERC/PERT da 450 Wp (5,85 kWp), "sistema di montaggio semi-integrato", inverter trifase e batteria agli ioni di litio contabilizzata in 15 kWh (dati della pagina nodo del computo, verificati a campione sul testo estratto).

### Lettura per i criteri
- C2.1: la soluzione base e' **non integrata** (moduli inclinati 30° su staffe, quindi emergenti dal piano della copertura e potenzialmente visibili/riflettenti); la miglioria BIPV deve confrontarsi con questa configurazione e con il limite di superficie del terrazzo <!-- confidence: inferito -->.
- C2.3: la capacita' di progetto qui e' 15 kWh, mentre altri elaborati indicano 20 kWh → la soglia ">20 kWh" del disciplinare va letta con cautela (nota N5 della criteria_matrix) <!-- confidence: inferito -->.

## Incoerenze
- 3 batterie / 15 kWh (qui, p. 7) vs 4 batterie / 15 kWh (RS-00 p. 11) vs 20 kWh (RS-03 p. 9, G-09 p. 14, SIC-00 p. 9, G-08 p. 15) → `02_graph/synthesis/fotovoltaico_e_accumulo.md`.
- Denominazione "Cineteatro Perez" (p. 2).

## Riferimenti a altri elaborati
- Nessun codice di elaborato citato. Richiamata (senza codice) da [[RS-00-ESEC-01_RELAZIONE_TECNICA_IMPIANTI]] p. 11 ("si rinvia alla specifica relazione").
- Tavola di progetto pertinente per tema (non citata nel testo): `PI-00-ESEC-01` progetto impianto fotovoltaico [[PI-00-ESEC-01_PROGETTO_IMPIANTO_FOTOVOLTAICO]]; tavola `PI-00a-ESEC-01` (FV integrato e fotoinserimenti, richiamata dal disciplinare per C2.1) [[PI-00a-ESEC-01_PLANIMETRIA_DI_INSIEME_CON_FOTOVOLTAICO_INTEGRATO_E_FOTOINSERIMENTI]]. Entrambe non citate nel testo: correlazione solo tematica.

## Sintesi tematiche collegate
`02_graph/synthesis/fotovoltaico_e_accumulo.md` · `02_graph/synthesis/copertura_terrazzi_e_cupola.md`
