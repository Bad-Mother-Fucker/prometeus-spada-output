# Matrice Criteri — Intervento di efficientamento energetico Istituto Comprensivo "De Luca Picione Caravita" (Cercola)

**CIG:** BC3ECFAA55 · **CUP:** G13C25000920001
**Fonte:** Disciplinare di gara, artt. 16, 18.1, 18.2, 18.3, 18.4
**OEPV:** Punteggio tecnico Pt = 90, Punteggio economico Pe = 10, Ptot = 100
**Soglia di sbarramento tecnico:** 45/90 (calcolata PRIMA della riparametrazione dei punteggi tecnici, art. 18.1 e 18.4)
**Riparametrazione:** se nessun concorrente ottiene il punteggio tecnico massimo, il punteggio tecnico viene riparametrato attribuendo il massimo al concorrente migliore e punteggio proporzionale decrescente agli altri (art. 18.4)

| ID | Codice disciplinare | Criterio | Punteggio max | Subcriteri | Metodo attribuzione | Note |
|---|---|---|---|---|---|---|
| C1 | A1 | Proposte integrative/migliorative delle opere inerenti al progetto di Efficientamento energetico, dei materiali impiegati e delle loro caratteristiche tecniche | 20 | Nessuno — criterio a blocco unico | Qualitativo discrezionale (coefficiente 0–1 per commissario, media aritmetica) | Richiede Allegato tecnico (Relazione energetica ex L. 10 + APE post operam), art. 16 lett. m |
| C2 | A2 | Proposte integrative/migliorative delle opere e delle caratteristiche tecniche relative alla fornitura e posa in opera degli infissi | 25 | Nessuno — criterio a blocco unico | Qualitativo discrezionale (coefficiente 0–1 per commissario, media aritmetica) | Richiede Allegato tecnico (Relazione energetica ex L. 10 + APE post operam), art. 16 lett. m |
| C3 | A3 | Proposte integrative/migliorative delle opere e delle caratteristiche tecniche relative all'impianto Fotovoltaico | 20 | Nessuno — criterio a blocco unico | Qualitativo discrezionale (coefficiente 0–1 per commissario, media aritmetica) | Richiede Allegato tecnico (Relazione energetica ex L. 10 + APE post operam), art. 16 lett. m |
| **Totale qualitativo** | | | **65** | | | |
| C4 | B1 | Interventi attinenti all'abbattimento delle barriere architettoniche — voci 01, 02, 04 del computo opere opzionali, valore economico € 67.000,00 | 13 | Nessuno — corrisponde all'insieme delle voci 01,02,04 | Tabellare on/off (presenza/assenza proposta = punteggio pieno/zero) | Proposta deve corrispondere alle specifiche dell'atto contabile delle opzioni |
| C5 | B2 | Interventi relativi alla sistemazione e decoro esterno — voci 03, 05, 06, 07, 08 del computo opere opzionali, valore economico € 46.000,00 | 10 | Nessuno — corrisponde all'insieme delle voci 03,05,06,07,08 | Tabellare on/off | Proposta deve corrispondere alle specifiche dell'atto contabile delle opzioni |
| C6 | B2 (refuso di battitura in tabella, verosimilmente B3) | Certificazione UNI/PdR 125:2022 | 2 | Nessuno | Tabellare on/off | Il disciplinare non specifica contenuto/modalità di comprova della certificazione: AMBIGUITÀ SEGNALATA |
| **Totale tabellare** | | | **25** | | | |
| **TOTALE PUNTEGGIO TECNICO (Pt)** | | | **90** | | | |
| Pe | — | Punteggio economico (interpolazione lineare Ci = Ai/Amax) | 10 | — | Lineare | Non oggetto di questa estrazione (criterio economico) |

## Note e ambiguità rilevate

1. **Refuso codice C6.** In tabella (art. 18.1) la "Certificazione UNI/PdR 125:2022" è riportata con codice "B2", identico al codice già usato per "Sistemazione e decoro esterno". Si tratta verosimilmente di un refuso di battitura (probabile B3), già segnalato in `PROJECT_CONFIG.json`. L'ID interno stabile assegnato resta C6.
2. **Assenza di sub-criteri interni per C1-C3.** Il disciplinare non suddivide A1, A2, A3 in ulteriori sub-criteri con punteggi parziali: ciascuno è valutato come blocco unico con un solo coefficiente discrezionale (0-1) moltiplicato per il punteggio massimo (20/25/20).
3. **Ambiguità sul limite facciate per sub-criterio (art. 16, lett. j).** Il testo prevede "un numero massimo di 6 facciate A4" per le proposte suddivise "per ognuno dei sub-criteri di cui alla tabella successiva": non è del tutto esplicito se il limite di 6 facciate sia per ciascun criterio (A1, A2, A3, B1, B2, C6 — quindi fino a 36 facciate complessive) oppure un totale complessivo. L'interpretazione più letterale, coerente con "fornite in cartelle... con un numero massimo di 6 facciate A4" riferito a ciascun sub-criterio, è TIPO A (limite fisso per sub-criterio/criterio = 6 facciate ciascuno). Vedi `vincoli_offerta_tecnica.md`.
4. **C6 — mancanza di dettaglio.** Il disciplinare non chiarisce se la certificazione UNI/PdR 125:2022 debba essere già posseduta al momento dell'offerta o se sia sufficiente un impegno ad ottenerla in fase esecutiva, né la documentazione di comprova richiesta.
