---
type: scope
gara: "Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)"
date: 2026-10-03
ai-first: true
fonte_lavorazioni: "[[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]]"
fonte_specifiche: ["[[G-02-ESEC-01_ELENCO_PREZZI]]", "[[G-03-ESEC-01_ANALISI_NUOVI_PREZZI]]"]
fonte_vincoli: ["[[C1]]", "[[C2]]", "[[C3]]", "[[C4]]", "[[C5]]", "[[C6]]", "[[C7]]", "03_criteria/criteria_matrix.md — Vincoli trasversali", "disciplinare artt. 3, 16, 18.1, 22, 23"]
voci_count: 139             # confidence: verificato
voci_np: 20                 # confidence: verificato (19 codici)
voci_tariffa: 119           # confidence: verificato (104 codici)
totale_lavori_eur: 381364.99  # confidence: verificato
confidence: verificato
---

# Scope — perimetro del progetto e limiti di modifica

## Per Claude futuro

Perimetro dei lavori a base di gara del Cineteatro «Periz» nel Castello di Bella (CIG BCF01395AF), ricavato **dall'ultima revisione del computo** [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] (139 voci, 381.364,99 €, tutte a misura) con le specifiche complete prese dall'elenco prezzi [[G-02-ESEC-01_ELENCO_PREZZI]]. La §4 elenca **tutte** le 139 voci con codice tariffa, origine del prezzo (20 righe NP / 119 da tariffa regionale), u.m., quantità, prezzo, importo, capitolo, categoria SOA e — dove pertinente — il sub-criterio di cui la voce costituisce la baseline. La §2 dice per ciascun sub-criterio cosa il progetto già prevede e cosa no; la §6 riporta i limiti di modifica del disciplinare (dai campi `modification_limits` e `fuori_scope_risks` delle pagine criterio). Cornice economica in [[economic_framework]]. Confidence: verificato (voci riconciliate al centesimo con i riepiloghi del computo).

## Regola d'uso per gli agenti

1. **Una proposta migliorativa è ammissibile solo se migliora o integra il perimetro descritto qui senza stravolgerlo** (nessuna variante: stesse opere, stesse quantità minime, stessa destinazione). Prima di proporre, individua nella §4 le voci di progetto su cui la miglioria agisce e citale per numero e codice (es. «voce 35, B.18.071.03»).
2. La **baseline** di un sub-criterio è ciò che il progetto prevede (colonna «Baseline criterio» e §2): la miglioria deve superarla con un indicatore misurabile (es. Uw < 0,90 W/m²K, accumulo > 15 kWh).
3. Se un elemento è nella lista «non previsto» della §2, la miglioria è **integrativa** (va descritta per intero, con quantità, nel computo metrico non estimativo).
4. Mai riportare prezzi, importi o percentuali di questa pagina nei documenti dell'offerta tecnica: **pena l'esclusione** (disciplinare art. 16 p. 26; art. 22 p. 33). Le quantità e le unità di misura si possono usare.
5. Le colonne «SOA» e «Baseline criterio» sono `inferito`; tutte le altre colonne della §4 sono `verificato`.

## 1. Perimetro in sintesi

| Dato | Valore | Fonte | Confidence |
|---|---|---|---|
| Oggetto | Adeguamento (antincendio, impianti, accessibilità) ed efficientamento energetico del cineteatro nel Castello di Bella, con fornitura di arredo di sala | disciplinare art. 3; computo | verificato |
| Forma | solo lavori a misura (corpo ed economia = 0) | QE G-01-ESEC-02 A1-A3 | verificato |
| Importo lavori | 381.364,99 € (+ 13.005,47 € sicurezza) | computo p. 23; SIC-03 | verificato |
| Struttura | 6 super-categorie, 19 capitoli, 139 voci, 123 codici | computo pp. 24-25 | verificato |
| Durata | 150 giorni naturali e consecutivi, comprese forniture e posa | disciplinare art. 3.1 p. 8 | verificato |
| Super-categorie | Lavori edili 130.094,30 · Imp. elettrico 34.285,65 · Efficientamento energetico 41.600,21 · Sollevamento 43.512,19 · Arredo 55.296,43 · Antincendio 76.576,21 | computo p. 24 | verificato |

## 2. Baseline di progetto per sub-criterio

| Sub | Cosa prevede il progetto (voci della §4) | Cosa NON è previsto | Confidence |
|---|---|---|---|
| C1.1 Infissi | Voce 35 B.18.071.03: 18,66 mq di serramenti PVC (3 porte di emergenza, finestroni con ante apribili e fisse, una finestra) con **Uw 0,90-1,09 W/m²K, Uf ≤ 1,4 W/m²K, Rw ≤ 37 dB**, g 50-60%, vetrocamera 33.1 BE + 33.1 con argon e warm edge, **posa UNI 11673**; voce 34 rimozione serramenti in ferro 12,79 mq; voce 46 motorizzazione di 3 serramenti asserviti all'IRAI; voce 37 PVC bicolore a quantità 0 | nessuna voce dedicata al nodo di posa oltre alla posa UNI 11673 compresa nel prezzo; nessuna superficie vetrata aggiuntiva | verificato |
| C1.2 Poltrone | Voce 102 NP 05: **134 poltrone** Operapulia «art. 310 Social» (poliuretano 35 kg/m³ ignifugo classe 1, ribaltamento a contrappeso, fiancate multistrato, braccioli in faggio); voce 101 rimozione di 120 poltrone esistenti. **Fase E (D18):** 134 = platea 53 + 54 (G-08 p. 20) + galleria 27, ma le tavole della pratica VV.F. approvata riportano 128 posti (53 + 48 + 27) e PI-03/PI-05 102 e 103 posti di platea: quantità di riferimento da confermare (quesito SA Q4, [[economic_framework]] §10) | nessuna scorta di rispetto; nessuna garanzia indicata (garanzia base TBD) | verificato (computo); parziale (tavole) |
| C1.3 Acustica | Voce 103 NP 12: **85,15 mq** di pannelli MDF / acustici / 3D «a scelta della D.L.»; voce 104 doghe in legno 415 m; voce 28 rimozione moquette 275 mq sostituita da pavimento in resina (voci 32-33, 182,5 mq) | nessuna prestazione acustica dichiarata (αw, tempo di riverbero) nelle voci | verificato |
| C2.1 FV | Voci 67-88 (27.040,58 €): **13 moduli da 450 Wp total black = 5,85 kWp** su «sistema di montaggio semi-integrato» (profili alluminio 47x37, staffe, graffe), inverter 6 kW trifase, quadri e protezioni, cavi | nessun sistema BIPV integrato (tegole/coppi FV o simili). Le relazioni dichiarano «impianto da 6 kW» sul tetto piano, con limite «imposto dallo spazio a disposizione sul tetto terrazzato» (RS-01 p. 2; G-08 p. 14): il computo paga 5,85 kWp di moduli e un inverter da 6 kW. Tavola di riferimento per la miglioria: [[PI-00a-ESEC-01_PLANIMETRIA_DI_INSIEME_CON_FOTOVOLTAICO_INTEGRATO_E_FOTOINSERIMENTI]] | verificato |
| C2.2 Antintrusione / TVCC | — | **nessuna voce** di antintrusione, allarme perimetrale/volumetrico o videosorveglianza nel computo e nell'elenco prezzi | verificato |
| C2.3 Accumulo e BA | Voce 78 R.01.020.01: **accumulo 15 kWh**; voce 66 NP 14: Building Automation a corpo (hardware + app per riscaldamento, ACS, climatizzazione, illuminazione); voce 60 NP 002 revisione quadro elettrico | capacità oltre 15 kWh. **Discordanza tra elaborati sulla baseline**: computo voce 78 = 15 kWh e [[RS-01-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_FOTOVOLTAICO]] p. 7 = 3 batterie / 15 kWh, [[RS-00-ESEC-01_RELAZIONE_TECNICA_IMPIANTI]] p. 11 = 4 batterie / 15 kWh, ma [[G-08-ESEC-01_RELAZIONE_GENERALE]] pp. 15 e 24 = 4 batterie / **20 kWh**. La quantità contrattuale è quella del computo (15 kWh); la soglia «>20 kWh» del sub (nota N5) coincide con il valore della relazione generale. **Fase E (D13):** 15 kWh confermato anche dalla tavola PI-00 (3 moduli, 15 kWh); 20 kWh anche in PSC p. 9, RS-03 p. 9, G-09 pp. 14, 16 — quesito SA Q1, [[economic_framework]] §10 | verificato |
| C3.1 Copertura e cupola | Voci 1-6: rimozione materiale arido, primer e **impermeabilizzazione poliureica su membrana bituminosa** di cupola (96,45 mq), terrazzi 1-4, torrette, locale caldaia (360,51 mq totali), trattamento delle parti metalliche; voce 7 NP 11: **pellicola antisolare 22 mq** sulla cupola | **nessuno strato di isolamento termico** in copertura; nessuna schermatura esterna della cupola | verificato |
| C3.2 Dotazioni cinematografiche | Voce 105 NP 07: palco (~7 mq), 2 stangoni, sipario di boccascena ignifugo, fondale, tenda d'ingresso, **americana 7,50 m con luci** (16.000 €); voce 58: 14 plafoniere LED indicate come «proiettori» | nessun proiettore cinematografico, impianto audio, schermo o arredo tecnico multimediale | verificato |
| C3.3 Protezione attrezzature esistenti | Solo voce 101 (rimozione e deposito in cantiere delle poltrone); apprestamenti di cantiere in [[SIC-03-ESEC-01_COSTI_PER_LA_SICUREZZA]] | nessuna voce di smontaggio, imballaggio, stoccaggio e rimontaggio/taratura di audio, proiettori e schermo esistenti; nessun deposito protetto | verificato |
| C4.1 Ascensore | Voce 96 D6.01.008.03: ascensore oleodinamico EN 81-2, **8 persone, cabina 1,45 mq**, corsa 18 m, 6 fermate, bottoniere antivandalo con caratteri Braille, telefono in cabina; voce 97 velocità fino a 0,80 m/s; voce 98 NP 04 impianto elettrico vano; voci 99-100 tinteggiatura vano. **Fase E (D14):** [[G-08-ESEC-01_RELAZIONE_GENERALE]] p. 17 e PSC p. 10 descrivono invece 6 persone, 3 fermate, corsa 9 m, 0,63 m/s (l'edificio ha 3 livelli); la voce 96 è la descrizione standard di tariffa; cronoprogramma e PSC p. 48 parlano di ascensore «elettrico a fune». Baseline da confermare (quesito SA Q3, [[economic_framework]] §10) | telecontrollo, sintesi vocale, Braille «avanzato», requisito di isolamento acustico della cabina | verificato |
| C4.2 CAM ed economia circolare | Voci 10-13: controsoffitto 200 mq, controparete 100 mq, parete REI 60 in calcio silicato + lana di roccia 14,61 mq, parete EI120 39 mq — le voci di cartongesso richiamano i CAM DM 11/10/2017 con **riciclato > 20%**; voce 8 NP 09 taglio solaio 3,24 mq «senza polveri e vibrazioni»; rimozioni (moquette 275 mq, serramenti, radiatori, caldaia) e conferimenti CER 17 06 04 / 17 04 05 / 17 03 03. **Fase E (D11):** «minimi CAM» da superare indeterminati — D.M. 24.11.2025 (disciplinare) vs D.M. 23/06/2022 (capitolato Cap. 5: ≥ 10%, ≥ 5% se a base gesso; G-09) vs DM 11/10/2017 (elenco prezzi: > 20%) — quesito SA Q2, [[economic_framework]] §10 | percentuali EPD superiori, legno FSC/PEFC, materiali Classe A+, piano di economia circolare e monitoraggio polveri/vibrazioni | verificato |
| C5-C7 | Non pertinenti al computo (requisiti dell'operatore economico) | — | verificato |

## 3. Riepilogo per capitolo

| Capitolo | Super-categoria | SOA | Voci | Righe NP | Righe tariffa | Importo € |
|---|---|---|---|---|---|---|
| Impermeabilizzazioni | Lavori edili | OG1 | 1-6 | 1 | 5 | 27.028,51 |
| Oscuramento cupola | Lavori edili | OG1 | 7 | 1 | 0 | 770,00 |
| Opere strutturali | Lavori edili | OG1 | 8-9 | 2 | 0 | 6.416,00 |
| Opere in cartongesso | Lavori edili | OG1 | 10-17 | 0 | 8 | 30.417,58 |
| Tinteggiatura (incl. radiatori) | Lavori edili | OG1 | 18-27 | 0 | 10 | 12.883,06 |
| Pavimentazione | Lavori edili | OG1 | 28-33 | 0 | 6 | 23.297,78 |
| Infissi | Lavori edili | OG1 | 34-46 | 0 | 13 | 22.530,17 |
| Impianto idrico | Lavori edili | OG1 | 47 | 1 | 0 | 3.000,00 |
| Opere da fabbro | Lavori edili | OG1 | 48-50 | 1 | 2 | 3.751,20 |
| Impianto elettrico | Adeguamento impianto elettrico | OS30 | 51-66 | 3 | 13 | 34.285,65 |
| Impianto Fotovoltaico | Efficientamento energetico | OG9 | 67-88 | 0 | 22 | 27.040,58 |
| Impianto di Riscaldamento - Caldaia | Efficientamento energetico | OG9 | 89-95 | 3 | 4 | 14.559,63 |
| Ascensore - impianto elettrico vano | Impianto di sollevamento | OS4 | 96-100 | 1 | 4 | 43.512,19 |
| Poltrone | Arredo | OG1 | 101-102 | 2 | 0 | 32.123,18 |
| Palco e allestimento scenografico | Arredo | OG1 | 103-105 | 3 | 0 | 23.173,25 |
| Impianto IRAI | Antincendio | OS3 | 106-115 | 1 | 9 | 10.888,76 |
| Estintori | Antincendio | OS3 | 116-117 | 0 | 2 | 2.429,22 |
| Idrico antincendio | Antincendio | OS3 | 118-138 | 0 | 21 | 12.424,84 |
| Impianto aspirazione forzata fumi e calore | Antincendio | OS3 | 139 | 1 | 0 | 50.833,39 |
| **Totale** | | | **139** | **20** | **119** | **381.364,99** |

## 4. Tabella lavorazioni completa (computo G-04-ESEC-02)

Legenda «Origine prezzo»: **NP (analisi G-03)** = nuovo prezzo con analisi in [[G-03-ESEC-01_ANALISI_NUOVI_PREZZI]]; **NP (no analisi)** = nuovo prezzo senza analisi; **Tariffa reg.** = codice della tariffa Regione Basilicata (edizione non dichiarata; attribuzione `inferito` dalla struttura del codice); **Tariffa (assente in G-02)** = codice di tariffa non presente nell'elenco prezzi; **Tariffa? (cod. anomalo)** = codice non NP con formato diverso dalla tariffa. «N.» = numero progressivo della voce; «ID» = secondo numero della coppia «n / m» stampata nel computo (identificativo interno della voce nel file di computo: **non** coincide con il «Nr.» dell'elenco prezzi G-02). Le descrizioni sono sintesi del testo del computo e dell'elenco prezzi. Totale di controllo = 381.364,99 € (riconciliato).

| N. | ID | Codice | Origine prezzo | Descrizione sintetica | U.M. | Quantità | P.U. € | Importo € | Super-cat. / Categoria | SOA | Baseline criterio | Confidence |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | 55 | NP 03 | NP (no analisi) | Rimozione materiale arido dai terrazzi, trasporto e conferimento a discarica | m3 | 32,89 | 40,00 | 1.315,60 | Edili / Impermeabilizzazioni | OG1 | — | verificato |
| 2 | 56 | B.10.001.01 | Tariffa reg. | Primer antipolvere sul piano di posa del manto (cupola, terrazzi 1-4, torrette, locale caldaia) | mq | 360,51 | 3,17 | 1.142,82 | Edili / Impermeabilizzazioni | OG1 | C3.1 | verificato |
| 3 | 57 | B.10.028.01 | Tariffa reg. | Impermeabilizzazione pedonabile con membrana poliureica bicomponente su membrana bituminosa esistente | mq | 360,51 | 62,88 | 22.668,87 | Edili / Impermeabilizzazioni | OG1 | C3.1 | verificato |
| 4 | 58 | B.21.039.02 | Tariffa reg. | Pulitura meccanica superfici metalliche arrugginite (cupola, terrazzi) | mq | 70,13 | 5,64 | 395,53 | Edili / Impermeabilizzazioni | OG1 | — | verificato |
| 5 | 59 | B.21.046.03 | Tariffa reg. | Pittura antiruggine su opere metalliche (cupola, terrazzi) | mq | 70,13 | 8,07 | 565,95 | Edili / Impermeabilizzazioni | OG1 | — | verificato |
| 6 | 60 | B.21.047.03 | Tariffa reg. | Pittura di finitura smalto alchidico uretanico su opere metalliche (cupola, terrazzi) | mq | 70,13 | 13,40 | 939,74 | Edili / Impermeabilizzazioni | OG1 | — | verificato |
| 7 | 88 | NP 11 | NP (no analisi) | Pellicola antisolare nera/argento scuro su vetri della cupola (92% energia solare respinta) | mq | 22,00 | 35,00 | 770,00 | Edili / Oscuramento cupola | OG1 | C3.1 | verificato |
| 8 | 98 | NP 09 | NP (no analisi) | Taglio di solaio con disco diamantato, senza polveri e vibrazioni (botola scala interna 1,80x1,80) | mq | 3,24 | 900,00 | 2.916,00 | Edili / Opere strutturali | OG1 | C4.2 | verificato |
| 9 | 99 | NP 10 | NP (no analisi) | Scala a chiocciola quadrata Ø180 cm h 3 m, acciaio e gradini in faggio (accesso camerini) | a corpo | 1,00 | 3.500,00 | 3.500,00 | Edili / Opere strutturali | OG1 | — | verificato |
| 10 | 1 | B.08.007.01 | Tariffa reg. | Controsoffitto continuo in cartongesso standard, lastre 12,5 mm (CAM DM 11/10/2017 in tariffa) | mq | 200,00 | 53,10 | 10.620,00 | Edili / Opere in cartongesso | OG1 | C4.2 | verificato |
| 11 | 2 | B.08.027.01 | Tariffa reg. | Controparete in cartongesso a singolo paramento (cassonetti per cavidotti) | mq | 100,00 | 44,24 | 4.424,00 | Edili / Opere in cartongesso | OG1 | C4.2 | verificato |
| 12 | 3 | B.08.038.01 | Tariffa reg. | Parete antincendio REI 60 in calcio silicato + lana di roccia 50 mm (chiusura vano scala) | mq | 14,61 | 107,07 | 1.564,29 | Edili / Opere in cartongesso | OG1 | C4.2 | verificato |
| 13 | 4 | B.08.037.01 | Tariffa reg. | Parete divisoria in cartongesso EI120 doppio paramento sp. 125 mm (pareti e soffitto spazio calmo) | mq | 39,00 | 78,52 | 3.062,28 | Edili / Opere in cartongesso | OG1 | C4.2 | verificato |
| 14 | 5 | B.08.008.01 | Tariffa reg. | Rasatura completa a gesso del cartongesso | mq | 407,22 | 8,28 | 3.371,78 | Edili / Opere in cartongesso | OG1 | — | verificato |
| 15 | 6 | B.21.001.01 | Tariffa reg. | Paraspigoli in lamiera zincata/alluminio h 2,5 m (sola fornitura) | cad | 15,00 | 5,19 | 77,85 | Edili / Opere in cartongesso | OG1 | — | verificato |
| 16 | 7 | B.21.006.01 | Tariffa reg. | Pittura di fondo acrilica (superfici in cartongesso) | mq | 407,22 | 3,28 | 1.335,68 | Edili / Opere in cartongesso | OG1 | — | verificato |
| 17 | 8 | B.21.011.03 | Tariffa reg. | Tinteggiatura con idropittura traspirante tinte scure, tre mani (superfici in cartongesso) | mq | 407,22 | 14,64 | 5.961,70 | Edili / Opere in cartongesso | OG1 | — | verificato |
| 18 | 75 | B.21.002.01 | Tariffa reg. | Stuccatura saltuaria di superfici interne lisciate a gesso (rappezzi) | mq | 150,00 | 2,93 | 439,50 | Edili / Tinteggiatura | OG1 | — | verificato |
| 19 | 76 | B.21.003.01 | Tariffa reg. | Rasatura di superfici interne intonacate (WC, sala principale, parti comuni) | mq | 285,12 | 6,18 | 1.762,04 | Edili / Tinteggiatura | OG1 | — | verificato |
| 20 | 77 | B.21.006.01 | Tariffa reg. | Pittura di fondo acrilica (WC, camerini, sala principale, parti comuni) | mq | 512,05 | 3,28 | 1.679,52 | Edili / Tinteggiatura | OG1 | — | verificato |
| 21 | 78 | B.21.011.03 | Tariffa reg. | Tinteggiatura con idropittura traspirante tinte scure, tre mani (WC, camerini, sala, parti comuni) | mq | 512,05 | 14,64 | 7.496,41 | Edili / Tinteggiatura | OG1 | — | verificato |
| 22 | 79 | B.02.026.07 | Tariffa reg. | Rimozione radiatori fino a 6 elementi | cad | 22,00 | 8,26 | 181,72 | Edili / Tinteggiatura | OG1 | — | verificato |
| 23 | 80 | B.02.026.08 | Tariffa reg. | Rimozione radiatori: per ogni elemento in piu' | cad | 120,00 | 1,09 | 130,80 | Edili / Tinteggiatura | OG1 | — | verificato |
| 24 | 81 | B.21.039.01 | Tariffa reg. | Spazzolatura e carteggiatura manuale dei termosifoni | mq | 35,00 | 2,24 | 78,40 | Edili / Tinteggiatura | OG1 | — | verificato |
| 25 | 82 | B.21.046.03 | Tariffa reg. | Pittura antiruggine dei termosifoni | mq | 35,00 | 8,07 | 282,45 | Edili / Tinteggiatura | OG1 | — | verificato |
| 26 | 83 | B.21.047.03 | Tariffa reg. | Pittura di finitura smalto alchidico dei termosifoni | mq | 35,00 | 13,40 | 469,00 | Edili / Tinteggiatura | OG1 | — | verificato |
| 27 | 84 | B.02.046.01 | Tariffa reg. | Ricollocamento in opera dei radiatori rimossi | cad | 22,00 | 16,51 | 363,22 | Edili / Tinteggiatura | OG1 | — | verificato |
| 28 | 92 | B.02.017.01 | Tariffa reg. | Rimozione moquette (sala principale, galleria, scalinata) | mq | 275,00 | 3,36 | 924,00 | Edili / Pavimentazione | OG1 | C4.2 | verificato |
| 29 | 93 | B.25.002.01 | Tariffa reg. | Trasporto a discarica del materiale di risulta (autocarro 3,5-8,5 t) | mc/km | 105,00 | 0,57 | 59,85 | Edili / Pavimentazione | OG1 | — | verificato |
| 30 | 94 | B.25.004.33 | Tariffa reg. | Conferimento a discarica/recupero CER 17 06 04 (materiali isolanti) | ql | 8,00 | 38,46 | 307,68 | Edili / Pavimentazione | OG1 | — | verificato |
| 31 | 95 | B.14.037.02 | Tariffa reg. | Levigatura e lucidatura a specchio di pavimenti in cemento (vano scala, ingressi) | mq | 75,00 | 34,51 | 2.588,25 | Edili / Pavimentazione | OG1 | — | verificato |
| 32 | 96 | B.14.028.01 | Tariffa reg. | Trattamento antipolvere con resina epossidica (sala principale, galleria) | mq | 182,50 | 20,86 | 3.806,95 | Edili / Pavimentazione | OG1 | — | verificato |
| 33 | 97 | B.14.031.01 | Tariffa reg. | Pavimento monolitico autolivellante in resina epossidica 2-3 mm, colore scuro (sala, galleria) | mq | 182,50 | 85,54 | 15.611,05 | Edili / Pavimentazione | OG1 | C1.3 | verificato |
| 34 | 9 | B.02.023.01 | Tariffa reg. | Rimozione serramenti in ferro > 2 mq (porte, finestroni) | mq | 12,79 | 7,37 | 94,26 | Edili / Infissi | OG1 | C1.1 | verificato |
| 35 | 61 | B.18.071.03 | Tariffa reg. | Serramenti in PVC Uw 0,90-1,09 W/m²K, Uf ≤ 1,4, Rw ≤ 37 dB, vetro 33.1 BE + argon, posa UNI 11673 (porte emergenza, finestroni, finestra) | mq | 18,66 | 522,17 | 9.743,69 | Edili / Infissi | OG1 | C1.1 | verificato |
| 36 | 62 | B.18.132.02 | Tariffa reg. | Maniglioni antipanico (interno) + maniglia esterna | cad | 6,00 | 227,07 | 1.362,42 | Edili / Infissi | OG1 | — | verificato |
| 37 | 63 | B.18.071.10 | Tariffa (assente in G-02) | Serramenti PVC rivestiti bicolore (60,96%): voce a quantita' 0 e prezzo 0 (era 11,40 in ESEC-01) | — | 0,00 | 0,00 | 0,00 | Edili / Infissi | OG1 | C1.1 | verificato |
| 38 | 64 | B.18.122.03 | Tariffa reg. | Porta tagliafuoco REI 60 a due battenti, foro 1.300x2.000 | cad | 2,00 | 844,39 | 1.688,78 | Edili / Infissi | OG1 | — | verificato |
| 39 | 65 | B.18.122.06 | Tariffa reg. | Porta tagliafuoco REI 60 a due battenti, foro 1.600x2.000 | cad | 2,00 | 893,82 | 1.787,64 | Edili / Infissi | OG1 | — | verificato |
| 40 | 66 | B.18.120.06 | Tariffa reg. | Porta tagliafuoco REI 60 a un battente, foro 900x2.150 | cad | 1,00 | 450,65 | 450,65 | Edili / Infissi | OG1 | — | verificato |
| 41 | 67 | B.18.120.07 | Tariffa reg. | Porta tagliafuoco REI 60 a un battente, foro 1.000x2.150 | cad | 2,00 | 469,85 | 939,70 | Edili / Infissi | OG1 | — | verificato |
| 42 | 68 | B.18.132.02 | Tariffa reg. | Maniglioni antipanico (interno) + maniglia esterna per porte REI | cad | 10,00 | 227,07 | 2.270,70 | Edili / Infissi | OG1 | — | verificato |
| 43 | 69 | B.18.124.01 | Tariffa reg. | Sovrapprezzo finestratura 300x400 su porte REI 60 | cad | 10,00 | 267,55 | 2.675,50 | Edili / Infissi | OG1 | — | verificato |
| 44 | 70 | B.25.003.01 | Tariffa reg. | Trasporto a discarica in centro storico, autocarro ≤ 3,5 t | mc/km | 60,00 | 2,13 | 127,80 | Edili / Infissi | OG1 | — | verificato |
| 45 | 71 | B.25.004.17 | Tariffa reg. | Conferimento CER 17 04 05 (ferro e acciaio) | ql | 15,00 | 7,33 | 109,95 | Edili / Infissi | OG1 | — | verificato |
| 46 | 117 | B.18.057.01 | Tariffa reg. | Motorizzazione serrande con elettrofreno (infissi asserviti all'IRAI) | cad | 3,00 | 426,36 | 1.279,08 | Edili / Infissi | OG1 | C1.1 | verificato |
| 47 | 87 | NP 06 | NP (no analisi) | Verifica e sostituzione parziale impianto idrico di adduzione e scarico, con collaudo e conformita' | a corpo | 1,00 | 3.000,00 | 3.000,00 | Edili / Impianto idrico | OG1 | — | verificato |
| 48 | 114 | NP 001 | NP (analisi G-03) | Scala alla marinara con gabbia (2 scale, 6,60 m) | m | 6,60 | 273,77 | 1.806,88 | Edili / Opere da fabbro | OG1 | — | verificato |
| 49 | 115 | S.06.010.04 | Tariffa reg. | Punti di rinvio certificati UNI EN 795 A1 (accesso scala) | a corpo | 2,00 | 101,41 | 202,82 | Edili / Opere da fabbro | OG1 | — | verificato |
| 50 | 116 | B.16.015.01 | Tariffa reg. | Parapetti e corrimano in acciaio inox AISI 304 satinato | kg | 150,00 | 11,61 | 1.741,50 | Edili / Opere da fabbro | OG1 | — | verificato |
| 51 | 22 | D3.06.002.01 | Tariffa reg. | Tubo rigido PVC serie media Ø16 | m | 200,00 | 3,53 | 706,00 | Imp. elettrico / Impianto elettrico | OS30 | — | verificato |
| 52 | 23 | D3.06.011.01 | Tariffa reg. | Scatole di derivazione da incasso 92x92x45 | cad | 15,00 | 3,07 | 46,05 | Imp. elettrico / Impianto elettrico | OS30 | — | verificato |
| 53 | 24 | D3.05.001.01 | Tariffa reg. | Conduttore N07V-K 1,5 mmq | m | 500,00 | 1,76 | 880,00 | Imp. elettrico / Impianto elettrico | OS30 | — | verificato |
| 54 | 25 | D3.06.002.02 | Tariffa reg. | Tubo rigido PVC serie media Ø20 | m | 150,00 | 3,74 | 561,00 | Imp. elettrico / Impianto elettrico | OS30 | — | verificato |
| 55 | 26 | D3.05.001.02 | Tariffa reg. | Conduttore N07V-K 2,5 mmq | m | 450,00 | 1,97 | 886,50 | Imp. elettrico / Impianto elettrico | OS30 | — | verificato |
| 56 | 27 | D3.10.010.01 | Tariffa reg. | Faretti LED a incasso | cad | 50,00 | 104,46 | 5.223,00 | Imp. elettrico / Impianto elettrico | OS30 | — | verificato |
| 57 | 28 | D3.10.010.02 | Tariffa reg. | Incremento per foro su controsoffitto (faretti) | cad | 50,00 | 10,02 | 501,00 | Imp. elettrico / Impianto elettrico | OS30 | — | verificato |
| 58 | 29 | D3.10.019.01 | Tariffa reg. | Plafoniere LED fino a 33 W (proiettori) | cad | 14,00 | 296,27 | 4.147,78 | Imp. elettrico / Impianto elettrico | OS30 | — | verificato |
| 59 | 30 | D3.10.019.05 | Tariffa reg. | Incremento per posa plafoniere oltre 3,50 m | cad | 14,00 | 13,01 | 182,14 | Imp. elettrico / Impianto elettrico | OS30 | — | verificato |
| 60 | 38 | NP 002 | NP (analisi G-03) | Revisione completa del quadro elettrico esistente con sostituzione interruttori | cadauno | 1,00 | 6.026,56 | 6.026,56 | Imp. elettrico / Impianto elettrico | OS30 | C2.3 | verificato |
| 61 | 39 | B.02.036.01 | Tariffa reg. | Taglio su superfici in cls per segnapassi | ml/cm | 150,00 | 2,16 | 324,00 | Imp. elettrico / Impianto elettrico | OS30 | — | verificato |
| 62 | 40 | B.02.019.01 | Tariffa reg. | Tracce in muratura per segnapassi | ml/cm | 480,00 | 4,38 | 2.102,40 | Imp. elettrico / Impianto elettrico | OS30 | — | verificato |
| 63 | 41 | NP 15 | NP (no analisi) | Segnapassi LED da pavimento 3x1 W | cadauno | 80,00 | 50,00 | 4.000,00 | Imp. elettrico / Impianto elettrico | OS30 | — | verificato |
| 64 | 42 | D3.10.014.06 | Tariffa reg. | Plafoniere di emergenza IP40 1x18 W, autonomia 2 h | cad | 14,00 | 297,18 | 4.160,52 | Imp. elettrico / Impianto elettrico | OS30 | — | verificato |
| 65 | 43 | D3.10.016.01 | Tariffa reg. | Plafoniere di emergenza IP55 1x18 W, autonomia 1 h | cad | 2,00 | 269,35 | 538,70 | Imp. elettrico / Impianto elettrico | OS30 | — | verificato |
| 66 | 44 | NP 14 | NP (no analisi) | Sistema di Building Automation (gestione e controllo remoto impianti, app) | a corpo | 1,00 | 4.000,00 | 4.000,00 | Imp. elettrico / Impianto elettrico | OS30 | C2.3 | verificato |
| 67 | 10 | A.01.024.03 | Tariffa reg. | Motocompressore per aria compressa (FV) | ora | 2,00 | 28,58 | 57,16 | Effic. energetico / Impianto Fotovoltaico | OG9 | — | verificato |
| 68 | 11 | A.01.030.02 | Tariffa reg. | Nolo carotatrice (FV) | ora | 2,00 | 52,05 | 104,10 | Effic. energetico / Impianto Fotovoltaico | OG9 | — | verificato |
| 69 | 12 | O.01.030.01 | Tariffa reg. | Perforazione a rotazione in muratura Ø45-65 per passaggio cavi | m | 2,00 | 123,49 | 246,98 | Effic. energetico / Impianto Fotovoltaico | OG9 | — | verificato |
| 70 | 13 | R.01.022.07 | Tariffa reg. | Moduli fotovoltaici monocristallini 450 Wp total black (13 moduli = 5,85 kWp) | cad | 13,00 | 407,85 | 5.302,05 | Effic. energetico / Impianto Fotovoltaico | OG9 | C2.1 | verificato |
| 71 | 14 | O.01.031.01 | Tariffa reg. | Sovrapprezzo perforazione a secco (presenza di affreschi) | m | 2,00 | 27,71 | 55,42 | Effic. energetico / Impianto Fotovoltaico | OG9 | — | verificato |
| 72 | 15 | R.01.011.03 | Tariffa reg. | Profili alluminio 47x37 L 3000 mm, montaggio semi-integrato FV | cad | 13,00 | 45,61 | 592,93 | Effic. energetico / Impianto Fotovoltaico | OG9 | C2.1 | verificato |
| 73 | 16 | R.01.011.01 | Tariffa reg. | Staffe universali inox A2, montaggio FV | cad | 26,00 | 22,69 | 589,94 | Effic. energetico / Impianto Fotovoltaico | OG9 | C2.1 | verificato |
| 74 | 17 | R.01.011.09 | Tariffa reg. | Elementi telescopici in alluminio per profilati, montaggio FV | cad | 13,00 | 31,15 | 404,95 | Effic. energetico / Impianto Fotovoltaico | OG9 | C2.1 | verificato |
| 75 | 18 | R.01.011.10 | Tariffa reg. | Graffe centrali in alluminio per moduli FV | cad | 26,00 | 7,99 | 207,74 | Effic. energetico / Impianto Fotovoltaico | OG9 | C2.1 | verificato |
| 76 | 19 | R.01.011.22 | Tariffa reg. | Viti a testa a martello M10 inox (confezione da 100) | cad | 1,00 | 3,64 | 3,64 | Effic. energetico / Impianto Fotovoltaico | OG9 | — | verificato |
| 77 | 20 | R.01.023.03 | Tariffa reg. | Inverter 6 kW trifase con monitoraggio | cad | 1,00 | 2.818,02 | 2.818,02 | Effic. energetico / Impianto Fotovoltaico | OG9 | C2.1 | verificato |
| 78 | 21 | R.01.020.01 | Tariffa reg. | Batteria di accumulo agli ioni di litio: 15 kWh | kwh | 15,00 | 877,83 | 13.167,45 | Effic. energetico / Impianto Fotovoltaico | OG9 | C2.3 | verificato |
| 79 | 45 | D3.04.007.04 | Tariffa reg. | Centralino IP65 a parete 24 moduli DIN | cad | 2,00 | 106,65 | 213,30 | Effic. energetico / Impianto Fotovoltaico | OG9 | — | verificato |
| 80 | 46 | D3.04.010.15 | Tariffa reg. | Interruttore magnetotermico tetrapolare 81-125 A, 10 kA | cad | 1,00 | 428,11 | 428,11 | Effic. energetico / Impianto Fotovoltaico | OG9 | — | verificato |
| 81 | 47 | D3.04.017.05 | Tariffa reg. | Interruttori magnetotermici differenziali tetrapolari 0-32 A, Id 0,03 A | cad | 2,00 | 429,02 | 858,04 | Effic. energetico / Impianto Fotovoltaico | OG9 | — | verificato |
| 82 | 48 | D3.04.021.06 | Tariffa reg. | Portafusibili sezionabili 2P 32 A | cad | 2,00 | 19,28 | 38,56 | Effic. energetico / Impianto Fotovoltaico | OG9 | — | verificato |
| 83 | 49 | D3.04.021.11 | Tariffa reg. | Fusibili a cartuccia T/F | cad | 2,00 | 3,88 | 7,76 | Effic. energetico / Impianto Fotovoltaico | OG9 | — | verificato |
| 84 | 50 | D3.04.022.03 | Tariffa reg. | Limitatori di sovratensione SPD 15 kA 4P | cad | 2,00 | 340,97 | 681,94 | Effic. energetico / Impianto Fotovoltaico | OG9 | — | verificato |
| 85 | 51 | D3.04.029.01 | Tariffa reg. | Spie luminose presenza rete su guida DIN | cad | 3,00 | 20,92 | 62,76 | Effic. energetico / Impianto Fotovoltaico | OG9 | — | verificato |
| 86 | 52 | D3.05.019.30 | Tariffa reg. | Cavo FG16 3x6 mmq | m | 50,00 | 6,41 | 320,50 | Effic. energetico / Impianto Fotovoltaico | OG9 | — | verificato |
| 87 | 53 | D3.06.016.01 | Tariffa reg. | Canale portacavi PVC 60x50 | m | 50,00 | 11,50 | 575,00 | Effic. energetico / Impianto Fotovoltaico | OG9 | — | verificato |
| 88 | 54 | S.06.010.04 | Tariffa reg. | Punti di rinvio certificati UNI EN 795 A1 (copertura) | a corpo | 3,00 | 101,41 | 304,23 | Effic. energetico / Impianto Fotovoltaico | OG9 | — | verificato |
| 89 | 31 | NP 16_D.02.083 | NP (no analisi) | Operaio impiantista metalmeccanico liv. C3: rimozione caldaia esistente (32 h) | ore | 32,00 | 25,71 | 822,72 | Effic. energetico / Impianto di Riscaldamento - Caldaia | OG9 | — | verificato |
| 90 | 32 | B.25.003.01 | Tariffa reg. | Trasporto a discarica in centro storico (caldaia) | mc/km | 60,00 | 2,13 | 127,80 | Effic. energetico / Impianto di Riscaldamento - Caldaia | OG9 | — | verificato |
| 91 | 33 | B.25.004.17 | Tariffa reg. | Conferimento CER 17 04 05 ferro e acciaio (caldaia) | ql | 5,00 | 7,33 | 36,65 | Effic. energetico / Impianto di Riscaldamento - Caldaia | OG9 | — | verificato |
| 92 | 34 | D2.03.006.04 | Tariffa reg. | Caldaia a basamento a condensazione 91-115 kW | cad | 1,00 | 8.994,37 | 8.994,37 | Effic. energetico / Impianto di Riscaldamento - Caldaia | OG9 | — | verificato |
| 93 | 35 | NP 16_D.02.083 | NP (no analisi) | Operaio impiantista metalmeccanico liv. C3: collegamento all'impianto esistente (64 h) | ore | 64,00 | 25,71 | 1.645,44 | Effic. energetico / Impianto di Riscaldamento - Caldaia | OG9 | — | verificato |
| 94 | 36 | NP 003 | NP (analisi G-03) | Lavaggio impianto con disincrostante e inibitore | a corpo | 1,00 | 1.670,18 | 1.670,18 | Effic. energetico / Impianto di Riscaldamento - Caldaia | OG9 | — | verificato |
| 95 | 37 | D2.02.016.01 | Tariffa reg. | Valvole termostatiche per radiatori 3/8" | cad | 23,00 | 54,89 | 1.262,47 | Effic. energetico / Impianto di Riscaldamento - Caldaia | OG9 | — | verificato |
| 96 | 72 | D6.01.008.03 | Tariffa reg. | Ascensore idraulico EN 81-2, 8 persone, cabina 1,45 mq, corsa 18 m, 6 fermate, bottoniere Braille | a corpo | 1,00 | 36.876,70 | 36.876,70 | Sollevamento / Ascensore - impianto elettrico vano ascensore | OS4 | C4.1 | verificato |
| 97 | 73 | D6.01.010.01 | Tariffa reg. | Sovrapprezzo velocita' ascensore fino a 0,80 m/s | a corpo | 1,00 | 2.093,22 | 2.093,22 | Sollevamento / Ascensore - impianto elettrico vano ascensore | OS4 | C4.1 | verificato |
| 98 | 74 | NP 04 | NP (no analisi) | Impianto elettrico del vano ascensore | a corpo | 1,00 | 3.000,00 | 3.000,00 | Sollevamento / Ascensore - impianto elettrico vano ascensore | OS4 | C4.1 | verificato |
| 99 | 100 | B.21.006.01 | Tariffa reg. | Pittura di fondo del vano ascensore | mq | 86,45 | 3,28 | 283,56 | Sollevamento / Ascensore - impianto elettrico vano ascensore | OS4 | — | verificato |
| 100 | 101 | B.21.012.01 | Tariffa reg. | Tinteggiatura lavabile bianca del vano ascensore | mq | 86,45 | 14,56 | 1.258,71 | Sollevamento / Ascensore - impianto elettrico vano ascensore | OS4 | — | verificato |
| 101 | 85 | NP 08 | NP (no analisi) | Rimozione delle poltrone esistenti (120) e deposito in cantiere | cadauno | 120,00 | 10,00 | 1.200,00 | Arredo / Poltrone | OG1 | C1.2 | verificato |
| 102 | 86 | NP 05 | NP (no analisi) | Poltrone tipo Operapulia «art. 310 Social», ignifughe classe 1 (134) | cadauno | 134,00 | 230,77 | 30.923,18 | Arredo / Poltrone | OG1 | C1.2 | verificato |
| 103 | 89 | NP 12 | NP (no analisi) | Pannelli da parete in MDF / acustici / 3D a scelta della D.L. | mq | 85,15 | 55,00 | 4.683,25 | Arredo / Palco e allestimeto scenografico | OG1 | C1.3 | verificato |
| 104 | 90 | NP 13 | NP (no analisi) | Divisorio a doghe in legno color rovere (parete divisoria, delimitazione scala palco) | m | 415,00 | 6,00 | 2.490,00 | Arredo / Palco e allestimeto scenografico | OG1 | C1.3, C3.2 | verificato |
| 105 | 91 | NP 07 | NP (no analisi) | Sistemazione palco (~7 mq) e allestimento scenografico: sipario, fondale, tenda, americana 7,50 m con luci | a corpo | 1,00 | 16.000,00 | 16.000,00 | Arredo / Palco e allestimeto scenografico | OG1 | C3.2 | verificato |
| 106 | 102 | D3.11.001.02 | Tariffa reg. | Centrale convenzionale di rivelazione incendi a 4 zone | cad | 1,00 | 736,21 | 736,21 | Antincendio / Impianto IRAI | OS3 | — | verificato |
| 107 | 103 | D3.11.004.01 | Tariffa reg. | Rivelatori ottici di fumo | cad | 15,00 | 87,36 | 1.310,40 | Antincendio / Impianto IRAI | OS3 | — | verificato |
| 108 | 104 | D3.11.019.01 | Tariffa reg. | Pulsanti di allarme a rottura vetro | cad | 8,00 | 70,39 | 563,12 | Antincendio / Impianto IRAI | OS3 | — | verificato |
| 109 | 105 | D3.11.021.03 | Tariffa reg. | Segnalatori ottico-acustici di allarme incendio | cad | 4,00 | 279,13 | 1.116,52 | Antincendio / Impianto IRAI | OS3 | — | verificato |
| 110 | 106 | D3.06.002.01 | Tariffa reg. | Tubo rigido PVC Ø16 (IRAI) | m | 200,00 | 3,53 | 706,00 | Antincendio / Impianto IRAI | OS3 | — | verificato |
| 111 | 107 | D3.06.016.01 | Tariffa reg. | Canale portacavi PVC 60x50 (IRAI) | m | 200,00 | 11,50 | 2.300,00 | Antincendio / Impianto IRAI | OS3 | — | verificato |
| 112 | 108 | D3.05.001.02 | Tariffa reg. | Conduttore N07V-K 2,5 mmq (IRAI) | m | 90,00 | 1,97 | 177,30 | Antincendio / Impianto IRAI | OS3 | — | verificato |
| 113 | 109 | D3.11.024.02 | Tariffa reg. | Cavo antifiamma per rivelazione incendi 1 coppia + T | m | 400,00 | 1,86 | 744,00 | Antincendio / Impianto IRAI | OS3 | — | verificato |
| 114 | 110 | NP 004 | NP (analisi G-03) | Sistema di comunicazione bidirezionale dello spazio calmo | cadauno | 1,00 | 3.064,74 | 3.064,74 | Antincendio / Impianto IRAI | OS3 | — | verificato |
| 115 | 111 | D3.11.021.11 | Tariffa reg. | Pannello luminoso/sirena di ripetizione allarme in reception | cad | 1,00 | 170,47 | 170,47 | Antincendio / Impianto IRAI | OS3 | — | verificato |
| 116 | 112 | D1.09.006.10 | Tariffa reg. | Estintori a polvere 6 kg 34A 233BC | cad | 13,00 | 72,30 | 939,90 | Antincendio / Estintori | OS3 | — | verificato |
| 117 | 113 | S.03.018.04 | Tariffa reg. | Estintori CO2 5 kg 89 BC | cad | 6,00 | 248,22 | 1.489,32 | Antincendio / Estintori | OS3 | — | verificato |
| 118 | 118 | H.05.039.01 | Tariffa reg. | Allacciamento PEAD Ø63 per uso antincendio, con nicchia/armadio | cad | 1,00 | 1.165,21 | 1.165,21 | Antincendio / Idrico antincendio | OS3 | — | verificato |
| 119 | 119 | D1.09.005.02 | Tariffa reg. | Idrante sottosuolo DN70 UNI 70 (idrante esterno) | cad | 1,00 | 560,81 | 560,81 | Antincendio / Idrico antincendio | OS3 | — | verificato |
| 120 | 120 | D1.09.001.03 | Tariffa reg. | Gruppo attacco motopompa VV.F. 2½" | cad | 1,00 | 219,63 | 219,63 | Antincendio / Idrico antincendio | OS3 | — | verificato |
| 121 | 121 | D1.09.002.07 | Tariffa reg. | Cassetta idrante da esterno UNI 70 con manichetta 30 m | cad | 1,00 | 410,73 | 410,73 | Antincendio / Idrico antincendio | OS3 | — | verificato |
| 122 | 122 | D1.09.004.01 | Tariffa reg. | Cassette naspi da interno UNI 45 | cad | 4,00 | 188,62 | 754,48 | Antincendio / Idrico antincendio | OS3 | — | verificato |
| 123 | 123 | D1.01.022.07 | Tariffa reg. | Tubazione PE100 PFA16 De 75 interrata | m | 100,00 | 10,51 | 1.051,00 | Antincendio / Idrico antincendio | OS3 | — | verificato |
| 124 | 124 | B.01.011.01 | Tariffa reg. | Scavo a sezione obbligata a mano in roccia, fino a 2 m | mc | 12,50 | 110,51 | 1.381,38 | Antincendio / Idrico antincendio | OS3 | — | verificato |
| 125 | 125 | B.25.003.01 | Tariffa reg. | Trasporto a discarica del materiale di scavo (≤ 3,5 t; 50% riutilizzato) | mc/km | 375,00 | 2,13 | 798,75 | Antincendio / Idrico antincendio | OS3 | — | verificato |
| 126 | 126 | B.25.004.10 | Tariffa reg. | Conferimento CER 17 03 03 (prodotti contenenti catrame) | ql | 18,75 | 3,83 | 71,81 | Antincendio / Idrico antincendio | OS3 | — | verificato |
| 127 | 127 | B.01.021.01 | Tariffa reg. | Rinterro con materiale di scavo | mc | 12,50 | 6,07 | 75,88 | Antincendio / Idrico antincendio | OS3 | — | verificato |
| 128 | 128 | E.00050 | Tariffa? (cod. anomalo) | Sabbia di cava (letto di posa) | m3 | 5,00 | 35,00 | 175,00 | Antincendio / Idrico antincendio | OS3 | — | verificato |
| 129 | 129 | E.04.023.01 | Tariffa reg. | Conglomerato bituminoso a freddo in sacchi (ripristini) | kg | 2.000,00 | 0,75 | 1.500,00 | Antincendio / Idrico antincendio | OS3 | — | verificato |
| 130 | 130 | D1.01.030.08 | Tariffa reg. | Tubazione in acciaio zincato DN 2½" | m | 30,00 | 47,32 | 1.419,60 | Antincendio / Idrico antincendio | OS3 | — | verificato |
| 131 | 131 | D1.01.030.07 | Tariffa reg. | Tubazione in acciaio zincato DN 2" | m | 30,00 | 32,75 | 982,50 | Antincendio / Idrico antincendio | OS3 | — | verificato |
| 132 | 132 | D1.01.030.06 | Tariffa reg. | Tubazione in acciaio zincato DN 1½" | m | 30,00 | 24,77 | 743,10 | Antincendio / Idrico antincendio | OS3 | — | verificato |
| 133 | 133 | D2.01.034.06 | Tariffa reg. | Collari in acciaio zincato DN40 | cad | 10,00 | 13,49 | 134,90 | Antincendio / Idrico antincendio | OS3 | — | verificato |
| 134 | 134 | D2.01.034.07 | Tariffa reg. | Collari in acciaio zincato DN50 | cad | 10,00 | 13,89 | 138,90 | Antincendio / Idrico antincendio | OS3 | — | verificato |
| 135 | 135 | D2.01.034.09 | Tariffa reg. | Collari in acciaio zincato DN63 | cad | 10,00 | 17,04 | 170,40 | Antincendio / Idrico antincendio | OS3 | — | verificato |
| 136 | 136 | A.01.024.03 | Tariffa reg. | Motocompressore per aria compressa (idrico antincendio) | ora | 8,00 | 28,58 | 228,64 | Antincendio / Idrico antincendio | OS3 | — | verificato |
| 137 | 137 | A.01.030.02 | Tariffa reg. | Nolo carotatrice (idrico antincendio) | ora | 8,00 | 52,05 | 416,40 | Antincendio / Idrico antincendio | OS3 | — | verificato |
| 138 | 139 | D2.02.007.01 | Tariffa reg. | Manometro INAIL Ø50 | cad | 1,00 | 25,72 | 25,72 | Antincendio / Idrico antincendio | OS3 | — | verificato |
| 139 | 138 | NP 005 | NP (analisi G-03) | Sistema di evacuazione forzata fumi e calore: 3 ventilatori 10.000 m³/h, condotte, serrande, quadro | cadauno | 1,00 | 50.833,39 | 50.833,39 | Antincendio / Impianto aspirazione forzata fumi e calore | OS3 | — | verificato |
| | | | | **TOTALE LAVORI A MISURA (139 voci)** | | | | **381.364,99** | | | | verificato |

Note alla tabella: voce 37 a quantità e prezzo nulli (in ESEC-01 q.tà 11,40); voci 89 e 93 con codice stampato su due righe («NP 16_D.02» + «083»); voce 128 con codice E.00050 di origine incerta. Le voci a corpo/cadauno con quantità 1 sono 11 (130.064,79 €), di cui 9 NP.

## 5. Voci a nuovo prezzo (NP)

19 codici NP su 20 righe di computo, 143.667,94 € (37,67% dei lavori). Solo 5 hanno un'analisi in [[G-03-ESEC-01_ANALISI_NUOVI_PREZZI]] (intestate «NP 01»-«NP 05»). Attenzione alla numerazione: **NP 003 ≠ NP 03, NP 004 ≠ NP 04, NP 005 ≠ NP 05** (lavorazioni diverse). Tutte le voci NP hanno manodopera 0,00 nel quadro [[G-05-ESEC-01_QUADRO_INCIDENZA_MANODOPERA]] (vedi [[economic_framework]] §3, D4).

| Codice NP | Voci computo | Lavorazione | U.M. | Q.tà | P.U. € | Importo € | Capitolo | Analisi in G-03 |
|---|---|---|---|---|---|---|---|---|
| NP 005 | 139 | Sistema di evacuazione forzata fumi e calore: 3 ventilatori 10.000 m³/h, condotte, serrande, quadro | cadauno | 1,00 | 50.833,39 | 50.833,39 | Impianto aspirazione forzata fumi e calore | sì (p. 16, «NP 05») |
| NP 05 | 102 | Poltrone tipo Operapulia «art. 310 Social», ignifughe classe 1 (134) | cadauno | 134,00 | 230,77 | 30.923,18 | Poltrone | no |
| NP 07 | 105 | Sistemazione palco (~7 mq) e allestimento scenografico: sipario, fondale, tenda, americana 7,50 m con luci | a corpo | 1,00 | 16.000,00 | 16.000,00 | Palco e allestimeto scenografico | no |
| NP 002 | 60 | Revisione completa del quadro elettrico esistente con sostituzione interruttori | cadauno | 1,00 | 6.026,56 | 6.026,56 | Impianto elettrico | sì (p. 13, «NP 02») |
| NP 12 | 103 | Pannelli da parete in MDF / acustici / 3D a scelta della D.L. | mq | 85,15 | 55,00 | 4.683,25 | Palco e allestimeto scenografico | no |
| NP 15 | 63 | Segnapassi LED da pavimento 3x1 W | cadauno | 80,00 | 50,00 | 4.000,00 | Impianto elettrico | no |
| NP 14 | 66 | Sistema di Building Automation (gestione e controllo remoto impianti, app) | a corpo | 1,00 | 4.000,00 | 4.000,00 | Impianto elettrico | no |
| NP 10 | 9 | Scala a chiocciola quadrata Ø180 cm h 3 m, acciaio e gradini in faggio (accesso camerini) | a corpo | 1,00 | 3.500,00 | 3.500,00 | Opere strutturali | no |
| NP 004 | 114 | Sistema di comunicazione bidirezionale dello spazio calmo | cadauno | 1,00 | 3.064,74 | 3.064,74 | Impianto IRAI | sì (p. 15, «NP 04») |
| NP 06 | 47 | Verifica e sostituzione parziale impianto idrico di adduzione e scarico, con collaudo e conformita' | a corpo | 1,00 | 3.000,00 | 3.000,00 | Impianto idrico | no |
| NP 04 | 98 | Impianto elettrico del vano ascensore | a corpo | 1,00 | 3.000,00 | 3.000,00 | Ascensore - impianto elettrico vano ascensore | no |
| NP 09 | 8 | Taglio di solaio con disco diamantato, senza polveri e vibrazioni (botola scala interna 1,80x1,80) | mq | 3,24 | 900,00 | 2.916,00 | Opere strutturali | no |
| NP 13 | 104 | Divisorio a doghe in legno color rovere (parete divisoria, delimitazione scala palco) | m | 415,00 | 6,00 | 2.490,00 | Palco e allestimeto scenografico | no |
| NP 16_D.02.083 | 89, 93 | Operaio impiantista metalmeccanico liv. C3 | ore | 96,00 | 25,71 | 2.468,16 | Impianto di Riscaldamento - Caldaia | no |
| NP 001 | 48 | Scala alla marinara con gabbia (2 scale, 6,60 m) | m | 6,60 | 273,77 | 1.806,88 | Opere da fabbro | sì (p. 12, «NP 01») |
| NP 003 | 94 | Lavaggio impianto con disincrostante e inibitore | a corpo | 1,00 | 1.670,18 | 1.670,18 | Impianto di Riscaldamento - Caldaia | sì (p. 14, «NP 03») |
| NP 03 | 1 | Rimozione materiale arido dai terrazzi, trasporto e conferimento a discarica | m3 | 32,89 | 40,00 | 1.315,60 | Impermeabilizzazioni | no |
| NP 08 | 101 | Rimozione delle poltrone esistenti (120) e deposito in cantiere | cadauno | 120,00 | 10,00 | 1.200,00 | Poltrone | no |
| NP 11 | 7 | Pellicola antisolare nera/argento scuro su vetri della cupola (92% energia solare respinta) | mq | 22,00 | 35,00 | 770,00 | Oscuramento cupola | no |
| **Totale NP** | 20 righe | 19 codici | | | | **143.667,94** | | 5 sì / 14 no |

## 6. Limiti di modifica imposti dal disciplinare

Riportati testualmente dai campi `modification_limits` (vincoli) e `fuori_scope_risks` (rischi) delle pagine criterio in `03_criteria/criteria/` (compilate da disciplinare-analyst). Le voci «inferito» sono rischi dedotti, non vincoli scritti.

### Vincoli trasversali (tutti i criteri)

- L'offerta tecnica deve rispettare, pena l'esclusione, le caratteristiche minime stabilite nei documenti di gara, nel rispetto del principio di equivalenza (art. 16, p. 25).
- Nessun prezzo, importo, ribasso, percentuale o valorizzazione economica in relazione tecnica, computo metrico non estimativo, cronoprogramma o altro documento dell'offerta tecnica: **esclusione** (art. 16, p. 26; art. 22, p. 33).
- Ogni miglioria va riportata nel computo metrico **non estimativo** con riferimento a criterio/sub-criterio, descrizione, unità di misura, quantità ed elementi tecnici di verifica (art. 16, pp. 25-26), e collocata nel cronoprogramma integrato (art. 16, p. 26).
- Le migliorie, sommate alle prestazioni di progetto, non devono far emergere dubbi sulla sostenibilità economica complessiva dell'offerta: parametro della verifica di anomalia (art. 23, p. 33).
- Durata fissa di 150 giorni naturali e consecutivi comprensivi di forniture e posa (art. 3.1, p. 8); nessun punteggio sul tempo.
- Escluse offerte parziali, plurime, condizionate, alternative (art. 17, p. 27; art. 22, p. 33).
- Relazione unica max 15 pagine fronte-retro = 30 facciate A4, font ≥ 11 pt (art. 16, p. 25).
- Progetto conforme ai CAM D.M. 24.11.2025 (edilizia) e D.M. 23 giugno 2022 n. 254 (arredi) (Premesse, p. 3).

### [[C1]] — Involucro, Poltrone ed Efficientamento Acustico (25 pt)

Vincoli (`modification_limits`):
- C1.1: le prestazioni termo-acustiche dei serramenti (Uf/Uw, Rw) devono essere superiori ai minimi di progetto: il progetto esecutivo validato è la soglia minima (art. 18.1, sub 1.1, p. 28)
- L'offerta tecnica deve rispettare, pena l'esclusione, le caratteristiche minime stabilite nei documenti di gara, nel rispetto del principio di equivalenza (art. 16, p. 25)
- Le poltrone sono arredi soggetti ai CAM D.M. 23 giugno 2022 n. 254; i lavori ai CAM D.M. 24.11.2025, richiamati nell'Elaborato B3 (Premesse, p. 3)
- Le migliorie, sommate alle prestazioni di progetto, non devono far emergere dubbi sulla sostenibilità economica complessiva dell'offerta: parametro della verifica di anomalia (art. 23, p. 33)
- Durata lavori fissa di 150 giorni naturali e consecutivi comprensivi di forniture e posa: le migliorie vanno inserite nel cronoprogramma dell'offerta (art. 3.1, p. 8; art. 16, p. 26)

Rischi fuori scope (`fuori_scope_risks`):
- C1.1: modifiche a geometria, partiture o aspetto esterno dei serramenti in un'ala del Castello Aragonese (art. 11, p. 16) potrebbero eccedere il progetto approvato e richiedere autorizzazioni di tutela (inferito: il disciplinare cita la Soprintendenza solo nel sub 2.1)
- C1.1: 'superfici vetrate aggiuntive' che comportino nuove aperture o modifiche dell'involucro non previste dal progetto validato configurano variante, non miglioria (inferito)
- C1.3: pannellature MDF o rivestimenti devono restare compatibili con l'adeguamento antincendio della sala (Premesse, p. 3) e con le classi di reazione al fuoco richieste (inferito)
- C1.2: scorta di poltrone ed estensione garanzia con incidenza economica rilevante ai fini della verifica di anomalia (art. 23, p. 33)

Aggancio al perimetro: baseline C1.1 = voce 35 (Uw 0,90-1,09; Uf ≤ 1,4; Rw ≤ 37 dB); C1.2 = voce 102 (134 poltrone); C1.3 = voce 103 (85,15 mq di pannelli senza prestazioni dichiarate).

### [[C2]] — Energie Rinnovabili e Sistemi di Sicurezza (30 pt)

Vincoli:
- C2.1: sistemi fotovoltaici integrati sulla copertura, valutati in base ad azzeramento dell'impatto visivo, assenza di riflettanza e totale conformità agli indirizzi di tutela del Castello della Soprintendenza Basilicata (art. 18.1, sub 2.1, p. 28)
- C2.1: ai fini della formulazione della miglioria il disciplinare rimanda all'elaborato grafico PI-00a-ESEC-01 Planimetria di insieme con fotovoltaico integrato e fotoinserimenti (art. 18.1, sub 2.1, p. 28)
- C2.3: è valutato l'incremento quantitativo della capacità di accumulo delle batterie con riferimento '>20 kWh' (art. 18.1, sub 2.3, p. 28)
- L'offerta tecnica deve rispettare, pena l'esclusione, le caratteristiche minime stabilite nei documenti di gara, nel rispetto del principio di equivalenza (art. 16, p. 25)
- Le migliorie, sommate alle prestazioni di progetto, non devono far emergere dubbi sulla sostenibilità economica complessiva dell'offerta: parametro della verifica di anomalia (art. 23, p. 33)

Rischi fuori scope:
- C2.1: soluzioni FV visibili, riflettenti o non conformi agli indirizzi di tutela: punteggio basso e rischio di non autorizzabilità (art. 18.1, sub 2.1, p. 28)
- C2.1: estensione del campo FV oltre la copertura o modifiche strutturali della copertura del castello (inferito)
- C2.2: installazioni a vista sui paramenti storici del castello e interferenze con gli impianti di progetto (inferito)
- C2.3: maggiore capacità di accumulo che richieda nuovi locali tecnici o misure antincendio aggiuntive (inferito)

Aggancio al perimetro: baseline C2.1 = voci 67-88 (5,85 kWp, montaggio semi-integrato); C2.2 = nessuna voce; C2.3 = voce 78 (15 kWh) e voce 66 (BA).

### [[C3]] — Logistica Cantieri e Dotazioni Cinematografiche (15 pt)

Vincoli:
- C3.2: le forniture sono valutate se aggiuntive o a prestazioni superiori rispetto alla configurazione base del cineteatro di progetto (art. 18.1, sub 3.2, p. 29)
- C3.3: la metodologia riguarda impianto audio, proiettori e schermo del cineteatro esistente (smontaggio, imballaggio protettivo, stoccaggio sicuro, rimontaggio/taratura) (art. 18.1, sub 3.3, p. 29)
- L'offerta tecnica deve rispettare, pena l'esclusione, le caratteristiche minime stabilite nei documenti di gara, nel rispetto del principio di equivalenza (art. 16, p. 25)
- Le migliorie, sommate alle prestazioni di progetto, non devono far emergere dubbi sulla sostenibilità economica complessiva dell'offerta: parametro della verifica di anomalia (art. 23, p. 33)

Rischi fuori scope:
- C3.1: interventi su cupola in vetro e copertura del castello visibili dall'esterno — possibile incompatibilità con la tutela (inferito; la sala è in un'ala del Castello Aragonese, art. 11, p. 16)
- C3.1: spessori e sovraccarichi aggiuntivi in copertura con impatto su impermeabilizzazione, quote e soglie (inferito)
- C3.2: forniture non pertinenti alla configurazione del cineteatro o con incidenza economica rilevante ai fini dell'anomalia (art. 23, p. 33)

Aggancio al perimetro: baseline C3.1 = voci 1-7 (impermeabilizzazione senza isolante, pellicola cupola); C3.2 = voce 105 (allestimento) e voce 58; C3.3 = nessuna voce dedicata.

### [[C4]] — Accessibilità Universale e Criteri CAM (10 pt)

Vincoli:
- C4.2: le percentuali di materiale riciclato certificato (EPD) in cartongesso, silicati antincendio e isolanti devono eccedere i minimi CAM (art. 18.1, sub 4.2, p. 29); CAM di riferimento D.M. 24.11.2025 (Premesse, p. 3)
- C4.1: gli accessori e dispositivi opzionali si riferiscono all'impianto (ascensore) idraulico nel vano circolare previsto (art. 18.1, sub 4.1, p. 29)
- L'offerta tecnica deve rispettare, pena l'esclusione, le caratteristiche minime stabilite nei documenti di gara, nel rispetto del principio di equivalenza (art. 16, p. 25)
- Le migliorie, sommate alle prestazioni di progetto, non devono far emergere dubbi sulla sostenibilità economica complessiva dell'offerta: parametro della verifica di anomalia (art. 23, p. 33)

Rischi fuori scope:
- C4.1: modifiche al vano circolare o alla tipologia di ascensore di progetto (inferito)
- C4.2: il piano di economia circolare deve riferirsi ai tagli solai e alle demolizioni già previsti in progetto, non introdurne di nuovi (inferito)
- C4.2: impegni su certificazioni (EPD, FSC/PEFC, Classe A+) non verificabili o non reperibili in esecuzione (inferito)

Aggancio al perimetro: baseline C4.1 = voci 96-98; C4.2 = voci 8, 10-13 e voci di rimozione/conferimento. Nota: le voci di cartongesso dell'elenco prezzi richiamano i CAM DM 11/10/2017 (riciclato > 20%), non il D.M. 24.11.2025 citato dal disciplinare.

### [[C5]] — Esperienza specifica pregressa (6 pt, tabellare)

Vincoli:
- Punteggio tabellare predeterminato: 1 punto per ciascun intervento ammissibile e adeguatamente documentato, fino a un massimo di 6 punti — nessuna proposta migliorativa possibile (art. 18.1, sub 5.1, p. 29)
- Ammissibili solo interventi analoghi su immobili destinati a cinema, teatro, cineteatri o altri edifici destinati prevalentemente ad attività di spettacolo e intrattenimento aperti al pubblico (art. 18.1, sub 5.1, p. 29)
- Per ciascun intervento è richiesta una scheda sintetica con almeno: committente, denominazione e ubicazione dell'immobile, destinazione d'uso, oggetto e descrizione delle lavorazioni eseguite, importo dei lavori, periodo di esecuzione e data di ultimazione (art. 18.1, sub 5.1, p. 29)
- Punteggio attribuito esclusivamente per gli interventi la cui documentazione consenta di verificare in maniera chiara la riconducibilità alle caratteristiche indicate (art. 18.1, sub 5.1, p. 29)

Rischi fuori scope:
- Interventi su edifici a destinazione mista o non prevalentemente di spettacolo e intrattenimento aperti al pubblico: rischio di non ammissibilità (p. 29)
- Schede prive di uno dei contenuti minimi o con documentazione non chiara: punto non attribuito (p. 29)

Aggancio al perimetro: l'«analogia» si misura sulle lavorazioni del computo (antincendio/evacuazione fumi, impianti, FV, ascensore, arredo di sala) — §3.

### [[C6]] — Criteri premiali art. 57 e Allegato II.3 (2 pt, tabellare)

Vincoli:
- Punteggio tabellare predeterminato (2 punti on/off): attribuito all'O.E. che nell'ultimo triennio ha rispettato gli obblighi della legge n. 68 del 1999 — nessuna proposta migliorativa possibile (art. 18.1, sub 6.1, p. 30; art. 1, co. 5 lett. e) all. II.3 al Codice)

Rischi fuori scope:
- Forma e collocazione della comprova non indicate dal disciplinare: rischio di mancata attribuzione se la documentazione non è inserita nell'offerta tecnica (TBD)
- Regola in caso di RTI non indicata (TBD)

### [[C7]] — Criteri premiali art. 108 co. 7 (2 pt, tabellare)

Vincoli:
- Punteggio tabellare predeterminato (2 punti on/off): attribuito al concorrente in possesso della certificazione del sistema di gestione per la parità di genere UNI/PdR 125:2022 in corso di validità — nessuna proposta migliorativa possibile (art. 18.1, sub 7.1, p. 30)
- In caso di R.T.I. la certificazione deve essere posseduta da tutti i componenti del raggruppamento (art. 18.1, sub 7.1, p. 30)

Rischi fuori scope:
- RTI con anche un solo componente privo di certificazione: 0 punti (art. 18.1, sub 7.1, p. 30)
- Certificazione non in corso di validità alla data di presentazione dell'offerta: 0 punti (inferito da 'in corso di validità')
- Modalità di comprova in offerta non indicate (TBD)

## 7. TBD residui

- Garanzia di base delle poltrone (C1.2) e prestazioni acustiche dei pannelli NP 12 (C1.3): non indicate nelle voci — da cercare in relazioni specialistiche (es. [[RS-03-ESEC-01_RELAZIONE_ACUSTICA]]) e capitolato.
- Edizione della tariffa regionale Basilicata: non dichiarata (vedi [[economic_framework]] §11).
- Origine del prezzo E.00050 (voce 128).
