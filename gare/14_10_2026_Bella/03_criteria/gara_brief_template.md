# Gara Brief — [PROJECT_CONFIG.gara.nome]

**CIG:** [CIG] · **Importo a base d'asta:** € [importo] · **Scadenza:** [data e ora]
**Stazione appaltante:** [SA]
**Generato il:** [data] · **Fonte:** solo disciplinare (elaborati non ancora caricati)

---

## In sintesi

[2-3 frasi: oggetto dell'appalto, localizzazione, caratteristiche principali
dell'opera. Estratto dalla sezione oggetto/descrizione del disciplinare.]

---

## Struttura del punteggio

| Criterio | Titolo | Punti | Peso% | Priorita' |
|---|---|---|---|---|
| C1 | [titolo] | [N] | [x]% | [ALTA se >20%] |
| C2 | [titolo] | [N] | [x]% | |
| **TOTALE OFFERTA TECNICA** | | **[N]** | **100%** | |

> I criteri con peso > 20% sono ad **ALTA priorita'**: concentrare qui
> le risorse di analisi.

---

## Criteri in dettaglio

> Una scheda per criterio: cosa valuta, cosa va materialmente prodotto
> e consegnato, e — man mano che l'analisi procede — a che punto siamo.
> La riga **Stato analisi** e' l'unica parte viva del brief: la aggiorna
> `evidence-auditor` a fine audit e `feedback-processor` a feedback
> elaborato. Il resto della scheda deriva dal solo disciplinare.

### [[C1]] — [titolo] ([N] punti)

**Sommario.** [2-3 frasi dal disciplinare: cosa valuta il criterio,
come viene attribuito il punteggio (formula o giudizio discrezionale),
quali elementi il disciplinare dichiara premianti.]

**Deliverables richiesti:**

| Deliverable | Vincolo di formato | Fonte |
|---|---|---|
| [es. Relazione tecnica per C1] | [es. max 5 facciate A4, Arial 11] | [art. X] |
| [es. Cronoprogramma migliorativo] | [es. Gantt allegato, non computato nelle facciate] | [art. X] |

**Stato analisi:** non ancora analizzato

---

### [[C2]] — [titolo] ([N] punti)

[stessa struttura: Sommario, Deliverables richiesti, Stato analisi]

---

## Dove si concentra il potenziale

[Criteri con subcriteri non rigidi, elementi premianti ampi, o
modification_limits vuoti — dove le proposte migliorative hanno
piu' liberta' di movimento.]

- **[C1.2 — titolo]**: elemento premiante [descrizione], nessun limite
  esplicito di modifica → margine ampio
- **[C2.1 — titolo]**: [motivazione]

---

## Vincoli principali

[Limitazioni che restringono le proposte — ricavate da modification_limits
e fuori_scope_risks dei criteri, e dagli articoli di disciplinare.]

- [C1]: [vincolo — es. "le migliorie non devono alterare il dimensionamento
  idraulico (art. 12)"]
- [C3]: punteggio predeterminato — nessuna proposta migliorativa possibile

---

## Elaborati citati nel disciplinare

> Prima lista di cosa serve. Verificare la presenza al momento del
> caricamento in 00_input/elaborati/.

| Elaborato | Sezione citata nel disciplinare | Priorita' per l'analisi |
|---|---|---|
| Relazione tecnica generale | [art. X] | Alta |
| Computo metrico | [art. X] | Alta |
| Planimetrie | [art. X] | Media |
| PSC | [art. X] | Alta |
| [altro elaborato] | [art. X] | [livello] |

---

## Domande aperte per il professionista

> Da discutere prima del Gate A (strategia) o durante.

1. [Domanda tecnica su un criterio ambiguo]
2. [Domanda sulla fattibilita' di un'area di opportunita']
3. [Aspetto che richiede valutazione di dominio]
4. [Elemento da chiarire con la stazione appaltante]
5. [Altro]

---

## Prossimi passi

1. Condividi questo brief con il professionista e l'operatore
2. Raccogli le prime indicazioni strategiche (Gate A anticipato)
3. Carica gli elaborati in `00_input/elaborati/`
4. Avvia la Fase 1 completa: `start_bid_analysis`
