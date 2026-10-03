# Audit Strategico — Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)

**Generato il:** 2026-10-03
**Agente:** strategy-auditor
**Knowledge graph:** 02_graph/index.md (build del 2026-10-03, invocazione 8 di graph-builder: 53 nodi, 11 sintesi, 7 contraddizioni irrisolte, 5 quesiti SA)

> ℹ️ Questo audit riporta misure e classificazioni, non raccomandazioni. Nessun importo o percentuale qui riportato può comparire nei documenti dell'offerta tecnica (disciplinare art. 16 p. 26 e art. 22 p. 33: esclusione).

---

## 1. Budget sicurezza

**Fonte:** [[SIC-03-ESEC-01_COSTI_PER_LA_SICUREZZA]] — Costi per la sicurezza / totale p. 3, 12 voci (confidence: verificato); valori ripresi in [[economic_framework]] §1, §3, §8
**Importo oneri sicurezza:** € 13.005,47
**Importo lavori:** € 381.364,99 (lavori a misura soggetti a ribasso, QE [[G-01-ESEC-02_QUADRO_ECONOMICO]] A1 = computo [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] p. 23)
**Percentuale:** 3,41%
**Classificazione:** ⚠️ BASSO

> ⚠️ ATTENZIONE: Gli oneri per la sicurezza rappresentano il 3,41% dell'importo lavori, sotto la soglia indicativa del 5%.

Verifica del calcolo: 13.005,47 / 381.364,99 × 100 = 3,410%, identico al campo `oneri_sicurezza_pct: 3.410` di [[economic_framework]] (nessuna discrepanza). Sul totale A di 394.370,46 € l'incidenza è 3,298% ([[economic_framework]] §3, verificato).

Coerenza tra fonti: `fonte_sicurezza` elenca una sola fonte (SIC-03). Lo stesso importo compare in QE A4, disciplinare Tabella 1 riga B, bando II.2.1, capitolato [[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]] artt. 1.2 e 2.15 e nella copia interna del PSC [[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]] pp. 256-258 (12/12 voci identiche, confronto della Fase E): **nessuna contraddizione sugli oneri**. Il PSC p. 2 riporta un importo presunto dei lavori di 391.795,41 €, diverso dal QE (contraddizione D16, origine non ricostruibile): non incide sugli oneri.

**Composizione degli oneri** (da [[SIC-03-ESEC-01_COSTI_PER_LA_SICUREZZA]]; percentuali calcolate sul totale degli oneri)

| Gruppo di voci | Voci SIC-03 | Importo € | % sugli oneri | Confidence |
|---|---|---|---|---|
| Ponteggio a tubi e giunti, 195 mq (15 × 13 m) | 2 | 6.374,55 | 49,01 | verificato (valore), calcolo (%) |
| Teli/reti di schermatura del ponteggio, 195 mq | 4 | 1.117,35 | 8,59 | verificato (valore), calcolo (%) |
| **Subtotale ponteggio + teli** | 2 + 4 | **7.491,90** | **57,61** | verificato (valore), calcolo (%) |
| Monoblocco 6 mesi (1 + 5) | 6, 7 | 2.061,52 | 15,85 | verificato (valore), calcolo (%) |
| Parapetto provvisorio anticaduta, 110 m | 3 | 1.107,70 | 8,52 | verificato (valore), calcolo (%) |
| Trabattello mobile, 60 gg | 1 | 1.005,60 | 7,73 | verificato (valore), calcolo (%) |
| Recinzione (40 mq per 2 mesi + 160 mq per le frazioni successive) | 8, 9 | 850,40 | 6,54 | verificato (valore), calcolo (%) |
| Imbracature anticaduta | 5 | 472,80 | 3,64 | verificato (valore), calcolo (%) |
| Cartelli di divieto, obbligo, pericolo (3) | 10-12 | 15,55 | 0,12 | verificato (valore), calcolo (%) |
| **Totale** | 12 | **13.005,47** | 100 | verificato |

**Elementi rilevati nel grafo**

- Durata implicita degli apprestamenti: monoblocco e recinzione per 6 mesi, contro 150 giorni naturali di lavori (disciplinare art. 3.1): circa un mese oltre la durata contrattuale ([[SIC-03-ESEC-01_COSTI_PER_LA_SICUREZZA]], osservazioni; confidence: inferito).
- Ponteggio su un solo fronte, il prospetto Nord-Est (15 × 13 m), usato anche per il carico e lo scarico dei moduli FV in copertura (PSC pp. 13, 16; layout nella copia PSC pp. 259-260, lettura visiva parziale). In copertura le protezioni stimate sono i parapetti (110 m) e le imbracature.
- Misure citate o prescritte dal PSC **senza voce negli oneri** ([[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]], [[SIC-03-ESEC-01_COSTI_PER_LA_SICUREZZA]], sintesi `logistica_cantiere`; confidence: verificato):
  - gru: sottofase «Montaggio della gru a torre» (PSC p. 36), assente da cronoprogramma e costi; autogrù, gru su autocarro e sollevatori telescopici previsti per il carico/scarico (PSC p. 16);
  - protezione delle attrezzature esistenti di sala (impianto audio, proiettori, schermo) e aree di stoccaggio coperte: nessuna voce; il PSC prescrive solo la protezione generica di pavimentazioni, pareti e arredi con coperture temporanee (p. 13);
  - monitoraggio delle vibrazioni «durante le lavorazioni più invasive» (PSC p. 17) e abbattimento delle polveri (p. 20): nessuna voce;
  - regolazione del traffico e segnaletica temporanea sulle strade di accesso (PSC p. 18): nessuna voce oltre ai 3 cartelli;
  - interferenze con residenti e visitatori del Castello (PSC pp. 17, 24): nessuna voce dedicata.
- Entità presunta del lavoro: 773 uomini-giorno, 2 imprese (PSC p. 2, verificato). Rischio di caduta dall'alto valutato ALTO [P3×E4] per l'impianto FV (PSC p. 54).

---

## 2. Analisi prezzi — gap rispetto al prezzario

**Documento prezzi usato:** [[G-02-ESEC-01_ELENCO_PREZZI]] — G-02-ESEC-01_ELENCO_PREZZI.pdf (is_latest: true); quantità e importi da [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] (is_latest: true; esiste la versione precedente [[G-04-ESEC-01_COMPUTO_METRICO_ESTIMATIVO]], is_latest: false, con voci e prezzi identici)
**Prezzario di riferimento:** Basilicata, anno TBD — percorso non compilato (`PROJECT_CONFIG.json → gara.prezzario_riferimento`: regione «Basilicata», anno vuoto, percorso vuoto)
**Voci campionate:** 0 su 139 (confronto non eseguito)
**Copertura per importo:** non calcolata (nessuna voce confrontata)
**Categorie coperte:** non calcolate (nessuna voce confrontata)
**Gap medio:** N.D.
**Classificazione:** NON DISPONIBILE

> ℹ️ Confronto non eseguibile: il prezzario Basilicata (anno non indicato) non e' disponibile in `prometeus-prezzari`. Per abilitare questa analisi vedi il README di quel repo (estrazione da Excel ufficiale + pubblicazione di una release), poi riesegui strategy-auditor.

Stato della procedura:

- Il professionista ha rinviato l'analisi economica. `scripts/prezzario/fetch_prezzario.sh` non è stato eseguito.
- In `prometeus-prezzari` è presente solo il prezzario Calabria 2025 (nota in `PROJECT_CONFIG.json`), non pertinente: non è stato usato come sostituto, né per codice né per parola chiave.
- Nessuna tabella di voci e nessuna tabella di copertura per categoria: nessuna voce è stata confrontata, quindi nessun gap è stato misurato.

**Fatti del grafo utili a preparare il confronto futuro** (nessuna classificazione del gap)

| Dato | Valore | Fonte | Confidence |
|---|---|---|---|
| Voci di computo | 139 righe, 123 codici distinti | [[scope]] §1; [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] | verificato |
| Quota a nuovi prezzi (NP) | 143.667,94 € = **37,67%** dell'importo lavori; 20 righe, 19 codici | [[economic_framework]] §3; [[scope]] §5 | verificato |
| — NP con analisi in G-03 | 5 codici (NP 001-005), 63.401,75 € | [[G-03-ESEC-01_ANALISI_NUOVI_PREZZI]] pp. 12-16 | verificato |
| — NP senza analisi | 14 codici / 15 righe, **80.266,19 €** (21,05% dell'importo lavori), comprese le poltrone NP 05 (30.923,18 €) e il palco e allestimento scenografico NP 07 (16.000,00 €) | [[G-03-ESEC-01_ANALISI_NUOVI_PREZZI]]; [[economic_framework]] §3, D5 | verificato |
| Quota da tariffa regionale | **237.697,05 €** = 62,33%; 119 righe, 104 codici | [[economic_framework]] §3 | verificato |
| Tariffa ed edizione | gli elaborati **non dichiarano** né la tariffa né l'edizione/anno; il disciplinare (p. 7) parla di «Listino regionale vigente»; l'attribuzione alla tariffa Regione Basilicata deriva dalla struttura dei codici (A., B., D1-D6., E., H., O., R., S.; es. B.10.001.01) | [[economic_framework]] §11, §13; [[G-02-ESEC-01_ELENCO_PREZZI]] | inferito (tariffa); TBD (edizione/anno) |
| Codici anomali | voce 128 E.00050 «sabbia di cava», 175,00 €: formato diverso dalla tariffa, non NP, senza analisi (D9); voce 37 B.18.071.10 a quantità e prezzo zero, assente da G-02 (D8) | [[economic_framework]] §10; [[scope]] §4 | verificato |

Capitoli del computo che pesano almeno il 5% dell'importo lavori (da [[economic_framework]] §5 e [[scope]] §3; la skill definisce la categoria sul primo livello del codice tariffa, il grafo documenta la ripartizione per capitolo):

| Capitolo | Peso sull'importo | di cui NP € | Righe da tariffa | Confidence |
|---|---|---|---|---|
| Impianto aspirazione forzata fumi e calore | 13,329% | 50.833,39 (100%, NP 005 con analisi) | 0 | verificato |
| Ascensore - impianto elettrico vano ascensore | 11,410% | 3.000,00 | 4 | verificato |
| Impianto elettrico | 8,990% | 14.026,56 | 13 | verificato |
| Poltrone | 8,423% | 32.123,18 (100%, senza analisi) | 0 | verificato |
| Opere in cartongesso | 7,976% | 0,00 | 8 | verificato |
| Impianto Fotovoltaico | 7,090% | 0,00 | 22 | verificato |
| Impermeabilizzazioni | 7,087% | 1.315,60 | 5 | verificato |
| Pavimentazione | 6,109% | 0,00 | 6 | verificato |
| Palco e allestimento scenografico | 6,076% | 23.173,25 (100%, senza analisi) | 0 | verificato |
| Infissi | 5,908% | 0,00 | 13 | verificato |

Tre di questi dieci capitoli (aspirazione fumi, poltrone, palco e allestimento: 27,83% dell'importo lavori) non contengono alcun codice di tariffa: nessuna loro voce è confrontabile con un prezzario regionale ([[economic_framework]] §11).

---

## 3. Posizione e viabilita' cantiere

**Fonti:** [[G-08-ESEC-01_RELAZIONE_GENERALE]] (relazione generale), [[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]] (PSC); a supporto [[SIC-01-ESEC-01_CRONOPROGRAMMA]], [[SIC-02-ESEC-01_LAYOUT_DI_CANTIERE]] (tavola non letta; copia nel PSC pp. 259-260, lettura visiva parziale), [[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]], disciplinare art. 11, sintesi `02_graph/synthesis/logistica_cantiere.md`
**Localizzazione estratta:** Via Guglielmo Marconi, 85051 Bella (PZ) (PSC p. 2); sala in un'ala del Castello Aragonese, di proprietà comunale, alla sommità del centro storico (G-08 p. 4; PSC pp. 13, 17); accesso da «un ampio piazzale accessibile agli automezzi (piazzale Periz)» (G-08 p. 10)
**Classificazione:** SFAVOREVOLE

Condizioni della skill:

| Condizione SFAVOREVOLE | Esito | Fonte |
|---|---|---|
| Centro storico o zona con ZTL | presente: centro storico di impianto medievale; ZTL non citata | PSC pp. 17-18; G-08 p. 4 |
| Strade di accesso citate come strette o con limitazioni | presente: strade «strette, con tracciati irregolari e pendenze accentuate» | PSC p. 18 |
| Divieti di transito mezzi pesanti citati esplicitamente | non come divieto: strade «spesso non progettate per il transito di mezzi pesanti o di grandi dimensioni» (descrizione); mezzi «necessariamente di dimensioni ridotte» (prescrizione del PSC) | PSC p. 18 |
| Orari di cantiere vincolati dalla normativa locale | nessuna norma locale citata; il PSC prescrive consegne «in fasce orarie controllate» e lavori esterni estivi nelle prime ore del giorno o dopo le 16:00 (microclima) | PSC p. 17 |

Nessuna condizione FAVOREVOLE rilevata: il sito non è in zona industriale o periferica, nessun accesso diretto da strade provinciali o autostrade è citato, la viabilità di accesso non è descritta come ampia.

**Elementi rilevati:**

- Viabilità: «L'impianto urbano di origine medievale, caratterizzato da strade strette, pendenze accentuate e spazi limitati, rende difficoltoso l'accesso e la movimentazione di mezzi e materiali» (PSC p. 17).
- Mezzi e approvvigionamenti: mezzi «necessariamente di dimensioni ridotte», «stoccaggio limitato in cantiere e frequenti approvvigionamenti frazionati»; «nei casi più critici» trasporto manuale o con attrezzature ausiliarie (PSC p. 18).
- Consegne e traffico: regolazione degli accessi al centro storico e consegne «in fasce orarie controllate» (PSC p. 17); regolazione del traffico e segnaletica temporanea per la limitata larghezza delle carreggiate (PSC p. 18).
- Area esterna di cantiere: occupazione temporanea della piazzetta antistante il teatro su via Guglielmo Marconi per baraccamenti, stoccaggio materiali, ricovero di mezzi e attrezzature, aree di lavorazione e area rifiuti (PSC p. 13). Tasse e oneri per l'occupazione temporanea di suolo pubblico a carico dell'appaltatore ([[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]] art. 2.22).
- Accessi e sollevamenti: ingresso/uscita dal piazzale tramite cancelli, solo veicoli leggeri a 10-15 km/h con assistenza a terra (PSC p. 23); carico/scarico con autogrù, gru su autocarro o sollevatori telescopici (PSC p. 16); ponteggio sul fronte anteriore per il carico/scarico in copertura, con verifica dei sovraccarichi da parte del committente (PSC pp. 13, 16).
- Layout: accesso carrabile e pedonale, area movimentazione mezzi, ufficio DL, cassone rifiuti, stoccaggio materiali, percorso pedonale; ponteggio fisso sul prospetto Nord-Est; aree di stoccaggio materiali e rifiuti **interne a ogni piano** e sul terrazzo (copia PSC pp. 259-260, confidence: parziale). Stoccaggio senza sovraccaricare i solai, percorsi separati per operatori e materiali (PSC p. 13).
- Interferenze: residenti e visitatori; il Castello ospita mostre ed eventi; visitatori ammessi solo in alcuni spazi, chiusura completa concordabile con i gestori (PSC pp. 16, 24); edifici storici contigui e murature antiche con possibili vibrazioni (PSC p. 17).
- Clima: posizione sopraelevata esposta al vento; lavori esterni estivi nelle prime ore del giorno o dopo le 16:00 (PSC p. 17).
- Tempi: 150 giorni naturali e consecutivi comprese forniture e posa (disciplinare art. 3.1; capitolato art. 2.6). Cronoprogramma [[SIC-01-ESEC-01_CRONOPROGRAMMA]]: 109 giorni lavorativi in 9 gruppi (allestimento 12, copertura 17, interni 40, impianti 23, sala e palco 1, FV 2, pitturazioni 4, finiture esterne 2, smobilizzo 8), zona unica Z1, fasi in sequenza stretta senza sovrapposizioni (verificato). Il calendario del Gantt va da fine maggio a fine ottobre 2026 ed è indicativo: l'aggiudicazione segue il 14/10/2026, il periodo effettivo di esecuzione è TBD.
- Lavorazioni senza fase nel cronoprogramma: infissi esterni, cupola (impermeabilizzazione e oscuramento), rivestimenti MDF e resina, naspi, IRAI, evacuazione fumi oltre ai fori, building automation, accumulo, smontaggio/protezione delle attrezzature esistenti (SIC-01 p. 2, verificato per assenza).
- Incoerenze del PSC sulla logistica: sottofase «Montaggio della gru a torre» (p. 36) assente da cronoprogramma e costi; residui di altri progetti «all'interno della chiesa» (p. 23) e «allegato H» (p. 24).
- Sopralluogo obbligatorio, motivato dalle «peculiari condizioni logistiche, distributive e operative» del sito (accessibilità, introduzione, movimentazione e deposito di materiali e mezzi, spazi per il cantiere, interferenze): richiesta entro il 05/10/2026 ore 12:00; la mancata effettuazione rende l'offerta inammissibile (disciplinare art. 11, pp. 16-17).

---

## 4. Capacita' di investimento migliorativo

**Gap medio vs prezzario:** N.D. (Analisi 2 NON DISPONIBILE)
**Importo lavori:** € 381.364,99 (da economic_framework.md, confidence: verificato)
**Margine teorico complessivo:** non calcolato
**Classificazione:** NON CALCOLABILE

**Categorie con maggiore spazio di investimento:**
| Voce | Gap% |
|---|---|
| nessuna voce confrontata | N.D. |

**Categorie con minore spazio (o gap negativo):**
| Voce | Gap% |
|---|---|
| nessuna voce confrontata | N.D. |

> ℹ️ Calcolo non eseguibile: Analisi 2 non disponibile (prezzario mancante). Aggiungere il prezzario e rieseguire l'audit per ottenere questa stima.

**Dati del grafo che delimitano la capacità di investimento** (non sono una misura del margine)

| Elemento | Dato | Fonte | Confidence |
|---|---|---|---|
| Migliorie a carico dell'appaltatore | «Sono altresì compresi, se recepiti dalla Stazione appaltante, i miglioramenti e le previsioni migliorative e aggiuntive contenute nell'offerta tecnica presentata dall'appaltatore, senza ulteriori oneri per la Stazione appaltante» | capitolato [[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]] art. 1.1 p. 2 | verificato |
| Verifica di anomalia | anormalmente basse le offerte «la cui particolare incidenza economica e organizzativa delle migliorie proposte nell'Offerta Tecnica, ove la loro concreta realizzazione, unitamente alle prestazioni previste dal progetto posto a base di gara, faccia emergere dubbi in ordine alla complessiva sostenibilità economica dell'offerta» | disciplinare art. 23 p. 33 | verificato |
| Ripartizione dei punteggi | tecnica 90 (80 discrezionali C1-C4 + 10 tabellari C5-C7), economica 10, tempo 0 | `03_criteria/criteria_matrix.md`; disciplinare art. 18 | verificato |
| Formula economica | ribasso unico % sui 381.364,99 €; bilineare con X = 0,85, Asoglia = media dei ribassi; punteggio = Ci × 10 | disciplinare art. 18.3 p. 31 | verificato |
| Soglia di sbarramento | 50/90 sul punteggio tecnico, calcolata prima della riparametrazione; sotto soglia esclusione | disciplinare art. 18.1 p. 30; art. 22 | verificato |
| Riparametrazione | per singolo sub-criterio | disciplinare art. 18.4 p. 31 | verificato |
| Costo della manodopera dichiarato | 47.849,85 € = 12,547% dei lavori; 0,00 su tutte le 19 voci NP (143.667,94 €) — contraddizione D4 | [[G-05-ESEC-01_QUADRO_INCIDENZA_MANODOPERA]]; [[economic_framework]] §3, §10 | verificato |
| Manodopera esplicita esclusa da G-05 | almeno 13.708,57 € (11.240,41 € nelle 5 analisi G-03 + 2.468,16 € della voce NP 16 «operaio impiantista C3»), circa +28,6% sul dichiarato; quota nei 13 NP senza analisi TBD; il PSC stima 773 uomini-giorno, circa 158.990 € (3,3 volte G-05, stima software) | [[economic_framework]] §3, D4 | verificato (valori), inferito (sottostima) |
| Quesito sulla manodopera | Q5 (priorità bassa, facoltativo): conferma della stima e riferimento alle sole voci di listino | [[economic_framework]] §10.1 | verificato |
| Forniture di arredo | 55.296,43 € = 14,5% dei lavori, 100% NP, manodopera 0,00 | [[economic_framework]] §1, §5 | verificato |
| Premio di accelerazione | 0,5% al giorno dell'ammontare netto contrattuale, max 10%, «nei limiti delle somme ... alla voce imprevisti» (prevale sul capitolato art. 2.14: 0,3‰ e tetto 5%, D7); tetto effettivo = imprevisti QE B3 7.386,68 € IVA compresa (circa 6.054,66 € netti, 1,6% dei lavori), esaurito con circa 3 giorni di anticipo; nessun punteggio sul tempo | disciplinare p. 8; [[economic_framework]] D7, §12 | verificato (valori), inferito (giorni) |
| Revisione prezzi | riconosciuto il 90% della variazione oltre il 3% (art. 60 D.Lgs. 36/2023); accantonamento QE B6 5.000,00 € (derivazione TBD) | capitolato art. 2.17 p. 27; [[economic_framework]] §6 | verificato |
| Baseline in contraddizione che condizionano il dimensionamento delle migliorie | D13 accumulo 15 vs 20 kWh (C2.3, quesito Q1); D11 versione CAM (C4.2, Q2); D14 ascensore 8 pers./6 fermate vs 6 pers./3 fermate (C4.1, Q3); D18 poltrone 134 vs 128 (C1.2, Q4) | [[economic_framework]] §10, §10.1 | verificato |
| Elementi senza alcuna voce a computo | antintrusione/TVCC (C2.2), isolamento termico della copertura (C3.1), attrezzature audio/proiezione/schermo (C3.2), protezione delle attrezzature esistenti (C3.3) | [[scope]] §2 | verificato |

---

## Domande chiave per il professionista

1. Il budget sicurezza del 3,41%, sotto la soglia indicativa del 5%, copre adeguatamente i rischi di cantiere identificati, visto che ponteggio e teli assorbono il 57,6% degli oneri e che mancano voci per gru, protezione delle attrezzature esistenti e monitoraggio delle vibrazioni (prescritto dal PSC p. 17)? Come vengono trattati nell'offerta i costi di queste misure non stimate, e si aggiunge un quesito alla SA sugli oneri (non coperti da Q1-Q5) entro il 06/10/2026 ore 12:00?
2. Il confronto prezzi è rinviato e l'edizione della tariffa Basilicata usata dal progetto non è dichiarata negli elaborati (il disciplinare cita il «Listino regionale vigente», p. 7): entro quale data, rispetto al termine offerte del 14/10/2026 ore 12:00, si esegue il confronto sulla quota da tariffa (237.697,05 €, 62,33% dei lavori), e l'edizione di riferimento si chiede alla SA entro il 06/10/2026 ore 12:00 (non coperta da Q1-Q5) o si ricava in altro modo?
3. I vincoli di viabilità identificati (centro storico medievale, strade strette e in pendenza, mezzi di piccole dimensioni, consegne in fasce orarie, approvvigionamenti frazionati, unica area esterna nella piazzetta su via G. Marconi) sono stati considerati nel cronoprogramma (109 giorni lavorativi in fasi strettamente sequenziali, zona unica) e nel PSC, e quali di essi (dimensioni ammesse dei mezzi, posizionamento di autogrù, aree di stoccaggio protetto, convivenza con visitatori ed eventi del Castello) si verificano al sopralluogo obbligatorio, da richiedere entro il 05/10/2026 ore 12:00?
4. Senza la misura del gap prezzi (margine NON CALCOLABILE), su quale base si fissa la quota di risorse destinabile alle migliorie, tenuto conto che le migliorie sono «senza ulteriori oneri» per la SA (capitolato art. 1.1), che la verifica di anomalia guarda alla loro incidenza economica e organizzativa (disciplinare art. 23), che la manodopera dichiarata (47.849,85 €) esclude almeno 13.708,57 € contenuti nelle voci NP (D4) e che l'offerta economica vale 10 punti (bilineare X = 0,85) contro 80 punti discrezionali con soglia di sbarramento 50/90? Il quesito facoltativo Q5 sulla manodopera si invia?
5. Quali dei quesiti Q1-Q5 già redatti in economic_framework §10.1 (Q1 accumulo, Q2 CAM, Q3 ascensore, Q4 poltrone, Q5 manodopera) si inviano entro il 06/10/2026 ore 12:00, considerando che le risposte sono attese entro l'08/10/2026, che Q1-Q4 fissano le baseline (C2.3, C4.2, C4.1, C1.2) su cui si dimensiona il costo delle migliorie e che D14 (ascensore) e D18 (poltrone) sono verificabili anche al sopralluogo?
6. Quale delle quattro analisi ha la priorita' maggiore per la costruzione dell'offerta tecnica?

---

## Riepilogo

| Analisi | Classificazione | Alert |
|---|---|---|
| Budget sicurezza | BASSO | ⚠️ Oneri 13.005,47 € = 3,41% dei lavori (381.364,99 €), sotto la soglia indicativa del 5%; ponteggio + teli = 57,6% degli oneri; nessuna voce per gru, protezione delle attrezzature esistenti, monitoraggio vibrazioni |
| Gap prezzi | NON DISPONIBILE | Prezzario Basilicata non disponibile in prometeus-prezzari; edizione/anno della tariffa non dichiarati negli elaborati; confronto rinviato dal professionista; 37,67% dei lavori a NP non confrontabile con alcun prezzario |
| Viabilita' cantiere | SFAVOREVOLE | Centro storico medievale: strade strette e in pendenza, mezzi di piccole dimensioni, consegne in fasce orarie, approvvigionamenti frazionati; unica area esterna nella piazzetta su via G. Marconi; sopralluogo obbligatorio (richiesta entro 05/10/2026 ore 12:00) |
| Investimento migliorativo | NON CALCOLABILE | — nessun margine calcolato (Analisi 2 non disponibile) |

---

## Indicazioni strategiche del professionista

> Compilare questa sezione dopo la lettura dell'audit.
> Le indicazioni guidano l'analisi dei criteri nelle fasi successive.

### Risposte alle domande chiave

1. Domanda 1 (budget sicurezza): [risposta]
2. Domanda 2 (confronto prezzi): [risposta]
3. Domanda 3 (viabilità e sopralluogo): [risposta]
4. Domanda 4 (risorse per le migliorie): [risposta]
5. Domanda 5 (quesiti Q1-Q5): [risposta]
6. Domanda 6 (priorità tra le analisi): [risposta]

### Direttive operative (indicazioni strategiche)

- Tono generale (conservativo / bilanciato / audace): [da compilare]

**Priorita' per criterio:**
- C1 — Involucro, Poltrone ed Efficientamento Acustico (25 pt): [indicazione]
- C2 — Energie Rinnovabili e Sistemi di Sicurezza (30 pt): [indicazione]
- C3 — Logistica Cantieri e Dotazioni Cinematografiche (15 pt): [indicazione]
- C4 — Accessibilità Universale e Criteri CAM (10 pt): [indicazione]
- C5 — Esperienza specifica pregressa (6 pt, tabellare): [indicazione]
- C6 — Criteri premiali art. 57 e Allegato II.3 (2 pt, tabellare): [indicazione]
- C7 — Criteri premiali art. 108 co. 7 (2 pt, tabellare): [indicazione]

**Vincoli specifici:**
- [vincolo]

**Opportunita' da valorizzare:**
- [opportunita']

**Note aggiuntive:**
- [testo libero]
