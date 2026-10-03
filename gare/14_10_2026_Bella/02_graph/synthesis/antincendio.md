---
type: synthesis
tema: "Prevenzione incendi: rete naspi, compartimentazioni, evacuazione fumi, parere VV.F."
gara: "Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)"
date: 2026-10-03
ai-first: true
confidence: verificato
criteri: ["[[C1]]", "[[C2]]", "[[C3]]"]
documenti:
  - "[[RS-02-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_IDRICO_ANTINCENDIO]]"
  - "[[G-10-ESEC-01_PIANO_DI_MANUTENZIONE]]"
  - "[[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]]"
  - "[[SIC-01-ESEC-01_CRONOPROGRAMMA]]"
  - "[[RS-00-ESEC-01_RELAZIONE_TECNICA_IMPIANTI]]"
  - "[[RS-03-ESEC-01_RELAZIONE_ACUSTICA]]"
  - "[[G-09-ESEC-01_RELAZIONE_CAM]]"
  - "[[G-08-ESEC-01_RELAZIONE_GENERALE]]"
  - "[[COM-PZ.REGISTRO-UFFICIALE.2026.0007341_Marcato]]"
  - "[[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]]"
  # --- aggiunti da graph-builder Fase D (2026-10-03): tavole antincendio citate nel corpo (non lette), collegate con archi tavola_di/referenced_by ---
  - "[[PI-01-ESEC-01_SISTEMA_EVACUAZIONE_FUMI_FORZATO]]"
  - "[[PI-02-ESEC-01_PROGETTO_CON_INDICAZIONE_CLASSI_RESISTENZA_AL_FUOCO]]"
  - "[[PI-03-ESEC-01_PROGETTO_IMPIANTO_IRAI]]"
  - "[[PI-06-ESEC-01_IMPIANTO_IDRICO_ANTINCENDIO]]"
  - "[[VVF-PI-01-00_PLANIMETRIA_GENERALE]]"
  - "[[VVF-PI-02-00_PIANTA_PIANO_TERRA]]"
  - "[[VVF-PI-03-00_PIANTA_PIANO_PRIMO]]"
  - "[[VVF-PI-04-00_PIANTA_PIANO_SECONDO]]"
  - "[[VVF-PI-05-00_PIANTA_PIANO_TERZO]]"
  - "[[VVF-PI-06-00_COPERTURA]]"
  - "[[VVF-PI-07-00_PROSPETTO_E_SEZIONE]]"
  - "[[VVF-PI-08-00_AREE_A_RISCHIO_SPECIFICO]]"
---

# Sintesi — Prevenzione incendi

## Per Claude futuro

Pagina di sintesi creata dal synthesis hook (Fase B, sottoinsieme 2): l'adeguamento antincendio della sala e' trattato in modo frammentario da almeno 8 elaborati, con descrizioni non coerenti tra loro (naspi vs "sprinkler" vs "idranti a colonna"). Nessun criterio premia direttamente l'antincendio, ma il tema e' un **vincolo trasversale** per le migliorie su materiali e arredi (C1.2, C1.3, C3.2), copertura e cupola (C3.1, C2.1), accumulo (C2.3) e logistica interna (C3.3). Le tavole specialistiche (PI-01, PI-02, PI-03, PI-06, VVF-PI-01…08) non sono state lette. Confidence: verificato.

## Quadro di progetto

| Aspetto | Contenuto | Fonte |
|---|---|---|
| Parere VV.F. | Comando di Potenza U.0007341 del 20/04/2026: **parere favorevole**, attivita' 65.1.B (locale di spettacolo 100-200 persone), condizionato a RTO DM 3/8/2015, RTV15 (DM 22/11/2022), RTV13; SCIA prima dell'esercizio | [[COM-PZ.REGISTRO-UFFICIALE.2026.0007341_Marcato]] p. 1 (dato dalla pagina nodo) |
| Rete idrica | **4 naspi DN25** UNI EN 671-1, UNI 10779 livello I, 35 l/min a 200 kPa, 30 min, alimentazione da acquedotto (173 l/min a 600 kPa); naspi su tutti i piani presso uscite e vie di esodo | [[RS-02-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_IDRICO_ANTINCENDIO]] pp. 10-11, 15, 18, 20 |
| Compartimentazione | controsoffitto per compartimentazione antincendio (2 fasi da 5 g) e pareti divisorie per compartimentazione (5 g) | [[SIC-01-ESEC-01_CRONOPROGRAMMA]] p. 2; [[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]] pp. 43-45 |
| Evacuazione fumi | **taglio della copertura/fori sulla cupola** per evacuazione fumi (4 g); impianto di aspirazione e ricambio aria ed evacuazione fumi con canalizzazioni, unita' di ventilazione, bocchette e griglie | SIC-01 p. 2; SIC-00 pp. 13, 40; tavola PI-01 (non letta) |
| Centrale termica | caldaia a condensazione **< 116 kW** scelta per non attivare il procedimento VV.F. sulla centrale termica | [[RS-00-ESEC-01_RELAZIONE_TECNICA_IMPIANTI]] p. 12; SIC-00 p. 9 |
| FV | installazione tale da evitare la propagazione dell'incendio dal generatore al fabbricato (CEI EN 61730) | RS-00 p. 7 |
| Accumulo | locale privo di umidita'/polveri, aerato (miscela idrogeno-ossigeno), estintori in prossimita' (riferito a batterie al piombo) | [[G-10-ESEC-01_PIANO_DI_MANUTENZIONE]] p. 30 |
| Poltrone | 134 poltrone "che rispettano la normativa sulla prevenzione incendi"; nel computo ignifughe classe 1 | SIC-00 p. 11; [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] (dato dalla pagina nodo) |
| Altre misure dichiarate | porte tagliafuoco con maniglioni antipanico, vie di esodo segnalate, illuminazione di emergenza | RS-03 p. 8; G-09 p. 14; [[G-08-ESEC-01_RELAZIONE_GENERALE]] p. 23 |
| Manutenzione | UT 01.07: tubazioni in acciaio zincato, idranti a colonna sottosuolo, rivelatori di fumo, serrande | G-10 p. 48 |
| Capitolato | capitolo antincendio generico (porte EI, rivelazione, sprinkler, water mist, evacuatori) | [[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]] cap. 10 (dato dalla pagina nodo) |

## Incoerenze tra documenti
1. **Sprinkler**: dichiarati in RS-03 p. 8, G-09 p. 14, G-08 p. 23 ("rilevazione incendi e impianti sprinkler integrati con controllo centralizzato") ma **assenti** dalla relazione di calcolo RS-02 (solo naspi) e dal cronoprogramma.
2. **Terminali idrici**: naspi DN25 (RS-02) vs "idranti a colonna sottosuolo" e tubazioni in acciaio zincato nel piano di manutenzione (G-10 p. 48).
3. **Rivelazione incendi**: citata come "sistemi di rilevazione" (RS-03, G-09) e "rivelatori di fumo" (G-10); presumibilmente oggetto dell'impianto IRAI (SIC-00 p. 9, tavola PI-03 non letta) — nessuna relazione testuale dedicata.
<!-- confidence: verificato per le citazioni; inferito per l'attribuzione all'IRAI -->

## Rilevanza come vincolo per i criteri
- [[C1]] — materiali di finitura acustica (C1.3) e poltrone (C1.2) offerti devono rispettare la reazione al fuoco richiesta per il locale di spettacolo (RTV15) e il parere VV.F.; serramenti (C1.1) su vie di esodo devono mantenere le funzioni antipanico.
- [[C3]] — C3.1: interventi sulla cupola (schermature, isolamento) devono preservare le aperture di evacuazione fumi ricavate nella cupola; C3.2: arredi/attrezzature aggiuntive in sala entro la classificazione 65.1.B; C3.3: depositi interni di attrezzature smontate senza ostacolare naspi e vie di esodo (layout SIC-00 p. 260).
- [[C2]] — C2.1: integrazione FV in copertura senza propagazione al fabbricato; C2.3: accumulo maggiorato con requisiti di locale/aerazione.
<!-- confidence: inferito (collegamenti logici, non scritti nei documenti) -->
