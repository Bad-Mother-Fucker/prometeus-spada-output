# Next Actions

## Azione immediata

Avviare la **Fase 1 — Analisi preliminare** su comando dell'utente ("avvia analisi gara" o equivalente, §5.1 CLAUDE.md). Sequenza da eseguire in ordine dal main loop:

1. **`document-preprocessor`** — `01_extracted/text/` è vuota e `_manifest_input.md` non esiste: eseguire estrazione completa di tutti i documenti in `00_input/disciplinare/` e `00_input/elaborati/` (43 file elaborati + 1 disciplinare + eventuali `.p7m`).
2. **`disciplinare-analyst`** — analisi formale del disciplinare, produzione/conferma di `03_criteria/criteria_matrix.md`, `criteria_matrix.json`, `criteria_checklist.md`, `03_criteria/criteria/criterion_Cx.md` per C1-C6. Verificare in questa fase il refuso B2/B3 (issue Q-CONFIG-001) e l'incongruenza importo base d'asta (Q-CONFIG-002).
3. **`graph-builder`** — 8 invocazioni distinte del main loop come da tabella CLAUDE.md §3 (Fasi 0-2 sequenziali, poi round A/B/C in parallelo, poi round D/E/F in parallelo, poi Fasi 4-5). Costruisce `02_graph/`, `scope.md`, `economic_framework.md`, `index.md`.
4. **`strategy-auditor`** — produce `03_criteria/strategy_audit.md` (budget sicurezza, gap prezzi, viabilità cantiere, capacità investimento migliorativo). Nota: se `gara.prezzario_riferimento` resta vuoto (Q-CONFIG-003), l'analisi gap prezzi sarà limitata/TBD — segnalare esplicitamente nel report.

## Dopo la Fase 1

- **STOP obbligatorio #1**: riportare in chat, senza riassumere, la tabella "Riepilogo" e le "Domande chiave" di `strategy_audit.md`. Attendere risposta utente e trascriverla in "Indicazioni strategiche del professionista".
- **STOP obbligatorio #2**: presentare il menu di scelta criteri (C1 singolo / combinazione / tutti / manuale). Attendere comando esplicito prima di avviare la Fase 2.

## Snapshot successivo

Da eseguire (da `context-monitor`) alla chiusura della Fase 1, dopo l'audit strategico — o prima, se il contesto supera 180k token durante il preprocessing/estrazione documenti (43 file da estrarre: monitorare la soglia).
