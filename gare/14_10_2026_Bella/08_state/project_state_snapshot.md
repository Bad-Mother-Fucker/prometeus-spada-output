# Snapshot stato progetto — Cineteatro «Sala Polifunzionale Periz», Castello di Bella (PZ)

**Aggiornato il:** 2026-10-03 13:25 CEST
**Agente:** context-monitor (unico autorizzato a scrivere questo file)
**Evento:** chiusura Fase 1 — analisi preliminare completata
**Stato in PROJECT_CONFIG.json:** `analisi_preliminare_completata` (ultimo aggiornamento 2026-10-03T13:23:25+02:00)
**Punto del workflow:** STOP OBBLIGATORIO #1 aperto — in attesa delle risposte del professionista all'audit strategico

> ALERT — SCADENZE. Richiesta di **sopralluogo OBBLIGATORIO entro lun 05/10/2026 ore 12:00** (pena inammissibilità, art. 11). Quesiti di chiarimento entro **mar 06/10/2026 ore 12:00** (risposte della SA entro gio 08/10/2026). Caricamento offerte entro **mer 14/10/2026 ore 12:00**. Oggi: sab 03/10/2026, 11 giorni alla scadenza offerte.

---

## 1. Gara

| Voce | Valore | Fonte |
|---|---|---|
| Gara | Lavori di adeguamento ed efficientamento energetico del Cineteatro «Sala Polifunzionale Periz», Castello di Bella (PZ) | `PROJECT_CONFIG.json` |
| Codice interno | 14_10_2026_Bella | `PROJECT_CONFIG.json` |
| CIG / CUP | BCF01395AF / D63I23000230009 | `PROJECT_CONFIG.json` |
| Stazione appaltante | Comune di Bella (PZ), Area III LL.PP. (RUP ing. Vito Menza); PAD ASMECOMM | `PROJECT_CONFIG.json` |
| Procedura | aperta telematica art. 71 D.Lgs. 36/2023, OEPV; appalto misto lavori + forniture, lotto unico | `PROJECT_CONFIG.json` |
| Importo | € 381.364,99 soggetti a ribasso (manodopera € 47.849,85) + € 13.005,47 sicurezza = € 394.370,46 IVA esclusa | disciplinare art. 3, Tab. 1 |
| Punteggi | tecnica 90 (80 D su C1-C4 + 10 T su C5-C7), economica 10 (bilineare X = 0,85), tempo 0 | [criteria_matrix](../03_criteria/criteria_matrix.md) |
| Soglia di sbarramento | 50/90 sul tecnico, prima della riparametrazione | art. 18.1 p. 30 |
| Durata | 150 giorni naturali consecutivi (fissa, nessun punteggio) | art. 3.1 p. 8 |
| Pubblicazione output | repository `prometeus-spada-output`, branch `main`, path `gare/` | `PROJECT_CONFIG.json` → remote_output (DEC-002) |

## 2. Fase corrente

| Fase / passo | Stato | Output verificato su file |
|---|---|---|
| Fase 1.1 — Preprocessing | completata | `00_input/_manifest_input.md`, `01_extracted/` |
| Fase 1.2 — Analisi disciplinare | completata | `03_criteria/criteria_matrix.md` + `.json`, `criteria_checklist.md`, `criteria/criterion_C1…C7.md`, `gara_brief.md`, `PROJECT_CONFIG.json → deliverables` (C1-C7 + trasversali) |
| Fase 1.3 — Knowledge graph (8 invocazioni graph-builder) | completata | `02_graph/index.md` (rebuild invocazione 8), `scope.md`, `economic_framework.md`, `log.md`, 53 nodi, 11 sintesi |
| Fase 1.4 — Audit strategico | completata | `03_criteria/strategy_audit.md` |
| STOP #1 — feedback sull'audit strategico | **APERTO** | sezione «Indicazioni strategiche del professionista» di `strategy_audit.md` ancora a segnaposto |
| STOP #2 — scelta criteri | non presentato | bloccato da STOP #1 |
| Fase 2 — Analisi criteri | non avviata | `04_doc_summaries/`, `05_criteria_outputs/`, `06_registers/`, `02_graph/proposals/` vuote |
| Fase 3 — Snapshot | eseguita (questo file) | `08_state/` |
| Stesura offerta (offer-writer) | non avviata | `10_offer/` vuota; `vincoli_offerta_tecnica.md` Sezione B non compilata |

## 3. Criteri estratti

| ID | Titolo | Pt | Natura | Sottocriteri (pt) | Analizzato | Feedback | Stato |
|---|---|---|---|---|---|---|---|
| C1 | Involucro, Poltrone ed Efficientamento Acustico | 25 | D | C1.1 (10) · C1.2 (7) · C1.3 (8) | no | — | da analizzare |
| C2 | Energie Rinnovabili e Sistemi di Sicurezza | 30 | D | C2.1 (15) · C2.2 (8) · C2.3 (7) | no | — | da analizzare |
| C3 | Logistica Cantieri e Dotazioni Cinematografiche | 15 | D | C3.1 (5) · C3.2 (5) · C3.3 (5) | no | — | da analizzare |
| C4 | Accessibilità Universale e Criteri CAM | 10 | D | C4.1 (5) · C4.2 (5) | no | — | da analizzare |
| C5 | Esperienza specifica pregressa | 6 | T | C5.1 (6) — 1 pt per intervento analogo, max 6 | no | — | da analizzare |
| C6 | Criteri premiali art. 57 e All. II.3 D.Lgs. 36/2023 | 2 | T | C6.1 (2) — L. 68/1999 ultimo triennio | no | — | da analizzare |
| C7 | Criteri premiali art. 108 co. 7 D.Lgs. 36/2023 | 2 | T | C7.1 (2) — UNI/PdR 125:2022 | no | — | da analizzare |
| | **Totale** | **90** | | 14 sottocriteri | 0/7 | 0/7 | |

Fonte: `PROJECT_CONFIG.json → criteri_stato` (tutti `analizzato: false`, `stato_feedback: null`); nessun file `05_criteria_outputs/Cx_output.md` esistente, quindi nessun `stato_feedback: in_attesa`.

## 4. Vincoli critici dal disciplinare

- **Sopralluogo obbligatorio**: richiesta su PAD entro 05/10/2026 ore 12:00 con nominativo e qualifica; senza sopralluogo offerta inammissibile (art. 11, pp. 16-17).
- **Relazione tecnica unica**: max 15 pagine fronte-retro = 30 facciate A4 numerate, font ≥ 11 pt, struttura per criteri e sub-criteri; limite totale distribuibile, nessun limite per sub-criterio; esclusi dal conteggio copertine, sommari, elaborati grafici, schede tecniche esplicative (art. 16, p. 25).
- **Allegati obbligatori**: computo metrico NON estimativo delle migliorie e cronoprogramma integrato con le migliorie (art. 16, pp. 25-26).
- **Nessun elemento economico in Busta B** (prezzi, importi, ribassi, percentuali, valorizzazioni) pena esclusione (art. 16, p. 26; art. 22, p. 33).
- **Caratteristiche minime** dei documenti di gara da rispettare pena esclusione, principio di equivalenza (art. 16, p. 25).
- **Soglia di sbarramento 50/90** prima della riparametrazione; riparametrazione per singolo sub-criterio (art. 18.1 p. 30; art. 18.4 p. 31).
- **Nessun soccorso istruttorio** sull'offerta tecnica (art. 14, p. 19).
- **Verifica di anomalia** sull'incidenza economica e organizzativa delle migliorie (art. 23, p. 33); migliorie «senza ulteriori oneri» per la SA (capitolato G-06-ESEC-02 art. 1.1).
- **CAM**: D.M. 24.11.2025 (edilizia) e D.M. 254/2022 (arredi), Premesse p. 3 — in contraddizione con gli elaborati (D11).
- **C2.1**: formulazione con riferimento a PI-00a-ESEC-01 e conformità agli indirizzi di tutela della Soprintendenza Basilicata (p. 28).
- **C7.1**: in RTI la certificazione UNI/PdR 125:2022 deve essere di tutti i componenti (p. 30).
- **Dichiarazione sull'uso di IA** nell'offerta tecnica da rendere nella domanda, Busta A (art. 15.1, p. 21).
- Escluse offerte parziali, plurime, condizionate, alternative (art. 22, p. 33).

## 5. Documenti analizzati

**Input censiti:** 56 file in `00_input/` — 53 con pagina nodo + 3 senza (disciplinare e bando: fonte di `03_criteria/`; `norme.tecniche`: non pertinente).
**Knowledge graph:** 53 nodi · 11 sintesi · 367 archi (114 documento→criterio + 253 documento→documento) · 3 orfani · 7 contraddizioni irrisolte · 5 risolte per gerarchia · 7 anomalie interne · 5 quesiti SA.
**Schede `04_doc_summaries/`:** 0 (lettura approfondita prevista in Fase 2, per criterio).

| Gruppo | N. | Stato | ID |
|---|---|---|---|
| Testuali/economici estratti | 23 | 21 verificato, 2 parziale (G-07 foto, RS-01 pp. 3-5) | G-00-ESEC-01 · G-01-ESEC-01 (superato) · G-01-ESEC-02 · G-02-ESEC-01 · G-03-ESEC-01 · G-04-ESEC-01 (superato) · G-04-ESEC-02 · G-05-ESEC-01 · G-06-ESEC-01 (superato) · G-06-ESEC-02 · G-07-ESEC-01 · G-08-ESEC-01 · G-09-ESEC-01 · G-10-ESEC-01 · G-11-ESEC-01 · RS-00-ESEC-01 · RS-01-ESEC-01 · RS-02-ESEC-01 · RS-03-ESEC-01 · SIC-00-ESEC-01 · SIC-01-ESEC-01 · SIC-03-ESEC-01 · COM-PZ.REGISTRO-UFFICIALE.2026.0007341 (parere VV.F.) |
| Tavole non estratte (archi inferiti) | 30 | da leggere con drawing-reader prima di citarle come evidenza | IT-00 · IT-01 · IT-02 · IT-03 · RIL-00 · RIL-01 · RIL-02 · PA-00 · PA-01 · PA-02 · PA-03 · PA-04 · PA-05 · PI-00 · PI-00a · PI-01 · PI-02 · PI-03 · PI-04 · PI-05 · PI-06 · SIC-02 · VVF-PI-01 … VVF-PI-08 |
| Tavole `alta` da leggere per prime | 5 | non lette | PI-00a-ESEC-01 (C2.1, rinvio espresso del disciplinare) · PI-00-ESEC-01 (C2.1, C2.3) · PA-05-ESEC-01 (C3.1) · SIC-02-ESEC-01 (C3.3) · PA-03-ESEC-01 (C4.1) |
| Orfani | 3 | da decidere con `/resolve_orphan` | IT-00-ESEC-01 · PI-06-ESEC-01 · VVF-PI-01-00 |
| Sintesi tematiche | 11 | complete | acustica_sala · antincendio · ascensore · cam_ed_economia_circolare · copertura_terrazzi_e_cupola · dotazioni_audio_video_scena · fotovoltaico_e_accumulo · logistica_cantiere · sala_e_poltrone · serramenti_e_ponti_termici · tutela_castello_e_impatto_visivo |

Versioni: G-01, G-04, G-06 → baseline ESEC-02 (`is_latest: true`); ESEC-01 solo per confronto.

## 6. Gap rilevati

**Gap formali (G-Cx-nnn):** nessuno — gli ID si assegnano in Fase 2 (criterion-agent).
**Segnali pre-gap dal grafo** (baseline [scope](../02_graph/scope.md) §2 ed evidenza debole [index](../02_graph/index.md) §8; non sono gap validati):

| Sub | Pt | Cosa il progetto NON prevede | Evidenza debole / dipendenza |
|---|---|---|---|
| C1.1 | 10 | nessuna voce per nodo di posa oltre UNI 11673; nessuna superficie vetrata aggiuntiva | Uw/Uf/Rw solo come range G-02 Nr. 24; relazione L. 10/91 e abaco serramenti assenti |
| C1.2 | 7 | nessuna scorta, nessuna garanzia indicata | base poltrone 134 vs 128 (D18, Q4) |
| C1.3 | 8 | nessuna prestazione acustica dichiarata nelle voci | reazione al fuoco finiture solo da tavole inferite; unico indice T60 (RS-03) |
| C2.1 | 15 | nessun BIPV (5,85 kWp su staffe semi-integrate) | PI-00a e PI-00 non lette; indirizzi Soprintendenza assenti |
| C2.2 | 8 | nessuna voce antintrusione / TVCC | archi `alta` solo di assenza; predisposizioni solo da tavole inferite |
| C2.3 | 7 | capacità oltre 15 kWh | baseline 15 vs 20 kWh (D13, Q1) |
| C3.1 | 5 | nessun isolamento termico in copertura; nessuna schermatura esterna cupola | PA-05 non letta |
| C3.2 | 5 | nessun proiettore, audio, schermo, arredo multimediale | configurazione base non descritta; verifica al sopralluogo |
| C3.3 | 5 | nessuna voce di smontaggio/stoccaggio/rimontaggio attrezzature esistenti | nessun censimento delle dotazioni esistenti; SIC-02 non letta |
| C4.1 | 5 | telecontrollo, sintesi vocale, Braille avanzato, isolamento acustico cabina | dati ascensore in contraddizione (D14, Q3); PA-03 non letta |
| C4.2 | 5 | EPD oltre minimi, FSC/PEFC, Classe A+, piano economia circolare | «minimi CAM» indeterminati (D11, Q2) |
| C5.1-C7.1 | 10 | non pertinenti al progetto | dipendono da requisiti dell'impresa |

## 7. Proposte candidate

Nessuna. Fase 2 non avviata; `06_registers/` e `02_graph/proposals/` vuote.

## 8. Proposte validate e approvate dall'utente

Nessuna.

## 9. Proposte scartate

Nessuna.

## 10. Decisioni utente registrate

| ID | Decisione | Effetto |
|---|---|---|
| DEC-001 | Analisi 2 «gap prezzi» rinviata a fase successiva: prezzario Basilicata (tariffa del progetto) non disponibile; in cache solo Calabria 2025, non pertinente | `strategy_audit.md` §2 = NON DISPONIBILE, §4 = NON CALCOLABILE |
| DEC-002 | Output della gara da pubblicare sul repository `prometeus-spada-output` | `/sync_output` → `gare/14_10_2026_Bella/` |

Dettaglio, decisioni di sistema e decisioni attese: [decision_log](decision_log.md).

## 11. Domande aperte senza risposta

- **STOP #1 — 6 domande chiave** di [strategy_audit](../03_criteria/strategy_audit.md): budget sicurezza (1), confronto prezzi ed edizione tariffa (2), viabilità e sopralluogo (3), risorse per le migliorie (4), quali quesiti Q1-Q5 inviare (5), priorità tra le analisi (6). Più direttive operative: tono, priorità per criterio C1-C7, vincoli, opportunità.
- **Quesiti SA Q1-Q5** ([economic_framework](../02_graph/economic_framework.md) §10.1): testi pronti, invio da decidere entro 06/10 ore 12:00.
- **Domande aperte del gara brief** (5): requisiti tabellari C5-C7 e forma di partecipazione; quota di margine per migliorie; indirizzi Soprintendenza per C2.1; quesiti extra (comprova C6.1/C7.1, schede C5.1 nelle 30 facciate, regole C5.1); chi fa il sopralluogo.
- **Orfani**: destinazione di IT-00, PI-06, VVF-PI-01.

Elenco completo con priorità e scadenze: [open_issues](open_issues.md).

## 12. Rischi identificati

| ID | Rischio | Livello | Origine |
|---|---|---|---|
| RISK-01 | Offerta inammissibile se la richiesta di sopralluogo non parte entro 05/10 ore 12:00 | CRITICO | disciplinare art. 11 |
| RISK-02 | Esclusione per elementi economici in relazione, computo non estimativo o cronoprogramma | CRITICO | art. 16 p. 26; art. 22 |
| RISK-03 | Migliorie dimensionate su baseline errate: C2.3 (D13), C4.2 (D11), C4.1 (D14), C1.2 (D18) = 24 pt | ALTO | economic_framework §10 |
| RISK-04 | C2.1 (15 pt, sub più pesante): indirizzi di tutela assenti, PI-00a non firmata, fuori elenco elaborati e non letta | ALTO | index §7.5, §8 |
| RISK-05 | Sostenibilità migliorie non misurabile (Analisi 2 e 4 non disponibili) con verifica di anomalia art. 23; manodopera dichiarata sottostimata (D4) | ALTO | strategy_audit §2, §4 |
| RISK-06 | Tempi: 7 criteri da analizzare con feedback per criterio in 11 giorni, e STOP #1 e #2 ancora aperti | ALTO | calendario |
| RISK-07 | Cantiere SFAVOREVOLE (centro storico, mezzi piccoli, consegne in fasce orarie): migliorie che appesantiscono logistica e 150 gg | MODERATO | strategy_audit §3 |
| RISK-08 | Oneri sicurezza BASSO (3,41%) e misure PSC senza voce (gru, protezione attrezzature, monitoraggio vibrazioni) | MODERATO | strategy_audit §1 |
| RISK-09 | Fuori scope: interventi visibili su involucro, copertura, cupola nel Castello (C1.1, C2.1, C3.1); materiali acustici vs antincendio (C1.3) | MODERATO | gara_brief «Vincoli principali» |
| RISK-10 | 30 tavole con archi solo inferiti: non usabili come evidenza prima di drawing-reader | MODERATO | index §9 (26 WARN) |
| RISK-11 | Conseguenza del superamento delle 30 facciate e conteggio delle schede C5.1 non indicati | MODERATO | criteria_matrix N8, N9 |
| RISK-12 | Dichiarazione sull'uso di IA in Busta A da non omettere | MODERATO | art. 15.1 p. 21 |

## 13. Prossime azioni

1. **Subito, entro lun 05/10 ore 12:00** — richiesta di sopralluogo obbligatorio su PAD (professionista/impresa).
2. **Ora** — risposte a STOP #1 → il main loop le scrive in `strategy_audit.md` § Indicazioni strategiche.
3. **Entro mar 06/10 ore 12:00** — decidere e inviare i quesiti (Q1-Q5 ed eventuali extra) via PAD «Sezione chiarimenti».
4. Dopo STOP #1 — STOP #2 (menu criteri); `/resolve_orphan` sui 3 orfani; drawing-reader sulle 5 tavole `alta`.
5. **Gio 08/10** — controllare le risposte della SA e acquisirle con `/update_document`.

Elenco completo: [next_actions](next_actions.md).
