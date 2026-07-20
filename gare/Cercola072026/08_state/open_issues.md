# Open Issues

| ID | Descrizione | Origine | Impatto | Stato |
|---|---|---|---|---|
| Q-CONFIG-001 | Refuso pag. 27 disciplinare: C6 riportato come "B2" insieme a C5 nella tabella criterio tabellare, probabile "B3" | `/new_bid` — nota `gara.note` in PROJECT_CONFIG.json | Rischio numerazione/conflitto in `criteria_matrix.md` | aperta |
| Q-CONFIG-002 | Incongruenza aritmetica nell'importo base d'asta: costi manodopera (€180.457,45) non soggetti a ribasso sembrano eccedere la somma dichiarata di lavori + oneri sicurezza | `/new_bid` — dati `gara.importo_base_asta` | Possibile errore di trascrizione da verificare su disciplinare originale prima di usarlo in analisi economiche | aperta |
| Q-CONFIG-003 | Prezzario di riferimento (regione/anno/percorso) non compilato in `PROJECT_CONFIG.json → gara.prezzario_riferimento` | `/new_bid` | Blocca il calcolo del gap prezzi in `strategy-auditor` durante Fase 1 | aperta — da compilare prima o durante l'audit strategico |

Nessuna issue tecnica di sistema (file mancanti attesi in questa fase, coerente con `stato: iniziata`).
