# Prometeus S.P.A.D.A — Output Gare

Repository degli output di analisi delle gare d'appalto.

## Struttura

```
gare/
└── <codice-gara>/
    ├── 02_index/           Indice documenti per criterio
    ├── 03_criteria/        Matrice criteri e analisi
    ├── 04_doc_summaries/   Sintesi documenti e tavole
    ├── 05_criteria_outputs/ Output completo per criterio
    ├── 06_registers/       Registri gap, proposte, audit
    ├── 07_questions/       Domande guida e feedback
    └── 10_offer/           Offerta tecnica
```

## Come contribuire

1. Clona questo repository
2. Trova la cartella della gara su cui stai lavorando in `gare/`
3. Leggi gli output in `05_criteria_outputs/` e `06_registers/`
4. Deposita il tuo feedback in `07_questions/user_answers.md`
   seguendo il template presente nel file
5. Fai push delle tue modifiche

## Regole

- Non modificare file fuori dalla cartella `07_questions/`
- Non caricare documenti originali di gara (PDF, tavole)
- Ogni modifica deve avere un messaggio di commit descrittivo:
  `feedback: [nome] — [criterio] — [data]`
