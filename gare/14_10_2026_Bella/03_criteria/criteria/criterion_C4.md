---
type: criterion
id: C4
gara: "Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)"
date: 2026-10-03
ai-first: true
confidence: verificato
titolo: "Accessibilità Universale e Criteri CAM"
criterio_disciplinare: "4. Accessibilità Universale e Criteri CAM"
punteggio_max: 10
peso_pct_tecnico: 11.1
natura: discrezionale
fonte: "Disciplinare art. 18.1, Tabella criteri D/T, p. 29"
subcriteri:
  - { id: "C4.1", titolo: "Integrazioni tecnologiche e comfort dell'ascensore", punti: 5, natura: "D" }
  - { id: "C4.2", titolo: "Criteri CAM avanzati, certificazioni di filiera ed economia circolare", punti: 5, natura: "D" }
modification_limits:
  - "C4.2: le percentuali di materiale riciclato certificato (EPD) in cartongesso, silicati antincendio e isolanti devono eccedere i minimi CAM (art. 18.1, sub 4.2, p. 29); CAM di riferimento D.M. 24.11.2025 (Premesse, p. 3)"
  - "C4.1: gli accessori e dispositivi opzionali si riferiscono all'impianto (ascensore) idraulico nel vano circolare previsto (art. 18.1, sub 4.1, p. 29)"
  - "L'offerta tecnica deve rispettare, pena l'esclusione, le caratteristiche minime stabilite nei documenti di gara, nel rispetto del principio di equivalenza (art. 16, p. 25)"
  - "Le migliorie, sommate alle prestazioni di progetto, non devono far emergere dubbi sulla sostenibilità economica complessiva dell'offerta: parametro della verifica di anomalia (art. 23, p. 33)"
fuori_scope_risks:
  - "C4.1: modifiche al vano circolare o alla tipologia di ascensore di progetto (inferito)"
  - "C4.2: il piano di economia circolare deve riferirsi ai tagli solai e alle demolizioni già previsti in progetto, non introdurne di nuovi (inferito)"
  - "C4.2: impegni su certificazioni (EPD, FSC/PEFC, Classe A+) non verificabili o non reperibili in esecuzione (inferito)"
# --- Aggiunto/aggiornato da graph-builder 2026-10-03 ---
# supported_by = archi inversi di supports_criteria delle pagine 02_graph/nodes/ (Fase F).
# Ordine: priority alta > media > bassa; a parita', confidence verificato > parziale > inferito, poi codice.
# confidence = dell'arco: esplicita sull'arco se presente, altrimenti quella della pagina nodo;
#   inferito se la reason dichiara il collegamento inferito/dedotto. Tavole: contenuto grafico non letto.
# sottocriteri = citati nella reason dell'arco; "trasversale" = cornice economica / verifica di anomalia (art. 23).
# is_latest: false = versione superata, solo confronto tra versioni, mai baseline.
# Evidenza debole per elemento premiante (Fase F; dettaglio in 02_graph/log.md):
#   C4.1 - isolamento acustico della cabina (dB) assente da tutti gli elaborati; dati ascensore in contraddizione (idraulico vs 'elettrico'; 6 pers./3 fermate/9 m vs 8/6/18 m); PA-03 (alta) non letta.
#   C4.2 - 'minimi CAM' di progetto riferiti al DM 23/06/2022 (G-06-ESEC-02, G-09) e al DM 11/10/2017 (G-02), non al DM 24.11.2025 del disciplinare; G-09 non dichiara percentuali di riciclato ne' EPD.
supported_by:
  - { doc: "[[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]]", priority: alta, confidence: verificato, sottocriteri: ["C4.1", "C4.2"] }
  - { doc: "[[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]]", priority: alta, confidence: verificato, sottocriteri: ["C4.1", "C4.2"] }
  - { doc: "[[G-08-ESEC-01_RELAZIONE_GENERALE]]", priority: alta, confidence: verificato, sottocriteri: ["C4.1"] }
  - { doc: "[[G-09-ESEC-01_RELAZIONE_CAM]]", priority: alta, confidence: verificato, sottocriteri: ["C4.1", "C4.2"] }
  - { doc: "[[PA-03-ESEC-01_PARTICOLARI_COSTRUTTIVI_scala_e_ascensore]]", priority: alta, confidence: inferito, sottocriteri: ["C4.1", "C4.2"] }
  - { doc: "[[G-02-ESEC-01_ELENCO_PREZZI]]", priority: media, confidence: verificato, sottocriteri: ["C4.1", "C4.2"] }
  - { doc: "[[G-10-ESEC-01_PIANO_DI_MANUTENZIONE]]", priority: media, confidence: verificato, sottocriteri: ["C4.1", "C4.2"] }
  - { doc: "[[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]]", priority: media, confidence: verificato, sottocriteri: ["C4.1", "C4.2"] }
  - { doc: "[[SIC-01-ESEC-01_CRONOPROGRAMMA]]", priority: media, confidence: verificato, sottocriteri: ["C4.1", "C4.2"] }
  - { doc: "[[G-07-ESEC-01_RELAZIONE_FOTOGRAFICA]]", priority: media, confidence: parziale, sottocriteri: ["C4.1", "C4.2"] }
  - { doc: "[[PA-04-ESEC-01_PARTICOLARI_COSTRUTTIVI_collegamenti_verticali]]", priority: media, confidence: inferito, sottocriteri: ["C4.1"] }
  - { doc: "[[PI-02-ESEC-01_PROGETTO_CON_INDICAZIONE_CLASSI_RESISTENZA_AL_FUOCO]]", priority: media, confidence: inferito, sottocriteri: ["C4.2"] }
  - { doc: "[[G-00-ESEC-01_ELENCO_ELABORATI]]", priority: bassa, confidence: verificato, sottocriteri: ["C4.1", "C4.2"] }
  - { doc: "[[G-01-ESEC-01_QUADRO_ECONOMICO]]", priority: bassa, confidence: verificato, sottocriteri: ["trasversale"], is_latest: false }
  - { doc: "[[G-01-ESEC-02_QUADRO_ECONOMICO]]", priority: bassa, confidence: verificato, sottocriteri: ["trasversale"] }
  - { doc: "[[G-04-ESEC-01_COMPUTO_METRICO_ESTIMATIVO]]", priority: bassa, confidence: verificato, sottocriteri: ["C4.1", "C4.2"], is_latest: false }
  - { doc: "[[G-05-ESEC-01_QUADRO_INCIDENZA_MANODOPERA]]", priority: bassa, confidence: verificato, sottocriteri: ["trasversale"] }
  - { doc: "[[G-06-ESEC-01_CAPITOLATO_SPECIALE_D_APPALTO]]", priority: bassa, confidence: verificato, sottocriteri: ["C4.1", "C4.2"], is_latest: false }
  - { doc: "[[SIC-03-ESEC-01_COSTI_PER_LA_SICUREZZA]]", priority: bassa, confidence: verificato, sottocriteri: ["C4.2"] }
  - { doc: "[[PA-00-ESEC-01_PIANTE_stato_di_progetto]]", priority: bassa, confidence: inferito, sottocriteri: ["C4.1", "C4.2"] }
  - { doc: "[[PA-02-ESEC-01_SEZIONI_stato_di_progetto]]", priority: bassa, confidence: inferito, sottocriteri: ["C4.1"] }
  - { doc: "[[SIC-02-ESEC-01_LAYOUT_DI_CANTIERE]]", priority: bassa, confidence: inferito, sottocriteri: ["C4.2"] }
graph_updated: 2026-10-03
---

# Criterio C4 — Accessibilità Universale e Criteri CAM

## Per Claude futuro

Pagina criterio C4 della gara Cineteatro “Periz” — Castello di Bella (CIG BCF01395AF). Criterio 4 della tabella art. 18.1 (p. 29): 10 punti su 90 (11,1%), interamente **discrezionale**, due sub-criteri da 5 punti: dotazioni e comfort dell'ascensore (idraulico, vano circolare) e prestazioni ambientali oltre i minimi CAM. La soglia di confronto per C4.2 sono i CAM D.M. 24.11.2025 richiamati dal progetto (Elaborato B3 / relazione CAM). Fonte unica: disciplinare. Confidence: verificato.

## Punteggio massimo

10 punti (art. 18.1, p. 29)

## Subcriteri

| ID sub | Descrizione | Punti | Natura |
|---|---|---|---|
| C4.1 | Integrazioni tecnologiche e comfort dell'ascensore | 5 | D |
| C4.2 | Criteri CAM avanzati, certificazioni di filiera ed economia circolare | 5 | D |

### Testo del disciplinare — "Oggetto della valutazione / perimetro tecnico delle migliorie" (p. 29)

- **C4.1** — "(D) Fornitura di accessori e dispositivi opzionali per l'impianto idraulico nel vano circolare (sistemi di telecontrollo, sintesi vocale, pulsanti Braille avanzati) e livello di isolamento acustico (dB) della cabina."
- **C4.2** — "(D) Percentuale di materiale riciclato certificata (EPD) in lastre di cartongesso, silicati antincendio e isolanti eccedente i minimi CAM; utilizzo di legno tracciabile (FSC/PEFC); impiego di materiali a bassissima emissione VOC (Classe A+); piano avanzato di economia circolare per la gestione, selezione e riciclo dei detriti da taglio solai e demolizioni con monitoraggio polveri/vibrazioni."

## Metodo di attribuzione

Discrezionale (art. 18.2, p. 30): coefficiente 0-1 per commissario sulla scala a sei livelli, media aritmetica per sub-criterio, I^ riparametrazione per sub-criterio (art. 18.4, p. 31).

## Elementi premianti

- C4.1 — sistemi di telecontrollo dell'ascensore
- C4.1 — sintesi vocale
- C4.1 — pulsanti Braille avanzati
- C4.1 — livello di isolamento acustico (dB) della cabina
- C4.2 — percentuale di riciclato certificata EPD **eccedente i minimi CAM** in lastre di cartongesso, silicati antincendio e isolanti
- C4.2 — legno tracciabile FSC/PEFC
- C4.2 — materiali a bassissima emissione VOC (Classe A+)
- C4.2 — piano avanzato di economia circolare per gestione, selezione e riciclo dei detriti da taglio solai e demolizioni, con monitoraggio polveri/vibrazioni

## Vincoli espliciti

- C4.2: soglia = minimi CAM (p. 29); CAM D.M. 24.11.2025 per i lavori (Premesse, p. 3).
- Rispetto, pena l'esclusione, delle caratteristiche minime dei documenti di gara (art. 16, p. 25).
- Computo metrico non estimativo per ogni miglioria, senza prezzi (art. 16, p. 26).
- Nessun elemento economico nell'offerta tecnica: **esclusione** (art. 16, p. 26; art. 22, p. 33).
- Migliorie parametro della verifica di anomalia (art. 23, p. 33).

## Vincoli impliciti

- Le percentuali e certificazioni offerte dovranno essere comprovate in esecuzione (inferito).
- Il monitoraggio polveri/vibrazioni si svolge in un edificio storico abitato da attrezzature esistenti (art. 11, p. 16; sub 3.3) (inferito).
- Durata lavori fissa 150 giorni (art. 3.1, p. 8).

## Limiti dimensionali o formali

- Sezione C4 entro le 30 facciate complessive (A4, numerate, font ≥ 11 pt) (art. 16, p. 25).
- Schede tecniche (es. EPD, certificazioni prodotto) ammesse e non conteggiate (art. 16, p. 25).

## Documenti richiesti

- Relazione tecnica — sezione C4, con una parte per ciascun sub-criterio C4.1, C4.2 (art. 16, p. 25)
- Computo metrico non estimativo — voci delle migliorie C4 (art. 16, pp. 25-26)
- Cronoprogramma delle lavorazioni (documento unico) che evidenzi l'inserimento delle migliorie C4 (art. 16, p. 26)
- Facoltativi: elaborati grafici e schede tecniche esplicative (art. 16, p. 25)

## Rischi fuori scope

- Modifiche al vano o alla tipologia di ascensore (inferito).
- Nuove demolizioni non previste dal progetto (inferito).
- Certificazioni non verificabili (inferito).

## Note e ambiguità

- "impianto idraulico nel vano circolare" (C4.1) è letto come ascensore idraulico nel vano circolare, coerentemente con il titolo del sub-criterio.
- Le Premesse citano "Elaborato B3 – Relazione sui Criteri Minimi Ambientali"; nel manifest la relazione CAM è `G-09-ESEC-01`: corrispondenza da verificare.

## Checklist operativa

- [ ] Ricavare dagli elaborati tipologia, dotazioni e prestazioni dell'ascensore di progetto (baseline C4.1)
- [ ] Ricavare dalla relazione CAM i minimi di riciclato per cartongesso, silicati antincendio, isolanti e i requisiti VOC/legno già previsti (baseline C4.2)
- [ ] Ricavare quantità e tipologia di tagli solai e demolizioni previsti (perimetro del piano di economia circolare)
- [ ] Per ogni miglioria: indicatore misurabile rispetto al minimo (percentuale, classe, dB)
- [ ] Per ogni miglioria: voce di computo non estimativo senza prezzi e collocazione nel cronoprogramma
