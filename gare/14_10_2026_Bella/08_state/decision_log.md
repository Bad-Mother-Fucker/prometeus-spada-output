# Decision log — Cineteatro «Sala Polifunzionale Periz», Castello di Bella (PZ)

**Aggiornato il:** 2026-10-03 13:25 CEST
**Agente:** context-monitor
**Fase:** chiusura Fase 1 (analisi preliminare completata)
**Regola:** un ID decisione non cambia; una decisione superata si marca «revocata» con rinvio alla nuova, non si cancella.

---

## 1. Decisioni del professionista

| ID | Data | Decisione | Motivo | Effetti e file impattati | Stato |
|---|---|---|---|---|---|
| DEC-001 | 2026-10-03 | Analisi 2 «gap prezzi» dell'audit strategico **rinviata a fase successiva** | Il progetto usa la tariffa Regione Basilicata (codici tipo B.10.001.01), ma il prezzario Basilicata non è disponibile in `prometeus-prezzari`; in cache c'è solo Calabria 2025, non pertinente | `strategy_audit.md` §2 = NON DISPONIBILE e §4 «Investimento migliorativo» = NON CALCOLABILE; `scripts/prezzario/fetch_prezzario.sh` non eseguito; nota in `PROJECT_CONFIG.json → gara.prezzario_riferimento` (anno e percorso vuoti); `economic_framework.md` §11, §13 | attiva — da riaprire quando il prezzario Basilicata (edizione corretta) è disponibile: fetch + `/run_strategy_audit` |
| DEC-002 | 2026-10-03 | Gli output della gara vanno **pubblicati sul repository `prometeus-spada-output`** | Condivisione degli output con i collaboratori | `PROJECT_CONFIG.json → remote_output` (repository `prometeus-spada-output`, branch `main`, path `gare/`); `/sync_output` (`scripts/setup/sync_output.sh`) rigenera `11_view/` e copia 02_graph, 03_criteria, 04_doc_summaries, 05_criteria_outputs, 06_registers, 08_state, 10_offer, 11_view e `PROJECT_CONFIG.json` in `gare/14_10_2026_Bella/` | attiva — esecuzione di `/sync_output` non verificata da questo snapshot |

## 2. Decisioni di sistema (applicazione di regole, non scelte del professionista)

| ID | Data | Decisione | Regola applicata | Agente | Rivedibile da |
|---|---|---|---|---|---|
| SYS-001 | 2026-10-03 | ID criteri C1-C7 assegnati secondo l'ordine della Tabella art. 18.1 del disciplinare | CLAUDE.md §4.1 (ID stabili) | disciplinare-analyst | nessuno: ID immutabili |
| SYS-002 | 2026-10-03 | Prezzario Calabria 2025 **non usato** come sostituto, né per codice né per parola chiave | conseguenza di DEC-001; pertinenza territoriale della tariffa | strategy-auditor | professionista |
| SYS-003 | 2026-10-03 | Baseline economiche e di computo dalle sole versioni `is_latest: true` (G-01, G-04, G-06 ESEC-02); ESEC-01 solo per confronto | CLAUDE.md §4.8 (versioni) | graph-builder | `/update_document` su nuova versione |
| SYS-004 | 2026-10-03 | Contraddizioni D1, D7, D15, D17, D19 **risolte per gerarchia delle fonti** (disciplinare > capitolato/contratto > elenco prezzi > computo/QE > relazioni > tavole) | `economic_framework.md` §10 | graph-builder (Fase E) | professionista, se dissente |
| SYS-005 | 2026-10-03 | Quesito su D19 (OG2 nell'Elenco Elaborati) **sconsigliato** senza valutazione del professionista: una riqualificazione in OG2 cambierebbe i requisiti di partecipazione | prudenza procedurale | graph-builder (Fase E) | professionista |
| SYS-006 | 2026-10-03 | Orfani IT-00, PI-06, VVF-PI-01 **non collegati d'iniziativa**: decisione rimessa al professionista | CLAUDE.md §4.8 (orfani) | graph-builder | professionista con `/resolve_orphan` |
| SYS-007 | 2026-10-03 | Artifact HTML in `11_view/` rigenerati **a mano** (`node scripts/render/md_to_html.js --all`): l'hook PostToolUse è legato alla cartella di progetto della sessione e non scatta su questa gara | CLAUDE.md §6.1 | context-monitor | ripristino dell'hook |

## 3. Decisioni attese (non ancora prese)

| Rif. | Decisione da prendere | Chi | Entro | Blocca |
|---|---|---|---|---|
| STOP #1 | Risposte alle 6 domande chiave e direttive operative (tono, priorità C1-C7, vincoli, opportunità) in `strategy_audit.md` | professionista | prima di STOP #2 | menu criteri, Fase 2 |
| Quesiti | Quali tra Q1-Q5 inviare, ed eventuali quesiti extra (oneri sicurezza, edizione tariffa, comprova C6.1/C7.1, schede C5.1, regole C5.1) | professionista | mar 06/10/2026 ore 12:00 | baseline C2.3, C4.2, C4.1, C1.2 |
| Sopralluogo | Invio richiesta e nominativo dell'incaricato | professionista / impresa | lun 05/10/2026 ore 12:00 | ammissibilità dell'offerta |
| Orfani | Destinazione di IT-00, PI-06, VVF-PI-01 | professionista | prima della Fase 2 su C1 e C3 | copertura vincoli C1.3, C3.3 |
| STOP #2 | Criteri da analizzare e ordine | professionista | dopo STOP #1 | Fase 2 |
| Requisiti T | Dati impresa per C5 (interventi analoghi), C6 (L. 68/1999), C7 (UNI/PdR 125); forma di partecipazione; eventuale avvalimento premiale | professionista / impresa | prima dell'analisi di C5-C7 | 10 pt tabellari |
| Vincoli offerta | `vincoli_offerta_tecnica.md` Sezione B (budget facciate, criteri esclusi, priorità) | professionista | prima di offer-writer | stesura offerta |
