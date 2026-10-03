---
type: synthesis
tema: "Logistica di cantiere in centro storico, fasi, stoccaggi e protezione dell'esistente"
gara: "Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)"
date: 2026-10-03
ai-first: true
confidence: verificato
criteri: ["[[C3]]", "[[C4]]"]
documenti:
  - "[[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]]"
  - "[[SIC-01-ESEC-01_CRONOPROGRAMMA]]"
  - "[[SIC-02-ESEC-01_LAYOUT_DI_CANTIERE]]"
  - "[[SIC-03-ESEC-01_COSTI_PER_LA_SICUREZZA]]"
  - "[[G-09-ESEC-01_RELAZIONE_CAM]]"
  - "[[RS-02-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_IDRICO_ANTINCENDIO]]"
  - "[[G-08-ESEC-01_RELAZIONE_GENERALE]]"
  # --- aggiunti da graph-builder Fase D (2026-10-03): elaborati dello stesso tema collegati dagli archi ---
  - "[[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]]"   # Art. 2.22 sorveglianza e custodia dei beni della SA; Art. 2.24 materiali di demolizione della SA
  - "[[IT-01-ESEC-00_INQUADRAMENTO_SU_CTR]]"   # planimetria generale 1:1000: accessi e viabilita' (non letta)
  - "[[RIL-00-ESEC-01_PLANIMETRIA_stato_di_fatto]]"   # aree esterne e accessi esistenti (non letta)
  - "[[RIL-01-ESEC-01_PIANTE_stato_di_fatto]]"   # localizzazione delle attrezzature esistenti da proteggere (non letta)
---

# Sintesi — Logistica di cantiere

## Per Claude futuro

Pagina di sintesi creata dal synthesis hook (Fase B, sottoinsieme 2): organizzazione, viabilita', fasi e stoccaggi del cantiere sono trattati da PSC, cronoprogramma, layout e costi della sicurezza (le ultime due anche come copie interne del PSC) e richiamati dalla relazione CAM. E' la baseline del sub-criterio **C3.3** (5 pt: metodologia di smontaggio, imballaggio, stoccaggio, rimontaggio e taratura di impianto audio, proiettori e schermo esistenti) e del "piano avanzato di economia circolare ... con monitoraggio polveri/vibrazioni" di **C4.2**. Fatto chiave: **nessun elaborato tratta le attrezzature cinematografiche esistenti**. Confidence: verificato (layout: lettura visiva della copia nel PSC).

## Vincoli del sito
- Sala in un'ala del Castello aragonese, sommita' del centro storico; strutture ricostruite dopo il sisma 1980; area acclive, spazi ridotti, dislivelli — [[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]] pp. 13, 17-19.
- **Viabilita' medievale**: strade strette, irregolari, a forte pendenza, non adatte a mezzi pesanti → mezzi di piccole dimensioni, consegne in fasce orarie, approvvigionamenti frazionati, possibile trasporto manuale — SIC-00 pp. 17-18.
- Presenza di residenti e visitatori; il Castello ospita mostre ed eventi; accesso dei visitatori solo ad alcuni spazi, chiusura completa concordabile con i gestori — SIC-00 pp. 16, 24.
- Accesso dalla piazza Periz/piazzale antistante il teatro (via G. Marconi), accessibile agli automezzi — SIC-00 pp. 13, 23; [[G-08-ESEC-01_RELAZIONE_GENERALE]] p. 10 (pagina nodo).

## Organizzazione prevista
| Elemento | Previsione | Fonte |
|---|---|---|
| Area esterna | piazzetta antistante su via G. Marconi: baraccamenti, stoccaggio materiali, ricovero mezzi e attrezzature, aree di lavorazione, area rifiuti | SIC-00 p. 13 |
| Layout | accesso carrabile e pedonale, area movimentazione mezzi, ufficio DL, area stoccaggio rifiuti con cassone, area stoccaggio materiali, percorso pedonale, ponteggio fisso sul prospetto Nord-Est; aree di stoccaggio materiali/rifiuti **interne a ogni piano** (terra, primo/platea, secondo/galleria) e sul terrazzo | SIC-00 pp. 259-260 (copia di [[SIC-02-ESEC-01_LAYOUT_DI_CANTIERE]]; lettura visiva, parziale) |
| Cantiere interno | per piano; protezione di pavimentazioni, pareti e **arredi** con coperture temporanee; percorsi dedicati per i materiali; trabattelli; contenimento polveri e rumori | SIC-00 p. 13 |
| Accessi e mezzi | ingresso/uscita dal piazzale con cancelli; veicoli leggeri a 10-15 km/h con assistenza a terra; autogru'/gru su autocarro per carico-scarico | SIC-00 pp. 16, 23 |
| Ponteggio | fronte anteriore, 15 x 13 m = 195 m2 con teli; anche per la salita dei pannelli FV | SIC-00 pp. 13, 16, 257 |
| Vibrazioni/polveri | monitoraggio vibrazioni nelle lavorazioni piu' invasive, tecniche a basso impatto sulle murature; abbattimento polveri | SIC-00 pp. 17, 20 |
| Orari | lavori esterni estivi in prima mattina o dopo le 16:00 | SIC-00 p. 17 |
| Recinzione | pannelli rigidi o rete plastificata, continua, cancelli a chiave, impatto visivo contenuto, anti-intrusione | SIC-00 p. 28; costi: 40 m2 primi 2 mesi + 160 m2 per 4 mesi |
| Durata | 150 gg naturali; 109 gg lavorativi in sequenza unica (zona Z1), nessuna sovrapposizione | SIC-00 p. 2; [[SIC-01-ESEC-01_CRONOPROGRAMMA]] p. 2 |
| Forza lavoro | 773 uomini-giorno, 2 imprese | SIC-00 p. 2 |
| Oneri sicurezza | 13.005,47 EUR (ponteggio + teli 7.491,90 EUR) | SIC-00 pp. 256-258 = [[SIC-03-ESEC-01_COSTI_PER_LA_SICUREZZA]] |
| CAM cantiere | criteri 2.6.1 (prestazioni ambientali del cantiere) e 3.1.1 (personale) rinviati al PSC; 2.6.2 demolizione selettiva senza stima del 70% ("quantitativo di rifiuti molto modesto") | [[G-09-ESEC-01_RELAZIONE_CAM]] pp. 42-45 |
| Vincolo antincendio interno | naspi su tutti i piani presso uscite e vie di esodo, da non ostruire | [[RS-02-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_IDRICO_ANTINCENDIO]] p. 10 |

## Gap documentali rilevanti per i criteri
- **C3.3** — attrezzature cinematografiche esistenti (impianto audio, proiettori, schermo): **nessuna menzione** in PSC, cronoprogramma, costi della sicurezza (ricerca testuale "proiettor", "schermo", "audio" nel PSC: solo illuminazione e DPI); G-08 cita la sala proiezioni nella galleria e i sipari (pagina nodo). Nessuna fase di smontaggio/stoccaggio/rimontaggio nel cronoprogramma; nessun onere per protezioni. Le aree di stoccaggio interne per piano del layout sono gli unici spazi individuati.
- **C4.2** — piano di economia circolare per detriti da taglio solai/demolizioni con monitoraggio polveri/vibrazioni: il PSC prescrive genericamente monitoraggio vibrazioni e abbattimento polveri; la relazione CAM non stima frazioni e percentuali di recupero. Le demolizioni/tagli espliciti sono: taglio copertura per fori evacuazione fumi (4 g), tracce a mano e meccaniche (10 g), rimozione caldaia, rimozione infissi, ghiaia e poltrone esistenti (SIC-01 p. 2; SIC-00 pp. 8-11).
- Incoerenze del PSC che toccano la logistica: sottofase "Montaggio della gru a torre" (p. 36) non presente in cronoprogramma ne' costi; residui "all'interno della chiesa" (p. 23) e "allegato H" (p. 24).

## Criteri collegati
- [[C3]] — C3.3 (logistica e protezione attrezzature), C3.1 (lavori in copertura in periodo estivo).
- [[C4]] — C4.2 (economia circolare, monitoraggio polveri/vibrazioni).
