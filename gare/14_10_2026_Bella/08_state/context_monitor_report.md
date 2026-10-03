# Report context monitor — chiusura Fase 1

**Aggiornato il:** 2026-10-03 13:25 CEST
**Agente:** context-monitor
**Attivazione:** chiusura della Fase 1 (indicizzazione + audit strategico), su richiesta del main loop
**Esito:** snapshot completo · pulizia del contesto CONSENTITA ORA, con le condizioni del §3

---

## 1. Stato del contesto

| Contesto | Misura | Fascia | Azione |
|---|---|---|---|
| Main loop | non misurabile da questo agente (contesto separato) | da verificare dal main loop | applicare le soglie sotto |
| context-monitor (questo passaggio) | letture mirate: config, matrice, brief, audit, index, economic_framework §10-13, scope §2 | nessun impatto sul main loop | — |

Soglie operative (CLAUDE.md §7):

| Token nel main context | Stato | Azione |
|---|---|---|
| 0-120k | OK | nessuna |
| 120k-180k | attenzione | avvisare l'utente |
| 180k-220k | preparare snapshot | snapshot pronto (questo) e proporre pulizia |
| 220k-250k | blocco letture massive | nessuna nuova lettura integrale |
| 250k-280k | snapshot obbligatorio | snapshot prima di proseguire |
| oltre 280k | zona rossa | stop operazioni massive |

## 2. Prerequisiti per la pulizia (verificati sui file)

| File | Stato rilevato | Esito |
|---|---|---|
| `PROJECT_CONFIG.json` | stato `analisi_preliminare_completata`; fasi preprocessing, analisi_disciplinare, knowledge_graph, audit_strategico; `criteri_stato` C1-C7 `analizzato: false`; `deliverables` C1-C7 + trasversali presenti | OK |
| `03_criteria/criteria_matrix.md` + `.json` | 7 criteri, 14 sottocriteri, somma 90 = totale tabella | OK |
| `03_criteria/criteria_checklist.md` | presente | OK |
| `03_criteria/gara_brief.md` | presente; «Stato analisi» C1-C7 = non ancora analizzato | OK |
| `03_criteria/strategy_audit.md` | presente; Riepilogo e Domande chiave completi; «Indicazioni strategiche del professionista» a segnaposto | ATTENZIONE — STOP #1 aperto |
| `02_graph/index.md`, `scope.md`, `economic_framework.md` | presenti, rebuild dell'invocazione 8 | OK |
| `06_registers/proposal_register.md`, `audit_summary.md` | assenti | atteso: nessun criterio analizzato |
| `05_criteria_outputs/Cx_output.md` | nessun file; nessuno `stato_feedback: in_attesa` | OK |
| `08_state/` (5 file) | scritti in questo passaggio | OK |

## 3. Verdetto sulla pulizia del contesto

**Pulizia:** CONSENTITA ORA
**Motivo:** Fase 1 chiusa (indicizzazione e audit completati); nessun criterio in analisi; nessun feedback in attesa di `/process_feedback`.

Condizioni:

- Le due decisioni del professionista comunicate in chat sono ora su file: DEC-001 (Analisi 2 rinviata) in `decision_log.md`, `PROJECT_CONFIG.json → gara.prezzario_riferimento.note` e `strategy_audit.md` §2; DEC-002 (pubblicazione su `prometeus-spada-output`) in `decision_log.md` e `PROJECT_CONFIG.json → remote_output`.
- Questo snapshot registra solo ciò che è nei file o nel prompt del main loop. Se in chat esistono altre informazioni (per esempio sopralluogo già richiesto, quesiti già decisi), il main loop deve farle scrivere prima di comprimere.
- **NON comprimere** dal momento in cui il professionista inizia a rispondere a STOP #1 fino a quando le risposte sono scritte in `strategy_audit.md` § «Indicazioni strategiche del professionista» (raccolta feedback e decisioni strategiche).
- **NON comprimere** durante l'analisi di un criterio (Fase 2) né prima che un `Cx_output.md` con `stato_feedback: in_attesa` sia elaborato.

## 4. Coerenza tra file centrali

| Controllo | Valore | Fonti confrontate | Esito |
|---|---|---|---|
| Pagine nodo | 53 | index frontmatter; file in `02_graph/nodes/`; strategy_audit intestazione | coerente |
| Sintesi | 11 | index; file in `02_graph/synthesis/` | coerente |
| Archi | 367 = 114 + 253 | index frontmatter e §10 | coerente |
| Orfani | 3 (IT-00, PI-06, VVF-PI-01) | index §6, §9 | coerente |
| Contraddizioni irrisolte | 7 (D13, D11, D14, D18, D4, D2, D16) | index §7.1; economic_framework «Per l'index» | coerente |
| Quesiti SA | 5 (Q1-Q5) | index §7.4; economic_framework §10.1; strategy_audit domanda 5 | coerente |
| Scadenze | 05/10, 06/10, 14/10 ore 12:00 | PROJECT_CONFIG; gara_brief; index §1; strategy_audit §3 | coerente |
| Punteggio tecnico | 90 (25+30+15+10+6+2+2) | criteria_matrix; gara_brief; PROJECT_CONFIG | coerente |

Disallineamenti non bloccanti (non corretti: fuori dal perimetro di context-monitor):

- `gara_brief.md` «Prossimi passi» punto 4 invita ad avviare la Fase 1 completa: superato, la Fase 1 è chiusa. Il brief è stato generato prima del grafo e non viene riscritto in Fase 1.
- I quesiti (b), (c), (d) delle «Domande aperte» del brief (comprova C6.1/C7.1, schede C5.1, regole C5.1) non sono tra Q1-Q5: tracciati come OI-04.

## 5. Artifact HTML (`11_view/`)

**Situazione prima dello snapshot:** 3 artifact presenti (`02_graph/index.html`, `03_criteria/gara_brief.html`, `03_criteria/strategy_audit.html`). L'hook PostToolUse non scatta su questa cartella (legato alla cartella di progetto della sessione): la rigenerazione è manuale (SYS-007).
**Rigenerazione:** `node scripts/render/md_to_html.js --all` seguito da `--check`, eseguiti al termine di questo snapshot (2026-10-03).
**Esito --all:** 12 artifact generati, exit 0
**Esito --check:** «Tutti gli artifact allineati (12)», exit 0

| Artifact | Note |
|---|---|
| `11_view/02_graph/index.html` · `economic_framework.html` · `scope.html` | Knowledge Graph |
| `11_view/03_criteria/gara_brief.html` | 6 campi compilabili |
| `11_view/03_criteria/strategy_audit.html` | 24 campi compilabili (risposte a STOP #1) |
| `11_view/03_criteria/criteria_matrix.html` · `criteria_checklist.html` | Matrice e checklist |
| `11_view/08_state/` (5 file) | questo snapshot |

Dopo ogni nuova modifica di un `.md` in whitelist ripetere `--all` e `--check` (NA-14).
