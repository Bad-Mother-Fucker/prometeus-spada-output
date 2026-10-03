---
type: criterion
id: C3
gara: "Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)"
date: 2026-10-03
ai-first: true
confidence: verificato
titolo: "Logistica Cantieri e Dotazioni Cinematografiche"
criterio_disciplinare: "3. Logistica Cantieri e Dotazioni Cinematografiche"
punteggio_max: 15
peso_pct_tecnico: 16.7
natura: discrezionale
fonte: "Disciplinare art. 18.1, Tabella criteri D/T, p. 29"
subcriteri:
  - { id: "C3.1", titolo: "Risoluzione delle carenze termiche su terrazzi e cupola", punti: 5, natura: "D" }
  - { id: "C3.2", titolo: "Attrezzature o arredi cinematografici migliorativi/aggiuntivi", punti: 5, natura: "D" }
  - { id: "C3.3", titolo: "Logistica e piano di protezione delle attrezzature esistenti", punti: 5, natura: "D" }
modification_limits:
  - "C3.2: le forniture sono valutate se aggiuntive o a prestazioni superiori rispetto alla configurazione base del cineteatro di progetto (art. 18.1, sub 3.2, p. 29)"
  - "C3.3: la metodologia riguarda impianto audio, proiettori e schermo del cineteatro esistente (smontaggio, imballaggio protettivo, stoccaggio sicuro, rimontaggio/taratura) (art. 18.1, sub 3.3, p. 29)"
  - "L'offerta tecnica deve rispettare, pena l'esclusione, le caratteristiche minime stabilite nei documenti di gara, nel rispetto del principio di equivalenza (art. 16, p. 25)"
  - "Le migliorie, sommate alle prestazioni di progetto, non devono far emergere dubbi sulla sostenibilità economica complessiva dell'offerta: parametro della verifica di anomalia (art. 23, p. 33)"
fuori_scope_risks:
  - "C3.1: interventi su cupola in vetro e copertura del castello visibili dall'esterno — possibile incompatibilità con la tutela (inferito; la sala è in un'ala del Castello Aragonese, art. 11, p. 16)"
  - "C3.1: spessori e sovraccarichi aggiuntivi in copertura con impatto su impermeabilizzazione, quote e soglie (inferito)"
  - "C3.2: forniture non pertinenti alla configurazione del cineteatro o con incidenza economica rilevante ai fini dell'anomalia (art. 23, p. 33)"
# --- Aggiunto/aggiornato da graph-builder 2026-10-03 ---
# supported_by = archi inversi di supports_criteria delle pagine 02_graph/nodes/ (Fase F).
# Ordine: priority alta > media > bassa; a parita', confidence verificato > parziale > inferito, poi codice.
# confidence = dell'arco: esplicita sull'arco se presente, altrimenti quella della pagina nodo;
#   inferito se la reason dichiara il collegamento inferito/dedotto. Tavole: contenuto grafico non letto.
# sottocriteri = citati nella reason dell'arco; "trasversale" = cornice economica / verifica di anomalia (art. 23).
# is_latest: false = versione superata, solo confronto tra versioni, mai baseline.
# Evidenza debole per elemento premiante (Fase F; dettaglio in 02_graph/log.md):
#   C3.1 - vincoli dei torrini di estrazione fumi sulla cupola solo da tavole inferite (VVF-PI-07, PI-01); PA-05 (alta) non letta.
#   C3.2 - copertura piu' bassa tra i sottocriteri discrezionali (6 documenti): unica baseline verificata = NP 07 palco e allestimento (G-04-ESEC-02, G-02); nessun elaborato descrive la configurazione base di attrezzature multimediali e cinematografiche.
#   C3.3 - nessun elaborato censisce impianto audio, proiettori e schermo esistenti (solo foto G-07, parziale): evidenza alta solo di assenza (PSC, cronoprogramma, computo).
supported_by:
  - { doc: "[[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]]", priority: alta, confidence: verificato, sottocriteri: ["C3.1", "C3.2", "C3.3"] }
  - { doc: "[[G-08-ESEC-01_RELAZIONE_GENERALE]]", priority: alta, confidence: verificato, sottocriteri: ["C3.1", "C3.3"] }
  - { doc: "[[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]]", priority: alta, confidence: verificato, sottocriteri: ["C3.1", "C3.3"] }
  - { doc: "[[SIC-01-ESEC-01_CRONOPROGRAMMA]]", priority: alta, confidence: verificato, sottocriteri: ["C3.1", "C3.3"] }
  - { doc: "[[G-07-ESEC-01_RELAZIONE_FOTOGRAFICA]]", priority: alta, confidence: parziale, sottocriteri: ["C3.1", "C3.2", "C3.3"] }
  - { doc: "[[PA-05-ESEC-01_cupola_e_impermeabilizzazione]]", priority: alta, confidence: inferito, sottocriteri: ["C3.1"] }
  - { doc: "[[SIC-02-ESEC-01_LAYOUT_DI_CANTIERE]]", priority: alta, confidence: inferito, sottocriteri: ["C3.3"] }
  - { doc: "[[G-02-ESEC-01_ELENCO_PREZZI]]", priority: media, confidence: verificato, sottocriteri: ["C3.1", "C3.2"] }
  - { doc: "[[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]]", priority: media, confidence: verificato, sottocriteri: ["C3.1", "C3.3"] }
  - { doc: "[[G-09-ESEC-01_RELAZIONE_CAM]]", priority: media, confidence: verificato, sottocriteri: ["C3.1"] }
  - { doc: "[[SIC-03-ESEC-01_COSTI_PER_LA_SICUREZZA]]", priority: media, confidence: verificato, sottocriteri: ["C3.3"] }
  - { doc: "[[PA-02-ESEC-01_SEZIONI_stato_di_progetto]]", priority: media, confidence: inferito, sottocriteri: ["C3.1"] }
  - { doc: "[[RIL-01-ESEC-01_PIANTE_stato_di_fatto]]", priority: media, confidence: inferito, sottocriteri: ["C3.1", "C3.3"] }
  - { doc: "[[G-00-ESEC-01_ELENCO_ELABORATI]]", priority: bassa, confidence: verificato, sottocriteri: ["C3.1", "C3.3"] }
  - { doc: "[[G-01-ESEC-01_QUADRO_ECONOMICO]]", priority: bassa, confidence: verificato, sottocriteri: ["trasversale"], is_latest: false }
  - { doc: "[[G-01-ESEC-02_QUADRO_ECONOMICO]]", priority: bassa, confidence: verificato, sottocriteri: ["trasversale"] }
  - { doc: "[[G-03-ESEC-01_ANALISI_NUOVI_PREZZI]]", priority: bassa, confidence: verificato, sottocriteri: ["C3.3"] }
  - { doc: "[[G-04-ESEC-01_COMPUTO_METRICO_ESTIMATIVO]]", priority: bassa, confidence: verificato, sottocriteri: ["C3.1", "C3.2"], is_latest: false }
  - { doc: "[[G-05-ESEC-01_QUADRO_INCIDENZA_MANODOPERA]]", priority: bassa, confidence: verificato, sottocriteri: ["C3.3"] }
  - { doc: "[[G-06-ESEC-01_CAPITOLATO_SPECIALE_D_APPALTO]]", priority: bassa, confidence: verificato, sottocriteri: ["C3.1", "C3.3"], is_latest: false }
  - { doc: "[[COM-PZ.REGISTRO-UFFICIALE.2026.0007341_Marcato]]", priority: bassa, confidence: inferito, sottocriteri: ["C3.2"] }
  - { doc: "[[IT-01-ESEC-00_INQUADRAMENTO_SU_CTR]]", priority: bassa, confidence: inferito, sottocriteri: ["C3.3"] }
  - { doc: "[[PA-00-ESEC-01_PIANTE_stato_di_progetto]]", priority: bassa, confidence: inferito, sottocriteri: ["C3.2", "C3.3"] }
  - { doc: "[[PI-00-ESEC-01_PROGETTO_IMPIANTO_FOTOVOLTAICO]]", priority: bassa, confidence: inferito, sottocriteri: ["C3.1"] }
  - { doc: "[[PI-01-ESEC-01_SISTEMA_EVACUAZIONE_FUMI_FORZATO]]", priority: bassa, confidence: inferito, sottocriteri: ["C3.1"] }
  - { doc: "[[RIL-00-ESEC-01_PLANIMETRIA_stato_di_fatto]]", priority: bassa, confidence: inferito, sottocriteri: ["C3.3"] }
  - { doc: "[[RIL-02-ESEC-01_PROSPETTI_stato_di_fatto]]", priority: bassa, confidence: inferito, sottocriteri: ["C3.1"] }
  - { doc: "[[RS-02-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_IDRICO_ANTINCENDIO]]", priority: bassa, confidence: inferito, sottocriteri: ["C3.3"] }
  - { doc: "[[VVF-PI-06-00_COPERTURA]]", priority: bassa, confidence: inferito, sottocriteri: ["C3.1"] }
  - { doc: "[[VVF-PI-07-00_PROSPETTO_E_SEZIONE]]", priority: bassa, confidence: inferito, sottocriteri: ["C3.1"] }
graph_updated: 2026-10-03
---

# Criterio C3 — Logistica Cantieri e Dotazioni Cinematografiche

## Per Claude futuro

Pagina criterio C3 della gara Cineteatro “Periz” — Castello di Bella (CIG BCF01395AF). Criterio 3 della tabella art. 18.1 (p. 29): 15 punti su 90 (16,7%), interamente **discrezionale**, tre sub-criteri da 5 punti. Attenzione: il titolo ("Logistica Cantieri") non descrive il sub 3.1, che riguarda l'isolamento termico della copertura piana e il carico termico estivo della cupola in vetro; il sub 3.3 è l'unico sub-criterio della gara di natura **metodologica** (protezione delle attrezzature esistenti), senza forniture. Fonte unica: disciplinare. Confidence: verificato.

## Punteggio massimo

15 punti (art. 18.1, p. 29)

## Subcriteri

| ID sub | Descrizione | Punti | Natura |
|---|---|---|---|
| C3.1 | Risoluzione delle carenze termiche su terrazzi e cupola | 5 | D |
| C3.2 | Attrezzature o arredi cinematografici migliorativi/aggiuntivi | 5 | D |
| C3.3 | Logistica e piano di protezione delle attrezzature esistenti | 5 | D |

### Testo del disciplinare — "Oggetto della valutazione / perimetro tecnico delle migliorie" (p. 29)

- **C3.1** — "(D) Proposte per l'inserimento dello strato di isolamento termico sulla copertura piana e sistemi per l'abbattimento del carico termico estivo (effetto serra) della cupola in vetro."
- **C3.2** — "(D) Proposte per la fornitura e posa in opera di components, arredi tecnici o attrezzature multimediali e cinematografiche aggiuntive o a prestazioni superiori rispetto alla configurazione base del cineteatro."
- **C3.3** — "(D) Metodologia operative per lo smontaggio, imballaggio protettivo, stoccaggio sicuro e successivo rimontaggio/taratura dell'impianto audio, proiettori e dello schermo del cineteatro esistente."

## Metodo di attribuzione

Discrezionale (art. 18.2, p. 30): coefficiente 0-1 per commissario sulla scala a sei livelli, media aritmetica per sub-criterio, I^ riparametrazione per sub-criterio (art. 18.4, p. 31).

## Elementi premianti

- C3.1 — inserimento dello strato di isolamento termico sulla copertura piana
- C3.1 — sistemi per l'abbattimento del carico termico estivo (effetto serra) della cupola in vetro
- C3.2 — componenti, arredi tecnici o attrezzature multimediali e cinematografiche **aggiuntive** o **a prestazioni superiori** rispetto alla configurazione base
- C3.3 — metodologia operativa di smontaggio, imballaggio protettivo, stoccaggio sicuro e rimontaggio/taratura di impianto audio, proiettori e schermo esistenti

## Vincoli espliciti

- C3.2: termine di confronto è la "configurazione base del cineteatro" (p. 29).
- C3.3: oggetto limitato a impianto audio, proiettori e schermo esistenti (p. 29).
- Rispetto, pena l'esclusione, delle caratteristiche minime dei documenti di gara (art. 16, p. 25).
- Computo metrico non estimativo per ogni miglioria (anche C3.3 se comporta prestazioni quantificabili), senza prezzi (art. 16, p. 26).
- Nessun elemento economico nell'offerta tecnica: **esclusione** (art. 16, p. 26; art. 22, p. 33).
- Migliorie parametro della verifica di anomalia (art. 23, p. 33).

## Vincoli impliciti

- Cantiere in un contesto edilizio esistente con peculiari condizioni logistiche: accessi, movimentazione, deposito di materiali e mezzi, spazi per l'allestimento del cantiere e interferenze (art. 11, pp. 16-17) — il disciplinare li indica come motivo dell'obbligo di sopralluogo, quindi sono rilevanti anche per C3.3.
- Durata lavori fissa 150 giorni (art. 3.1, p. 8): smontaggio e rimontaggio delle attrezzature e posa delle forniture C3.2 vanno collocati nel cronoprogramma.

## Limiti dimensionali o formali

- Sezione C3 entro le 30 facciate complessive (A4, numerate, font ≥ 11 pt) (art. 16, p. 25).
- Elaborati grafici e schede tecniche non conteggiati (art. 16, p. 25).

## Documenti richiesti

- Relazione tecnica — sezione C3, con una parte per ciascun sub-criterio C3.1, C3.2, C3.3 (art. 16, p. 25)
- Computo metrico non estimativo — voci delle migliorie C3 (art. 16, pp. 25-26)
- Cronoprogramma delle lavorazioni (documento unico) che evidenzi l'inserimento delle migliorie C3 (art. 16, p. 26)
- Facoltativi: elaborati grafici e schede tecniche esplicative (art. 16, p. 25)

## Rischi fuori scope

- Interventi visibili su cupola e copertura in edificio tutelato (inferito).
- Sovraccarichi o spessori in copertura (inferito).
- Forniture non pertinenti o economicamente rilevanti (art. 23, p. 33).

## Note e ambiguità

- Il titolo del criterio non corrisponde al contenuto del sub 3.1 (termico): trattarlo comunque sotto C3 come da tabella.
- Refusi nel testo originale: "components" (C3.2), "Metodologia operative" (C3.3).

## Checklist operativa

- [ ] Ricavare dagli elaborati stratigrafia attuale e di progetto di copertura piana/terrazzi e cupola in vetro (baseline C3.1)
- [ ] Verificare se il progetto prevede già isolamento in copertura e schermature della cupola
- [ ] Ricavare la "configurazione base del cineteatro" di progetto: forniture cinematografiche, arredi tecnici e attrezzature (baseline C3.2) — incluse forniture € 55.296,43 (art. 3, p. 7)
- [ ] Censire le attrezzature esistenti da proteggere (audio, proiettori, schermo) e verificare se il progetto ne prevede già lo smontaggio (C3.3)
- [ ] Ricavare layout di cantiere, accessi e aree di stoccaggio disponibili
- [ ] Per ogni miglioria: voce di computo non estimativo senza prezzi e collocazione nel cronoprogramma
