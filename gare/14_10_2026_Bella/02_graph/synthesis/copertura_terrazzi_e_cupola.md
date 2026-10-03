---
type: synthesis
tema: "Copertura piana, terrazzi e cupola in acciaio e vetro"
gara: "Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)"
date: 2026-10-03
ai-first: true
confidence: verificato
criteri: ["[[C3]]", "[[C2]]"]
documenti:
  - "[[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]]"
  - "[[SIC-01-ESEC-01_CRONOPROGRAMMA]]"
  - "[[G-09-ESEC-01_RELAZIONE_CAM]]"
  - "[[G-10-ESEC-01_PIANO_DI_MANUTENZIONE]]"
  - "[[RS-01-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_FOTOVOLTAICO]]"
  - "[[G-08-ESEC-01_RELAZIONE_GENERALE]]"
  - "[[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]]"
  - "[[PA-05-ESEC-01_cupola_e_impermeabilizzazione]]"
  - "[[PI-01-ESEC-01_SISTEMA_EVACUAZIONE_FUMI_FORZATO]]"
  - "[[VVF-PI-07-00_PROSPETTO_E_SEZIONE]]"
  # --- aggiunti da graph-builder Fase D (2026-10-03): elaborati dello stesso tema collegati dagli archi ---
  - "[[G-02-ESEC-01_ELENCO_PREZZI]]"   # NP 11 pellicola cupola (92% energia respinta, posa interna), B.10.028.01 membrana poliureica senza isolante
  - "[[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]]"   # Art. 6.8 coperture continue piane, schemi stratigrafici generici
  - "[[G-07-ESEC-01_RELAZIONE_FOTOGRAFICA]]"   # cupola con telo provvisorio, terrazzi a ghiaia, scossaline arrugginite (figg. 14-16, 20, 22-25)
  - "[[PA-02-ESEC-01_SEZIONI_stato_di_progetto]]"   # sezioni di copertura e cupola (non letta)
  - "[[PI-00-ESEC-01_PROGETTO_IMPIANTO_FOTOVOLTAICO]]"   # campo FV sulla copertura +14,57 (non letta)
  - "[[RIL-02-ESEC-01_PROSPETTI_stato_di_fatto]]"   # pianta coperture con piani di taglio, stato di fatto (non letta)
  - "[[VVF-PI-06-00_COPERTURA]]"   # pianta coperture della pratica VV.F. (non letta)
---

# Sintesi — Copertura, terrazzi e cupola

## Per Claude futuro

Pagina di sintesi creata dal synthesis hook (Fase B, sottoinsieme 2): la copertura piana terrazzata e la cupola in acciaio e vetro della sala sono trattate da almeno 7 elaborati. Il progetto le **impermeabilizza** (poliurea), ricava **fori nella cupola per l'evacuazione fumi**, applica una **pellicola antisolare** e una **tenda motorizzata** alla cupola e posa il FV sul terrazzo, ma **non isola termicamente** la copertura. E' la baseline del sub-criterio **C3.1** (5 pt: isolamento copertura piana e carico termico estivo della cupola) e il supporto fisico di **C2.1** (BIPV). I dati di G-08 e G-04-ESEC-02 provengono dalle loro pagine nodo (altre fasi), verificati a campione sui testi estratti. Confidence: verificato.

## Stato di fatto
- Copertura piana terrazzata su piu' livelli, guaina bitumata ricoperta di ghiaia, infiltrazioni sui livelli 2 e 3 — [[G-08-ESEC-01_RELAZIONE_GENERALE]] pp. 12-13.
- **Cupola in acciaio e vetro** che illumina la sala, "giunzioni e guarnizioni fortemente danneggiate", infiltrazioni evidenti — G-08 p. 13. Nel layout di cantiere la cupola appare come lucernario circolare centrale a raggiera sopra la platea — SIC-00 pp. 259-260 (lettura visiva, parziale).

## Interventi di progetto
| Intervento | Contenuto | Fonte |
|---|---|---|
| Impermeabilizzazione | rimozione ghiaia, pulitura guaina, primer, **membrana in poliurea pura a spruzzo**; scossaline trattate | SIC-00 p. 8; G-08 p. 14 |
| Quantita' | impermeabilizzazione poliureica su membrana bituminosa di cupola, terrazzi e torrette: 360,51 m2 (cupola 96,45 m2) | [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] (pagina nodo; "Cupola 96,45" verificato sul testo p. 2) |
| Isolamento termico | **nessuno**: G-09 "nessun intervento e' previsto per quanto attiene la coibentazione delle componenti opache" | [[G-09-ESEC-01_RELAZIONE_CAM]] p. 30; G-08 p. 14 (pagina nodo); computo (assenza) |
| Cupola — carico solare | **pellicola antisolare** ("Oscuramento cupola": pellicola nera di protezione dal calore, argento scuro all'esterno, 22 m2, 92% energia respinta) | computo voce 7 / NP 11 (testo p. 3 verificato; 92% e 22 m2 dalla pagina nodo); G-09 p. 29 ("pellicole schermanti in copertura") |
| Cupola — oscuramento | **tenda motorizzata** per la copertura "all'occorrenza" della cupola (non precisato se interna o esterna) | G-08 p. 14; SIC-00 p. 10 ("Installazione di una tenda") |
| Cupola — sicurezza | **fori sulla cupola per l'evacuazione dei fumi** in caso di incendio; taglio copertura 4 g | SIC-00 p. 13; [[SIC-01-ESEC-01_CRONOPROGRAMMA]] p. 2 |
| Terrazzo | rifacimento pavimentazione + **13 pannelli FV** | SIC-00 p. 13 |
| FV | moduli su staffe inclinate (30°), superficie disponibile limitante (max 6 kW) | [[RS-01-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_FOTOVOLTAICO]] pp. 2-3 |
| Vetro serramenti | fattore di trasmissione solare 0,35 (infissi, non cupola) | G-09 p. 29 |
| Manutenzione | piano include manto impermeabilizzante con moduli FV flessibili, adatto a coperture piane con pendenze ricavate da pannelli isolanti | [[G-10-ESEC-01_PIANO_DI_MANUTENZIONE]] p. 38 |
| Cronoprogramma | gruppo "Copertura" 17 g a giugno-luglio 2026: fori evacuazione fumi 4 g, impermeabilizzazione 3 g, scossaline/gronde 5 g, pluviali/canne 5 g; nessuna fase per pellicola, tenda o isolamento | SIC-01 p. 2 |
| Cantiere | lavori in copertura nelle ore fresche (prima mattina o dopo le 16:00), parapetti, ponteggio frontale, verifica sovraccarichi | SIC-00 pp. 16-17 |
| Tavola | particolari costruttivi cupola e impermeabilizzazione; il testo grafico del cartiglio/tavola cita un "filtro adesivo oscurante" sulla cupola (segnale della Fase C, log 2026-10-03) | [[PA-05-ESEC-01_cupola_e_impermeabilizzazione]] (non letta in Fase B) |
| Torrini fumi | torrini di estrazione fumi sulla cupola (segnale della Fase C dalle tavole VVF-PI-07-00 e PI-01-ESEC-01) | [[VVF-PI-07-00_PROSPETTO_E_SEZIONE]], [[PI-01-ESEC-01_SISTEMA_EVACUAZIONE_FUMI_FORZATO]] (non lette in Fase B; confidence inferito) |

## Rilevanza per i criteri
- [[C3]] — C3.1: baseline = copertura **non isolata** + cupola trattata solo con pellicola e tenda; qualsiasi strato isolante o sistema di schermatura aggiuntivo e' oltre il progetto. Vincoli: compatibilita' con la membrana in poliurea, con i fori di evacuazione fumi della cupola e con il FV sul terrazzo; edificio nel Castello (visibilita' esterna).
- [[C2]] — C2.1: la copertura e' il supporto del FV; spessori e pendenze aggiuntive per l'isolamento interagiscono con la posa dei moduli e con il limite di superficie.
<!-- confidence: inferito per le implicazioni; verificato per i fatti in tabella -->
