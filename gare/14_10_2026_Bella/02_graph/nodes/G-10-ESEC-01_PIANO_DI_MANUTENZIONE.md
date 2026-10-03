---
type: document
subtype: relazione_tecnica
gara: "Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)"
date: 2026-10-03
ai-first: true
codice: "G-10-ESEC-01"
file: "G-10-ESEC-01_PIANO_DI_MANUTENZIONE.pdf"
section: "G"
version_group: "G-10"
is_latest: true
status: estratto
extracted_md: "01_extracted/text/G-10-ESEC-01_PIANO_DI_MANUTENZIONE.md"
confidence: verificato
nota_confidence: "Letti per intero indice, descrizioni delle unita' tecnologiche e requisiti rilevanti (Manuale d'Uso pp. 2-53, Manuale di Manutenzione pp. 54-60); per Programma di Manutenzione (pp. 162-226) letti l'elenco requisiti e la struttura. Contenuto in gran parte generico da catalogo software."
descrizione_ufficiale: "PIANO DI MANUTENZIONE (elenco elaborati G-00-ESEC-01)"
pagine: 227
data_documento: "aprile 2026 (rev. ESEC-01; ESEC-00 febbraio 2025)"
supports_criteria:
  - { criterion: "[[C2]]", priority: media, reason: "Unita' 01.05 Impianto fotovoltaico con 22 elementi manutenibili, tra cui accumulatore (descritto come al piombo acido, vita 6-8 anni, p. 30), inverter trifase, moduli monocristallini, e soprattutto 'elementi di copertura per tetti con funzione fotovoltaica' per centri storici 'limitando al minimo l'impatto visivo' (pp. 35-36), frangisole FV (p. 36) e manto impermeabilizzante integrato con moduli FV flessibili (p. 38): soluzioni BIPV gia' contemplate nel piano (C2.1). Nessuna unita' per antintrusione/TVCC o building automation (C2.2/C2.3): andranno aggiunte se offerte" }
  - { criterion: "[[C4]]", priority: media, reason: "C4.1: unita' 01.03 Ascensori con 21 elementi di tipo idraulico/oleodinamico (attuatore e centralina idraulica, pistone, macchinari oleodinamici, p. 11); dotazioni minime di sicurezza: ritorno al piano con apertura porte, comunicazione vocale con centro assistenza, citofono, luce di emergenza (p. 15). C4.2: il piano soddisfa il CAM 2.4.12 dichiarato in G-09 (p. 32 di G-09)" }
  - { criterion: "[[C1]]", priority: bassa, reason: "C1.3: unica unita' di finitura e' 01.01 Controsoffitti (cartongesso e pannelli) con livelli minimi generici: potere fonoisolante 25-30 dB(A), fonoassorbenza 0,60-0,80 a 500-1000 Hz (p. 57); mancano rivestimenti MDF, poltrone e serramenti, da integrare nel piano se oggetto di miglioria" }
related_documents:
  - { doc: "[[G-00-ESEC-01_ELENCO_ELABORATI]]", type: referenced_by, confidence: verificato, reason: "L'elenco elaborati G-00-ESEC-01 lo elenca per codice (p. 2) come «PIANO DI MANUTENZIONE»: fonte della descrizione ufficiale" }
  - { doc: "[[G-09-ESEC-01_RELAZIONE_CAM]]", type: referenced_by, confidence: verificato, reason: "La relazione CAM G-09 lo cita come Piano di Manutenzione dell'Opera per il criterio CAM 2.4.12 (p. 32)" }
---

# G-10-ESEC-01 — Piano di manutenzione

> **# ATTENZIONE (Fase E, 2026-10-03):** (1) accumulatori indicati come più idonei «al piombo acido» (p. 30) → il computo [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] voce 78 e l'elenco prezzi Nr. 118 prevedono batterie agli **ioni di litio**, 15 kWh (D13); (2) gli «idranti a colonna sottosuolo» (pp. 48-49) **trovano riscontro** nel computo (voce 119, idrante sottosuolo DN70 misurato «idrante esterno a colonna», con attacco motopompa voce 120) e nelle tavole VV.F.: non è un errore; manca invece la rete di 4 naspi interni di [[RS-02-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_IDRICO_ANTINCENDIO]] (D15). Vedi [[economic_framework]] §10.

## Per Claude futuro

Questo e' il piano di manutenzione `G-10-ESEC-01` della gara Cineteatro "Sala Polifunzionale Periz" — Castello di Bella (PZ). Descrizione ufficiale: "PIANO DI MANUTENZIONE". 227 pagine generate da software di catalogo: Manuale d'Uso (pp. 2-53), Manuale di Manutenzione (pp. 54-161), Programma di Manutenzione con Sottoprogramma delle Prestazioni (pp. 162-199), dei Controlli (pp. 200-215), degli Interventi (pp. 216-226); p. 227 vuota. Un solo corpo d'opera "01 Edilizia strutture civili" con **7 unita' tecnologiche**: controsoffitti, parapetti, ascensori, impianto elettrico, fotovoltaico, illuminazione LED, sicurezza e antincendio. Copre solo una parte delle opere (mancano infissi, impianto termico, pavimenti, rivestimenti MDF, poltrone, impermeabilizzazioni, naspi). Utile come elenco dei componenti e per sapere cosa una miglioria dovra' aggiungere al piano. Confidence: verificato (con le limitazioni in `nota_confidence`).

## Contenuto chiave

### Oggetto (p. 2)
"Lavori di efficientamento energetico e di adeguamento e potenziamento dei servizi del Cine-Teatro e sala polifunzionale 'Periz' ubicata nel Castello di Bella (PZ)".

### Unita' tecnologiche ed elementi manutenibili (indice p. 3 e pp. 4-48)
| UT | Elementi manutenibili | Note rilevanti | Pag. |
|---|---|---|---|
| 01.01 Controsoffitti | 01.01.01 controsoffitti in cartongesso; 01.01.02 pannelli | isolamento termo-acustico, protezione al fuoco | 4-7 |
| 01.02 Parapetti | accessori per balaustre; balaustre a correnti | — | 8-10 |
| 01.03 Ascensori e montacarichi | 21 elementi: armadi, **attuatore idraulico**, cabina, **centralina idraulica**, contrappeso, livellazione, **elevatore idraulico**, fotocellule, funi, guide, extracorsa, limitatore di velocita', **macchinari oleodinamici**, paracadute, **pistone a trazione diretta**, pulsantiera, quadro di manovra, scheda elettronica, serrature, arresto morbido, vani corsa | ascensore **oleodinamico**: dotazioni di sicurezza "ritorno in emergenza con apertura porte", "limitatore di carico", "sistema di comunicazione per colloquio vocale fra passeggeri e centro di assistenza", "citofono", luce e pulsante di allarme; altezza libera cabina >= 2 m | 11-24 |
| 01.04 Impianto elettrico | interruttori, prese, quadri BT, cablaggi | — | 25-28 |
| 01.05 Impianto fotovoltaico | 22 elementi: **accumulatore**, aste di captazione, cassetta di terminazione, cella solare, conduttori, connettore/sezionatore, dispositivi di generatore/interfaccia/generale, **elementi di copertura per tetti con funzione fotovoltaica**, **frangisole fotovoltaico**, **inverter trifase**, **manto impermeabilizzante per coperture con moduli FV**, **modulo in silicio monocristallino**, moduli massimizzatori, quadro, regolatore di carica, rele' interfaccia, scaricatori, **sensore di irraggiamento**, dispersione, equipotenzializzazione | accumulatori "al piombo acido ... durata media 6-8 anni", locale aerato per miscela idrogeno/ossigeno (p. 30); tegole/elementi FV "per edifici situati nei centri storici o in aree con vincoli ... limitando al minimo l'impatto visivo" (pp. 35-36); manto in poliolefina con moduli FV flessibili, leggero, adatto a coperture piane con pendenza ricavata da pannelli isolanti (p. 38) | 29-44 |
| 01.06 Illuminazione a LED | apparecchio a incasso, diffusori, modulo LED | — | 45-47 |
| 01.07 Impianto di sicurezza e antincendio | tubazioni in acciaio zincato, **idranti a colonna sottosuolo**, **rivelatori di fumo**, serrande di aspirazione | descrizione generica di rivelazione e allarme | 48-53 |
<!-- confidence: verificato; pagine di inizio UT verificate sui marcatori di pagina, pagine di fine approssimate -->

### Requisiti prestazionali con valori (Manuale di Manutenzione)
- 01.01.R01 Isolamento acustico controsoffitti: **potere fonoisolante 25-30 dB(A)**; **fonoassorbenza 0,60-0,80** (500-1000 Hz) <!-- p. 57 -->.
- 01.01.R02 Isolamento termico controsoffitti: resistenza termica 0,50-1,55 m2K/W <!-- p. 57 -->.
- 01.01.R06 Resistenza al fuoco controsoffitti: REI 60 per altezza antincendio 12-32 m <!-- p. 58 -->.
- Requisiti ambientali ricorrenti (CAM): utilizzo di materiali riciclati, certificazione ecologica, separabilita' dei componenti, gestione ecocompatibile dei rifiuti (es. 01.01.R08-R13, 01.03.R04-R07, 01.05.R09-R10) — formulati in modo generico <!-- pp. 162-199 -->.
- FV: requisiti "efficienza di conversione" (celle e moduli monocristallini), "controllo della potenza" (inverter) <!-- Sottoprogramma Prestazioni, pp. 162-199 -->.

### Opere di progetto NON coperte dal piano (verificate per assenza nel testo)
Serramenti/infissi esterni, impianto termico (caldaia, radiatori, valvole), pavimento in resina, rivestimenti MDF, poltrone, impermeabilizzazione terrazzi/cupola e pellicole/tenda, rete naspi, impianto IRAI, evacuazione fumi, building automation, antintrusione/TVCC. Ricerca testuale: "Poltron" 0, "MDF" 0, "cupola" 0, "naspi" 0, "antintrusione/TVCC/building" 0.

### Lettura per i criteri
- Ogni miglioria (nuovi componenti C1, C2.2, C2.3, C3, C4.1) comporta l'aggiornamento del piano di manutenzione: argomento spendibile nell'offerta (schede di manutenzione dei componenti offerti) <!-- confidence: inferito -->.
- La presenza nel piano di "elementi di copertura con funzione fotovoltaica" e "manto impermeabilizzante con moduli FV" mostra che soluzioni integrate erano contemplate dal progettista, mentre le relazioni RS-00/RS-01 prevedono moduli su staffe inclinate <!-- confidence: inferito -->.

## Incoerenze
- Accumulatori descritti come al piombo acido (p. 30) mentre il computo [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] prevede batterie agli ioni di litio (lettura in sola consultazione) → `02_graph/synthesis/fotovoltaico_e_accumulo.md`.
- Antincendio: "idranti a colonna sottosuolo" e "tubazioni in acciaio zincato" (p. 48) vs rete di 4 naspi DN25 in PE/acciaio filettato in [[RS-02-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_IDRICO_ANTINCENDIO]] → `02_graph/synthesis/antincendio.md`.
- Ascensore idraulico (coerente con PSC p. 10 e computo) vs fase "ascensore elettrico" del cronoprogramma → `02_graph/synthesis/ascensore.md`.

## Riferimenti a altri elaborati
- Nessun codice di elaborato citato nel testo (solo il proprio cartiglio G-10-ESEC-00 febbraio 2025 / G-10-ESEC-01 aprile 2026).
- Citato (senza codice) da [[G-09-ESEC-01_RELAZIONE_CAM]] p. 32 ("Piano di Manutenzione dell'Opera allegato al progetto", criterio CAM 2.4.12).
- Struttura delle schede ripresa nel Fascicolo dell'opera di [[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]] pp. 184-255 (stessi codici 01.01 … 01.07).

## Sintesi tematiche collegate
`02_graph/synthesis/fotovoltaico_e_accumulo.md` · `02_graph/synthesis/ascensore.md` · `02_graph/synthesis/antincendio.md` · `02_graph/synthesis/acustica_sala.md`
