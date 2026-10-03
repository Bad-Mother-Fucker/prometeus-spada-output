---
type: criterion
id: C5
gara: "Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)"
date: 2026-10-03
ai-first: true
confidence: verificato
titolo: "Esperienza specifica pregressa"
criterio_disciplinare: "5. Esperienza specifica pregressa"
punteggio_max: 6
peso_pct_tecnico: 6.7
natura: tabellare
fonte: "Disciplinare art. 18.1, Tabella criteri D/T, p. 29"
subcriteri:
  - { id: "C5.1", titolo: "Esperienza pregressa di realizzazione di interventi analoghi su immobili destinati a cinema, teatro, cineteatri o altri edifici destinati prevalentemente ad attività di spettacolo e intrattenimento aperti al pubblico", punti: 6, natura: "T" }
modification_limits:
  - "Punteggio tabellare predeterminato: 1 punto per ciascun intervento ammissibile e adeguatamente documentato, fino a un massimo di 6 punti — nessuna proposta migliorativa possibile (art. 18.1, sub 5.1, p. 29)"
  - "Ammissibili solo interventi analoghi su immobili destinati a cinema, teatro, cineteatri o altri edifici destinati prevalentemente ad attività di spettacolo e intrattenimento aperti al pubblico (art. 18.1, sub 5.1, p. 29)"
  - "Per ciascun intervento è richiesta una scheda sintetica con almeno: committente, denominazione e ubicazione dell'immobile, destinazione d'uso, oggetto e descrizione delle lavorazioni eseguite, importo dei lavori, periodo di esecuzione e data di ultimazione (art. 18.1, sub 5.1, p. 29)"
  - "Punteggio attribuito esclusivamente per gli interventi la cui documentazione consenta di verificare in maniera chiara la riconducibilità alle caratteristiche indicate (art. 18.1, sub 5.1, p. 29)"
fuori_scope_risks:
  - "Interventi su edifici a destinazione mista o non prevalentemente di spettacolo e intrattenimento aperti al pubblico: rischio di non ammissibilità (p. 29)"
  - "Schede prive di uno dei contenuti minimi o con documentazione non chiara: punto non attribuito (p. 29)"
# --- Aggiunto/aggiornato da graph-builder 2026-10-03 ---
# supported_by = archi inversi di supports_criteria delle pagine 02_graph/nodes/ (Fase F).
# Ordine: priority alta > media > bassa; a parita', confidence verificato > parziale > inferito, poi codice.
# confidence = dell'arco: esplicita sull'arco se presente, altrimenti quella della pagina nodo;
#   inferito se la reason dichiara il collegamento inferito/dedotto. Tavole: contenuto grafico non letto.
# sottocriteri = citati nella reason dell'arco; "trasversale" = cornice economica / verifica di anomalia (art. 23).
# is_latest: false = versione superata, solo confronto tra versioni, mai baseline.
# Evidenza debole per elemento premiante (Fase F; dettaglio in 02_graph/log.md):
#   C5.1 - atteso: criterio tabellare, l'evidenza e' il curriculum dell'impresa; i 2 archi (bassa) servono solo a definire l'intervento analogo.
supported_by:
  - { doc: "[[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]]", priority: bassa, confidence: verificato, sottocriteri: ["C5.1"] }
  - { doc: "[[G-08-ESEC-01_RELAZIONE_GENERALE]]", priority: bassa, confidence: verificato, sottocriteri: ["C5.1"] }
graph_updated: 2026-10-03
---

# Criterio C5 — Esperienza specifica pregressa

## Per Claude futuro

Pagina criterio C5 della gara Cineteatro “Periz” — Castello di Bella (CIG BCF01395AF). Criterio 5 della tabella art. 18.1 (p. 29): 6 punti su 90 (6,7%), **tabellare (T)**: 1 punto per intervento analogo ammissibile e documentato, max 6. Non ammette proposte migliorative: il punteggio dipende solo dal curriculum dell'operatore economico e dalla qualità delle schede. Fonte unica: disciplinare. Confidence: verificato.

## Punteggio massimo

6 punti (art. 18.1, p. 29)

## Subcriteri

| ID sub | Descrizione | Punti | Natura |
|---|---|---|---|
| C5.1 | Esperienza pregressa di realizzazione di interventi analoghi a quello oggetto di affidamento, realizzati su immobili destinati a cinema, teatro, cineteatri o altri edifici destinati prevalentemente ad attività di spettacolo e intrattenimento aperti al pubblico | 6 | T |

### Testo del disciplinare (p. 29)

"(T) Per ciascun intervento ritenuto ammissibile e adeguatamente documentato sarà attribuito 1 punto, fino a un massimo di 6 punti. Ai fini della valutazione, l'Operatore Economico dovrà produrre per ciascun intervento una scheda sintetica contenente almeno: committente, denominazione e ubicazione dell'immobile, destinazione d'uso, oggetto e descrizione delle lavorazioni eseguite, importo dei lavori, periodo di esecuzione e data di ultimazione. La Commissione procederà all'attribuzione del punteggio esclusivamente per gli interventi per i quali la documentazione prodotta consenta di verificare in maniera chiara la riconducibilità alle caratteristiche sopra indicate."

## Metodo di attribuzione

Tabellare (art. 18.2, p. 30): punteggio assegnato automaticamente e in valore assoluto in base alla presenza dell'elemento richiesto — 1 punto per ogni intervento ammissibile, fino a 6.

## Elementi premianti

- Numero di interventi analoghi ammissibili e documentati (fino a 6)
- Chiarezza della documentazione nel dimostrare: destinazione d'uso a spettacolo/intrattenimento aperto al pubblico e analogia con l'intervento in gara

## Vincoli espliciti

- Immobili destinati a cinema, teatro, cineteatri o altri edifici destinati prevalentemente ad attività di spettacolo e intrattenimento aperti al pubblico (p. 29).
- Interventi "analoghi a quello oggetto di affidamento" (p. 29). Il disciplinare non definisce l'analogia; l'oggetto dell'affidamento è descritto all'art. 3 (p. 7): lavori di adeguamento ed efficientamento energetico e fornitura di arredo per l'allestimento delle aree interne.
- Una scheda sintetica per intervento con il contenuto minimo elencato (p. 29).
- Massimo 6 punti (p. 29).

## Vincoli impliciti

- L'avvalimento è ammesso anche "per migliorare la propria offerta" (avvalimento premiale, art. 7, p. 13): con contratto di avvalimento premiale allegato alla domanda (art. 15.4, p. 23); la mancata produzione del contratto premiale comporta la mancata attribuzione del punteggio (art. 14, p. 20). Ausiliaria e ausiliata non possono partecipare alla stessa gara (art. 7, p. 13).

## Limiti dimensionali o formali

- Formato e lunghezza della scheda: [non indicato].
- Conteggio delle schede nelle 30 facciate della relazione: [non indicato] — sono esclusi dal conteggio solo copertine, sommari, elaborati grafici e "schede tecniche esplicative" (art. 16, p. 25).

## Documenti richiesti

- Scheda sintetica per ciascun intervento analogo (max 6 utili), con: committente; denominazione e ubicazione dell'immobile; destinazione d'uso; oggetto e descrizione delle lavorazioni eseguite; importo dei lavori; periodo di esecuzione e data di ultimazione (art. 18.1, sub 5.1, p. 29)
- Eventuale contratto di avvalimento premiale, se l'esperienza è di un'ausiliaria (allegato alla domanda, Busta A) (art. 7, p. 13; art. 15.4, p. 23)

## Rischi fuori scope

- Edifici a destinazione mista o non prevalentemente di spettacolo (p. 29).
- Schede incomplete o poco chiare (p. 29).

## Note e ambiguità

- Nessun arco temporale (es. ultimi N anni), nessun importo minimo, nessuna indicazione se l'intervento debba essere stato eseguito direttamente dall'O.E. o se valgano lavori in subappalto/ATI.
- Il campo "importo dei lavori" nella scheda non è un elemento dell'offerta economica, ma va comunque gestito con attenzione al divieto di elementi economici nell'offerta tecnica (art. 16, p. 26), che riguarda prezzi e ribassi dell'offerta in gara.

## Checklist operativa

- [ ] Raccogliere dall'impresa l'elenco degli interventi su cinema/teatri/cineteatri/edifici di spettacolo aperti al pubblico
- [ ] Per ciascuno verificare la disponibilità di tutti i dati minimi della scheda e della documentazione probatoria (certificati di esecuzione lavori o equivalenti)
- [ ] Selezionare i 6 interventi più chiaramente riconducibili ("analoghi" e destinazione prevalente)
- [ ] Valutare l'avvalimento premiale se gli interventi propri sono meno di 6
- [ ] Decidere la collocazione delle schede (allegato o nella relazione) dopo eventuale chiarimento sul limite facciate
