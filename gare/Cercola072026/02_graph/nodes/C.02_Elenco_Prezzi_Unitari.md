---
type: document
subtype: elenco_prezzi
gara: "Procedura aperta telematica per l'affidamento dell'appalto dei lavori di \"Intervento di efficientamento energetico dell'Istituto Comprensivo 'De Luca Picione Caravita' sito alla Via Nuova\""
date: 2026-07-20
ai-first: true
codice: "C.02"
file: "sub_12901568693736854610_C.02 - ELENCO PREZZI UNITARI.PDF"
section: "08"
version_group: "C.02"
is_latest: true
status: estratto
estrazione: integrale          # 10/10 pagine, re-ingest 2026-07-20 (prima: parziale, pag. 1-2)
extracted_md: "01_extracted/text/sub_12901568693736854610_C.02 - ELENCO PREZZI UNITARI.md"
confidence: verificato
supports_criteria:
  - { criterion: "[[C1]]", priority: media, confidence: verificato, reason: "Listino completo dei 98 prezzi unitari applicati nel computo, con descrizione tecnica integrale di ogni voce. E' la fonte per il price-gap check sulle voci di efficientamento (cappotto CAM25_E10.040.040.E(CAM) 80,46 €/mq; nuovo impianto termico NP.06 73.911,60 €/cad; corpi illuminanti LED CAM25_L03.100.030.I/J(CAM) 138,95 e 188,29 €/cad) e per verificare la sostenibilita' economica di una miglioria sui materiali. Priorita' media e non alta perche' l'evidenza quantitativa (quantita' e importi) sta in C.01: qui c'e' il prezzo e la specifica tecnica, non la misura" }
  - { criterion: "[[C2]]", priority: media, confidence: verificato, reason: "Contiene i 4 prezzi unitari degli infissi a progetto con la descrizione tecnica integrale (CAM25_E18.090.012.B/C/D — PVC bianco massa con rinforzo in acciaio, zona climatica C-D, 635,39 / 650,75 / 875,72 €/mq; NP.10 481,47 €/mq): base per quantificare l'extra-costo di un infisso migliorativo rispetto al prezzo a progetto" }
  - { criterion: "[[C3]]", priority: media, confidence: verificato, reason: "Contiene i prezzi unitari dei componenti fotovoltaici con la specifica tecnica integrale (moduli 105062a 1,01 €/W fino a 20 kW e 105062b 0,93 €/W oltre i 20 kW, silicio monocristallino, tensione max 1.000 V, connettori MC4; inverter NP.09; struttura NP.08): base per valutare economicamente un incremento di potenza o un upgrade dei componenti" }
related_documents:
  - { doc: "[[C.01_Computo_Metrico_Estimativo]]", type: referenced_by, reason: "Tutti i 98 codici di questo elenco sono usati nelle 101 righe del computo e i 98 prezzi coincidono uno a uno (0 scostamenti, verifica incrociata in estrazione integrale del 2026-07-20)" }
  - { doc: "[[C.03_Analisi_dei_Prezzi]]", type: references, reason: "Le 12 voci NP.01-NP.12 di questo elenco sono prezzi nuovi, la cui composizione (materiali, manodopera, utile) e' sviluppata in C.03" }
  - { doc: "[[C.04_Stima_Incidenza_Manodopera]]", type: referenced_by, reason: "C.04 cita C.02 per il dettaglio delle voci NP.xx e usa lo stesso prezzario di riferimento" }
  - { doc: "[[C.06_Elenco_Prezzi_Sicurezza]]", type: stesso_lotto, reason: "Elaborato omologo per gli oneri della sicurezza: stessa natura documentale (listino prezzi) e stesso prezzario Campania 2025, perimetro economico complementare (C.02 = lavori a misura, C.06 = oneri sicurezza)" }
  - { doc: "[[C.07_Quadro_Economico]]", type: stesso_lotto, reason: "Stessa sezione economica 08: i prezzi di questo elenco concorrono, tramite C.01, alla voce A.1 del quadro economico" }
  - { doc: "[[S.01_Capitolato_Speciale_Appalto]]", type: stesso_lotto, reason: "Stessa sezione economico-contrattuale (08); nessun riferimento testuale diretto individuato, discipline documentali diverse (elenco_prezzi vs capitolato)" }
  - { doc: "[[COMPUTO_OPERE_OPZIONALI]]", type: stesso_lotto, reason: "Stessa sezione economico-contrattuale (08); le opere opzionali sono computate a corpo e non usano questo elenco prezzi" }
cost_summary:
  totale_eur: NA                # un elenco prezzi non ha un totale: e' un listino, non un computo
  voci_count: 98                # confidence: verificato — Nr. 1-98, nessuna mancante, 0 non parsate
  voci_con_prezzo: 98           # confidence: verificato
  voci_senza_codice: 0          # confidence: verificato
prezzario_riferimento: "Regione Campania 2025"   # confidence: verificato — prefisso CAM25_ su 70 voci su 98
famiglie_codice:                # confidence: verificato — stessa tripartizione di C.01
  - { famiglia: "CAM25_*", voci: 70, confrontabile_con_prezzario: true }
  - { famiglia: "NP.01-NP.12", voci: 12, confrontabile_con_prezzario: false }
  - { famiglia: "sei cifre + lettera", voci: 16, confrontabile_con_prezzario: false }
---

## Per Claude futuro

Questo e' l'elenco_prezzi C.02 della gara "efficientamento energetico Istituto Comprensivo De Luca
Picione Caravita" (Cercola, NA): l'Elenco Prezzi Unitari applicato nel
[[C.01_Computo_Metrico_Estimativo]] (10 pagine, stampa PriMus, World Building Engineering S.r.l. —
Ing. Martino Rango, 31/03/2026).

**Re-ingest 2026-07-20 — estrazione ora INTEGRALE (10/10 pagine).** La versione precedente di
questa pagina si basava su 2 pagine su 10 (copertina + la sola voce NP.01) e portava
`confidence: parziale` con `voci_count: TBD`. Ora sono disponibili **tutte le 98 voci** con
**codice tariffa, descrizione tecnica integrale, unita' di misura, prezzo unitario in cifre e in
lettere**, piu' il riferimento esplicito della voce base per le 18 voci "idem c.s.". Confidence
della pagina: `verificato`.

Verifica incrociata eseguita in estrazione: **i 98 codici di questo elenco sono tutti usati in
[[C.01_Computo_Metrico_Estimativo]] e i 98 prezzi unitari coincidono uno a uno con quelli del
computo — 0 scostamenti.** Elenco prezzi e computo sono quindi mutuamente coerenti: non esiste
alcuna voce a listino non computata, ne' alcuna voce computata a prezzo diverso dal listino.

Cosa cambia per gli agenti a valle: questa e' ora la fonte autoritativa per **prezzo unitario e
specifica tecnica** di ogni lavorazione (C.01 resta la fonte per quantita' e importi). Una
proposta migliorativa su un materiale si dimensiona economicamente confrontando il prezzo di
progetto qui riportato con il prezzo del prodotto migliorativo. Non serve riaprire il PDF.

## Tripartizione dei codici — perimetro del price-gap check

Le 98 voci si dividono nelle stesse tre famiglie di [[C.01_Computo_Metrico_Estimativo]], e **solo
la prima e' confrontabile con il prezzario regionale**:

| Famiglia | Cosa e' | Voci | Confrontabile col prezzario |
|---|---|---:|---|
| `CAM25_*` | Prezzario Regione Campania 2025 (con e senza marcatore CAM) | 70 | **SI** |
| `NP.01`–`NP.12` | Nuovi prezzi — composizione in [[C.03_Analisi_dei_Prezzi]] | 12 | **NO — per definizione assenti dal prezzario** |
| sei cifre + lettera | Fuori dallo schema di codifica regionale | 16 | **NO — listino di provenienza non dichiarato: TBD** |

Confidence: `verificato`. Le stesse 3 famiglie coprono in C.01 rispettivamente il 66,44%, il 28,41%
e il 5,15% dell'importo lavori: **un price-gap check contro il Prezzario Campania 2025 puo' coprire
al massimo il 66,44% dell'importo.** Vedi la tabella completa con gli importi in
[[C.01_Computo_Metrico_Estimativo]].

I 16 codici a sei cifre: `015008c`, `015032d`, `015041c`, `025165c`, `025236c`, `025237a`,
`035060d`, `035217f`, `035404n`, `105025`, `105028`, `105046d`, `105046e`, `105062a`, `105062b`,
`205015e_`.

## Avvertenze di matching (da tramandare a chi fa lookup sui codici)

1. **Suffisso `(CAM)`** — es. `CAM25_C01.070.080.B(CAM)`: e' il marcatore PriMus di voce conforme
   ai Criteri Ambientali Minimi, **non fa parte del codice di prezzario**. Per il lookup usare la
   radice senza suffisso (`CAM25_C01.070.080.B`). Nel PDF il codice e' stampato spezzato su piu'
   righe (`CAM25_C01` / `.070.080.B (` / `CAM)`) ed e' stato ricomposto in forma compatta.
2. **`205015e_`** — l'underscore finale e' stampato cosi' nel PDF, non e' un artefatto di parsing.
3. **Voci "idem c.s."** (18 su 98) — la descrizione e' un differenziale rispetto a una voce piena
   precedente (es. Nr. 42 `CAM25_E18.090.012.D` = "idem c.s. ...Infisso scorrevole complanare a 2
   ante", rif. Nr. 40 `CAM25_E18.090.012.B`). La colonna "Rif. idem" del file estratto esplicita il
   numero e il codice della voce base: **non leggere mai una voce idem senza risalire alla base**,
   altrimenti si perde la specifica tecnica completa.
4. **Artefatti tipografici PriMus**: parole spezzate da uno spazio ("p osa", "Imp ianto"). Testo
   lasciato verbatim: tenerne conto nelle ricerche full-text.
5. Questo elaborato **non ha un totale**: e' un listino. Ogni ragionamento su importi complessivi
   va fatto su [[C.01_Computo_Metrico_Estimativo]].

## Prezzi di riferimento sui temi dei criteri (confidence: verificato)

### Infissi — [[C2]]

| Nr. | Codice | Voce | U.M. | Prezzo (€) | Famiglia |
|---:|---|---|---|---:|---|
| 40 | `CAM25_E18.090.012.B` | Infisso PVC bianco massa, rinforzo acciaio, zona climatica C-D | mq | 635,39 | CAM25 |
| 41 | `CAM25_E18.090.012.C` | idem — infisso a 2 ante a battente (rif. Nr. 40) | mq | 650,75 | CAM25 |
| 42 | `CAM25_E18.090.012.D` | idem — scorrevole complanare (ribalta/scorri) a 2 ante (rif. Nr. 40) | mq | 875,72 | CAM25 |
| — | `NP.10` | Finestra PVC 4 ante a vasistas, zona climatica C | mq | 481,47 | NP |

### Fotovoltaico — [[C3]]

| Nr. | Codice | Voce | U.M. | Prezzo (€) | Famiglia |
|---:|---|---|---|---:|---|
| 14 | `105062a` | Modulo FV silicio monocristallino, 1.000 V, connettori MC4, diodi di by-pass | W | 1,01 | sei cifre |
| 15 | `105062b` | idem — quota per potenze tra 20 e 100 kW, oltre i primi 20 kW (rif. Nr. 14) | W | 0,93 | sei cifre |
| — | `NP.09` | Inverter trifase 20 kW | cad | 3.016,62 | NP |
| — | `NP.08` | Struttura di sostegno pannelli con zavorre | cad | 141,06 | NP |
| 11 | `105028` | Protezione di interfaccia CEI 0-21, trifase B.T. | cad | 1.534,42 | sei cifre |
| 10 | `105025` | Rele' di monitoraggio trifase | cad | 983,41 | sei cifre |

I componenti fotovoltaici principali sono tutti fuori dal prezzario regionale (sei cifre o NP):
il confronto prezzi per C3 e' possibile solo sugli accessori `CAM25_*` (cavi, canaline, opere
edili), che pesano poco piu' del 5% del capitolo fotovoltaico.

### Isolamento ed efficientamento — [[C1]]

| Nr. | Codice | Voce | U.M. | Prezzo (€) | Famiglia |
|---:|---|---|---|---:|---|
| 28 | `CAM25_E10.040.040.E(CAM)` | Cappotto in EPS additivato con grafite su pareti esterne | mq | 80,46 | CAM25 |
| — | `NP.02` | Isolamento orizzontale su manto di copertura | mq | 146,44 | NP |
| 26 | `CAM25_E07.005.040.A(CAM)` | Massetto cementizio fibrorinforzato con resine acriliche | mc | 546,67 | CAM25 |
| — | `NP.06` | Nuovo impianto termico "factory made" (condensazione + pompa di calore) | cad | 73.911,60 | NP |
| — | `NP.05` | Nuova rete di distribuzione impianto termico | cad | 27.192,69 | NP |
| — | `NP.07` | Sistema di regolazione caldaia/pompa di calore | cad | 2.921,94 | NP |
| — | `NP.04` | Adeguamento impianto elettrico ai nuovi carichi | cad | 23.401,78 | NP |

Le voci di impianto termico ed elettrico — il cuore dell'efficientamento — sono **tutte nuovi
prezzi**: la loro congruita' non e' verificabile sul prezzario, va letta in
[[C.03_Analisi_dei_Prezzi]]. Il cappotto verticale e' invece una voce `CAM25_*` confrontabile.

## Estremi del listino

Prezzo minimo: **0,93 €/W** (`105062b`, modulo FV oltre i 20 kW). Prezzo massimo: **73.911,60
€/cad** (`NP.06`, nuovo impianto termico). Confidence: `verificato`.

## Riferimenti a altri elaborati

- [[C.01_Computo_Metrico_Estimativo]] — applica tutte le 98 voci qui elencate; prezzi coincidenti 1:1
- [[C.03_Analisi_dei_Prezzi]] — composizione delle 12 voci NP.01-NP.12
- [[C.04_Stima_Incidenza_Manodopera]] — incidenza manodopera sulle stesse voci
- [[C.06_Elenco_Prezzi_Sicurezza]] — elenco prezzi omologo per gli oneri della sicurezza
- `02_graph/economic_framework.md` — conferma il prezzario Campania 2025 come riferimento di gara
