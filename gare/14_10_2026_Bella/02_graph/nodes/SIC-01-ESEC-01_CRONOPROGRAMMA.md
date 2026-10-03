---
type: document
subtype: cronoprogramma
gara: "Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)"
date: 2026-10-03
ai-first: true
codice: "SIC-01-ESEC-01"
file: "SIC-01-ESEC-01_CRONOPROGRAMMA.pdf"
section: "SIC"
version_group: "SIC-01"
is_latest: true
status: estratto
extracted_md: "01_extracted/text/SIC-01-ESEC-01_CRONOPROGRAMMA.md"
confidence: verificato
descrizione_ufficiale: "CRONOPROGRAMMA (elenco elaborati G-00-ESEC-01)"
pagine: 2
data_documento: "aprile 2026 (rev. ESEC-01; ESEC-00 febbraio 2025)"
supports_criteria:
  - { criterion: "[[C3]]", priority: alta, reason: "Cronoprogramma di progetto da integrare con le migliorie (obbligatorio, art. 16 p. 26): sequenza unica in zona Z1 senza sovrapposizioni, 109 gg lavorativi; C3.3 non ha alcuna fase di smontaggio/protezione/rimontaggio di audio, proiettori e schermo esistenti; C3.1 copertura 17 g senza fasi per isolamento o schermatura cupola" }
  - { criterion: "[[C1]]", priority: media, reason: "Baseline temporale per le migliorie C1: posa sedute per teatro 1 g, nessuna fase per gli infissi esterni (solo serramenti e porte interne 10 g), nessuna fase per rivestimenti acustici MDF; le migliorie C1 vanno inserite nel cronoprogramma dell'offerta" }
  - { criterion: "[[C2]]", priority: media, reason: "Baseline temporale C2: impianto FV 2 g in coda ai lavori (ottobre 2026), nessuna fase per accumulo, building automation, antintrusione/TVCC; le migliorie C2 vanno integrate nel cronoprogramma" }
  - { criterion: "[[C4]]", priority: media, reason: "C4.1: fase 'Realizzazione di impianto ascensore elettrico' 5 g (il progetto prevede ascensore idraulico); C4.2: nessuna fase dedicata a demolizioni/gestione detriti oltre al taglio copertura per fori evacuazione fumi 4 g" }
related_documents:
  - { doc: "[[G-00-ESEC-01_ELENCO_ELABORATI]]", type: referenced_by, confidence: verificato, reason: "L'elenco elaborati G-00-ESEC-01 lo elenca per codice (p. 2) come «CRONOPROGRAMMA»: fonte della descrizione ufficiale" }
  - { doc: "[[G-06-ESEC-01_CAPITOLATO_SPECIALE_D_APPALTO]]", type: referenced_by, confidence: verificato, reason: "Il capitolato superato G-06-ESEC-01 lo include tra i documenti contrattuali e lo richiama per il programma esecutivo (Artt. 2.2, 2.5)" }
  - { doc: "[[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]]", type: referenced_by, confidence: verificato, reason: "Il capitolato G-06-ESEC-02 lo include tra i documenti contrattuali e lo richiama per il programma esecutivo (Artt. 2.2, 2.5)" }
  - { doc: "[[G-11-ESEC-01_SCHEMA_DI_CONTRATTO]]", type: referenced_by, confidence: verificato, reason: "Lo schema di contratto G-11 lo richiama come cronoprogramma di progetto, documento contrattuale (artt. 1, 9)" }
  - { doc: "[[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]]", type: referenced_by, confidence: verificato, reason: "Il PSC SIC-00 ne contiene una copia identica alle pp. 85-87 (copertina con codice SIC-01-ESEC-01)" }
  - { doc: "[[SIC-02-ESEC-01_LAYOUT_DI_CANTIERE]]", type: stesso_lotto, confidence: verificato, reason: "Sezione SIC (progetto sicurezza), cronoprogramma / layout: fasi di allestimento (12 g) e smobilizzo (8 g) del cantiere organizzato nel layout" }
  - { doc: "[[SIC-03-ESEC-01_COSTI_PER_LA_SICUREZZA]]", type: stesso_lotto, confidence: verificato, reason: "Sezione SIC, cronoprogramma / costi sicurezza: apprestamenti stimati per 6 mesi (monoblocco, recinzione) contro 109 gg lavorativi / 150 gg naturali" }
durata:
  lavorativi_somma_fasi: 109        # confidence: verificato, somma dei 9 gruppi (12+17+40+23+1+2+4+2+8)
  naturali_dichiarati_psc: 150      # confidence: verificato, SIC-00 p. 2; disciplinare art. 3.1
  inizio_gantt: "settimana del 25/05/2026 (prima barra circa 28/05)"   # confidence: parziale, lettura visiva
  fine_gantt: "circa fine ottobre 2026"                                # confidence: parziale, lettura visiva
---

# SIC-01-ESEC-01 — Cronoprogramma

> **# ATTENZIONE (Fase E, 2026-10-03):** la fase «Realizzazione di impianto ascensore elettrico» (5 g, p. 2) contrasta con l'ascensore **idraulico** del disciplinare (sub 4.1, p. 29), del computo [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] voce 96 e del PSC p. 10: residuo di template (cfr. piè di pagina «ascensore esterno in edificio esistente»), da allineare nel cronoprogramma integrato dell'offerta (inferito). Portata e fermate dell'impianto sono a loro volta discordanti tra computo e relazioni (D14, quesito SA Q3). Vedi [[economic_framework]] §10.

## Per Claude futuro

Questo e' il cronoprogramma `SIC-01-ESEC-01` della gara Cineteatro "Sala Polifunzionale Periz" — Castello di Bella (PZ). Descrizione ufficiale: "CRONOPROGRAMMA". Gantt di 1 pagina (p. 2) con 9 gruppi di lavorazioni, durate in giorni lavorativi, zona unica Z1, tutte le fasi in sequenza stretta (nessuna sovrapposizione). Somma 109 gg lavorativi, distribuiti da fine maggio a fine ottobre 2026 (circa 150 gg naturali, coerente con i 150 gg del disciplinare). E' il documento di partenza per il **cronoprogramma integrato con le migliorie** richiesto dall'art. 16 del disciplinare per tutti i criteri. Copia identica nel PSC [[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]] pp. 85-87. Confidence: verificato (testo + verifica visiva del Gantt; date di inizio/fine solo da lettura visiva).

## Contenuto chiave

### Fasi e durate (p. 2)
| Gruppo | Durata | Sottofasi (durata) |
|---|---|---|
| Allestimento del cantiere | 12 g | recinzione e accessi (2 g); depositi/stoccaggi/impianti fissi (2 g); tubazioni in PVC per messa in sicurezza linee elettriche aeree (3 g); impianto elettrico di cantiere (2 g), messa a terra (2 g), protezione scariche atmosferiche (1 g) |
| Copertura | 17 g | taglio copertura per fori evacuazione fumi (4 g); impermeabilizzazione coperture (3 g); scossaline e canali di gronda (5 g); pluviali e canne di ventilazione (5 g) |
| Interni | 40 g | controsoffitto per compartimentazione antincendio (5 g); tracce a mano (5 g); tracce meccaniche (5 g); controsoffitto compartimentazione (5 g); pareti divisorie per compartimentazione antincendio (5 g); tinteggiatura (5 g); montaggio serramenti interni (5 g); porte interne (5 g) |
| Impianti tecnici edificio | 23 g | impianto ascensore "elettrico" (5 g); impianto elettrico (5 g); messa a terra (3 g); protezione scariche atmosferiche (2 g); illuminazione ad alta efficienza (3 g); rimozione caldaia (2 g); centrale termica (1 g); rete di distribuzione e terminali (2 g) |
| Allestimento sala e palco | 1 g | posa in opera di sedute per teatro (1 g) |
| Impianti energetici | 2 g | impianto solare fotovoltaico (2 g) |
| Pitturazioni interne | 4 g | tinteggiatura (4 g) |
| Finiture esterne | 2 g | verniciatura opere in ferro (1 g); posa conduttura elettrica (1 g) |
| Smobilizzo del cantiere | 8 g | smontaggio ponteggio (3 g); pulizia (2 g); smobilizzo (3 g) |
| **Totale** | **109 g lavorativi** | <!-- confidence: verificato, somma --> |

- Legenda: "Z1 = ZONA UNICA". Le bande gialle verticali del Gantt corrispondono ai fine settimana (giorni non lavorativi) <!-- confidence: parziale, lettura visiva -->.
- Calendario: intestazione da 25/05/2026 a 09/11/2026; prima barra circa 28/05/2026, ultima (smobilizzo) circa fine ottobre 2026 <!-- confidence: parziale, lettura visiva -->. Le date sono indicative: l'aggiudicazione avverra' dopo il 14/10/2026.

### Lavorazioni di progetto NON presenti come fase (rilevante per l'integrazione delle migliorie)
- Sostituzione infissi esterni (prevista in SIC-00 p. 9 e G-09 p. 27): nessuna fase (ci sono solo serramenti e porte interne).
- Oscuramento/tenda della cupola, impermeabilizzazione cupola (previste in G-08 e nel computo): non distinte.
- Rivestimenti MDF e pavimento in resina (RS-03 p. 7): nessuna fase.
- Rete naspi antincendio (RS-02), impianto IRAI, impianto di evacuazione fumi forzato (oltre al taglio dei fori), building automation e accumulo: nessuna fase.
- Smontaggio/protezione/rimontaggio delle attrezzature cinematografiche esistenti (oggetto di C3.3): nessuna fase.
<!-- confidence: verificato per assenza nel testo estratto di p. 2 -->

### Osservazioni per l'offerta
- Sequenza strettamente lineare in zona unica: margine per proporre lavorazioni in parallelo (esterno/interno, piani diversi) gia' implicito nel PSC (cantiere esterno + cantiere interno per piano, SIC-00 p. 13) <!-- confidence: inferito -->.
- Le lavorazioni in copertura (giugno-luglio) cadono nel periodo estivo per cui il PSC limita gli orari esterni (prima mattina o dopo le 16:00, SIC-00 p. 17) <!-- confidence: inferito -->.

## Incoerenze e residui di template
- Fase "Realizzazione di impianto ascensore elettrico": il progetto prevede ascensore idraulico (SIC-00 pp. 10-11; computo G-04-ESEC-02 p. 17) → `02_graph/synthesis/ascensore.md`.
- Pie' di pagina "Realizzazione di un ascensore esterno in edificio esistente - Pag. 2": residuo di un altro progetto.
- Il PSC aggiunge la sottofase "Montaggio della gru a torre" non presente qui.

## Riferimenti a altri elaborati
- Nessun codice di elaborato citato nel testo (solo il proprio codice nel cartiglio: SIC-01-ESEC-00 febbraio 2025, SIC-01-ESEC-01 aprile 2026).
- Copia interna in `SIC-00-ESEC-01` pp. 85-87 → [[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]]

## Sintesi tematiche collegate
`02_graph/synthesis/logistica_cantiere.md` · `02_graph/synthesis/ascensore.md` · `02_graph/synthesis/copertura_terrazzi_e_cupola.md`
