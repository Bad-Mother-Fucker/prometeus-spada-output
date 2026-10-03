---
type: economic_framework
gara: "Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)"
date: 2026-10-03
ai-first: true
importo_lavori_eur: 381364.99             # confidence: verificato — lavori a misura soggetti a ribasso, QE G-01-ESEC-02 A1 = computo G-04-ESEC-02 p. 23
oneri_sicurezza_eur: 13005.47             # confidence: verificato — QE A4 = SIC-03-ESEC-01 p. 3
oneri_sicurezza_pct: 3.410                # confidence: verificato — 13.005,47 / 381.364,99 × 100 (3,298% sul totale 394.370,46)
importo_complessivo_eur: 394370.46        # confidence: verificato — QE «TOTALE LAVORI (1+2+3+4)»
manodopera_eur: 47849.85                  # confidence: verificato — G-05-ESEC-01 p. 11-12 = disciplinare art. 3 p. 7
manodopera_pct: 12.547                    # confidence: verificato — G-05-ESEC-01 (su 381.364,99)
forniture_eur: 55296.43                   # confidence: verificato — computo super-categoria 005 ARREDO = disciplinare Tabella 1 riga 2
importo_np_eur: 143667.94                 # confidence: verificato — 20 righe / 19 codici NP del computo (37,67%)
somme_a_disposizione_eur: 125629.54       # confidence: verificato — QE G-01-ESEC-02 B
costo_complessivo_progetto_eur: 520000.00 # confidence: verificato — QE G-01-ESEC-02 A+B+C
iva_lavori_eur: 59428.23                  # confidence: verificato (valore letto); NON coerente con l'aliquota 22% dichiarata
fonte_qe: "[[G-01-ESEC-02_QUADRO_ECONOMICO]]"
fonte_computo: "[[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]]"
fonte_sicurezza: ["[[SIC-03-ESEC-01_COSTI_PER_LA_SICUREZZA]]"]
fonte_manodopera: "[[G-05-ESEC-01_QUADRO_INCIDENZA_MANODOPERA]]"
fonte_prezzi: ["[[G-02-ESEC-01_ELENCO_PREZZI]]", "[[G-03-ESEC-01_ANALISI_NUOVI_PREZZI]]"]
versioni_superate: ["[[G-01-ESEC-01_QUADRO_ECONOMICO]]", "[[G-04-ESEC-01_COMPUTO_METRICO_ESTIMATIVO]]"]
prezzario_riferimento: "Tariffa Regione Basilicata (codici tipo B.10.001.01) — edizione non dichiarata negli elaborati (TBD); non disponibile in cache prometeus-prezzari"
confronto_prezzi: rinviato
contraddizioni_fase_e: "2026-10-03 — registro D1-D19 (§10): 7 irrisolte (D2, D4, D11, D13, D14, D16, D18), 5 quesiti SA proposti (Q1-Q5, §10.1)"   # confidence: verificato
confidence: verificato
---

# Cornice economica — Cineteatro «Periz», Castello di Bella

## Per Claude futuro

Cornice economica della gara «Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)» (CIG BCF01395AF), costruita **solo dalle versioni `is_latest: true`**: QE [[G-01-ESEC-02_QUADRO_ECONOMICO]], computo [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]], costi sicurezza [[SIC-03-ESEC-01_COSTI_PER_LA_SICUREZZA]], manodopera [[G-05-ESEC-01_QUADRO_INCIDENZA_MANODOPERA]], prezzi [[G-02-ESEC-01_ELENCO_PREZZI]] e [[G-03-ESEC-01_ANALISI_NUOVI_PREZZI]]. Numeri chiave: **381.364,99 € soggetti a ribasso** (di cui manodopera 47.849,85 € = 12,547% e forniture di arredo 55.296,43 € = 14,5%) + **13.005,47 € di sicurezza** (3,41%) = **394.370,46 €**; costo complessivo di progetto 520.000,00 €. Tutti i riferimenti del disciplinare sono confermati dagli elaborati. Il registro delle contraddizioni (§10, D1-D19) è stato **verificato sulle fonti in Fase E**: le più rilevanti per l'offerta sono la capacità di accumulo (15 kWh nel computo contro 20 kWh nella relazione generale, baseline del sub C2.3), la versione dei CAM (D.M. 24.11.2025 nel disciplinare contro D.M. 23/06/2022 e 11/10/2017 negli elaborati, baseline del sub C4.2), l'ascensore (8 persone / 6 fermate nel computo contro 6 persone / 3 fermate nella relazione, sub C4.1), il numero di poltrone (134 nel computo contro 128 nelle tavole VV.F., sub C1.2) e la manodopera nulla sulle voci NP; per queste la §10.1 propone i testi dei quesiti alla SA (termine 06/10/2026 ore 12:00). Le contraddizioni irrisolte da riportare nell'index sono elencate in fondo, sezione «Per l'index». Il 37,7% dei lavori è a nuovi prezzi (NP), 14 codici NP su 19 senza analisi. Il confronto con il prezzario regionale è **rinviato** (tariffa Basilicata non in cache). Confidence: verificato.

## 1. Importi a base di gara

| Voce | Importo € | Fonte | Confidence |
|---|---|---|---|
| Lavori a misura soggetti a ribasso (A1) | 381.364,99 | QE G-01-ESEC-02 A1; computo G-04-ESEC-02 p. 23; capitolato G-06-ESEC-02 art. 1.2 | verificato |
| — di cui costi della manodopera (non ribassabili salvo giustificazione) | 47.849,85 | G-05-ESEC-01 pp. 11-12; disciplinare art. 3 p. 7 | verificato |
| — di cui forniture di poltrone, palco e allestimento (super-cat. ARREDO) | 55.296,43 | computo p. 24; disciplinare Tabella 1 riga 2 | verificato |
| — di cui lavori al netto delle forniture | 326.068,56 | calcolato 381.364,99 − 55.296,43 | verificato (calcolo) |
| Lavori a corpo / in economia (A2, A3) | 0,00 / 0,00 | QE A2-A3 | verificato |
| Oneri della sicurezza non soggetti a ribasso (A4) | 13.005,47 | SIC-03-ESEC-01 p. 3; QE A4 | verificato |
| **Totale lavori (A)** | **394.370,46** | QE; disciplinare Tabella 1; bando II.2.1 | verificato |
| Somme a disposizione (B) | 125.629,54 | QE B | verificato |
| Forniture e servizi (C) | 0,00 | QE C (le forniture di arredo sono in A1) | verificato |
| **Costo complessivo progetto (A+B+C)** | **520.000,00** | QE | verificato |
| Base del ribasso | 381.364,99, comprensiva della manodopera | disciplinare art. 3 p. 7 | verificato |

## 2. Verifica dei riferimenti di controllo del disciplinare

| Riferimento (disciplinare) | Valore disciplinare | Valore negli elaborati | Esito |
|---|---|---|---|
| Importo a base di gara soggetto a ribasso | 381.364,99 € (Tab. 1, p. 7) | 381.364,99 € (QE A1, computo, capitolato art. 1.2) | **coincide** |
| Costi manodopera | 47.849,85 € (p. 7) | 47.849,85 € (G-05, capitolato art. 1.2) | **coincide** |
| Oneri sicurezza | 13.005,47 € (Tab. 1 riga B) | 13.005,47 € (SIC-03, QE A4, capitolato, bando, copia PSC SIC-00) | **coincide** |
| Importo complessivo | 394.370,46 € (Tab. 1 A+B) | 394.370,46 € (QE, bando, capitolato) | **coincide** |
| Forniture | 55.296,43 € (Tab. 1 riga 2) | 55.296,43 € (computo super-cat. 005 ARREDO, 100% NP) | **coincide** |
| Tab. 1 riga 1 «Lavori di adeguamento impiantistico» | 339.074,03 € | 394.370,46 − 55.296,43 = 339.074,03 → include la sicurezza; lavori netti = 326.068,56 € | **discrepanza di etichetta**: righe 1+2 = 394.370,46 € ma la tabella le totalizza come «A) Importo a base di gara 381.364,99 €» (nota N2 di criteria_matrix, confermata) |
| OG1 prevalente | 185.390,73 €, 48,613%, cl. I, subappalto 49,99% | 185.390,73 € = LAVORI EDILI 130.094,30 + ARREDO 55.296,43; 48,612% (computo p. 27) | **coincide** (scarto 0,001 punti % di arrotondamento) |
| OS3 | 76.576,21 €, 20,080%, cl. I, subappalto 100% | 76.576,21 € = ANTINCENDIO | **coincide** |
| OS4 | 43.512,19 €, 11,410%, cl. I, subappalto 100% | 43.512,19 € = IMPIANTO DI SOLLEVAMENTO | **coincide** |
| OG9 | 41.600,21 €, 10,908%, cl. I, subappalto 100% | 41.600,21 € = EFFICIENTAMENTO ENERGETICO (FV + caldaia) | **coincide** |
| OS30 | 34.285,65 €, 8,990%, cl. I, subappalto 100% | 34.285,65 € = ADEGUAMENTO IMPIANTO ELETTRICO | **coincide** |
| Somma categorie SOA | 381.364,99 € (p. 8) | 381.364,99 € | **coincide**: le forniture (55.296,43) sono qualificate in OG1 |
| Garanzia provvisoria | 7.887,41 € = 2% del valore complessivo (art. 10) | 2% × 394.370,46 = 7.887,41 € | **coincide** |

Altre note di coerenza: il capitolato G-06-ESEC-02 (art. 1.3) scrive l'importo complessivo in cifre 394.370,46 € ma in lettere «…trecentosettanta/44» (refuso, verificato nel testo estratto).

## 3. Incidenze

| Indicatore | Valore | Base di calcolo | Fonte | Confidence |
|---|---|---|---|---|
| Incidenza manodopera | **12,547%** | 47.849,85 / 381.364,99 | G-05 (dichiarata) | verificato |
| Incidenza manodopera sul totale | 12,133% | 47.849,85 / 394.370,46 | calcolo | verificato |
| Incidenza manodopera sulle sole voci di tariffa | 20,13% | 47.849,85 / 237.697,05 | calcolo (NP = 0) | verificato |
| Incidenza sicurezza sui lavori a base | **3,410%** | 13.005,47 / 381.364,99 | calcolo | verificato |
| Incidenza sicurezza sul totale | 3,298% | 13.005,47 / 394.370,46 | calcolo | verificato |
| Incidenza forniture (arredo) | 14,500% | 55.296,43 / 381.364,99 | computo p. 24 | verificato |
| Quota a nuovi prezzi (NP) | 37,67% (143.667,94 €; 20 righe, 19 codici) | somma voci NP | computo | verificato |
| Quota a prezzi di tariffa | 62,33% (237.697,05 €; 119 righe, 104 codici) | somma voci non NP | computo | verificato |
| NP con analisi in G-03 | 5 codici (NP 001-005), 63.401,75 € | — | G-03 pp. 12-16 | verificato |
| NP senza analisi | 14 codici / 15 righe, 80.266,19 € (incl. poltrone 30.923,18 e palco 16.000,00) | — | G-03 | verificato |

**Manodopera sulle voci NP.** Il quadro G-05 attribuisce manodopera 0,00 a tutte le 19 voci NP. Gli elaborati contengono però almeno **13.708,57 €** di manodopera esplicita su voci NP: 11.240,41 € nelle 5 analisi G-03 (a costo, prima di SG 15% e utile 10%) e 2.468,16 € della voce NP 16_D.02.083 «operaio impiantista C3» (96 h × 25,71 €/h), che è solo manodopera. Il costo della manodopera dichiarato dalla SA (47.849,85 €) risulterebbe quindi sottostimato di almeno questo importo (≈ +28,6%), oltre alla quota TBD dei 13 NP senza analisi. Confidence: valori `verificato`, conclusione `inferito`. Rilevante per la dichiarazione dei costi della manodopera in offerta e per la verifica di anomalia (analisi per `strategy-auditor`).

## 4. Ripartizione per categorie SOA

| SOA | Declaratoria | Importo € | % (computo p. 27) | Class. | Subappalto (disc. p. 8) | Super-categoria del computo | di cui NP € (% cat.) | Manodopera G-05 € (incid.) |
|---|---|---|---|---|---|---|---|---|
| **OG1** (prevalente) | Edifici civili e industriali | 185.390,73 | 48,612 | I | 49,99% | 001 LAVORI EDILI + 005 ARREDO | 68.604,91 (37,0%) | 28.910,29 (15,59%) |
| OS3 | Impianti idrico-sanitario, cucine, lavanderie | 76.576,21 | 20,080 | I | 100% | 006 ANTINCENDIO (IRAI, estintori, idrico antincendio, evacuazione fumi) | 53.898,13 (70,4%) | 5.991,48 (7,82%) |
| OS4 | Impianti elettromeccanici trasportatori | 43.512,19 | 11,410 | I | 100% | 004 IMPIANTO DI SOLLEVAMENTO | 3.000,00 (6,9%) | 6.415,06 (14,74%) |
| OG9 | Impianti per la produzione di energia elettrica | 41.600,21 | 10,908 | I | 100% | 003 EFFICIENTAMENTO ENERGETICO (FV + caldaia) | 4.138,34 (9,9%) | 1.647,89 (3,96%) |
| OS30 | Impianti interni elettrici, telefonici, radiotelefonici e televisivi | 34.285,65 | 8,990 | I | 100% | 002 ADEGUAMENTO IMPIANTO ELETTRICO | 14.026,56 (40,9%) | 4.885,13 (14,25%) |
| | **Totale** | **381.364,99** | 100,000 | | | | **143.667,94** | **47.849,85** |

Abbinamento super-categoria → SOA: `inferito` per uguaglianza esatta degli importi (il computo dà i due riepiloghi separati, pp. 24 e 27); importi `verificato`. Il disciplinare (p. 8) consente all'impresa con OG11 di eseguire OS3 e OS30 nei limiti della classifica posseduta.

## 5. Ripartizione per super-categorie e capitoli del computo

| Cat. | Capitolo | Super-categoria | SOA | N. voci | Importo € | % | di cui NP € | Manodopera € | Incid. % |
|---|---|---|---|---|---|---|---|---|---|
| 001 | Impermeabilizzazioni | Lavori edili | OG1 | 6 | 27.028,51 | 7,087 | 1.315,60 | 4.587,24 | 16,972 |
| 002 | Oscuramento cupola | Lavori edili | OG1 | 1 | 770,00 | 0,202 | 770,00 | 0,00 | 0,000 |
| 003 | Opere strutturali | Lavori edili | OG1 | 2 | 6.416,00 | 1,682 | 6.416,00 | 0,00 | 0,000 |
| 004 | Opere in cartongesso | Lavori edili | OG1 | 8 | 30.417,58 | 7,976 | 0,00 | 11.418,01 | 37,538 |
| 005 | Tinteggiatura | Lavori edili | OG1 | 10 | 12.883,06 | 3,378 | 0,00 | 5.582,26 | 43,330 |
| 006 | Pavimentazione | Lavori edili | OG1 | 6 | 23.297,78 | 6,109 | 0,00 | 6.220,04 | 26,698 |
| 007 | Infissi | Lavori edili | OG1 | 13 | 22.530,17 | 5,908 | 0,00 | 989,42 | 4,392 |
| 008 | Impianto idrico | Lavori edili | OG1 | 1 | 3.000,00 | 0,787 | 3.000,00 | 0,00 | 0,000 |
| 017 | Opere da fabbro | Lavori edili | OG1 | 3 | 3.751,20 | 0,984 | 1.806,88 | 113,32 | 3,021 |
| | *Totale 001 LAVORI EDILI* | | | *50* | *130.094,30* | *34,113* | *13.308,48* | *28.910,29* | *22,223* |
| 009 | Impianto elettrico | Adeguamento impianto elettrico | OS30 | 16 | 34.285,65 | 8,990 | 14.026,56 | 4.885,13 | 14,248 |
| 010 | Impianto Fotovoltaico | Efficientamento energetico | OG9 | 22 | 27.040,58 | 7,090 | 0,00 | 1.348,39 | 4,987 |
| 011 | Impianto di Riscaldamento - Caldaia | Efficientamento energetico | OG9 | 7 | 14.559,63 | 3,818 | 4.138,34 | 299,50 | 2,057 |
| | *Totale 003 EFFICIENTAMENTO ENERGETICO* | | | *29* | *41.600,21* | *10,908* | *4.138,34* | *1.647,89* | *3,961* |
| 012 | Ascensore - impianto elettrico vano ascensore | Impianto di sollevamento | OS4 | 5 | 43.512,19 | 11,410 | 3.000,00 | 6.415,06 | 14,743 |
| 013 | Poltrone | Arredo | OG1 | 2 | 32.123,18 | 8,423 | 32.123,18 | 0,00 | 0,000 |
| 014 | Palco e allestimento scenografico | Arredo | OG1 | 3 | 23.173,25 | 6,076 | 23.173,25 | 0,00 | 0,000 |
| | *Totale 005 ARREDO (= forniture)* | | | *5* | *55.296,43* | *14,500* | *55.296,43* | *0,00* | *0,000* |
| 015 | Impianto IRAI | Antincendio | OS3 | 10 | 10.888,76 | 2,855 | 3.064,74 | 2.508,82 | 23,040 |
| 016 | Estintori | Antincendio | OS3 | 2 | 2.429,22 | 0,637 | 0,00 | 5,27 | 0,217 |
| 018 | Idrico antincendio | Antincendio | OS3 | 21 | 12.424,84 | 3,258 | 0,00 | 3.477,39 | 27,987 |
| 019 | Impianto aspirazione forzata fumi e calore | Antincendio | OS3 | 1 | 50.833,39 | 13,329 | 50.833,39 | 0,00 | 0,000 |
| | *Totale 006 ANTINCENDIO* | | | *34* | *76.576,21* | *20,080* | *53.898,13* | *5.991,48* | *7,824* |
| | **TOTALE** | | | **139** | **381.364,99** | **100,000** | **143.667,94** | **47.849,85** | **12,547** |

Fonti: importi e % da computo p. 25 (verificato); n. voci e quote NP da parser riconciliato (verificato); manodopera da G-05 p. 12 (verificato).

## 6. Tipologie omogenee di lavorazione (TOL) e revisione prezzi

| TOL | Descrizione | Importo € | Peso % | Nel calcolo Is |
|---|---|---|---|---|
| TOL1 | Opere edili | 170.213,53 | 44,63 | sì |
| TOL4 | Movimento terra e demolizioni | 7.637,69 | 2,00 | no (< 4%) |
| TOL5 | Pavimentazione bitume | 1.500,00 | 0,39 | no |
| TOL6 | Strutture e opere in acciaio | 9.050,40 | 2,37 | no |
| TOL14 | Impianti elettrici, tecnologici, radiotelefonici e antintrusione | 126.144,57 | 33,07 | sì |
| TOL15 | Impianti meccanici, termici, idrico-sanitari e trasportatori | 66.292,71 | 17,38 | sì |
| TOL20 | Conferimento rifiuti | 526,09 | 0,14 | no |

Is aprile 2025 = 97,89; Is febbraio 2026 = 98,10; ΔIs = +0,21; revisione al 90% dell'eccedenza oltre il 3% (computo G-04-ESEC-02 Allegato I, pp. 28-35, verificato). Accantonamento in QE B6: 5.000,00 € (derivazione dell'importo non esplicitata: TBD).

## 7. Somme a disposizione della stazione appaltante (QE)

| Riga | Voce | ESEC-02 (mag. 2026) € | ESEC-01 (apr. 2026, superato) € |
|---|---|---|---|
| B1 | Lavori in economia esclusi, rimborsi | 2.000,00 | 2.000,00 |
| B2 | Allacciamenti | 0,00 | 0,00 |
| B3 | Imprevisti | 7.386,68 (IVA 22% compresa) | 5.982,30 |
| B4-B5 | Acquisizioni / espropri | 0,00 | 0,00 |
| B6 | Accantonamento adeguamento prezzi | 5.000,00 | 0,00 |
| B7 | Pubblicità | 378,32 | 378,32 |
| B8 | Spese artt. 90-92 | 0,00 | 0,00 |
| B9 | Spese connesse all'attuazione (a 1.000,00; b spese tecniche 40.373,79; c incentivo 4.322,05; d 2.000,00; e commissione 500,00; h IVA 1.492,00) | 49.687,84 | 49.687,84 |
| B10 | IVA sui lavori «al 22%» | 59.428,23 | 59.428,23 |
| B11 | IVA su altre somme | 1.623,23 | 1.839,34 |
| B12 | Altre imposte | 125,24 | 125,24 |
| | **Totale B** | **125.629,54** | **119.441,27** |
| | **Costo complessivo (A+B+C)** | **520.000,00** | **513.811,73** |

Fonte: [[G-01-ESEC-02_QUADRO_ECONOMICO]], [[G-01-ESEC-01_QUADRO_ECONOMICO]] — tutti verificati.

## 8. Costi della sicurezza

13.005,47 € in 12 voci ([[SIC-03-ESEC-01_COSTI_PER_LA_SICUREZZA]]): ponteggio 195 mq (6.374,55 €, 49%), monoblocco 6 mesi (2.061,52 €), parapetti 110 m, teli 195 mq, trabatello 60 gg, recinzione, imbracature, 3 cartelli. Nessuna discordanza tra stima sicurezza (SIC-03), QE A4, disciplinare, bando, capitolato e copia nel PSC SIC-00 pp. 256-258 (12/12 voci identiche per u.m., quantità, prezzo e importo — confronto voce per voce eseguito in Fase E): **nessuna contraddizione sugli oneri della sicurezza**. L'importo presunto dei lavori del PSC (p. 2) è invece discordante: vedi D16. Nessuna voce per protezione/stoccaggio attrezzature esistenti o monitoraggio polveri/vibrazioni.

## 9. Differenze ESEC-01 → ESEC-02 (da approfondire in Fase E)

| Elaborato | Differenza | Effetto economico | Confidence |
|---|---|---|---|
| QE G-01 | B3 imprevisti 5.982,30 → 7.386,68 € (ora IVA compresa) | +1.404,38 € | verificato |
| QE G-01 | B6 accantonamento adeguamento prezzi 0,00 → 5.000,00 € | +5.000,00 € | verificato |
| QE G-01 | B11 IVA altre somme 1.839,34 → 1.623,23 € (base B1+B3+B7 → B1+B6+B7) | −216,11 € | verificato (valori), inferito (basi) |
| QE G-01 | Totale B 119.441,27 → 125.629,54; costo complessivo 513.811,73 → 520.000,00 | +6.188,27 € | verificato |
| QE G-01 | Parte A (lavori, sicurezza, totale) | nessuno | verificato |
| Computo G-04 | 139 voci, prezzi, quantità, importi e riepiloghi identici | nessuno | verificato |
| Computo G-04 | Voce 37 B.18.071.10 q.tà 11,40 → 0,00 (prezzo 0) | nessuno | verificato |
| Computo G-04 | Aggiunti: riepilogo TOL (p. 26), categorie SOA (p. 27), Allegato I revisione prezzi (pp. 28-35) | giustifica B6 | verificato |
| G-02, G-03, G-05, SIC-03 | Nessuna revisione ESEC-02; contenuto coerente con G-04-ESEC-02 (G-05 riporta ancora q.tà 11,40 della voce 37) | nessuno | verificato |

## 10. Registro discrepanze e contraddizioni (verificato in Fase E, 2026-10-03)

D1-D13 sono state trovate dalla Fase A; la **Fase E** (round 2) le ha riverificate sulle fonti (testi in `01_extracted/text/`, PDF in `01_extracted/p7m_extracted/`, livello di testo delle tavole via `pdftotext`) e ha aggiunto **D14-D19**, contraddizioni tra elaborati tecnici con impatto su criteri o economia. Gerarchia applicata: **disciplinare > capitolato/contratto > computo/QE** (tra questi l'elenco prezzi prevale sul computo, capitolato G-06-ESEC-02 art. 2.2) **> relazioni > tavole**; tra versioni dello stesso elaborato prevale `is_latest: true`. «Esito»: confermata / smentita / parziale. I testi dei quesiti sono in §10.1; termine per i chiarimenti **06/10/2026 ore 12:00** (disciplinare, Timing p. 18; quesiti via PAD asmecomm «Sezione chiarimenti», art. 2.2 p. 6). Sopralluogo obbligatorio da richiedere entro il 05/10/2026 ore 12:00: utile per verificare sul posto D14 e D18.

| # | Discrepanza | Esito Fase E | Valori e fonti (pag.) | Fonte prevalente | Impatto (criteri / economia) | Quesito SA | Confidence |
|---|---|---|---|---|---|---|---|
| D1 | Etichetta della Tabella 1 del disciplinare | **confermata** | disciplinare Tab. 1 p. 7: riga 1 «Lavori di adeguamento impiantistico» (P) 339.074,03 + riga 2 «Forniture di poltrone, palco e allestimento scenografico» (S) 55.296,43 = 394.370,46, totalizzate «A) Importo a base di gara 381.364,99»; seguono B) 13.005,47 e A+B 394.370,46. Valore corretto della riga 1 = 326.068,56 (computo p. 24: 381.364,99 − 55.296,43); 339.074,03 include la sicurezza | disciplinare art. 3 p. 7 (testo: ribasso «sull'importo a base di gara» 381.364,99) + QE [[G-01-ESEC-02_QUADRO_ECONOMICO]] A1 | nessuno sul ribasso; marginale sulla quota della prestazione principale in caso di RTI misto (339.074,03 vs 326.068,56) | No (facoltativo) | verificato |
| D2 | IVA sui lavori nel QE | **confermata**, causa non ricostruibile | QE G-01-ESEC-02 p. 2 riga B10 «I.V.A. sui lavori al 22%» 59.428,23 € = 15,07% di 394.370,46 (al 22%: 86.761,50 €, differenza 27.333,27 €); identica in [[G-01-ESEC-01_QUADRO_ECONOMICO]]. Fase E: nessuna combinazione di aliquote 4/10/22% applicata alle super-categorie del computo ricostruisce il valore (verifica aritmetica) | — (somme a disposizione della SA) | nessuno sull'offerta; possibile sotto-copertura del QE della SA | No | verificato (valore), causa TBD |
| D3 | IVA B9 h) nel QE | anomalia interna (Fase A) | 1.492,00 € ≠ 22% delle voci a, c, e, f, g (1.280,85 €) | — | nessuno | No | verificato (valore), causa TBD |
| D4 | Manodopera nulla sulle voci NP | **confermata** + nuovo indizio | [[G-05-ESEC-01_QUADRO_INCIDENZA_MANODOPERA]] pp. 9-12: 0,00 su tutte le 19 voci NP (143.667,94 €), compresa NP 16_D.02.083 «operaio impiantista C3» 96 h × 25,71 = 2.468,16 € (p. 10), totale 47.849,85 €; [[G-03-ESEC-01_ANALISI_NUOVI_PREZZI]] pp. 12-16: 11.240,41 € di manodopera nelle 5 analisi → ≥ 13.708,57 € esclusi. Nuovo: PSC [[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]] p. 2 «Entità presunta del lavoro: 773 uomini/giorno» ≈ 158.990 € a 8 h × 25,71 €/h (3,3 volte G-05; stima software del PSC, inferito) | G-05 per il valore dichiarato dalla SA (richiamato dal disciplinare art. 3 p. 7); G-03 per il contenuto reale delle lavorazioni | i costi della manodopera da dichiarare in offerta economica saranno verosimilmente > 47.849,85 € (nessun rischio di esclusione: il vincolo tutela il minimo); argomento per la verifica di anomalia e per la sostenibilità delle migliorie C1-C4 | **Sì — Q5** (bassa, facoltativo) | verificato (valori), inferito (conclusione) |
| D5 | NP senza analisi | anomalia interna (Fase A) | 14 codici / 80.266,19 € (poltrone, palco, BA, pannelli MDF, segnapassi, taglio solaio, ecc.) senza analisi in G-03 | — | prezzi non verificabili per componenti | No | verificato |
| D6 | Numerazione NP ambigua | anomalia interna (Fase A) | NP 001-005 (analisi intestate «NP 01-05») coesistono con NP 03, NP 04, NP 05 riferiti ad altre lavorazioni | — | rischio di errore in contabilità | No | verificato |
| D7 | Premio di accelerazione | **confermata** e più ampia | disciplinare p. 8: 0,5%/giorno dell'ammontare netto contrattuale, max 10%, «nei limiti delle somme ... alla voce imprevisti»; capitolato [[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]] art. 2.14 p. 25: «stessi criteri ... della penale» (0,3‰/giorno) e tetto 5% dell'importo netto, dagli imprevisti; [[G-06-ESEC-01_CAPITOLATO_SPECIALE_D_APPALTO]] p. 25: penale non compilata, nessun tetto. Divergono **sia il tasso giornaliero** (0,5% contro 0,3‰) **sia il tetto** (10% contro 5%) | disciplinare (lex specialis) | nessun punteggio sul tempo; il tetto effettivo è il fondo imprevisti QE B3: 7.386,68 € IVA compresa (≈ 6.054,66 € netti, 1,6% di 381.364,99), che al tasso del disciplinare si esaurisce con circa 3 giorni di anticipo | No (risolta per gerarchia) | verificato |
| D8 | Voce 37 a quantità/prezzo nulli | anomalia interna (Fase A) | B.18.071.10 presente nel computo, assente dall'elenco prezzi | — | nessuno | No | verificato |
| D9 | Codice anomalo | anomalia interna (Fase A) | E.00050 «sabbia di cava» non NP, senza analisi, formato diverso dalla tariffa | — | trascurabile (175,00 €) | No | verificato |
| D10 | Riferimenti normativi del QE | anomalia interna (Fase A) | art. 133, 90, 92, 113 «del codice» e DPR 207/2010 (vecchio codice) mentre l'Allegato I del computo cita art. 60 D.Lgs. 36/2023 | — | formale | No | verificato |
| D11 | Versione dei CAM di riferimento | **confermata** e più ampia | disciplinare Premesse p. 3: CAM **D.M. 24.11.2025** (edilizia) + D.M. 23/06/2022 n. 254 (arredi), «richiamati ... nell'Elaborato B3 – Relazione sui Criteri Minimi Ambientali» — nessun elaborato B3 in [[G-00-ESEC-01_ELENCO_ELABORATI]] (la relazione CAM è G-09); [[G-09-ESEC-01_RELAZIONE_CAM]] p. 4 (premessa DM 11/01/2017) e p. 8 (DM 23/06/2022, DM n. 256/2022, DM 5/8/2024), nessun D.M. 24.11.2025; capitolato G-06-ESEC-02 Cap. 5 p. 84 e indice p. 257: D.M. 23/06/2022, minimi cartongesso ≥ 10% (≥ 5% se a base gesso, p. 94); capitolato art. 8.2.5 p. 183 (FV): DM 11/10/2017; [[G-02-ESEC-01_ELENCO_PREZZI]] pp. 2-3 (B.08.007.01 ecc.): «DM 11/10/2017 (CAM)», riciclato > 20%. Le soglie del D.M. 24.11.2025 non sono riportate in alcun elaborato (TBD) | disciplinare per la conformità richiesta (D.M. 24.11.2025), ma le sue soglie non sono negli atti | **C4.2** («percentuale di materiale riciclato certificata (EPD) ... eccedente i minimi CAM», disciplinare p. 29): la baseline da superare è indeterminata (5-10%, > 20% o soglie 2025); C1.2: CAM arredi D.M. 254/2022 coerente | **Sì — Q2** (alta) | verificato |
| D12 | Capitolato art. 1.3 | anomalia interna (Fase A) | 394.370,46 in cifre, «/44» in lettere | — | formale | No | verificato |
| D13 | Capacità di accumulo di progetto | **confermata** | **15 kWh**: computo [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] voce 78 p. 15 (R.01.020.01, ioni di litio, 15 kWh; identica in ESEC-01 p. 15); [[RS-01-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_FOTOVOLTAICO]] p. 7 («n. 3 batterie ... 15 kwh»); [[RS-00-ESEC-01_RELAZIONE_TECNICA_IMPIANTI]] p. 11 («n. 4 batterie ... 15 kwh»); tavola [[PI-00-ESEC-01_PROGETTO_IMPIANTO_FOTOVOLTAICO]] («FV da 6 kWp trifase con accumulo da 15 kWh», «sistema di accumulo P = 6 kW, n. 3 moduli, C = 15 kWh», livello di testo). **20 kWh**: [[G-08-ESEC-01_RELAZIONE_GENERALE]] p. 15 («n. 4 batterie ... 20 kwh») e p. 24; [[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]] p. 9; [[RS-03-ESEC-01_RELAZIONE_ACUSTICA]] p. 9; [[G-09-ESEC-01_RELAZIONE_CAM]] pp. 14, 16. Inoltre [[G-10-ESEC-01_PIANO_DI_MANUTENZIONE]] p. 30: accumulatori «al piombo acido» contro litio di computo ed elenco prezzi (Nr. 118); capitolato art. 8.3.2 p. 185: capacità «$MANUAL$» | computo/elenco prezzi (15 kWh, litio): quantità contrattuale, confermata da relazione specialistica e tavola; il valore 20 kWh compare solo nella relazione generale e nei testi descrittivi che la riprendono | **C2.3** (7 pt), disciplinare p. 28: «Incremento quantitativo della capacità di accumulo delle batterie (>20 kWh)». Con base 15 kWh, un'offerta di 20 kWh è un incremento (+5 kWh) ma non supera la soglia: per prudenza l'offerta deve superare 20 kWh complessivi (inferito) | **Sì — Q1** (alta) | verificato |
| D14 | Ascensore: tipologia e caratteristiche | **confermata** | **Tipo** — idraulico/oleodinamico: disciplinare p. 29 sub 4.1 («impianto idraulico nel vano circolare»), G-08 p. 17, PSC p. 10, computo voce 96 p. 17 («Ascensore idraulico (oleoelettrico) ... EN 81-2»), G-02 Nr. 87 p. 8, G-10 UT 01.03 (pp. 11-24), tavola PI-02 (livello di testo); «elettrico a fune»: [[SIC-01-ESEC-01_CRONOPROGRAMMA]] p. 2 («Realizzazione di impianto ascensore elettrico», 5 g) e PSC p. 48 («ascensore elettrico a fune ... motore di trazione delle funi (in apposito locale in copertura)»; anche pp. 60, 63, 64, 84, 86, 102); G-08 p. 17 elenca «funi di trazione». **Caratteristiche** — G-08 p. 17 e PSC p. 10: 6 persone, 3 fermate, corsa utile 9 m, 0,63 m/s; computo voce 96 («capienza 8 persone, superficie minima della cabina 1,45 mq», descrizione troncata) ed elenco prezzi Nr. 87 (testo integrale: corsa utile 18 m, 6 fermate, 6 servizi, 0,50-0,60 m/s); voce 97: sovrapprezzo velocità fino a 0,80 m/s. L'edificio ha 3 livelli (+0,15 / +3,07 / +7,19, G-08 pp. 10-12): 3 fermate e corsa ≈ 7-9 m sono coerenti con G-08/PSC (inferito) | tipo: disciplinare (idraulico), la dicitura «elettrico a fune» è un residuo di template; caratteristiche: formalmente elenco prezzi/computo (capitolato art. 2.2), ma la voce D6.01.008.03 è la descrizione standard di tariffa non adattata all'edificio → **irrisolta** | **C4.1** (5 pt): dispositivi opzionali (telecontrollo, sintesi vocale, Braille avanzato, isolamento acustico) dimensionati su fermate e portata; cronoprogramma integrato: fase «ascensore elettrico» da allineare | **Sì — Q3** (media) + verifica al sopralluogo | verificato |
| D15 | Antincendio: sprinkler, idranti, naspi | **parziale** | **Sprinkler** — «sistemi di rilevazione incendi e impianti sprinkler» in G-08 p. 23, RS-03 p. 8, G-09 pp. 14-15: **errore confermato**, nessuno sprinkler nel computo/elenco prezzi, in [[RS-02-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_IDRICO_ANTINCENDIO]], nella tavola PI-06 e nelle tavole VV.F. **«Idranti a colonna sottosuolo»** (G-10 pp. 48-49): **smentita** come errore, il computo contabilizza la protezione esterna (voce 118 allacciamento PEAD Ø63, voce 119 idrante sottosuolo DN70 UNI 70 misurato «idrante esterno a colonna», voce 120 attacco motopompa VV.F., voce 121 cassetta esterna UNI 70, pp. 20-21) e le tavole VVF-PI-01…04 riportano «idrante soprasuolo / per la protezione esterna» e «attacco per motopompa». **Residuo** — RS-02 pp. 10-11, 15 e PI-06 descrivono solo 4 naspi DN25 UNI EN 671-1 (protezione interna), mentre il computo voce 122 prezza 4 «cassette da interno per idranti ... manichetta nylon 20 m ... UNI 45» misurate «naspi» (idranti a muro, EN 671-2) | computo per le quantità; RS-02 + PI-06 + pratica VV.F. (parere favorevole COM-PZ 20/04/2026) per la tipologia dei terminali interni (naspi DN25) | nessun sub-criterio premia l'antincendio; vincolo per C1.3/C3.3 (non ostacolare naspi e vie d'esodo; nessuno sprinkler da coordinare con controsoffitti e pannelli); differenza UNI 45/DN25 di modesto impatto economico, da chiarire con la DL | No | verificato (testi), parziale (tavole: livello di testo) |
| D16 | Importo lavori nel PSC | **confermata**, origine non ricostruibile | PSC [[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]] p. 2 «Importo presunto dei Lavori: 391´795,41 euro» contro 381.364,99 (A1) e 394.370,46 (A) del QE: +10.430,42 € / −2.575,05 €; nessuna relazione aritmetica con lavori, sicurezza, NP, manodopera o forniture (verifica aritmetica). Gli oneri del PSC (pp. 256-258) coincidono invece voce per voce con SIC-03 (12/12) | QE [[G-01-ESEC-02_QUADRO_ECONOMICO]] (`is_latest`) + disciplinare art. 3 | nessuno su offerta e criteri: dato anagrafico del PSC | No | verificato (valori), causa TBD |
| D17 | Unità FV e generatore di calore | **confermata** (entrambe) | FV — «6 kw»: G-08 p. 14, RS-00 p. 11, RS-01 p. 2, PSC p. 8; «6 kWh»: G-08 p. 24, RS-03 p. 8, G-09 pp. 14, 16; computo voce 70 (13 × 450 Wp = 5,85 kWp) e voce 77 (inverter 6 kW); RS-01 p. 3 (PVGIS) e tavola PI-00: 6 kWp. Generatore — caldaia a condensazione < 116 kW: G-08 p. 15, RS-00 p. 12, PSC p. 9, G-09 p. 27, computo voce 92 (D2.03.006.04 caldaia a basamento a condensazione 91-115 kW), tavola PI-04 (livello di testo); «pompe di calore»: G-08 p. 24, RS-03 p. 9, G-09 pp. 15-16, nessuna voce di pompa di calore in computo ed elenco prezzi | computo (5,85 kWp di moduli + inverter 6 kW; caldaia a condensazione) | C2.1: baseline in kWp, non kWh; C2.3 (Building Automation): la climatizzazione da gestire è caldaia + radiatori con valvole termostatiche, non pompe di calore; nessun impatto economico | No (risolta per gerarchia) | verificato |
| D18 | Numero di poltrone | **parziale** | «134 contro 107» **smentita**: G-08 p. 20 «platea ... due settori da 53 e 54 posti» = 107 posti di sola platea; la galleria ha 27 posti (tavole PA-00, PI-04, PI-05, VVF-PI-04-00, livello di testo) → 53 + 54 + 27 = **134** = G-08 p. 18, PSC p. 11, RS-03 p. 16, computo voce 102 (134 × NP 05; voce 101 rimozione di 120 esistenti). **Residuo confermato** — le tavole riportano configurazioni diverse: [[VVF-PI-03-00_PIANTA_PIANO_PRIMO]] (pratica VV.F. 21079, parere favorevole COM-PZ 20/04/2026 per «cineteatro con capienza inferiore a 200 posti») platea 53 + 48 posti fissi (1 per disabili ciascuno) + galleria 27 ([[VVF-PI-04-00_PIANTA_PIANO_SECONDO]]) = **128**; [[PI-03-ESEC-01_PROGETTO_IMPIANTO_IRAI]] «totale posti a sedere platea: 102, di cui 2 per disabili» (+ 27 = 129); [[PI-05-ESEC-01_INTERVENTI_ELETTRICI]] 54 + 49 + 27 = 130 | computo voce 102 per la fornitura (134); pratica VV.F. approvata per l'affollamento (128) | **C1.2** (scorta di rispetto, qualità poltrone): la base su cui calcolare la scorta cambia (134 o 128); 134 sedute fisse contro 128 della pratica approvata potrebbero richiedere l'aggiornamento della SCIA antincendio (inferito; capienza comunque < 200) | **Sì — Q4** (media) + verifica al sopralluogo | verificato (testi), parziale (tavole: livello di testo) |
| D19 | Categoria «OG2» nell'Elenco Elaborati | **confermata** | [[G-00-ESEC-01_ELENCO_ELABORATI]] p. 2: colonna «Categoria opere generali» = OG2 su tutti i 40 elaborati; disciplinare p. 8 (tabella categorie) e pp. 11-12 (requisiti SOA): **OG1** prevalente 185.390,73 € (48,613%) + OS3, OS4, OG9, OS30; capitolato G-06-ESEC-02 art. 1.3 pp. 3-4: OG1 (l'unica occorrenza di «OG 2» nel capitolato è l'elenco generico delle declaratorie, p. 8) | disciplinare + capitolato (OG1) | nessuno sui criteri; requisiti di partecipazione = OG1 | No — **sconsigliato** senza valutazione del professionista: una risposta che riqualificasse i lavori in OG2 (lavori su beni tutelati, disciplina speciale del Codice — inferito) cambierebbe i requisiti di partecipazione | verificato |

Nessuna contraddizione tra QE, stima sicurezza e PSC sugli oneri (13.005,47 € ovunque; SIC-03 e copia PSC pp. 256-258 identiche voce per voce, verificato in Fase E). Le versioni superate (G-01, G-04, G-06 ESEC-01) non introducono contraddizioni nuove oltre a quelle elencate (vedi §9).

**Pagine nodo aggiornate dalla Fase E.** Sezione «Contraddizioni rilevate» nella pagina più autorevole coinvolta: [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] (D13, D14, D15, D17, D18), [[G-01-ESEC-02_QUADRO_ECONOMICO]] (D1, D2, D3, D16), [[G-05-ESEC-01_QUADRO_INCIDENZA_MANODOPERA]] (D4), [[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]] (D7, D11, D19; il disciplinare non ha pagina nodo). Nota `# ATTENZIONE` nelle pagine più vecchie o meno autorevoli che riportano il valore in conflitto.

### 10.1 Quesiti proposti alla stazione appaltante (entro il 06/10/2026 ore 12:00)

Testi pronti da inoltrare via PAD; nessuno contiene elementi dell'offerta. Priorità: alta = condiziona la baseline di un sub-criterio; media = condiziona il dimensionamento di una miglioria; bassa = utile ma non bloccante.

**Q1 — Capacità di accumulo di progetto e soglia del sub-criterio 2.3 (alta, D13).** «Con riferimento al sub-criterio 2.3 "Incremento quantitativo della capacità di accumulo delle batterie (>20 kWh)", si rileva che gli elaborati indicano valori diversi per il sistema di accumulo di progetto: 15 kWh nel computo metrico estimativo G-04-ESEC-02 (voce R.01.020.01), nella relazione RS-01-ESEC-01 (p. 7), nella relazione RS-00-ESEC-01 (p. 11) e nella tavola PI-00-ESEC-01; 20 kWh (n. 4 batterie) nella relazione generale G-08-ESEC-01 (p. 15), nel PSC SIC-00-ESEC-01 (p. 9) e nelle relazioni RS-03-ESEC-01 e G-09-ESEC-01. Si chiede di confermare: a) la capacità di accumulo del progetto posto a base di gara; b) se l'indicazione "(>20 kWh)" vada intesa come capacità complessiva che l'offerta deve superare per conseguire punteggio, oppure se sia valutato ogni incremento rispetto alla capacità di progetto.»

**Q2 — Versione dei CAM e «minimi CAM» del sub-criterio 4.2 (alta, D11).** «Il disciplinare (Premesse, p. 3) richiede la conformità ai CAM di cui al D.M. 24.11.2025, richiamati nell'"Elaborato B3 – Relazione sui Criteri Minimi Ambientali". Tra gli elaborati pubblicati non risulta un elaborato B3: la relazione CAM G-09-ESEC-01 verifica i criteri ai sensi del D.M. 23/06/2022 e del D.M. 5/8/2024, il capitolato G-06-ESEC-02 (Cap. 5) richiama il D.M. 23/06/2022 e l'elenco prezzi G-02-ESEC-01 (voci di cartongesso) il D.M. 11/10/2017. Si chiede di chiarire: a) se l'"Elaborato B3" corrisponda alla relazione G-09-ESEC-01; b) quale decreto CAM costituisca il riferimento per i "minimi CAM" che le percentuali di materiale riciclato offerte nel sub-criterio 4.2 devono eccedere.»

**Q3 — Caratteristiche dell'ascensore di progetto (media, D14).** «Per il sub-criterio 4.1 il disciplinare si riferisce all'"impianto idraulico nel vano circolare". La relazione generale G-08-ESEC-01 (p. 17) e il PSC SIC-00-ESEC-01 (p. 10) descrivono un ascensore idraulico da 6 persone, 3 fermate, corsa utile 9 m, 0,63 m/s; il computo G-04-ESEC-02 (voce D6.01.008.03) e l'elenco prezzi G-02-ESEC-01 (Nr. 87) prevedono un ascensore oleodinamico da 8 persone con corsa utile 18 m e 6 fermate; il cronoprogramma SIC-01-ESEC-01 e il PSC (p. 48) indicano un "impianto ascensore elettrico a fune". Si chiede di confermare tipologia, portata, numero di fermate e corsa dell'impianto da assumere come configurazione di base per le integrazioni del sub-criterio 4.1.»

**Q4 — Numero e distribuzione delle poltrone (media, D18).** «Il computo G-04-ESEC-02 (voce NP 05) prevede la fornitura di 134 poltrone, coerentemente con la relazione generale G-08-ESEC-01 (pp. 18 e 20: platea 53 + 54 posti, oltre ai 27 della galleria). Le tavole della pratica di prevenzione incendi n. 21079 (VVF-PI-03-00 e VVF-PI-04-00) riportano invece 53 + 48 posti in platea e 27 in galleria (128 posti), la tavola PI-03-ESEC-01 102 posti in platea e la tavola PI-05-ESEC-01 54 + 49 posti in platea. Si chiede di confermare il numero di poltrone da fornire e la configurazione di riferimento della sala, anche ai fini della valutazione della "scorta di rispetto" di cui al sub-criterio 1.2.»

**Q5 — Costo della manodopera sulle voci a nuovo prezzo (bassa, facoltativo, D4).** «Il quadro di incidenza della manodopera G-05-ESEC-01, posto a base della stima dei costi della manodopera (€ 47.849,85, disciplinare art. 3), attribuisce costo della manodopera pari a zero a tutte le voci a nuovo prezzo, comprese la voce NP 16_D.02.083 (operaio impiantista, 96 ore) e le voci analizzate nell'elaborato G-03-ESEC-01, le cui analisi contengono quote di manodopera. Si chiede di confermare la stima dei costi della manodopera indicata nel disciplinare e se essa debba intendersi riferita alle sole voci desunte dal listino regionale.»

Non si propongono quesiti per D1, D2, D3, D7, D15, D16, D17 (risolte per gerarchia o senza impatto sull'offerta) né per D19 (vedi colonna «Quesito SA»).

## 11. Prezzario di riferimento e confronto prezzi

- Gli elaborati economici **non dichiarano** la tariffa né l'edizione; il disciplinare (p. 7) parla di «Listino regionale vigente». I codici (A.01…, B.10.001.01, D3.06.002.01, R.01.022.07, S.01.043.02, ecc.) hanno la struttura della **Tariffa Regione Basilicata** indicata in `PROJECT_CONFIG.json` (inferito).
- Il prezzario Basilicata **non è disponibile in cache** (prometeus-prezzari contiene solo Calabria 2025, non pertinente): **il confronto prezzi di progetto / prezzario (Analisi 2 «gap prezzi» di strategy-auditor) è rinviato**. Edizione e anno della tariffa: TBD.
- Le 19 voci NP (37,7% dei lavori) non sono confrontabili con alcun prezzario in ogni caso; per 5 di esse l'analisi G-03 consente un controllo per componenti (SG 15%, utile 10%, operaio a 25,71 €/h).

## 12. Altri parametri economici di gara

| Parametro | Valore | Fonte | Confidence |
|---|---|---|---|
| Garanzia provvisoria | 7.887,41 € (2% di 394.370,46) | disciplinare art. 10 | verificato |
| Anticipazione | 20% del prezzo contrattuale | disciplinare p. 8 (rinvio a capitolato art. 2.17) | verificato |
| Premio di accelerazione | vedi D7; fondo = imprevisti 7.386,68 € | disciplinare p. 8; capitolato art. 2.14; QE B3 | verificato |
| Durata lavori | 150 giorni naturali e consecutivi, comprese forniture e posa | disciplinare art. 3.1 | verificato |
| Offerta economica | ribasso unico % sul 381.364,99; 10 punti, formula bilineare X = 0,85 | criteria_matrix (disciplinare art. 17-18.3) | verificato |
| Finanziamento | «Cultura Missione Comune 2023» e «2026» | disciplinare p. 8 | verificato |

## 13. TBD residui

- Edizione/anno della tariffa regionale Basilicata usata dal progetto — non dichiarata negli elaborati.
- Confronto prezzi di progetto vs prezzario — rinviato (prezzario non in cache).
- Manodopera contenuta nei 13 NP senza analisi (incluse poltrone e allestimento) — non determinabile dagli elaborati.
- Causa dell'IVA lavori 59.428,23 € (D2; nessuna combinazione di aliquote la ricostruisce) e dell'IVA B9 h) 1.492,00 € (D3).
- Derivazione dell'accantonamento B6 di 5.000,00 € dall'Allegato I del computo.
- Origine dell'importo presunto dei lavori del PSC, 391.795,41 € (D16).
- Capacità di accumulo di progetto e lettura della soglia «>20 kWh» del sub C2.3 (D13) — in attesa della risposta al quesito Q1.
- Soglie di riciclato del D.M. 24.11.2025 da assumere come «minimi CAM» del sub C4.2 (D11) — quesito Q2.
- Portata, fermate e corsa dell'ascensore di base (D14) — quesito Q3 / sopralluogo.
- Numero di poltrone di riferimento, 134 o 128 (D18) — quesito Q4 / sopralluogo.
- ~~Confronto voce per voce tra SIC-03 e la copia nel PSC SIC-00 pp. 256-258~~ — chiuso in Fase E: 12/12 voci identiche.

## Per l'index

Righe da riportare nella sezione «Orfani e contraddizioni» di `02_graph/index.md` (le scrive l'invocazione 8; la Fase E non tocca l'index). Sono le contraddizioni **irrisolvibili senza lettura umana o risposta della SA**; dettaglio in §10, quesiti in §10.1.

- CONTRADDIZIONE: capacità di accumulo di progetto 15 kWh ([[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] voce 78, RS-01 p. 7, RS-00 p. 11, tavola PI-00) vs 20 kWh / 4 batterie ([[G-08-ESEC-01_RELAZIONE_GENERALE]] p. 15, PSC p. 9, RS-03 p. 9, G-09 pp. 14, 16); lettura della soglia «>20 kWh» del sub C2.3 (D13, quesito Q1) — verifica manuale richiesta
- CONTRADDIZIONE: CAM di riferimento D.M. 24.11.2025 (disciplinare p. 3, «Elaborato B3» inesistente) vs D.M. 23/06/2022 ([[G-09-ESEC-01_RELAZIONE_CAM]], [[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]] Cap. 5) vs DM 11/10/2017 ([[G-02-ESEC-01_ELENCO_PREZZI]], capitolato p. 183); «minimi CAM» del sub C4.2 indeterminati (D11, quesito Q2) — verifica manuale richiesta
- CONTRADDIZIONE: ascensore 8 persone / 6 fermate / corsa 18 m (computo voce 96, elenco prezzi Nr. 87) vs 6 persone / 3 fermate / corsa 9 m (G-08 p. 17, PSC p. 10); «elettrico a fune» ([[SIC-01-ESEC-01_CRONOPROGRAMMA]] p. 2, PSC p. 48) vs idraulico (disciplinare sub 4.1, computo) — baseline sub C4.1 (D14, quesito Q3) — verifica manuale richiesta
- CONTRADDIZIONE: numero di poltrone 134 (computo voce 102, G-08, PSC, RS-03) vs 128 (tavole VV.F. approvate [[VVF-PI-03-00_PIANTA_PIANO_PRIMO]] + [[VVF-PI-04-00_PIANTA_PIANO_SECONDO]]) / 129 (PI-03) / 130 (PI-05) — baseline sub C1.2 (D18, quesito Q4) — verifica manuale richiesta
- CONTRADDIZIONE: manodopera 0,00 su tutte le voci NP in [[G-05-ESEC-01_QUADRO_INCIDENZA_MANODOPERA]] vs ≥ 13.708,57 € in [[G-03-ESEC-01_ANALISI_NUOVI_PREZZI]] e NP 16 (PSC: 773 uomini-giorno) (D4, quesito Q5 facoltativo) — verifica manuale richiesta
- CONTRADDIZIONE: IVA sui lavori 59.428,23 € dichiarata «al 22%» (= 15,07% di A) in [[G-01-ESEC-02_QUADRO_ECONOMICO]]; causa non ricostruibile, nessun impatto sull'offerta (D2) — verifica manuale richiesta
- CONTRADDIZIONE: importo presunto dei lavori 391.795,41 € nel PSC [[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]] p. 2 vs 381.364,99 / 394.370,46 € del QE; origine non ricostruibile, nessun impatto sull'offerta (D16) — verifica manuale richiesta

Risolte per gerarchia delle fonti (da elencare nell'index come «risolte», senza verifica manuale): D1 Tabella 1 del disciplinare; D7 premio di accelerazione (prevale il disciplinare); D15 sprinkler inesistenti (residuo naspi DN25 / cassette UNI 45 da chiarire con la DL in esecuzione); D17 «6 kWh» e «pompe di calore» (prevale il computo); D19 OG2 nell'Elenco Elaborati (prevale OG1 del disciplinare).
