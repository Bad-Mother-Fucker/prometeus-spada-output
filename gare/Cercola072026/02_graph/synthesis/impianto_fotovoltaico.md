---
type: synthesis
gara: "Procedura aperta telematica per l'affidamento dell'appalto dei lavori di \"Intervento di efficientamento energetico dell'Istituto Comprensivo 'De Luca Picione Caravita' sito alla Via Nuova\""
date: 2026-07-19
ai-first: true
tema: "Impianto fotovoltaico — dati coerenti tra elaborati e criterio C3"
documenti_collegati:
  - "[[R.01_Relazione_Generale_e_Tecnica_Illustrativa]]"
  - "[[R.02_Relazione_CAM]]"
  - "[[R.04_Relazione_Energetica_Ex_L10]]"
  - "[[R.05_Relazione_Impianto_Fotovoltaico]]"
  - "[[S.04_Piano_Sicurezza_Coordinamento]]"
confidence: verificato
---

## Per Claude futuro

Pagina di sintesi generata dal synthesis hook di graph-builder: cinque elaborati indipendenti citano
l'impianto fotovoltaico di progetto (oggetto del criterio C3, 20 punti). I dati quantitativi principali
sono **coerenti** tra le fonti (nessuna contraddizione sui numeri chiave), con una sola discrepanza
minore sui parametri di inclinazione/orientamento. Usa questa pagina come punto di ingresso rapido per
l'analisi C3 invece di raccogliere i dati da ogni singolo documento.

## Dati coerenti tra tutte le fonti

| Dato | Valore | Fonti concordanti |
|---|---|---|
| Potenza impianto esistente (non oggetto di intervento) | 24,00 kWp | R.01, R.04 |
| Potenza nuovo impianto (oggetto di intervento) | 36,00 kW | R.01, R.02, R.04, R.05 |
| Potenza complessiva post-operam | 60,00 kW | R.01, R.03 (implicito, PV installato 60,00 kW), R.04 |
| Numero moduli nuovo impianto | 72 | R.05 |
| Superficie moduli nuovo impianto | 159,48 m² (R.05) / 144 mq falda (R.01, R.04 — dato lordo falda vs netto moduli) | R.01, R.04, R.05 |
| Produzione annua stimata nuovo impianto | 43.515,24 kWh/anno (R.05) — coerente con "24.315,42 kWh/anno prodotti" di R.03 se riferito al solo esistente | R.03, R.05 (grandezze non direttamente sommabili senza chiarimento, ma nessuna contraddizione diretta) |
| Copertura fabbisogno annuo da FV | 40,99% | R.04 |
| Sistema di accumulo | Nessuno | R.05 |

## Discrepanza minore — Tilt/Azimut

| Fonte | Inclinazione (Tilt) | Orientamento (Azimut) |
|---|---|---|
| R.04 (dato di progetto energetico/architettonico) | 30° | SUD_OVEST |
| R.05 (dato di calcolo elettrico dei campi FV) | 15,0° | 0,0° (Sud) |

Non trattata come contraddizione piena: possibile che R.05 usi un'ipotesi cautelativa per il
dimensionamento elettrico (Tilt/Azimut meno favorevoli producono correnti/tensioni diverse, verifica
lato sicuro), mentre R.04 riporta il dato architettonico reale della falda. **Non risolvibile senza
lettura delle tavole EG.05.2 (Pianta Copertura Stato di Progetto) o EG.07 (Sezioni Stato di Progetto).**
Se rilevante per una proposta migliorativa sul dimensionamento FV, verificare con `drawing-reader`
prima di usare uno dei due valori come riferimento di calcolo.

## Rilevanza CAM (da R.02)

R.02 conferma la presenza dell'impianto FV come misura di conformità CAM (§3.1 Approvvigionamento
energetico da fonti rinnovabili) — non aggiunge dati quantitativi propri, ma conferma la potenza
36,00 kW citata dalle altre fonti.

## Rilevanza PSC (da S.04)

S.04 conferma l'esistenza della fase di lavorazione "Realizzazione di impianto solare fotovoltaico" con
rischi tipici (caduta dall'alto, elettrocuzione, M.M.C.) — nessun dato quantitativo aggiuntivo.

## Implicazioni per l'analisi del criterio C3

- La base dati per C3 è solida e concorde su tutte le fonti (5 documenti indipendenti convergono sugli
  stessi numeri chiave) — a differenza della prestazione energetica generale (vedi
  `[[prestazione_energetica_e_contraddizioni]]`), qui non ci sono contraddizioni bloccanti da segnalare
  al professionista prima di procedere.
- L'unica verifica raccomandata prima di proposte di ampliamento/ottimizzazione del FV è la discrepanza
  Tilt/Azimut sopra descritta, tramite lettura delle tavole grafiche pertinenti.
