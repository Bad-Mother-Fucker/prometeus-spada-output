---
type: document
subtype: relazione_tecnica
gara: "Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)"
date: 2026-10-03
ai-first: true
codice: "RS-00-ESEC-01"
file: "RS-00-ESEC-01_RELAZIONE_TECNICA_IMPIANTI.pdf"
section: "RS"
version_group: "RS-00"
is_latest: true
status: estratto
extracted_md: "01_extracted/text/RS-00-ESEC-01_RELAZIONE_TECNICA_IMPIANTI.md"
confidence: verificato
descrizione_ufficiale: "RELAZIONE TECNICA IMPIANTI (elenco elaborati G-00-ESEC-01)"
pagine: 13
data_documento: "aprile 2026"
supports_criteria:
  - { criterion: "[[C2]]", priority: alta, reason: "Baseline impiantistica di C2: FV 6 kW sul tetto piano su staffe inclinate (p. 11) — riferimento per l'integrazione BIPV di C2.1; accumulo 'n. 4 batterie per un totale di 15 kwh' (p. 11) — riferimento per l'interpretazione della soglia '>20 kWh' di C2.3; nessun impianto antintrusione, TVCC o building automation descritto (C2.2/C2.3)" }
related_documents:
  - { doc: "[[RS-01-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_FOTOVOLTAICO]]", type: references, confidence: verificato, reason: "«Per maggiori dettagli si rinvia alla specifica relazione» sul fotovoltaico (p. 11): unica relazione FV del progetto" }
  - { doc: "[[G-00-ESEC-01_ELENCO_ELABORATI]]", type: referenced_by, confidence: verificato, reason: "L'elenco elaborati G-00-ESEC-01 lo elenca per codice (p. 2) come «RELAZIONE TECNICA IMPIANTI»: fonte della descrizione ufficiale" }
  - { doc: "[[G-09-ESEC-01_RELAZIONE_CAM]]", type: referenced_by, confidence: inferito, reason: "La relazione CAM G-09 rinvia a una «Relazione tecnica impianti elettrici e speciali» (pp. 25, 30): titolo assente dall'elenco, corrispondenza inferita" }
  - { doc: "[[PI-00-ESEC-01_PROGETTO_IMPIANTO_FOTOVOLTAICO]]", type: relazione_di, confidence: inferito, reason: "La relazione impianti descrive il FV 6 kW su staffe e l'accumulo 4 batterie / 15 kWh (p. 11) rappresentati nella tavola — abbinamento per disciplina, contenuto grafico non letto" }
  - { doc: "[[PI-01-ESEC-01_SISTEMA_EVACUAZIONE_FUMI_FORZATO]]", type: relazione_di, confidence: inferito, reason: "Disciplina impianti: tavola dell'evacuazione forzata fumi, NON descritta nel testo di RS-00 (nessuna relazione dedicata) — abbinamento per disciplina, contenuto grafico non letto" }
  - { doc: "[[PI-03-ESEC-01_PROGETTO_IMPIANTO_IRAI]]", type: relazione_di, confidence: inferito, reason: "Disciplina impianti: tavola dell'impianto IRAI, NON descritto nel testo di RS-00 (nessuna relazione dedicata) — abbinamento per disciplina, contenuto grafico non letto" }
  - { doc: "[[PI-04-ESEC-01_INTERVENTI_TERMICI]]", type: relazione_di, confidence: inferito, reason: "La relazione descrive caldaia a condensazione < 116 kW e valvole termostatiche (p. 12) rappresentate nella tavola degli interventi termici — abbinamento per disciplina, contenuto grafico non letto" }
  - { doc: "[[PI-05-ESEC-01_INTERVENTI_ELETTRICI]]", type: relazione_di, confidence: inferito, reason: "La relazione descrive LED, controsoffitto per cavidotti, cavi e quadro elettrico (pp. 9, 12-13) rappresentati nella tavola degli interventi elettrici — abbinamento per disciplina, contenuto grafico non letto" }
---

# RS-00-ESEC-01 — Relazione tecnica impianti

## Per Claude futuro

Questa e' la relazione tecnica `RS-00-ESEC-01` della gara Cineteatro "Sala Polifunzionale Periz" — Castello di Bella (PZ). Descrizione ufficiale: "RELAZIONE TECNICA IMPIANTI". 13 pagine, di cui 6 di elenco normativo (pp. 2-7). Descrive lo stato di fatto degli impianti (p. 8) e quattro interventi: caldaia a condensazione + valvole termostatiche, LED + controsoffitto per cavidotti, revisione quadro elettrico, fotovoltaico 6 kW con accumulo (pp. 9-13). E' la baseline per C2 (FV e accumulo); non contiene antintrusione, TVCC, building automation, ne' l'ascensore. Confidence: verificato.

## Contenuto chiave

### Stato di fatto (sopralluogo, p. 8)
- Caldaia in centrale termica obsoleta, consumi elevati di gas; termosifoni senza valvole termostatiche.
- Faretti incassati nei solai in c.a. non funzionanti per infiltrazioni; cavi deteriorati; cortocircuiti con interruttori non riarmabili e **principi di incendio nel quadro elettrico**.
- Illuminazione energivora.

### Interventi (pp. 9-13)
| Impianto | Progetto | Pag. |
|---|---|---|
| Fotovoltaico | **6 kW** sul **tetto piano**, "mediante staffe di supporto al fine di garantire un'inclinazione" (moduli inclinati, non integrati); rinvio alla "specifica relazione" | 11 |
| Accumulo | **"n. 4 batterie di accumulo per un totale di 15 kwh"**, motivate dal consumo serale/notturno dell'illuminazione | 11 |
| Riscaldamento | caldaia attuale a basamento 90.000 kcal/h, rendimento ~85% → **caldaia a condensazione** 90.000 kcal/h, rendimento ~95%, potenza **< 116 kW** "al fine di evitare l'attivazione del procedimento antincendio presso i VV.F."; terminali a termosifoni con **valvole termostatiche** | 12 |
| Elettrico / illuminazione | **controsoffitto** per alloggiare cavidotti e faretti LED a incasso; sostituzione cavi deteriorati; faretti e plafoniere a LED (−90% consumi, > 30.000 h) | 12-13 |
| Quadro elettrico | revisione | 9 |
- 90.000 kcal/h ≈ 104,7 kW (< 116 kW) <!-- confidence: inferito, conversione -->.
- Norme: elenco include CEI EN 61215/61646/61730 per moduli FV; "l'installazione dovra' essere eseguita in modo da evitare la propagazione di un incendio dal generatore fotovoltaico al fabbricato" <!-- p. 7 -->.

### Assenze rilevanti per i criteri (verificate sul testo)
- Nessun impianto antintrusione/allarme, nessuna videosorveglianza TVCC (C2.2).
- Nessun sistema di building automation / supervisione remota (C2.3) — il computo [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] contiene pero' una voce NP 14 "Sistema di building automation" (p. 13 del computo, lettura in sola consultazione).
- Nessuna descrizione dell'ascensore, della rete naspi, dell'impianto IRAI o dell'evacuazione fumi (trattati altrove).

## Incoerenze
- Accumulo 4 batterie / 15 kWh (qui) vs 3 batterie / 15 kWh ([[RS-01-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_FOTOVOLTAICO]] p. 7) vs 20 kWh ([[RS-03-ESEC-01_RELAZIONE_ACUSTICA]] p. 9, [[G-09-ESEC-01_RELAZIONE_CAM]] p. 14, [[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]] p. 9) → `02_graph/synthesis/fotovoltaico_e_accumulo.md`.
- Riscaldamento con caldaia a condensazione (qui) vs "impianti di climatizzazione ad alta efficienza con pompe di calore" dichiarati in RS-03 p. 9 e G-09 p. 15.
- Denominazione "Cineteatro Perez" (p. 2) invece di "Periz".

## Riferimenti a altri elaborati
- "Per maggiori dettagli si rinvia alla specifica relazione" (p. 11) → relazione FV `RS-01-ESEC-01` [[RS-01-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_FOTOVOLTAICO]] (rinvio implicito, senza codice)
- Nessun codice di elaborato citato esplicitamente.

## Sintesi tematiche collegate
`02_graph/synthesis/fotovoltaico_e_accumulo.md` · `02_graph/synthesis/antincendio.md`
