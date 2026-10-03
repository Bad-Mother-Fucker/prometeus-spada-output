---
type: document
subtype: computo_metrico
gara: "Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)"
date: 2026-10-03
ai-first: true
codice: "G-04-ESEC-02"
file: "G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO.pdf"
file_originale: "00_input/p7m/progetto.esecutivo.a.base.di.gara/Progetto esecutivo_Integrazione 2026/G_04_ESEC_02_COMPUTO METRICO ESTIMATIVO.PDF.p7m"
section: "G"
version_group: "G-04"
is_latest: true
status: estratto
extracted_md: "01_extracted/text/G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO.md"
pagine: 35
data_elaborato: "maggio 2026 (cartiglio); computo datato 14/05/2026 (p. 27)"
copertura_lettura: "integrale pp. 1-35; 139 voci estratte con parser e riconciliate al centesimo con i riepiloghi del documento (super-categorie p. 24, categorie p. 25, TOL p. 26, categorie SOA p. 27)"
confidence: verificato
cost_summary:
  totale_eur: 381364.99            # confidence: verificato, "T O T A L E euro" p. 23 e riepiloghi pp. 24-27
  voci_count: 139                  # confidence: verificato, righe di computo n. 1-139 (123 codici distinti)
  codici_distinti: 123             # confidence: verificato (104 tariffa + 19 NP)
  voci_np: 20                      # confidence: verificato, 19 codici NP (NP 16_D.02.083 usato 2 volte)
  importo_np_eur: 143667.94        # confidence: verificato, somma voci NP = 37,67% del totale
  importo_tariffa_eur: 237697.05   # confidence: verificato
  forniture_arredo_eur: 55296.43   # confidence: verificato, super-categoria 005 ARREDO p. 24
supports_criteria:
  - { criterion: "[[C1]]", priority: alta, reason: "Baseline 'minimi di progetto' dei tre sub: C1.1 voce 35 (B.18.071.03) 18,66 mq di serramenti PVC con Uw 0,90-1,09 W/m²K, Uf ≤ 1,4, Rw ≤ 37 dB (specifiche complete in G-02), voci 34/37/46; C1.2 voce 102 (NP 05) 134 poltrone 'Operapulia art. 310 Social' + voce 101 rimozione di 120 esistenti, nessuna scorta né garanzia indicate; C1.3 voce 103 (NP 12) 85,15 mq di pannelli MDF/acustici 'a scelta della D.L.' senza prestazioni acustiche, voce 104 doghe legno, voce 28 rimozione moquette 275 mq sostituita da resina (voci 32-33)" }
  - { criterion: "[[C2]]", priority: alta, reason: "C2.1: categoria Impianto Fotovoltaico (voci 67-88, 27.040,58 €) con 13 moduli 450 Wp total black (5,85 kWp) su 'sistema di montaggio semi-integrato' e inverter 6 kW — FV non BIPV; C2.3: voce 78 (R.01.020.01) accumulo di 15 kWh — coerente con RS-01/RS-00 (15 kWh) ma non con la relazione generale G-08 (4 batterie / 20 kWh), rilevante per la nota N5 '>20 kWh' — e voce 66 (NP 14) Building Automation a corpo; C2.2: nessuna voce di antintrusione o TVCC nel computo (miglioria interamente integrativa)" }
  - { criterion: "[[C3]]", priority: alta, reason: "C3.1: voci 1-6 rifacimento impermeabilizzazione (membrana poliureica su bituminosa, 360,51 mq tra cupola, terrazzi, torrette) senza alcuno strato di isolamento termico; voce 7 (NP 11) pellicola antisolare 22 mq sulla cupola; C3.2: voce 105 (NP 07) palco e allestimento scenografico 16.000 € (sipario, fondale, americana 7,50 m con luci) come 'configurazione base'; C3.3: nessuna voce per smontaggio/stoccaggio/rimontaggio di audio, proiettori e schermo esistenti" }
  - { criterion: "[[C4]]", priority: alta, reason: "C4.1: voci 96-98 ascensore idraulico EN 81-2 da 8 persone, cabina 1,45 mq, corsa 18 m, 6 fermate, bottoniere Braille, sovrapprezzo velocità 0,80 m/s, impianto elettrico vano (NP 04) — nessun telecontrollo, sintesi vocale o requisito acustico; C4.2: voci 10-13 cartongesso/silicati (quantità su cui misurare il riciclato EPD), voce 8 (NP 09) taglio solaio 3,24 mq 'in assenza di polveri e vibrazioni', voci di rimozione e conferimento CER 17 06 04 / 17 04 05 / 17 03 03 (perimetro del piano di economia circolare)" }
  - { criterion: "[[C5]]", priority: bassa, reason: "Definisce l'oggetto dell'intervento (antincendio, efficientamento, ascensore, arredo di sala) rispetto al quale la commissione valuta l'analogia degli interventi pregressi del sub 5.1" }
related_documents:
  - { doc: "[[G-04-ESEC-01_COMPUTO_METRICO_ESTIMATIVO]]", type: versione_precedente, confidence: verificato, reason: "Revisione aprile 2026 superata (is_latest: false): voci, prezzi e totale identici, senza riepiloghi TOL/SOA ne' Allegato I" }
  - { doc: "[[G-08-ESEC-01_RELAZIONE_GENERALE]]", type: computo_di, confidence: verificato, reason: "Il computo misura le lavorazioni descritte nella relazione generale (par. 5 pp. 14-18: impermeabilizzazione, caldaia, LED, infissi, FV/accumulo, ascensore, poltrone); difformita' note: accumulo 15 vs 20 kWh, ascensore 8 pers./6 fermate/18 m vs 6/3/9 m" }
  - { doc: "[[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]]", type: referenced_by, confidence: verificato, reason: "Il capitolato G-06-ESEC-02 lo richiama come computo metrico estimativo, subordinato all'elenco prezzi (Art. 2.2, p. 8)" }
  - { doc: "[[G-01-ESEC-02_QUADRO_ECONOMICO]]", type: stesso_lotto, confidence: verificato, reason: "Sezione G, computo / quadro economico: il totale del computo (381.364,99 €) e' la riga A1 del QE; l'Allegato I giustifica B6 accantonamento 5.000 € (derivazione TBD)" }
  - { doc: "[[G-02-ESEC-01_ELENCO_PREZZI]]", type: stesso_lotto, confidence: verificato, reason: "Sezione G, computo / elenco prezzi: 122 codici su 122 con prezzo identico; l'elenco riporta il testo completo delle voci troncate nel computo (es. Nr. 24 serramenti, NP 05 poltrone)" }
  - { doc: "[[G-03-ESEC-01_ANALISI_NUOVI_PREZZI]]", type: stesso_lotto, confidence: verificato, reason: "Sezione G, computo / analisi nuovi prezzi: 5 NP analizzati (63.401,75 € nel computo), 14 codici NP senza analisi (80.266,19 €)" }
  - { doc: "[[G-05-ESEC-01_QUADRO_INCIDENZA_MANODOPERA]]", type: stesso_lotto, confidence: verificato, reason: "Sezione G, computo / quadro manodopera: stessi 123 codici e importi (unica differenza q.ta' B.18.071.10 a prezzo zero); manodopera 47.849,85 € = 12,547%, nulla sulle voci NP" }
---

# G-04-ESEC-02 — Computo metrico estimativo (revisione maggio 2026)

## Per Claude futuro

Questo è il computo metrico estimativo G-04-ESEC-02 della gara «Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)» (CIG BCF01395AF). Descrizione ufficiale: «COMPUTO METRICO ESTIMATIVO» (voce G-04-ESEC-01 di [[G-00-ESEC-01_ELENCO_ELABORATI]]; la revisione ESEC-02 è successiva all'elenco, cartella «Integrazione 2026»). **Aggiorna [[G-04-ESEC-01_COMPUTO_METRICO_ESTIMATIVO]] (is_latest: false).** Modifiche rispetto alla versione precedente: stesse 139 voci con stessi prezzi e importi (totale invariato 381.364,99 €); unica differenza di voce è la n. 37 (B.18.071.10, quantità 11,40 → 0,00, importo 0 in entrambe); ESEC-02 aggiunge il riepilogo per sub-categorie TOL (p. 26), il riepilogo per categorie SOA (p. 27) e l'Allegato I «Relazione tecnica di revisione ed aggiornamento prezzi» (pp. 28-35). Contiene tutte le lavorazioni a misura (non ci sono lavori a corpo o in economia), organizzate in 6 super-categorie e 19 categorie. È la **fonte della tabella lavorazioni di [[scope]]** e dei riparti di [[economic_framework]]. Confidence: verificato (parser riconciliato al centesimo con tutti i riepiloghi del documento).

## Contenuto chiave

### Totali e riepiloghi (pp. 23-27)

| Dato | Valore | Fonte | Confidence |
|---|---|---|---|
| Totale lavori a misura (soggetti a ribasso) | 381.364,99 € | p. 23 «T O T A L E euro» | verificato |
| N. voci / codici distinti | 139 / 123 (104 tariffa + 19 NP) | conteggio voci n. 1-139 | verificato |
| Voci NP (nuovi prezzi) | 20 righe, 19 codici, 143.667,94 € (37,67%) | somma voci NP | verificato |
| Voci da tariffa | 119 righe, 104 codici, 237.697,05 € (62,33%) | somma voci non NP | verificato |
| Oneri sicurezza | non nel computo (stima separata [[SIC-03-ESEC-01_COSTI_PER_LA_SICUREZZA]]) | — | verificato |
| Data computo | 14/05/2026 | p. 27 | verificato |

**Super-categorie (p. 24) e corrispondenza con le categorie SOA (p. 27):**

| Super-categoria | Importo € | % | Categoria SOA (p. 27) | di cui NP € |
|---|---|---|---|---|
| 001 LAVORI EDILI | 130.094,30 | 34,113 | OG1 (insieme ad ARREDO) | 13.308,48 |
| 002 ADEGUAMENTO IMPIANTO ELETTRICO | 34.285,65 | 8,990 | OS30 34.285,65 | 14.026,56 |
| 003 EFFICIENTAMENTO ENERGETICO | 41.600,21 | 10,908 | OG9 41.600,21 | 4.138,34 |
| 004 IMPIANTO DI SOLLEVAMENTO | 43.512,19 | 11,410 | OS4 43.512,19 | 3.000,00 |
| 005 ARREDO | 55.296,43 | 14,500 | OG1 (130.094,30 + 55.296,43 = 185.390,73) | 55.296,43 |
| 006 ANTINCENDIO | 76.576,21 | 20,080 | OS3 76.576,21 | 53.898,13 |
| **Totale** | **381.364,99** | 100 | | 143.667,94 |

La corrispondenza super-categoria → SOA è ricavata dall'uguaglianza esatta degli importi (il documento non la dichiara riga per riga): confidence `inferito` sull'abbinamento, `verificato` sugli importi. Nota: la caldaia (categoria 011) è dentro EFFICIENTAMENTO ENERGETICO e quindi in OG9 «Impianti per la produzione di energia elettrica»; IRAI ed evacuazione fumi sono in ANTINCENDIO e quindi in OS3.

**Categorie (p. 25):** 19 capitoli — Impermeabilizzazioni 27.028,51; Oscuramento cupola 770,00; Opere strutturali 6.416,00; Opere in cartongesso 30.417,58; Tinteggiatura 12.883,06; Pavimentazione 23.297,78; Infissi 22.530,17; Impianto idrico 3.000,00; Impianto elettrico 34.285,65; Impianto Fotovoltaico 27.040,58; Impianto di Riscaldamento - Caldaia 14.559,63; Ascensore - impianto elettrico vano ascensore 43.512,19; Poltrone 32.123,18; Palco e allestimento scenografico 23.173,25; Impianto IRAI 10.888,76; Estintori 2.429,22; Opere da fabbro 3.751,20; Idrico antincendio 12.424,84; Impianto aspirazione forzata fumi e calore 50.833,39. Dettaglio con n. voci e quota NP in [[economic_framework]] §5.

**Sub-categorie TOL (p. 26):** TOL1 170.213,53; TOL4 7.637,69; TOL5 1.500,00; TOL6 9.050,40; TOL14 126.144,57; TOL15 66.292,71; TOL20 526,09 (totale 381.364,99).

### Voci rilevanti come baseline dei criteri

| Voce | Codice | Contenuto | Q.tà | Importo € | Sub-criterio |
|---|---|---|---|---|---|
| 35 | B.18.071.03 | Serramenti PVC (porte di emergenza, finestroni, finestra) — specifiche in [[G-02-ESEC-01_ELENCO_PREZZI]]: Uw 0,90-1,09 W/m²K, Uf ≤ 1,4 W/m²K, Rw ≤ 37 dB, g 50-60%, vetrocamera 33.1 BE + 33.1 con argon e warm edge, posa UNI 11673 | 18,66 mq | 9.743,69 | C1.1 |
| 102 | NP 05 | Poltrone «Operapulia art. 310 Social», ignifughe classe 1 | 134 cad | 30.923,18 | C1.2 |
| 103 | NP 12 | Pannelli da parete MDF / acustici / 3D «a scelta della D.L.» | 85,15 mq | 4.683,25 | C1.3 |
| 70, 72-77 | R.01.022.07, R.01.011.xx, R.01.023.03 | 13 moduli 450 Wp total black (5,85 kWp), montaggio «semi-integrato», inverter 6 kW trifase | — | 9.919,27 | C2.1 |
| 78 | R.01.020.01 | Accumulo agli ioni di litio | 15 kWh | 13.167,45 | C2.3 |
| 66 | NP 14 | Building Automation (hardware + app per riscaldamento, ACS, climatizzazione, illuminazione) | 1 a corpo | 4.000,00 | C2.3 |
| 1-6 | NP 03, B.10.xxx, B.21.xxx | Impermeabilizzazione poliureica su membrana bituminosa di cupola, terrazzi, torrette, locale caldaia — nessun isolante termico | 360,51 mq | 27.028,51 | C3.1 |
| 7 | NP 11 | Pellicola antisolare sulla cupola (92% energia solare respinta) | 22 mq | 770,00 | C3.1 |
| 105 | NP 07 | Palco (~7 mq) e allestimento scenografico: stangoni, sipario, fondale, tenda, americana 7,50 m con luci | 1 a corpo | 16.000,00 | C3.2 |
| 96-98 | D6.01.008.03, D6.01.010.01, NP 04 | Ascensore idraulico 8 persone, cabina 1,45 mq, corsa 18 m, 6 fermate, Braille; velocità 0,80 m/s; impianto elettrico vano | — | 41.969,92 | C4.1 |
| 8 | NP 09 | Taglio solaio con disco diamantato, senza polveri e vibrazioni (botola 1,80x1,80) | 3,24 mq | 2.916,00 | C4.2 |
| 10-13 | B.08.007.01, B.08.027.01, B.08.038.01, B.08.037.01 | Controsoffitto 200 mq, controparete 100 mq, parete REI 60 in silicato 14,61 mq, parete EI120 39 mq | — | 19.670,57 | C4.2 |

**Assenze verificate** (ricerca nel computo e nell'elenco prezzi): nessuna voce di isolamento termico in copertura (C3.1), di antintrusione/videosorveglianza/TVCC (C2.2), di attrezzature audio/video/proiezione/schermo né di loro smontaggio e protezione (C3.2, C3.3).

### Allegato I — Relazione tecnica di revisione ed aggiornamento prezzi (pp. 28-35)

- Scopo: indice sintetico revisionale di progetto (Is) per gli accantonamenti di revisione prezzi ex art. 60 e All. II.2-bis D.Lgs. 36/2023 (p. 29).
- Pesi TOL su 381.364,99 €: TOL1 44,63%, TOL14 33,07%, TOL15 17,38%; escluse dal calcolo le TOL < 4% (TOL4, TOL5, TOL6, TOL20) (pp. 30-32).
- Is aprile 2025 = 97,89; Is febbraio 2026 = 98,10; ΔIs = +0,21 (p. 33). Revisione riconosciuta al 90% della parte eccedente il 3% (p. 34).
- Collegamento: giustifica la nuova voce B6 «accantonamento adeguamento prezzi» 5.000,00 € del QE [[G-01-ESEC-02_QUADRO_ECONOMICO]] (assente in ESEC-01). Il documento non calcola esplicitamente l'importo di 5.000 €: TBD la derivazione.

### Anomalie di contenuto

- Voce 37 (B.18.071.10, sovrapprezzo serramenti PVC rivestiti bicolore 60,96%): quantità 0,00, prezzo 0,00, importo 0,00 — voce «morta»; in ESEC-01 e in [[G-05-ESEC-01_QUADRO_INCIDENZA_MANODOPERA]] ha quantità 11,40 (sempre a prezzo 0). Il codice non compare nell'elenco prezzi G-02.
- Voci 89 e 93: codice reso su due righe nel PDF («NP 16_D.02» + «083»), qui normalizzato «NP 16_D.02.083»: è manodopera pura (operaio impiantista C3, 96 h × 25,71 €/h = 2.468,16 €) contabilizzata come NP.
- Voce 128: codice «E.00050» (sabbia di cava, 35 €/m³) con struttura diversa dagli altri codici di tariffa, non marcato NP e senza analisi: origine del prezzo TBD.
- Forfettari dentro i lavori «a misura»: il QE dichiara 0,00 € di lavori a corpo, ma 11 righe hanno u.m. «a corpo» o «cadauno» con quantità 1 e prezzo forfettario, per 130.064,79 € complessivi (es. voce 139 NP 005 50.833,39 €, voce 96 D6.01.008.03 36.876,70 €, voce 105 NP 07 16.000,00 €); 9 di queste 11 sono NP.

## Contraddizioni rilevate (Fase E, 2026-10-03)

Questo computo (`is_latest: true`) è la fonte prevalente tra le pagine coinvolte (gerarchia: computo/QE > relazioni > tavole; l'elenco prezzi [[G-02-ESEC-01_ELENCO_PREZZI]] prevale sul computo per le descrizioni, capitolato art. 2.2). Registro completo, fonti e testi dei quesiti in [[economic_framework]] §10-§10.1.

| # | Tema | Valore in questo computo | Valore in conflitto (fonte, pag.) | Prevale | Stato |
|---|---|---|---|---|---|
| D13 | Capacità di accumulo (C2.3) | voce 78 R.01.020.01: **15 kWh**, ioni di litio (p. 15) | **20 kWh / 4 batterie**: [[G-08-ESEC-01_RELAZIONE_GENERALE]] pp. 15, 24; [[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]] p. 9; [[RS-03-ESEC-01_RELAZIONE_ACUSTICA]] p. 9; [[G-09-ESEC-01_RELAZIONE_CAM]] pp. 14, 16. Batterie «al piombo acido»: [[G-10-ESEC-01_PIANO_DI_MANUTENZIONE]] p. 30 | questo computo (15 kWh), concorde con [[RS-01-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_FOTOVOLTAICO]] p. 7, [[RS-00-ESEC-01_RELAZIONE_TECNICA_IMPIANTI]] p. 11 e tavola [[PI-00-ESEC-01_PROGETTO_IMPIANTO_FOTOVOLTAICO]] (3 moduli, 15 kWh) | irrisolta per la soglia «>20 kWh» del sub 2.3 → quesito SA Q1 |
| D14 | Ascensore (C4.1) | voce 96 D6.01.008.03 (p. 17): idraulico (oleoelettrico) EN 81-2, 8 persone, cabina 1,45 mq; testo integrale in G-02 Nr. 87: corsa 18 m, 6 fermate, 0,50-0,60 m/s; voce 97: velocità fino a 0,80 m/s | 6 persone, 3 fermate, corsa 9 m, 0,63 m/s: G-08 p. 17, SIC-00 p. 10; «ascensore elettrico a fune»: [[SIC-01-ESEC-01_CRONOPROGRAMMA]] p. 2, SIC-00 p. 48 | tipo idraulico: disciplinare sub 4.1 + questo computo; caratteristiche: formalmente elenco prezzi/computo, ma la voce è la descrizione standard di tariffa e l'edificio ha 3 livelli (G-08 pp. 10-12) | irrisolta → quesito Q3 / sopralluogo |
| D15 | Antincendio | voci 118-138 (pp. 20-21): 4 «cassette da interno per idranti ... UNI 45» con manichetta 20 m misurate «naspi» (voce 122); 1 idrante sottosuolo DN70 misurato «idrante esterno a colonna» (voce 119); attacco motopompa VV.F. (voce 120); **nessuno sprinkler** | «impianti sprinkler»: G-08 p. 23, RS-03 p. 8, G-09 pp. 14-15; solo 4 naspi DN25 UNI EN 671-1 senza protezione esterna: [[RS-02-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_IDRICO_ANTINCENDIO]] pp. 10-11, 15 | sprinkler esclusi (nessuna fonte prevalente li prevede); quantità: questo computo; tipologia dei terminali interni: naspi DN25 (RS-02, PI-06, pratica VV.F.) | risolta per gli sprinkler; UNI 45 / DN25 da chiarire con la DL (nessun quesito) |
| D17 | FV e generatore di calore | voce 70: 13 × 450 Wp = 5,85 kWp; voce 77: inverter 6 kW; voce 92: caldaia a condensazione 91-115 kW | «impianto fotovoltaico da 6 kWh» e «pompe di calore»: G-08 p. 24, RS-03 pp. 8-9, G-09 pp. 14-16 | questo computo | risolta (errore di unità e testo descrittivo comune) |
| D18 | Poltrone (C1.2) | voce 102 NP 05: **134** poltrone; voce 101: rimozione di 120 esistenti | 134 = platea 53 + 54 (G-08 p. 20) + galleria 27: coerente. Tavole (livello di testo): 128 = 53 + 48 ([[VVF-PI-03-00_PIANTA_PIANO_PRIMO]]) + 27 ([[VVF-PI-04-00_PIANTA_PIANO_SECONDO]]), pratica VV.F. approvata; platea 102 ([[PI-03-ESEC-01_PROGETTO_IMPIANTO_IRAI]]); 54 + 49 + 27 = 130 ([[PI-05-ESEC-01_INTERVENTI_ELETTRICI]]) | questo computo per la fornitura (134); pratica VV.F. per l'affollamento (128) | parziale → quesito Q4 / sopralluogo |

Confidence: verificato sui testi estratti; parziale per i valori letti dal livello di testo delle tavole.

## Riferimenti a altri elaborati

- Nessun codice di altro elaborato citato nel testo. Riferimenti interni: «Vedi voce n° 12» (voce 71 → voce 69, perforazioni), storia revisioni nel cartiglio (G-04-ESEC-00 febbraio 2025 — non presente in `00_input`; G-04-ESEC-01 aprile 2026; G-04-ESEC-02 maggio 2026).
- Per Fase D (archi strutturali, non citazioni): stesso `version_group` di [[G-04-ESEC-01_COMPUTO_METRICO_ESTIMATIVO]]; prezzi da [[G-02-ESEC-01_ELENCO_PREZZI]] e [[G-03-ESEC-01_ANALISI_NUOVI_PREZZI]]; manodopera in [[G-05-ESEC-01_QUADRO_INCIDENZA_MANODOPERA]]; totale riportato in A1 di [[G-01-ESEC-02_QUADRO_ECONOMICO]].
