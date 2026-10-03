---
type: criterion
id: C2
gara: "Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)"
date: 2026-10-03
ai-first: true
confidence: verificato
titolo: "Energie Rinnovabili e Sistemi di Sicurezza"
criterio_disciplinare: "2. Energie Rinnovabili e Sistemi di Sicurezza"
punteggio_max: 30
peso_pct_tecnico: 33.3
natura: discrezionale
fonte: "Disciplinare art. 18.1, Tabella criteri D/T, p. 28"
subcriteri:
  - { id: "C2.1", titolo: "Integrazione architettonica dell'impianto fotovoltaico (BIPV)", punti: 15, natura: "D" }
  - { id: "C2.2", titolo: "Sistemi antintrusione e videosorveglianza", punti: 8, natura: "D" }
  - { id: "C2.3", titolo: "Sistemi di accumulo e Building Automation", punti: 7, natura: "D" }
modification_limits:
  - "C2.1: sistemi fotovoltaici integrati sulla copertura, valutati in base ad azzeramento dell'impatto visivo, assenza di riflettanza e totale conformità agli indirizzi di tutela del Castello della Soprintendenza Basilicata (art. 18.1, sub 2.1, p. 28)"
  - "C2.1: ai fini della formulazione della miglioria il disciplinare rimanda all'elaborato grafico PI-00a-ESEC-01 Planimetria di insieme con fotovoltaico integrato e fotoinserimenti (art. 18.1, sub 2.1, p. 28)"
  - "C2.3: è valutato l'incremento quantitativo della capacità di accumulo delle batterie con riferimento '>20 kWh' (art. 18.1, sub 2.3, p. 28)"
  - "L'offerta tecnica deve rispettare, pena l'esclusione, le caratteristiche minime stabilite nei documenti di gara, nel rispetto del principio di equivalenza (art. 16, p. 25)"
  - "Le migliorie, sommate alle prestazioni di progetto, non devono far emergere dubbi sulla sostenibilità economica complessiva dell'offerta: parametro della verifica di anomalia (art. 23, p. 33)"
fuori_scope_risks:
  - "C2.1: soluzioni FV visibili, riflettenti o non conformi agli indirizzi di tutela: punteggio basso e rischio di non autorizzabilità (art. 18.1, sub 2.1, p. 28)"
  - "C2.1: estensione del campo FV oltre la copertura o modifiche strutturali della copertura del castello (inferito)"
  - "C2.2: installazioni a vista sui paramenti storici del castello e interferenze con gli impianti di progetto (inferito)"
  - "C2.3: maggiore capacità di accumulo che richieda nuovi locali tecnici o misure antincendio aggiuntive (inferito)"
# --- Aggiunto/aggiornato da graph-builder 2026-10-03 ---
# supported_by = archi inversi di supports_criteria delle pagine 02_graph/nodes/ (Fase F).
# Ordine: priority alta > media > bassa; a parita', confidence verificato > parziale > inferito, poi codice.
# confidence = dell'arco: esplicita sull'arco se presente, altrimenti quella della pagina nodo;
#   inferito se la reason dichiara il collegamento inferito/dedotto. Tavole: contenuto grafico non letto.
# sottocriteri = citati nella reason dell'arco; "trasversale" = cornice economica / verifica di anomalia (art. 23).
# is_latest: false = versione superata, solo confronto tra versioni, mai baseline.
# Evidenza debole per elemento premiante (Fase F; dettaglio in 02_graph/log.md):
#   C2.1 - PI-00a (rinvio espresso del disciplinare) e PI-00 non lette; indirizzi di tutela della Soprintendenza assenti da tutti gli elaborati; impatto visivo e riflettanza senza evidenza verificata di progetto (solo foto G-07 parziale e tavole di contesto inferite).
#   C2.2 - evidenza alta solo di assenza (nessun impianto o voce in G-04-ESEC-02, G-08, RS-00); predisposizioni elettriche solo da tavole inferite (PI-05, PI-03).
#   C2.3 - baseline accumulo in contraddizione: 15 kWh (RS-00, RS-01, computo voce 78) vs 20 kWh (G-08, SIC-00, G-09, RS-03).
supported_by:
  - { doc: "[[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]]", priority: alta, confidence: verificato, sottocriteri: ["C2.1", "C2.2", "C2.3"] }
  - { doc: "[[G-08-ESEC-01_RELAZIONE_GENERALE]]", priority: alta, confidence: verificato, sottocriteri: ["C2.1", "C2.2", "C2.3"] }
  - { doc: "[[PI-00a-ESEC-01_PLANIMETRIA_DI_INSIEME_CON_FOTOVOLTAICO_INTEGRATO_E_FOTOINSERIMENTI]]", priority: alta, confidence: verificato, sottocriteri: ["C2.1"] }
  - { doc: "[[RS-00-ESEC-01_RELAZIONE_TECNICA_IMPIANTI]]", priority: alta, confidence: verificato, sottocriteri: ["C2.1", "C2.2", "C2.3"] }
  - { doc: "[[RS-01-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_FOTOVOLTAICO]]", priority: alta, confidence: parziale, sottocriteri: ["C2.1", "C2.3"] }
  - { doc: "[[PI-00-ESEC-01_PROGETTO_IMPIANTO_FOTOVOLTAICO]]", priority: alta, confidence: inferito, sottocriteri: ["C2.1", "C2.3"] }
  - { doc: "[[G-02-ESEC-01_ELENCO_PREZZI]]", priority: media, confidence: verificato, sottocriteri: ["C2.1", "C2.3"] }
  - { doc: "[[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]]", priority: media, confidence: verificato, sottocriteri: ["C2.1", "C2.2", "C2.3"] }
  - { doc: "[[G-09-ESEC-01_RELAZIONE_CAM]]", priority: media, confidence: verificato, sottocriteri: ["C2.3"] }
  - { doc: "[[G-10-ESEC-01_PIANO_DI_MANUTENZIONE]]", priority: media, confidence: verificato, sottocriteri: ["C2.1", "C2.2", "C2.3"] }
  - { doc: "[[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]]", priority: media, confidence: verificato, sottocriteri: ["C2.1", "C2.3"] }
  - { doc: "[[SIC-01-ESEC-01_CRONOPROGRAMMA]]", priority: media, confidence: verificato, sottocriteri: ["C2.1", "C2.2", "C2.3"] }
  - { doc: "[[G-07-ESEC-01_RELAZIONE_FOTOGRAFICA]]", priority: media, confidence: parziale, sottocriteri: ["C2.1", "C2.2"] }
  - { doc: "[[PI-04-ESEC-01_INTERVENTI_TERMICI]]", priority: media, confidence: inferito, sottocriteri: ["C2.3"] }
  - { doc: "[[PI-05-ESEC-01_INTERVENTI_ELETTRICI]]", priority: media, confidence: inferito, sottocriteri: ["C2.2", "C2.3"] }
  - { doc: "[[VVF-PI-08-00_AREE_A_RISCHIO_SPECIFICO]]", priority: media, confidence: inferito, sottocriteri: ["C2.3"] }
  - { doc: "[[G-00-ESEC-01_ELENCO_ELABORATI]]", priority: bassa, confidence: verificato, sottocriteri: ["C2.1"] }
  - { doc: "[[G-01-ESEC-01_QUADRO_ECONOMICO]]", priority: bassa, confidence: verificato, sottocriteri: ["trasversale"], is_latest: false }
  - { doc: "[[G-01-ESEC-02_QUADRO_ECONOMICO]]", priority: bassa, confidence: verificato, sottocriteri: ["trasversale"] }
  - { doc: "[[G-03-ESEC-01_ANALISI_NUOVI_PREZZI]]", priority: bassa, confidence: verificato, sottocriteri: ["C2.3"] }
  - { doc: "[[G-04-ESEC-01_COMPUTO_METRICO_ESTIMATIVO]]", priority: bassa, confidence: verificato, sottocriteri: ["C2.1", "C2.3"], is_latest: false }
  - { doc: "[[G-05-ESEC-01_QUADRO_INCIDENZA_MANODOPERA]]", priority: bassa, confidence: verificato, sottocriteri: ["trasversale"] }
  - { doc: "[[G-06-ESEC-01_CAPITOLATO_SPECIALE_D_APPALTO]]", priority: bassa, confidence: verificato, sottocriteri: ["C2.1", "C2.2", "C2.3"], is_latest: false }
  - { doc: "[[RS-03-ESEC-01_RELAZIONE_ACUSTICA]]", priority: bassa, confidence: verificato, sottocriteri: ["C2.3"] }
  - { doc: "[[COM-PZ.REGISTRO-UFFICIALE.2026.0007341_Marcato]]", priority: bassa, confidence: inferito, sottocriteri: ["C2.1", "C2.2", "C2.3"] }
  - { doc: "[[IT-02-ESEC-00_INQUADRAMENTO_SU_ORTOFOTO]]", priority: bassa, confidence: inferito, sottocriteri: ["C2.1"] }
  - { doc: "[[IT-03-ESEC-00_INQUADRAMENTO_SU_DTM_CURVE_DI_LIVELLO]]", priority: bassa, confidence: inferito, sottocriteri: ["C2.1"] }
  - { doc: "[[PA-01-ESEC-01_PROSPETTI_stato_di_progetto]]", priority: bassa, confidence: inferito, sottocriteri: ["C2.1", "C2.2"] }
  - { doc: "[[PI-01-ESEC-01_SISTEMA_EVACUAZIONE_FUMI_FORZATO]]", priority: bassa, confidence: inferito, sottocriteri: ["C2.1", "C2.3"] }
  - { doc: "[[PI-03-ESEC-01_PROGETTO_IMPIANTO_IRAI]]", priority: bassa, confidence: inferito, sottocriteri: ["C2.2", "C2.3"] }
  - { doc: "[[VVF-PI-06-00_COPERTURA]]", priority: bassa, confidence: inferito, sottocriteri: ["C2.1"] }
graph_updated: 2026-10-03
---

# Criterio C2 — Energie Rinnovabili e Sistemi di Sicurezza

## Per Claude futuro

Pagina criterio C2 della gara Cineteatro “Periz” — Castello di Bella (CIG BCF01395AF). Criterio 2 della tabella art. 18.1 (p. 28): **30 punti su 90 (33,3%), il criterio più pesante**, priorità ALTA, interamente **discrezionale**. Contiene il sub-criterio singolo più pesante della gara (C2.1 BIPV, 15 punti), per il quale il disciplinare rinvia espressamente all'elaborato `PI-00a-ESEC-01` (presente in `00_input` ma non firmato e non in Elenco Elaborati, secondo il manifest). C2.2 è una "proposta integrativa" (impianto non previsto come tale nel perimetro della tabella). Fonte unica: disciplinare. Confidence: verificato.

## Punteggio massimo

30 punti (art. 18.1, p. 28)

## Subcriteri

| ID sub | Descrizione | Punti | Natura |
|---|---|---|---|
| C2.1 | Integrazione architettonica dell'impianto fotovoltaico (BIPV) | 15 | D |
| C2.2 | Sistemi antintrusione e videosorveglianza | 8 | D |
| C2.3 | Sistemi di accumulo e Building Automation | 7 | D |

### Testo del disciplinare — "Oggetto della valutazione / perimetro tecnico delle migliorie" (p. 28)

- **C2.1** — "(D) Sistemi fotovoltaici integrati sulla copertura, valutati in base all'azzeramento dell'impatto visivo, assenza di riflettanza e totale conformità agli indirizzi di tutela del vicino Castello della Soprintendenza Basilicata. (ai fini della formulazione della miglioria, si rimanda all'elaborato grafico PI-00a-ESEC-01_PLANIMETRIA DI INSIEME CON FOTOVOLTAICO INTEGRATO E FOTOINSERIMENTI)"
- **C2.2** — "(D) Proposta integrativa per la fornitura e installazione di un impianto di allarme perimetrale/volumetrico e di videosorveglianza TVCC a protezione della struttura e dei suoi accessi."
- **C2.3** — "(D) Incremento quantitativo della capacità di accumulo delle batterie (>20 kWh) e sistemi software di gestione e controllo remoto integrato degli impianti del teatro."

## Metodo di attribuzione

Discrezionale (art. 18.2, p. 30): coefficiente 0-1 per commissario sulla scala a sei livelli, media aritmetica per sub-criterio, I^ riparametrazione per sub-criterio (art. 18.4, p. 31). Per C2.1 il disciplinare esplicita i tre parametri di giudizio: impatto visivo (azzeramento), riflettanza (assenza), conformità agli indirizzi di tutela (totale).

## Elementi premianti

- C2.1 — azzeramento dell'impatto visivo del fotovoltaico integrato sulla copertura
- C2.1 — assenza di riflettanza
- C2.1 — totale conformità agli indirizzi di tutela della Soprintendenza Basilicata
- C2.2 — impianto di allarme perimetrale/volumetrico
- C2.2 — videosorveglianza TVCC a protezione della struttura e dei suoi accessi
- C2.3 — incremento quantitativo della capacità di accumulo delle batterie (>20 kWh)
- C2.3 — software di gestione e controllo remoto integrato degli impianti del teatro

## Vincoli espliciti

- C2.1: FV "integrato sulla copertura" e formulato con riferimento all'elaborato `PI-00a-ESEC-01` (p. 28).
- C2.1: conformità totale agli indirizzi di tutela della Soprintendenza Basilicata (p. 28).
- C2.3: riferimento quantitativo ">20 kWh" (p. 28).
- Rispetto, pena l'esclusione, delle caratteristiche minime dei documenti di gara (art. 16, p. 25).
- Computo metrico non estimativo per ogni miglioria, senza prezzi (art. 16, p. 26).
- Nessun elemento economico nei documenti dell'offerta tecnica: **esclusione** (art. 16, p. 26; art. 22, p. 33).
- Migliorie parametro della verifica di anomalia (art. 23, p. 33).

## Vincoli impliciti

- La sala è in un'ala del Castello Aragonese di Bella (art. 11, p. 16): ogni intervento visibile in copertura ricade nella tutela (inferito).
- Durata lavori fissa 150 giorni (art. 3.1, p. 8).
- Il progetto comprende già lavori di categoria OG9 "Impianti per la produzione di energia elettrica" per € 41.600,21 (p. 8): C2.1 e C2.3 migliorano un impianto già previsto, non ne introducono uno nuovo (inferito dalla categoria).

## Limiti dimensionali o formali

- Sezione C2 entro le 30 facciate complessive della relazione (A4, numerate, font ≥ 11 pt) (art. 16, p. 25).
- Elaborati grafici e schede tecniche non conteggiati (art. 16, p. 25): rilevanti per C2.1 (fotoinserimenti, dettagli di integrazione).

## Documenti richiesti

- Relazione tecnica — sezione C2, con una parte per ciascun sub-criterio C2.1, C2.2, C2.3 (art. 16, p. 25)
- Computo metrico non estimativo — voci delle migliorie C2 (art. 16, pp. 25-26)
- Cronoprogramma delle lavorazioni (documento unico) che evidenzi l'inserimento delle migliorie C2 (art. 16, p. 26)
- Facoltativi: elaborati grafici (es. fotoinserimenti, planimetrie impianto) e schede tecniche esplicative (art. 16, p. 25)

## Rischi fuori scope

- C2.1 non conforme alla tutela o con impatto visivo/riflettanza (p. 28).
- Estensione del campo FV oltre la copertura o modifiche strutturali (inferito).
- C2.2 con installazioni invasive su paramenti storici (inferito).
- C2.3 con esigenze di nuovi locali o presidi antincendio (inferito).

## Note e ambiguità

- **">20 kWh" (C2.3):** non è chiaro se 20 kWh sia la capacità di progetto (e quindi si valuta l'incremento oltre 20) o una soglia minima dell'offerta. Da verificare sugli elaborati e, se necessario, con chiarimento entro il 06/10/2026 ore 12:00.
- **"vicino Castello" (C2.1):** la sala è dentro il castello (art. 11, p. 16); gli "indirizzi di tutela" non sono riportati nel disciplinare.
- `PI-00a-ESEC-01` (rinviato dal sub 2.1): nel manifest è un PDF non firmato, assente dall'Elenco Elaborati `G-00-ESEC-01`, con dicitura "dettaglio offerta tecnica".

## Checklist operativa

- [ ] Leggere `PI-00a-ESEC-01` (planimetria FV integrato e fotoinserimenti) come riferimento obbligato per C2.1
- [ ] Ricavare dagli elaborati configurazione, superficie e potenza del FV di progetto e gli eventuali indirizzi/pareri di tutela
- [ ] Ricavare la capacità di accumulo di progetto per interpretare ">20 kWh" (C2.3)
- [ ] Verificare se il progetto prevede già impianti antintrusione/TVCC o predisposizioni (C2.2)
- [ ] Verificare impianti elettrici e di supervisione di progetto per l'integrazione della Building Automation (C2.3)
- [ ] Per C2.1: rendere verificabili impatto visivo, riflettanza e conformità (fotoinserimenti, schede prodotto)
- [ ] Per ogni miglioria: voce di computo non estimativo senza prezzi e collocazione nel cronoprogramma
