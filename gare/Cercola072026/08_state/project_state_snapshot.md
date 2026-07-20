# Project State Snapshot

## 1. Data aggiornamento

2026-07-18T00:00:00 (snapshot iniziale, post `/new_bid`)

## 2. Fase corrente del progetto

Gara inizializzata (`stato: iniziata`). Fase 1 — Analisi preliminare **non ancora avviata**.
`fasi_completate`: nessuna.

Prerequisiti Fase 1 verificati:
- `00_input/disciplinare/` contiene 1 file: `20260701122234433_DISCIPLINARE DI GARA_revisione 23.06.2026.pdf`
- `00_input/elaborati/` popolata (43 file: relazioni, computi, tavole EG.xx, documenti S.xx, verbali di verifica/validazione, quadro economico)
- `01_extracted/text/` vuota — nessun preprocessing eseguito
- `02_graph/` non ancora creata — knowledge graph non costruito
- `03_criteria/criteria_matrix.md`, `criteria_matrix.json`, `criteria_checklist.md`, `03_criteria/criteria/criterion_Cx.md` — non ancora presenti (solo `.gitkeep` e template brief)
- `03_criteria/strategy_audit.md` — non ancora presente

## 3. Criteri estratti — stato

Dati provenienti da `PROJECT_CONFIG.json → criteri` (estratti in fase `/new_bid` dal disciplinare, non ancora formalizzati in `criteria_matrix.md`).

| ID | Cod. disciplinare | Titolo | Punti max | Tipo | Stato |
|---|---|---|---|---|---|
| C1 | A1 | Proposte integrative/migliorative opere efficientamento energetico, materiali e caratteristiche tecniche | 20 | qualitativo | da analizzare |
| C2 | A2 | Proposte integrative/migliorative opere e caratteristiche tecniche — fornitura e posa infissi | 25 | qualitativo | da analizzare |
| C3 | A3 | Proposte integrative/migliorative opere e caratteristiche tecniche — impianto fotovoltaico | 20 | qualitativo | da analizzare |
| C4 | B1 | Abbattimento barriere architettoniche (voci 01,02,04 computo opere opzionali — €67.000,00) | 13 | tabellare | da analizzare |
| C5 | B2 | Sistemazione e decoro esterno (voci 03,05,06,07,08 computo opere opzionali — €46.000,00) | 10 | tabellare | da analizzare |
| C6 | B2 (probabile refuso, verosimilmente B3) | Certificazione UNI/PdR 125:2022 | 2 | tabellare | da analizzare |

Nessun criterio è ancora stato analizzato (`criteri_stato` in `PROJECT_CONFIG.json` è vuoto). `criteri_attivi` è vuoto: l'utente non ha ancora scelto quali criteri analizzare (Stop obbligatorio #2, non ancora raggiunto).

Totale punteggio tecnico: 90 punti (65 qualitativo C1-C3 + 25 tabellare C4-C6). Punteggio economico: 10 punti. Soglia di sbarramento tecnico: 45/90.

## 4. Vincoli critici dal disciplinare (noti da `/new_bid`, da confermare in analisi disciplinare formale)

- CIG: BC3ECFAA55 — CUP: G13C25000920001
- Stazione appaltante: Comune di Cercola (NA), V Settore — RUP fase aggiudicazione: ing. Lorenzo D'Alessandro
- Importo base d'asta complessivo: € 954.883,79 (di cui € 915.809,83 lavori soggetti a ribasso; € 39.073,96 oneri sicurezza non soggetti a ribasso; € 180.457,45 costi manodopera non soggetti a ribasso — dato da verificare per coerenza interna, il totale citato eccede la somma dei primi due)
- Scadenza offerta: 2026-08-06T23:59:00
- OEPV: 90 punti tecnici / 10 punti economici
- Soglia di sbarramento tecnico: 45/90
- Nota di attenzione dal disciplinare (pag. 27): refuso di battitura — C6 riportato come "B2" insieme a C5 nella tabella criterio tabellare; probabile intento "B3". Da verificare in analisi disciplinare formale.
- Prezzario di riferimento: non ancora compilato (`gara.prezzario_riferimento` vuoto in `PROJECT_CONFIG.json`) — necessario per `strategy-auditor` (calcolo gap prezzi)

## 5. Documenti analizzati

Nessuno. Preprocessing non ancora eseguito.

Documenti disponibili in `00_input/elaborati/` (43 file, non ancora estratti/censiti):
- Disciplinare di gara e disciplinare telematico
- Verbali di verifica e validazione del progetto
- Quadro economico (xlsx e pdf)
- Elenco elaborati (xlsx)
- Computi metrici (C.01, C.05, opere opzionali), elenco prezzi (C.02, C.06), analisi prezzi (C.03), stima manodopera (C.04), quadro economico (C.07)
- Tavole grafiche EG.01-EG.12 (planimetria, piante, prospetti, sezioni, schema centrale termica, abaco infissi, particolari costruttivi)
- Relazioni tecniche R.01-R.06 (relazione generale, CAM, DNSH, APE, relazione energetica L.10, relazione fotovoltaico, calcolo illuminotecnico)
- Documenti S.01-S.05 (schema contratto/capitolato, piano manutenzione, cronoprogramma, PSC, layout cantiere)

## 6. Gap rilevati

Nessuno. L'analisi criteri non è ancora iniziata.

## 7. Proposte candidate

Nessuna.

## 8. Proposte validate e approvate dall'utente

Nessuna.

## 9. Proposte scartate

Nessuna.

## 10. Decisioni utente registrate

Nessuna decisione ancora richiesta. Prima decisione attesa: risposta alle domande chiave dell'audit strategico (Stop obbligatorio #1), poi scelta dei criteri da analizzare (Stop obbligatorio #2).

## 11. Domande aperte senza risposta

- Q-CONFIG-001: verificare con l'utente/disciplinare il refuso pag. 27 (C6 = "B2" vs probabile "B3")
- Q-CONFIG-002: incongruenza aritmetica nell'importo base d'asta (costi manodopera € 180.457,45 superiore alla somma lavori+sicurezza dichiarata) — da chiarire in analisi disciplinare
- Q-CONFIG-003: prezzario di riferimento (regione/anno/percorso) non compilato — necessario prima dell'audit strategico

## 12. Rischi identificati

- R-CONFIG-001: senza prezzario di riferimento compilato, `strategy-auditor` non potrà calcolare il gap prezzi in Fase 1 — rischio di analisi budget sicurezza/gap prezzi incompleta
- R-CONFIG-002: refuso su B2/B3 in tabella criteri tabellari (C5/C6) potrebbe generare doppia numerazione o conflitto in `criteria_matrix.md` se non chiarito prima dell'analisi disciplinare formale

## 13. Prossime azioni

Vedi `08_state/next_actions.md`.
