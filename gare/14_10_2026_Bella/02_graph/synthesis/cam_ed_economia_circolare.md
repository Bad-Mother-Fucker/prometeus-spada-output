---
type: synthesis
tema: "Criteri Ambientali Minimi (CAM), certificazioni di filiera ed economia circolare dei rifiuti di cantiere"
gara: "Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)"
date: 2026-10-03
ai-first: true
confidence: verificato
criteri: ["[[C4]]"]
documenti:
  - "[[G-09-ESEC-01_RELAZIONE_CAM]]"
  - "[[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]]"
  - "[[G-02-ESEC-01_ELENCO_PREZZI]]"
  - "[[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]]"
  - "[[G-10-ESEC-01_PIANO_DI_MANUTENZIONE]]"
  - "[[RS-03-ESEC-01_RELAZIONE_ACUSTICA]]"
  - "[[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]]"
  - "[[SIC-01-ESEC-01_CRONOPROGRAMMA]]"
  - "[[SIC-02-ESEC-01_LAYOUT_DI_CANTIERE]]"
  - "[[SIC-03-ESEC-01_COSTI_PER_LA_SICUREZZA]]"
  - "[[G-07-ESEC-01_RELAZIONE_FOTOGRAFICA]]"
  - "[[G-00-ESEC-01_ELENCO_ELABORATI]]"
  - "[[PI-02-ESEC-01_PROGETTO_CON_INDICAZIONE_CLASSI_RESISTENZA_AL_FUOCO]]"
---

# Sintesi — CAM ed economia circolare

## Per Claude futuro

Pagina di sintesi creata dalla Fase D (synthesis hook segnalato dalla Fase B, sottoinsieme 1): i Criteri Ambientali Minimi e la gestione dei rifiuti di demolizione sono trattati da almeno 8 elaborati. È la baseline del sub-criterio **C4.2** (5 pt: riciclato certificato EPD in cartongesso, silicati antincendio e isolanti oltre i minimi CAM; legno FSC/PEFC; VOC classe A+; piano avanzato di economia circolare dei detriti da taglio solai e demolizioni con monitoraggio di polveri e vibrazioni). Fatti chiave: (1) negli elaborati compaiono **tre edizioni dei CAM** e nessuna è quella del disciplinare (D.M. 24.11.2025); (2) la relazione CAM [[G-09-ESEC-01_RELAZIONE_CAM]] è **dichiarativa**: nessuna percentuale di riciclato, EPD, FSC/PEFC, classe A+ né stima della demolizione selettiva; (3) il disciplinare chiama la relazione CAM «Elaborato B3», codice che non esiste nell'elenco (nota N11 della criteria_matrix). Per la logistica e il monitoraggio in cantiere vedi anche `02_graph/synthesis/logistica_cantiere.md`. Confidence: verificato.

## Riferimenti normativi CAM negli elaborati

| Edizione CAM | Dove è citata | Confidence |
|---|---|---|
| D.M. 11/01/2017 | Premessa della relazione CAM (G-09 p. 4) | verificato |
| D.M. 11/10/2017 | Voci di cartongesso dell'elenco prezzi (B.08.007.01, B.08.027.01, B.08.037.01) in [[G-02-ESEC-01_ELENCO_PREZZI]]; CAM del fotovoltaico nel capitolato (Art. 8.2.5 p. 183) | verificato |
| D.M. 23/06/2022 | Cap. 5 CAM di [[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]] (indice p. 257); G-09 p. 8; valutazione acustica di [[RS-03-ESEC-01_RELAZIONE_ACUSTICA]] p. 3 | verificato |
| D.M. 05/08/2024 | G-09 p. 8 | verificato |
| **D.M. 24.11.2025** | Solo nel disciplinare (Premesse, `01_extracted/text/disciplinare.di.gara.md`), che lo pone come riferimento dei «minimi CAM» di C4.2 — **assente da tutti gli elaborati** (ricerca testuale su G-09; G-06-02 e G-02 citano altre edizioni) | verificato |

## Minimi CAM di progetto (da superare per C4.2)

| Ambito | Minimo / prescrizione | Fonte | Confidence |
|---|---|---|---|
| Tramezzature, contropareti, controsoffitti a secco | ≥ 10% di riciclato (≥ 5% se a base gesso) | G-06-02 Cap. 5 p. 94; G-09 p. 38 (2.5.8 «verificato», rinvio all'esecuzione) | verificato |
| Cartongesso a prezzo di progetto | Pannelli «DM 11/10/2017 (CAM)», asserzione ambientale UNI EN ISO 14021, riciclabili 100%, **riciclato minimo > 20%**; EI120 con lastre tipo F A2-s1-d0 | G-02 | verificato |
| Legno | Strutturale FSC o PEFC; isolante in legno ≥ 70% riciclato | G-06-02 p. 93 | verificato |
| Pannelli MDF | G-09 dichiara che «rispettano i criteri» 2.5.6 senza certificazione indicata; stessa frase ripetuta per gli isolanti (2.5.7) | G-09 pp. 36-37 | verificato |
| Isolanti | Requisiti generali e CAM (marcatura CE, REACH, no ODP); **tabella delle % minime di riciclato non presente nel testo estratto** | G-06-02 Art. 4.11, Cap. 5 pp. 93-94 | verificato (tabella: TBD) |
| Emissioni indoor (VOC) | Si applica a pitture, pavimenti, adesivi, rivestimenti, pannelli, controsoffitti; **tabella dei limiti non presente nel testo estratto**; G-09 rinvia a UNI EN 16516 / ISO 16000-9 e all'esecuzione | G-06-02 p. 91; G-09 p. 34 | verificato (tabella: TBD) |
| Serramenti PVC | ≥ 20% di riciclato | G-06-02 p. 95; G-09 p. 39 | verificato |
| Demolizione selettiva | **≥ 70% in peso** dei rifiuti non pericolosi a riutilizzo/riciclo/recupero, con stima a progetto | G-06-02 Cap. 5 §2.6.2 pp. 96-97 | verificato |
| Stima demolizione di progetto | **Nessuna stima**: «quantitativo di rifiuti molto modesto», avvio «al più vicino centro di riciclaggio» | G-09 pp. 43-44 | verificato |
| Disassemblaggio e fine vita | Dichiarazione di principio, soglia del 70% non quantificata | G-09 pp. 32-33 | verificato |
| Cantiere | 15 misure: polveri (irrorazione), rumore e **vibrazioni**, macchine fase IIIA/IV/V, impatto visivo, demolizione selettiva, raccolta differenziata; G-09 rinvia al PSC (2.6.1, 3.1.1) | G-06-02 pp. 95-96; G-09 pp. 42, 45 | verificato |
| Proprietà dei materiali di demolizione | Materiali di escavazione e demolizione di proprietà della stazione appaltante, da accatastare dove essa indica | G-06-02 Art. 2.24 p. 37 | verificato |
| Piano di manutenzione | Requisiti ambientali generici (riciclato, certificazione ecologica, separabilità, gestione ecocompatibile dei rifiuti); CAM 2.4.12 dichiarato soddisfatto | [[G-10-ESEC-01_PIANO_DI_MANUTENZIONE]] pp. 162-199; G-09 p. 32 | verificato |

## Perimetro fisico a computo (quantità su cui misurare riciclato e rifiuti)

| Voce | Contenuto | Fonte | Confidence |
|---|---|---|---|
| 10-13 | Controsoffitto 200 mq, controparete 100 mq, parete REI 60 in silicato 14,61 mq, parete EI120 39 mq — 19.670,57 € | [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] | verificato |
| 8 (NP 09) | Taglio solaio con disco diamantato «in assenza di polveri e vibrazioni», botola 1,80 × 1,80 m, 3,24 mq — 2.916,00 € | G-04-02 | verificato |
| Rimozioni | Moquette 275 mq (voce 28); ghiaia dei terrazzi a discarica (G-08 p. 14); NP 03 rimozione materiale arido 1.315,60 €; 120 poltrone esistenti (voce 101); conferimenti CER 17 06 04 / 17 04 05 / 17 03 03 | G-04-02; [[G-03-ESEC-01_ANALISI_NUOVI_PREZZI]] (elenco NP) | verificato |
| Finiture da rimuovere visibili | Moquette blu usurata (fig. 7), controsoffitto blu con distacchi (fig. 15) | [[G-07-ESEC-01_RELAZIONE_FOTOGRAFICA]] | parziale |
| Elementi con classi al fuoco | Tavola delle classi di reazione/resistenza al fuoco, dove verosimilmente sono indicati cartongesso e silicati antincendio | [[PI-02-ESEC-01_PROGETTO_CON_INDICAZIONE_CLASSI_RESISTENZA_AL_FUOCO]] | inferito (non letta) |

## Cantiere: monitoraggio e gestione rifiuti

- PSC: «monitoraggio delle vibrazioni durante le lavorazioni più invasive», tecniche a basso impatto sulle murature (p. 17); abbattimento polveri (p. 20); depositi di rifiuti separati per tipologia (pp. 31-34) — [[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]]. <!-- confidence: verificato -->
- Layout: area di stoccaggio rifiuti con cassone e aree interne per piano (copia nel PSC pp. 259-260) — [[SIC-02-ESEC-01_LAYOUT_DI_CANTIERE]]. <!-- confidence: parziale, lettura visiva della copia -->
- Costi della sicurezza: **nessuna voce** per monitoraggio di polveri/vibrazioni o gestione selettiva dei detriti — [[SIC-03-ESEC-01_COSTI_PER_LA_SICUREZZA]]. <!-- confidence: verificato -->
- Cronoprogramma: nessuna fase dedicata a demolizioni o gestione dei detriti; lavorazioni demolitive esplicite: taglio copertura per fori evacuazione fumi (4 g), tracce a mano e meccaniche (10 g), rimozione caldaia (2 g) — [[SIC-01-ESEC-01_CRONOPROGRAMMA]] p. 2. <!-- confidence: verificato -->

## Incongruenze

1. **Edizione dei CAM (contraddizione D11 di [[economic_framework]], verificata dalla Fase E).** Il disciplinare (Premesse p. 3) richiede i CAM del D.M. 24.11.2025 (edilizia) e del D.M. 23/06/2022 n. 254 (arredi); capitolato, relazione CAM e relazione acustica sono redatti sul D.M. 23/06/2022 (edilizia), l'elenco prezzi sul D.M. 11/10/2017. Le soglie del D.M. 24.11.2025 non sono riportate in alcun elaborato (TBD): la baseline «minimi CAM» di C4.2 è indeterminata. Quesito Q2 alla SA proposto in [[economic_framework]] §10.1. <!-- confidence: verificato -->
2. **Cartongesso.** L'elenco prezzi già prevede riciclato > 20% (DM 2017), sopra il minimo del capitolato (≥ 10%, ≥ 5% se a base gesso, DM 2022): il livello «oltre i minimi» va misurato rispetto a quale dei due riferimenti è da chiarire. <!-- confidence: verificato sui valori; implicazione inferita -->
3. **Demolizione selettiva.** Il capitolato richiede la stima a progetto della quota ≥ 70%; la relazione CAM non la fornisce. <!-- confidence: verificato -->
4. **«Elaborato B3».** Il disciplinare cita una relazione CAM con questo codice; l'elenco [[G-00-ESEC-01_ELENCO_ELABORATI]] non lo contiene e la relazione CAM è G-09 (nota N11). <!-- confidence: verificato -->

## Rilevanza per i criteri

- [[C4]] — C4.2: tutti i quattro elementi premianti (EPD su cartongesso/silicati/isolanti, FSC/PEFC, VOC A+, piano di economia circolare con monitoraggio) sono privi di quantificazione nel progetto; il perimetro fisico è dato dalle voci 8, 10-13 e dalle rimozioni del computo.
<!-- confidence: inferito per l'implicazione; verificato per i fatti -->
