---
type: synthesis
tema: "Acustica della sala: tempo di riverbero, materiali di finitura, poltrone"
gara: "Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)"
date: 2026-10-03
ai-first: true
confidence: verificato
criteri: ["[[C1]]"]
documenti:
  - "[[RS-03-ESEC-01_RELAZIONE_ACUSTICA]]"
  - "[[G-09-ESEC-01_RELAZIONE_CAM]]"
  - "[[G-10-ESEC-01_PIANO_DI_MANUTENZIONE]]"
  - "[[G-08-ESEC-01_RELAZIONE_GENERALE]]"
  - "[[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]]"
  - "[[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]]"
  # --- aggiunti da graph-builder Fase D (2026-10-03): elaborati dello stesso tema collegati dagli archi ---
  - "[[G-02-ESEC-01_ELENCO_PREZZI]]"   # NP 12 pannelli MDF/acustici senza prestazioni dichiarate; NP 05 poltrone
  - "[[G-07-ESEC-01_RELAZIONE_FOTOGRAFICA]]"   # finiture esistenti: moquette, soffitto dipinto, controsoffitto ammalorato, diffusori (figg. 7-15)
  - "[[PA-00-ESEC-01_PIANTE_stato_di_progetto]]"   # tavola_di RS-03: piante della sala (non letta)
  - "[[PA-02-ESEC-01_SEZIONI_stato_di_progetto]]"   # tavola_di RS-03: volume acustico della sala (non letta)
  - "[[PI-02-ESEC-01_PROGETTO_CON_INDICAZIONE_CLASSI_RESISTENZA_AL_FUOCO]]"   # classi di reazione al fuoco per finiture e pannellature (non letta)
---

# Sintesi — Acustica della sala

## Per Claude futuro

Pagina di sintesi creata dal synthesis hook (Fase B, sottoinsieme 2): l'acustica interna della sala e' trattata da almeno 5 elaborati. La sola fonte numerica e' [[RS-03-ESEC-01_RELAZIONE_ACUSTICA]] (T60 di Sabine 0,79 s a 500 Hz, V = 986 m3); gli altri documenti ripetono la stessa descrizione dei materiali (MDF a parete, poltroncine in tessuto, pavimento in resina). E' la baseline del sub-criterio **C1.3** (8 pt) e in parte di **C1.2** (poltrone). I dati di G-08 e G-04-ESEC-02 provengono dalle loro pagine nodo (altre fasi). Confidence: verificato.

## Parametri e materiali di progetto

| Elemento | Dato | Fonte |
|---|---|---|
| Volume analizzato | platea 862 m3 + galleria 124 m3 = **986 m3** | RS-03 p. 15 |
| Metodo | formula di Sabine, valori medi da foglio di calcolo; verifica con misure in opera al collaudo (Tecnico Competente in Acustica) | RS-03 pp. 3, 13, 17 |
| T60 | 1,77 / 1,11 / **0,79** / 0,65 / 0,56 / 0,61 s a 125-4000 Hz | RS-03 p. 17 |
| Obiettivo | "praticamente coincidente" con l'ottimo per sala polifunzionale (grafico); **nessun valore numerico di T ottimale** | RS-03 pp. 17-18 |
| Altri indici (STI, C50, C80, D50) | **non calcolati** | RS-03 (assenza) |
| Pareti | pannelli **MDF** (in tabella "listelli in legno"), 99,35 m2, alfa500 = 0,20 | RS-03 pp. 7, 16; G-09 p. 14; G-08 p. 20 |
| Pannelli MDF a computo | "pannelli da parete MDF / acustici / 3D a scelta della D.L.", 85,15 m2 (NP 12) | [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] (dato dalla pagina nodo) |
| Soffitto | cemento faccia vista 79,02 m2, alfa500 = 0,03 (da preservare, omaggio al restauro Pagliara secondo G-08 p. 20) | RS-03 p. 16 |
| Controsoffitto | cartongesso 14,88 m2, alfa500 = 0,05 | RS-03 p. 16 |
| Pavimento | resina epossidica 2-3 mm, 175,42 m2, alfa500 = 0,02 | RS-03 pp. 7, 16 |
| Sipari | palco e dietroscena 64,56 m2, cotone, alfa500 = 0,10 | RS-03 p. 16 |
| Poltrone | 134 poltroncine in tessuto (cotone) azzurro petrolio; calcolo a sala piena (alfa per persona 1,1 a 500 Hz) | RS-03 pp. 8, 16; SIC-00 p. 11; G-09 p. 14 |
| Requisito di manutenzione controsoffitti | potere fonoisolante 25-30 dB(A), fonoassorbenza 0,60-0,80 (500-1000 Hz) — valori generici di catalogo | [[G-10-ESEC-01_PIANO_DI_MANUTENZIONE]] p. 57 |
| CAM 2.4.11 | dichiarato soddisfatto con MDF e poltroncine, rinvio a RS-03 | [[G-09-ESEC-01_RELAZIONE_CAM]] p. 31 |
| Normativa | DM 23/06/2022 (CAM), UNI EN 12354-6; G-08 cita UNI 11532 | RS-03 p. 4; [[G-08-ESEC-01_RELAZIONE_GENERALE]] pp. 22-23 |

## Osservazioni di sintesi (fatti utili all'analisi di C1.3)
- Il bilancio di assorbimento a 500 Hz e' dominato dal pubblico (152,9 m2 su 206,2 m2): la sala vuota o parzialmente occupata non e' valutata.
- Ampie superfici riflettenti restano invariate in progetto (soffitto in cemento, pavimento in resina): sono le superfici su cui un intervento sui materiali inciderebbe di piu' — con il vincolo di preservare il cemento faccia vista del soffitto dichiarato da G-08.
- Le finiture acustiche devono restare compatibili con l'adeguamento antincendio della sala (locale di spettacolo 65.1.B, RTV15) → `02_graph/synthesis/antincendio.md`.
- Incongruenza sui posti: 134 poltrone (RS-03, SIC-00, G-08 p. 18) vs platea in due settori da 53 + 54 = 107 posti (G-08 p. 20; differenza attribuibile alla galleria, inferito dalla pagina nodo G-08).
- Nessun documento del tema tratta isolamento acustico di facciata o rumore degli impianti (ventilazione/evacuazione fumi introdotta dal progetto, SIC-00 p. 13).

## Criteri collegati
- [[C1]] — C1.3 (baseline T60 e materiali), C1.2 (numero e tessuto poltrone), C1.1 (solo finestre 7 m2 nel calcolo).
