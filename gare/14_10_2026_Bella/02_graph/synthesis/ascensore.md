---
type: synthesis
tema: "Ascensore per l'abbattimento delle barriere architettoniche (vano circolare)"
gara: "Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)"
date: 2026-10-03
ai-first: true
confidence: verificato
criteri: ["[[C4]]"]
documenti:
  - "[[SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO]]"
  - "[[SIC-01-ESEC-01_CRONOPROGRAMMA]]"
  - "[[G-10-ESEC-01_PIANO_DI_MANUTENZIONE]]"
  - "[[G-09-ESEC-01_RELAZIONE_CAM]]"
  - "[[G-08-ESEC-01_RELAZIONE_GENERALE]]"
  - "[[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]]"
  - "[[PA-03-ESEC-01_PARTICOLARI_COSTRUTTIVI_scala_e_ascensore]]"
  # --- aggiunti da graph-builder Fase D (2026-10-03): elaborati dello stesso tema collegati dagli archi ---
  - "[[G-02-ESEC-01_ELENCO_PREZZI]]"   # D6.01.008.03 testo completo: oleodinamico EN 81-2, 8 persone, 6 fermate, corsa 18 m, Braille, telefono in cabina
  - "[[G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO]]"   # Art. 7.4 ascensori: UNI EN 81-20/50/70/40, Braille, segnalazione sonora di arrivo al piano
  - "[[G-07-ESEC-01_RELAZIONE_FOTOGRAFICA]]"   # fig. 19 vano circolare esistente privo di impianto
  - "[[PA-04-ESEC-01_PARTICOLARI_COSTRUTTIVI_collegamenti_verticali]]"   # cartiglio con titolo «corpo scala e ascensore», legenda vano ascensore (non letta)
---

# Sintesi — Ascensore

## Per Claude futuro

Pagina di sintesi creata dal synthesis hook (Fase B, sottoinsieme 2): l'ascensore nel vano circolare esistente e' descritto da almeno 6 elaborati con **dati non coerenti** (tipo di azionamento, capienza, corsa, fermate). E' la baseline del sub-criterio **C4.1** (5 pt: telecontrollo, sintesi vocale, pulsanti Braille avanzati, isolamento acustico in dB della cabina). Nessun documento prevede sintesi vocale, telecontrollo o un valore di isolamento acustico della cabina. I dati di G-08 e G-04-ESEC-02 provengono dalle loro pagine nodo (altre fasi). Confidence: verificato.

## Dati di progetto a confronto

| Parametro | PSC SIC-00 (pp. 10-11) | G-08 (pp. 16-17, da pagina nodo) | Computo G-04-ESEC-02 (voci 96-98, da pagina nodo) | Altri |
|---|---|---|---|---|
| Azionamento | **idraulico** automatico, macchinario in basso | idraulico | **idraulico (oleoelettrico) EN 81-2** (verificato sul testo p. 17) | G-10: oleodinamico (attuatore/centralina idraulica, pistone, p. 11-15); SIC-01 p. 2 e SIC-00 p. 48: "impianto ascensore **elettrico**" |
| Vano | proprio, gia' realizzato, **circolare** | gia' realizzato, predisposto | — | — |
| Capienza | **6 persone** | 6 persone | **8 persone** | — |
| Fermate | **3** | 3 | **6** | — |
| Corsa utile | **9 m** | 9 m | **18 m** | — |
| Velocita' | 0,63 m/s (rallentamento 0,15) | 0,63 m/s | sovrapprezzo per velocita' fino a 0,80 m/s | — |
| Cabina | >= 1,45 m2; rivestimento in materiale plastico; pavimento linoleum/gomma | >= 1,45 m2 | 1,45 m2 | G-10: altezza libera >= 2 m |
| Porte | automatiche a scorrimento laterale, fotocellula/costole mobili, aperte >= 8 s, chiusura > 4 s | idem | — | — |
| Comandi | pulsante piu' alto <= 1,20 m; **numerazione in rilievo e scritte Braille** | idem | bottoniere Braille | G-09 p. 14: percorsi tattili e cartellonistica braille |
| Comunicazione | **citofono a 1,20 m**; impianto telefonico in fossa e sul tetto cabina; allaccio linea telefonica | idem | — | G-10 p. 15: "sistema di comunicazione per colloquio vocale fra passeggeri e centro di assistenza", citofono, luce di emergenza, ritorno al piano con apertura porte |
| Sintesi vocale / telecontrollo / dB cabina | **assenti** | assenti | assenti | assenti in G-09, G-10 (ricerca testuale) |
| Norme | L. 13/1989 | L. 13/1989, DM 236/1989 | Direttiva 95/16/CE, EN 81-2 | — |
| Cronoprogramma | — | — | — | 5 g a settembre 2026 (SIC-01 p. 2) |

## Incoerenze
1. **Idraulico vs elettrico**: tutte le descrizioni tecniche e il computo dicono idraulico; il cronoprogramma e le schede di fase del PSC usano la voce di software "impianto ascensore elettrico".
2. **6 persone / 3 fermate / 9 m** (PSC, G-08) vs **8 persone / 6 fermate / 18 m** (computo, secondo la pagina nodo di G-04-ESEC-02). I livelli dell'edificio sono tre (+0,15, +3,05/3,07, +7,19; layout SIC-00 p. 260): i dati del PSC sono coerenti con la geometria (inferito).
3. "Funi di trazione" nell'elenco componenti di un ascensore idraulico (SIC-00 p. 11; G-08 p. 17).
4. Il pie' di pagina del cronoprogramma ("Realizzazione di un ascensore esterno in edificio esistente") e' un residuo di altro progetto.
<!-- confidence: verificato per le citazioni; inferito per il punto 2 (coerenza geometrica) -->

## Rilevanza per i criteri
- [[C4]] — C4.1: baseline = ascensore idraulico con Braille e citofono; mancano telecontrollo/teleassistenza remota, sintesi vocale, isolamento acustico cabina in dB. Vincolo: vano circolare esistente e tipologia idraulica (modificarli e' fuori scope secondo la pagina criterio). Tavola di dettaglio: [[PA-03-ESEC-01_PARTICOLARI_COSTRUTTIVI_scala_e_ascensore]] (non letta).
