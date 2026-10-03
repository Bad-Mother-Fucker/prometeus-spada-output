---
type: synthesis
tema: "Impianto fotovoltaico, accumulo e gestione energetica"
gara: "Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)"
date: 2026-10-03
ai-first: true
confidence: verificato
criteri: ["[[C2]]"]
documenti:
  - "[[RS-00-ESEC-01_RELAZIONE_TECNICA_IMPIANTI]]"
  - "[[RS-01-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_FOTOVOLTAICO]]"
  - "[[RS-03-ESEC-01_RELAZIONE_ACUSTICA]]"
  - "[[G-09-ESEC-01_RELAZIONE_CAM]]"
  - "[[G-10-ESEC-01_PIANO_DI_MANUTENZIONE]]"
  - "[[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]]"
  - "[[SIC-01-ESEC-01_CRONOPROGRAMMA]]"
  - "[[G-08-ESEC-01_RELAZIONE_GENERALE]]"
  - "[[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]]"
  - "[[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]]"
  - "[[PI-00-ESEC-01_PROGETTO_IMPIANTO_FOTOVOLTAICO]]"
  - "[[PI-00a-ESEC-01_PLANIMETRIA_DI_INSIEME_CON_FOTOVOLTAICO_INTEGRATO_E_FOTOINSERIMENTI]]"
  # --- aggiunti da graph-builder Fase D (2026-10-03): elaborati dello stesso tema collegati dagli archi ---
  - "[[G-02-ESEC-01_ELENCO_PREZZI]]"   # testo completo voci FV (450 Wp, semi-integrato, inverter 6 kW), Nr. 118 accumulo al litio 877,83 €/kWh, NP 14 Building Automation
  - "[[PI-05-ESEC-01_INTERVENTI_ELETTRICI]]"   # quadri e distribuzione su cui integrare accumulo e supervisione (tavola non letta)
  - "[[VVF-PI-06-00_COPERTURA]]"   # copertura +14,00 m con fotovoltaico nella pratica VV.F. (testo grafico)
  - "[[VVF-PI-08-00_AREE_A_RISCHIO_SPECIFICO]]"   # vincolo antincendio su un accumulo maggiorato (tavola non letta)
---

# Sintesi — Fotovoltaico, accumulo e gestione energetica

## Per Claude futuro

Pagina di sintesi creata dal synthesis hook (Fase B, sottoinsieme 2): il tema FV/accumulo e' trattato da almeno 9 elaborati testuali, con **valori discordanti sulla capacita' di accumulo** (15 kWh vs 20 kWh) che incidono direttamente sull'interpretazione della soglia ">20 kWh" del sub-criterio **C2.3** (7 pt) e una configurazione di base **non integrata** (moduli su staffe inclinate) che e' il termine di confronto del sub-criterio **C2.1 BIPV** (15 pt). Leggere questa pagina prima delle singole pagine nodo quando si analizza [[C2]]. I dati di G-08, G-04-ESEC-02 e G-06-ESEC-02 provengono dalle loro pagine nodo (altre fasi) e sono stati verificati a campione sui testi estratti. Confidence: verificato (salvo valori PVGIS letti da immagine, parziale).

## Configurazione del FV di progetto

| Dato | Valore | Fonte |
|---|---|---|
| Potenza | 6 kW / 6 kWp | [[RS-01-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_FOTOVOLTAICO]] p. 2; [[RS-00-ESEC-01_RELAZIONE_TECNICA_IMPIANTI]] p. 11; [[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]] p. 8 |
| Unita' errata "6 kWh" | — | [[RS-03-ESEC-01_RELAZIONE_ACUSTICA]] p. 8; [[G-09-ESEC-01_RELAZIONE_CAM]] p. 14; [[G-08-ESEC-01_RELAZIONE_GENERALE]] p. 24 |
| Moduli | 13 moduli da 450 Wp (5,85 kWp), tecnologia PERC/PERT | [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] (voci 67-88); "13 pannelli" anche in SIC-00 p. 13 |
| Posa | sul tetto piano/terrazzato, **su staffe di supporto inclinate** (30°, azimut sud); computo: "sistema di montaggio semi-integrato" | RS-01 pp. 2-3 (30° da immagine PVGIS, parziale); RS-00 p. 11; G-04-ESEC-02 |
| Vincolo di superficie | "Il limite di 6 kw e' imposto dallo spazio a disposizione sul tetto terrazzato" | RS-01 p. 2 |
| Produzione | 7.964,4 kWh/anno (PVGIS-SARAH2, perdite sistema 14%) | RS-01 pp. 2-3 |
| Fabbisogno stimato | 6.570 kWh/anno (6 kWh/h x 3 h x 365) | RS-01 p. 6 |
| Durata posa in cronoprogramma | 2 g (ottobre 2026), dopo l'impermeabilizzazione (giugno) | [[SIC-01-ESEC-01_CRONOPROGRAMMA]] p. 2 |
| Cantiere | carico/scarico pannelli tramite ponteggio frontale; rischio caduta dall'alto ALTO | SIC-00 pp. 16, 54 |
| Manutenzione | piano include "elementi di copertura con funzione fotovoltaica" per centri storici "limitando al minimo l'impatto visivo", frangisole FV, manto impermeabilizzante con moduli FV flessibili | [[G-10-ESEC-01_PIANO_DI_MANUTENZIONE]] pp. 35-38 |
| Tavole | pianta coperture con FV; planimetria con FV integrato e fotoinserimenti (richiamata dal disciplinare per C2.1, non firmata, non in elenco) | [[PI-00-ESEC-01_PROGETTO_IMPIANTO_FOTOVOLTAICO]], [[PI-00a-ESEC-01_PLANIMETRIA_DI_INSIEME_CON_FOTOVOLTAICO_INTEGRATO_E_FOTOINSERIMENTI]] (non lette) |

## CONTRADDIZIONE — capacita' di accumulo di progetto

| Fonte | Valore dichiarato | Pag. |
|---|---|---|
| [[RS-00-ESEC-01_RELAZIONE_TECNICA_IMPIANTI]] | n. 4 batterie, **15 kWh** | 11 |
| [[RS-01-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_FOTOVOLTAICO]] | n. **3** batterie, **15 kWh** | 7 |
| [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] | batteria ioni di litio, **15 kWh** contabilizzati (voce 78, R.01.020.01) | 14-15 del computo |
| [[G-08-ESEC-01_RELAZIONE_GENERALE]] | n. 4 batterie, **20 kWh** | 15 (e 24) |
| [[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]] | n. 4 batterie, **20 kWh** | 9 |
| [[G-09-ESEC-01_RELAZIONE_CAM]] | "batterie di accumulo da **20 kWh**" | 14, 16 |
| [[RS-03-ESEC-01_RELAZIONE_ACUSTICA]] | "batterie di accumulo da **20 kWh**" | 9 |
| [[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]] | accumulo ibrido con EMS ed EPS, capacita' segnaposto "$MANUAL$" | art. 8.3 (dato dalla pagina nodo) |
| [[G-10-ESEC-01_PIANO_DI_MANUTENZIONE]] | accumulatori descritti come al **piombo acido** (vita 6-8 anni), nessuna capacita' | 30 |

- Le fonti quantitative ed economiche (relazioni specialistiche e computo) indicano **15 kWh**; le fonti descrittive (relazione generale, PSC, CAM, acustica) indicano **20 kWh**. Il disciplinare (sub 2.3) premia l'"incremento quantitativo della capacita' di accumulo delle batterie (>20 kWh)" (nota N5 della criteria_matrix).
- Implicazione per [[C2]] (fatto, non proposta): se la base contrattuale e' il computo, la capacita' di progetto e' 15 kWh e qualunque offerta <= 20 kWh rischia di non essere riconosciuta come incremento nel senso del disciplinare; il valore da assumere come baseline va chiarito (eventuale quesito entro il 06/10/2026 ore 12:00) — **CONTRADDIZIONE da riportare in index.md (Fase E/8)**.
- Tecnologia batterie: litio (computo) vs piombo acido (piano di manutenzione) — incoerenza secondaria.

## Gestione energetica / building automation (C2.3)
- Relazioni specialistiche RS-00/RS-01: nessun sistema di supervisione o controllo remoto.
- Computo: voce NP 14 "Sistema di building automation" (hardware + app per riscaldamento, ACS, climatizzazione, illuminazione) — dato dalla pagina nodo di [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]], verificato sul testo (p. 13 del computo).
- G-09 p. 25: illuminazione di sicurezza "controllata in modo centralizzato da un sistema intelligente"; G-09/RS-03/G-08: LED con sensori di presenza; "controllo centralizzato" della sicurezza antincendio.
- Capitolato: EMS dell'accumulo ibrido (art. 8.3, dato dalla pagina nodo).
- Cronoprogramma: nessuna fase per BA o accumulo.

## Integrazione architettonica (C2.1)
- Base di progetto: moduli emergenti dalla copertura su staffe a 30° (non BIPV); la sala e' in un'ala del Castello aragonese in sommita' al centro storico (RS-03 p. 5; SIC-00 p. 13).
- Nessun elaborato testuale del sottoinsieme riporta indirizzi o pareri di tutela della Soprintendenza specifici per il progetto (ricerca "soprintend/tutela" su RS-00, RS-01, RS-03, G-09, G-10, SIC-00: in G-09 "Soprintendenze" compare solo nel testo normativo del criterio CAM 2.4.7, p. 28; altrove solo "tutela della salute/superfici").
- RS-00 p. 7: requisito di installazione che eviti la propagazione dell'incendio dal generatore al fabbricato (CEI EN 61730) — rilevante per soluzioni integrate in copertura.

## Criteri collegati
- [[C2]] — C2.1 (configurazione e vincolo di superficie), C2.3 (capacita' di accumulo, BA). C2.2 non trattato da alcun documento del tema.
