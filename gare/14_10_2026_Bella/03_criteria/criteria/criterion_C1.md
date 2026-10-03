---
type: criterion
id: C1
gara: "Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)"
date: 2026-10-03
ai-first: true
confidence: verificato
titolo: "Involucro, Poltrone ed Efficientamento Acustico"
criterio_disciplinare: "1. Involucro, Poltrone ed Efficientamento Acustico"
punteggio_max: 25
peso_pct_tecnico: 27.8
natura: discrezionale
fonte: "Disciplinare art. 18.1, Tabella criteri D/T, p. 28"
subcriteri:
  - { id: "C1.1", titolo: "Qualità, quantità ed efficientamento nodi dei nuovi infissi", punti: 10, natura: "D" }
  - { id: "C1.2", titolo: "Fornitura quantitativa e qualità delle nuove poltrone", punti: 7, natura: "D" }
  - { id: "C1.3", titolo: "Efficientamento e risanamento acustico dei materiali interni", punti: 8, natura: "D" }
modification_limits:
  - "C1.1: le prestazioni termo-acustiche dei serramenti (Uf/Uw, Rw) devono essere superiori ai minimi di progetto: il progetto esecutivo validato è la soglia minima (art. 18.1, sub 1.1, p. 28)"
  - "L'offerta tecnica deve rispettare, pena l'esclusione, le caratteristiche minime stabilite nei documenti di gara, nel rispetto del principio di equivalenza (art. 16, p. 25)"
  - "Le poltrone sono arredi soggetti ai CAM D.M. 23 giugno 2022 n. 254; i lavori ai CAM D.M. 24.11.2025, richiamati nell'Elaborato B3 (Premesse, p. 3)"
  - "Le migliorie, sommate alle prestazioni di progetto, non devono far emergere dubbi sulla sostenibilità economica complessiva dell'offerta: parametro della verifica di anomalia (art. 23, p. 33)"
  - "Durata lavori fissa di 150 giorni naturali e consecutivi comprensivi di forniture e posa: le migliorie vanno inserite nel cronoprogramma dell'offerta (art. 3.1, p. 8; art. 16, p. 26)"
fuori_scope_risks:
  - "C1.1: modifiche a geometria, partiture o aspetto esterno dei serramenti in un'ala del Castello Aragonese (art. 11, p. 16) potrebbero eccedere il progetto approvato e richiedere autorizzazioni di tutela (inferito: il disciplinare cita la Soprintendenza solo nel sub 2.1)"
  - "C1.1: 'superfici vetrate aggiuntive' che comportino nuove aperture o modifiche dell'involucro non previste dal progetto validato configurano variante, non miglioria (inferito)"
  - "C1.3: pannellature MDF o rivestimenti devono restare compatibili con l'adeguamento antincendio della sala (Premesse, p. 3) e con le classi di reazione al fuoco richieste (inferito)"
  - "C1.2: scorta di poltrone ed estensione garanzia con incidenza economica rilevante ai fini della verifica di anomalia (art. 23, p. 33)"
# --- Aggiunto/aggiornato da graph-builder 2026-10-03 ---
# supported_by = archi inversi di supports_criteria delle pagine 02_graph/nodes/ (Fase F).
# Ordine: priority alta > media > bassa; a parita', confidence verificato > parziale > inferito, poi codice.
# confidence = dell'arco: esplicita sull'arco se presente, altrimenti quella della pagina nodo;
#   inferito se la reason dichiara il collegamento inferito/dedotto. Tavole: contenuto grafico non letto.
# sottocriteri = citati nella reason dell'arco; "trasversale" = cornice economica / verifica di anomalia (art. 23).
# is_latest: false = versione superata, solo confronto tra versioni, mai baseline.
# Evidenza debole per elemento premiante (Fase F; dettaglio in 02_graph/log.md):
#   C1.1 - Uw/Uf/Rw di progetto solo come range della voce Nr. 24 di G-02 (computo voce 35); relazione ex L. 10/91 e abaco serramenti richiamati dal capitolato assenti da 00_input; geometria e partiture solo da tavole inferite (PA-01, RIL-01, RIL-02).
#   C1.2 - estensione della garanzia: solo G-11 (bassa, garanzia contrattuale, nessuna di prodotto); scorta assente nel computo; il 'preventivo allegato' delle poltrone (G-08, SIC-00) non e' tra gli elaborati.
#   C1.3 - classi di reazione al fuoco di finiture e MDF solo da tavole inferite (PI-02, VVF-PI-02...05) e prescrizioni generali RTV15 (COM-PZ); unico indice acustico calcolato = T60 (RS-03).
supported_by:
  - { doc: "[[G-02-ESEC-01_ELENCO_PREZZI]]", priority: alta, confidence: verificato, sottocriteri: ["C1.1", "C1.2", "C1.3"] }
  - { doc: "[[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]]", priority: alta, confidence: verificato, sottocriteri: ["C1.1", "C1.2", "C1.3"] }
  - { doc: "[[G-08-ESEC-01_RELAZIONE_GENERALE]]", priority: alta, confidence: verificato, sottocriteri: ["C1.1", "C1.2", "C1.3"] }
  - { doc: "[[RS-03-ESEC-01_RELAZIONE_ACUSTICA]]", priority: alta, confidence: verificato, sottocriteri: ["C1.1", "C1.2", "C1.3"] }
  - { doc: "[[COM-PZ.REGISTRO-UFFICIALE.2026.0007341_Marcato]]", priority: media, confidence: verificato, sottocriteri: ["C1.1", "C1.2", "C1.3"] }
  - { doc: "[[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]]", priority: media, confidence: verificato, sottocriteri: ["C1.1"] }
  - { doc: "[[G-09-ESEC-01_RELAZIONE_CAM]]", priority: media, confidence: verificato, sottocriteri: ["C1.1", "C1.3"] }
  - { doc: "[[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]]", priority: media, confidence: verificato, sottocriteri: ["C1.1", "C1.2"] }
  - { doc: "[[SIC-01-ESEC-01_CRONOPROGRAMMA]]", priority: media, confidence: verificato, sottocriteri: ["C1.1", "C1.2", "C1.3"] }
  - { doc: "[[G-07-ESEC-01_RELAZIONE_FOTOGRAFICA]]", priority: media, confidence: parziale, sottocriteri: ["C1.1", "C1.2", "C1.3"] }
  - { doc: "[[PA-00-ESEC-01_PIANTE_stato_di_progetto]]", priority: media, confidence: inferito, sottocriteri: ["C1.1", "C1.2", "C1.3"] }
  - { doc: "[[PA-01-ESEC-01_PROSPETTI_stato_di_progetto]]", priority: media, confidence: inferito, sottocriteri: ["C1.1"] }
  - { doc: "[[PI-02-ESEC-01_PROGETTO_CON_INDICAZIONE_CLASSI_RESISTENZA_AL_FUOCO]]", priority: media, confidence: inferito, sottocriteri: ["C1.3"] }
  - { doc: "[[G-00-ESEC-01_ELENCO_ELABORATI]]", priority: bassa, confidence: verificato, sottocriteri: ["C1.1", "C1.2", "C1.3"] }
  - { doc: "[[G-01-ESEC-01_QUADRO_ECONOMICO]]", priority: bassa, confidence: verificato, sottocriteri: ["trasversale"], is_latest: false }
  - { doc: "[[G-01-ESEC-02_QUADRO_ECONOMICO]]", priority: bassa, confidence: verificato, sottocriteri: ["trasversale"] }
  - { doc: "[[G-04-ESEC-01_COMPUTO_METRICO_ESTIMATIVO]]", priority: bassa, confidence: verificato, sottocriteri: ["C1.1", "C1.2", "C1.3"], is_latest: false }
  - { doc: "[[G-05-ESEC-01_QUADRO_INCIDENZA_MANODOPERA]]", priority: bassa, confidence: verificato, sottocriteri: ["trasversale"] }
  - { doc: "[[G-06-ESEC-01_CAPITOLATO_SPECIALE_D_APPALTO]]", priority: bassa, confidence: verificato, sottocriteri: ["C1.1"], is_latest: false }
  - { doc: "[[G-10-ESEC-01_PIANO_DI_MANUTENZIONE]]", priority: bassa, confidence: verificato, sottocriteri: ["C1.3"] }
  - { doc: "[[G-11-ESEC-01_SCHEMA_DI_CONTRATTO]]", priority: bassa, confidence: verificato, sottocriteri: ["C1.2"] }
  - { doc: "[[PA-02-ESEC-01_SEZIONI_stato_di_progetto]]", priority: bassa, confidence: inferito, sottocriteri: ["C1.3"] }
  - { doc: "[[RIL-01-ESEC-01_PIANTE_stato_di_fatto]]", priority: bassa, confidence: inferito, sottocriteri: ["C1.1"] }
  - { doc: "[[RIL-02-ESEC-01_PROSPETTI_stato_di_fatto]]", priority: bassa, confidence: inferito, sottocriteri: ["C1.1"] }
  - { doc: "[[RS-02-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_IDRICO_ANTINCENDIO]]", priority: bassa, confidence: inferito, sottocriteri: ["C1.2", "C1.3"] }
  - { doc: "[[VVF-PI-02-00_PIANTA_PIANO_TERRA]]", priority: bassa, confidence: inferito, sottocriteri: ["C1.3"] }
  - { doc: "[[VVF-PI-03-00_PIANTA_PIANO_PRIMO]]", priority: bassa, confidence: inferito, sottocriteri: ["C1.3"] }
  - { doc: "[[VVF-PI-04-00_PIANTA_PIANO_SECONDO]]", priority: bassa, confidence: inferito, sottocriteri: ["C1.3"] }
  - { doc: "[[VVF-PI-05-00_PIANTA_PIANO_TERZO]]", priority: bassa, confidence: inferito, sottocriteri: ["C1.3"] }
graph_updated: 2026-10-03
---

# Criterio C1 — Involucro, Poltrone ed Efficientamento Acustico

## Per Claude futuro

Pagina criterio C1 della gara Cineteatro “Periz” — Castello di Bella (CIG BCF01395AF). Criterio 1 della tabella art. 18.1 del disciplinare (p. 28): 25 punti su 90 tecnici (27,8%, priorità ALTA), interamente **discrezionale**, in tre sub-criteri (serramenti 10, poltrone 7, acustica materiali interni 8). Il riferimento di confronto è sempre il progetto esecutivo a base di gara ("minimi di progetto"). Fonte unica: disciplinare; nessun elaborato di progetto letto. Confidence: verificato (testo tabella confrontato con il PDF originale).

## Punteggio massimo

25 punti (art. 18.1, p. 28)

## Subcriteri

| ID sub | Descrizione | Punti | Natura |
|---|---|---|---|
| C1.1 | Qualità, quantità ed efficientamento nodi dei nuovi infissi | 10 | D |
| C1.2 | Fornitura quantitativa e qualità delle nuove poltrone | 7 | D |
| C1.3 | Efficientamento e risanamento acustico dei materiali interni | 8 | D |

### Testo del disciplinare — "Oggetto della valutazione / perimetro tecnico delle migliorie" (p. 28)

- **C1.1** — "(D) Proposte per il miglioramento delle prestazioni termo-acustiche complessive dei serramenti (trasmittanza Uf/Uw e abbattimento Rw) superiori ai minimi di progetto; fornitura quantitativa aggiuntiva di superfici vetrate performanti; soluzioni di isolamento termo-acustico integrativo dei nodi di posa (infisso-muratura) per l'eliminazione dei ponti termici e la prevenzione di condense/muffe."
- **C1.2** — "(D) Parametri migliorativi relativi all'ergonomia delle sedute, alla quantità di poltrone complete fornite come scorta di rispetto e all'estensione della garanzia."
- **C1.3** — "(D) Proposte per l'impiego di materiali di finitura, pannellature (MDF) o rivestimenti speciali a elevate prestazioni fonoassorbenti/fonoisolanti per ottimizzare il tempo di riverbero e l'acustica della sala."

## Metodo di attribuzione

Discrezionale (art. 18.2, p. 30): ogni commissario (3 membri, art. 19) assegna per ciascun sub-criterio un coefficiente 0-1 (eccellente/ottimo 0,81-1; buono 0,61-0,80; discreto/adeguato 0,41-0,60; sufficiente 0,21-0,40; scarso/mediocre 0,01-0,20; insufficiente/non valutabile 0). Coefficiente = media aritmetica. Punteggio = coefficiente × punti del sub. I^ riparametrazione per sub-criterio: il migliore prende il massimo, gli altri in proporzione (art. 18.4, p. 31). Arrotondamento a 2 decimali.

## Elementi premianti

- C1.1 — trasmittanza Uf/Uw e abbattimento acustico Rw dei serramenti **superiori ai minimi di progetto**
- C1.1 — fornitura quantitativa aggiuntiva di superfici vetrate performanti
- C1.1 — isolamento termo-acustico integrativo dei nodi di posa infisso-muratura (eliminazione ponti termici, prevenzione condense/muffe)
- C1.2 — ergonomia delle sedute
- C1.2 — quantità di poltrone complete fornite come scorta di rispetto
- C1.2 — estensione della garanzia
- C1.3 — materiali di finitura, pannellature (MDF) o rivestimenti speciali ad elevate prestazioni fonoassorbenti/fonoisolanti
- C1.3 — ottimizzazione del tempo di riverbero e dell'acustica della sala

## Vincoli espliciti

- Prestazioni dei serramenti superiori ai minimi di progetto (art. 18.1, sub 1.1, p. 28).
- Rispetto, pena l'esclusione, delle caratteristiche minime dei documenti di gara, principio di equivalenza (art. 16, p. 25).
- Relazione strutturata per criteri e sub-criteri: per C1.1, C1.2, C1.3 va descritto quanto offerto (art. 16, p. 25).
- Ogni miglioria deve comparire nel computo metrico non estimativo con riferimento al sub-criterio, descrizione, unità di misura, quantità ed elementi tecnici di verifica (art. 16, p. 26).
- Nessun prezzo, importo, ribasso o valorizzazione economica in relazione, computo non estimativo e cronoprogramma: **esclusione** (art. 16, p. 26; art. 22, p. 33).
- CAM D.M. 24.11.2025 (lavori) e D.M. 23 giugno 2022 n. 254 (arredi) richiamati dal progetto (Premesse, p. 3).
- Le migliorie sono parametro della verifica di anomalia (art. 23, p. 33).

## Vincoli impliciti

- Durata lavori fissa di 150 giorni naturali e consecutivi (art. 3.1, p. 8): forniture aggiuntive (vetrate, poltrone di scorta) e lavorazioni dei nodi vanno integrate nel cronoprogramma senza criterio premiale sul tempo.
- Edificio esistente in un'ala del Castello Aragonese con accessi, movimentazione e deposito condizionati (art. 11, pp. 16-17): incide sulla fattibilità delle forniture voluminose.
- La sala è oggetto di adeguamento antincendio (Premesse, p. 3): i materiali interni proposti in C1.3 devono rispettare i requisiti di reazione al fuoco (inferito).

## Limiti dimensionali o formali

- Sezione C1 entro il limite complessivo della relazione: max 15 pagine fronte-retro = 30 facciate A4 numerate, font ≥ 11 pt, per tutti i criteri (tipo B, distribuibile) (art. 16, p. 25).
- Elaborati grafici e schede tecniche esplicative ammessi e non conteggiati (art. 16, p. 25).

## Documenti richiesti

- Relazione tecnica — sezione C1, con una parte per ciascun sub-criterio C1.1, C1.2, C1.3 (art. 16, p. 25)
- Computo metrico non estimativo — voci delle migliorie C1 (art. 16, pp. 25-26)
- Cronoprogramma delle lavorazioni (documento unico) che evidenzi l'inserimento delle migliorie C1 (art. 16, p. 26)
- Facoltativi: elaborati grafici e schede tecniche esplicative (es. schede prodotto serramenti/poltrone/materiali) (art. 16, p. 25)

## Rischi fuori scope

- Modifiche all'aspetto esterno dei serramenti in edificio storico (inferito).
- Nuove aperture o modifiche d'involucro per "superfici vetrate aggiuntive" (inferito).
- Materiali acustici non compatibili con la prevenzione incendi (inferito).
- Incidenza economica elevata di scorte e garanzie (art. 23, p. 33).

## Note e ambiguità

- Il disciplinare non quantifica i "minimi di progetto" (Uf/Uw, Rw), il numero di poltrone né la garanzia base: vanno ricavati dagli elaborati in fase di analisi.

## Checklist operativa

- [ ] Ricavare dagli elaborati i valori minimi di progetto di Uf, Uw, Rw e l'abaco dei nuovi serramenti (baseline C1.1)
- [ ] Ricavare i dettagli dei nodi di posa infisso-muratura previsti in progetto
- [ ] Ricavare numero, tipologia, specifiche ergonomiche e garanzia delle poltrone di progetto (baseline C1.2) e i requisiti CAM arredi applicabili
- [ ] Ricavare tempo di riverbero di progetto/obiettivo e materiali interni previsti (baseline C1.3)
- [ ] Verificare i requisiti di reazione al fuoco per finiture e pannellature (pratica VV.F. / tavole prevenzione incendi)
- [ ] Verificare vincoli di tutela sull'involucro del castello
- [ ] Per ogni miglioria: indicatore misurabile rispetto al minimo di progetto (valore offerto vs valore di progetto)
- [ ] Per ogni miglioria: voce di computo non estimativo (u.m., quantità) senza prezzi
- [ ] Per ogni miglioria: collocazione nel cronoprogramma entro 150 giorni
