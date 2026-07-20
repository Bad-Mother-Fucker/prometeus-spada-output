---
type: economic_framework
gara: "Procedura aperta telematica per l'affidamento dell'appalto dei lavori di \"Intervento di efficientamento energetico dell'Istituto Comprensivo 'De Luca Picione Caravita' sito alla Via Nuova\""
date: 2026-07-19
ai-first: true
importo_lavori_eur: 915809.83        # confidence: verificato — voce A.1 [[C.07_Quadro_Economico]], coincide col totale [[C.01_Computo_Metrico_Estimativo]]
importo_base_asta_eur: 954883.79     # confidence: verificato — A.1+A.2+A.3, coincide con PROJECT_CONFIG.gara.importo_base_asta
costi_manodopera_eur: 180457.45      # confidence: verificato — voce A.2, coincide col totale [[C.04_Stima_Incidenza_Manodopera]]
oneri_sicurezza_eur: 39073.96        # confidence: verificato — voce A.3 (etichettata "A.2" nel PDF per refuso), coincide con [[C.05_Computo_Metrico_Sicurezza]] e [[C.06_Elenco_Prezzi_Sicurezza]]
oneri_sicurezza_pct: 4.27             # confidence: verificato — calcolato come 39.073,96 / 915.809,83 * 100 (base: importo lavori puro A.1)
oneri_sicurezza_pct_su_base_asta: 4.09  # confidence: verificato — calcolo alternativo su 954.883,79 (base asta complessiva incl. manodopera+sicurezza), riportato per trasparenza metodologica
somme_a_disposizione_eur: 412266.21  # confidence: verificato — sezione B del quadro economico (totale generale 1.367.150,00 - base asta 954.883,79)
totale_quadro_economico_eur: 1367150.00  # confidence: verificato
fonte_qe: "[[C.07_Quadro_Economico]]"
fonte_sicurezza: ["[[C.05_Computo_Metrico_Sicurezza]]", "[[C.06_Elenco_Prezzi_Sicurezza]]"]
confidence: verificato
---

## Per Claude futuro

Questa e' la cornice economica della gara "efficientamento energetico Istituto Comprensivo De Luca
Picione Caravita" (Cercola, NA) (CIG BC3ECFAA55). I dati
qui riportati sono tutti `verificato` — letti direttamente dai documenti economici estratti
([[C.01_Computo_Metrico_Estimativo]], [[C.04_Stima_Incidenza_Manodopera]],
[[C.05_Computo_Metrico_Sicurezza]], [[C.06_Elenco_Prezzi_Sicurezza]], [[C.07_Quadro_Economico]]).
I quattro documenti economici sopra citati **coincidono esattamente** sui rispettivi importi
incrociati (importo lavori, costo manodopera, oneri sicurezza): nessuna contraddizione rilevata
sulla cornice economica generale. **Esiste invece una contraddizione critica e irrisolta** sulla
ripartizione delle opere opzionali tra i criteri tabellari C4 e C5 (vedi sezione dedicata sotto):
va verificata manualmente prima di procedere con l'analisi di quei due criteri.

## Quadro Economico generale (fonte: [[C.07_Quadro_Economico]])

| Voce | Descrizione | Importo (€) | Confidence |
|---|---|---|---|
| A.1 | Lavori a base d'appalto (soggetti a ribasso) | 915.809,83 | verificato |
| A.2 | Costi manodopera (non soggetti a ribasso) | 180.457,45 | verificato |
| A.3 | Oneri sicurezza (non soggetti a ribasso) | 39.073,96 | verificato |
| **Totale base d'appalto** | | **954.883,79** | verificato |
| B.1 | Prestazioni tecniche (progettazione, DL, CSE, RUP, energy manager, APE) | 187.238,14 | verificato |
| B.2 | Imprevisti sui lavori | 57.166,84 | verificato |
| B.3 | Previdenza CNPAIA/EPAP | 6.878,40 | verificato |
| B.4 | Forniture | 0,00 | verificato |
| B.5 | Oneri discarica | 25.000,00 | verificato |
| B.6 | Altro (spese gara, ANAC, GSE) | 1.150,00 | verificato |
| B.7 | IVA | 134.832,83 | verificato |
| **Totale somme a disposizione** | | **412.266,21** | verificato (calcolato per differenza, quadra col totale generale) |
| **TOTALE GENERALE** | | **1.367.150,00** | verificato |

Oneri sicurezza / importo lavori: **4,27%** (39.073,96 / 915.809,83) oppure **4,09%** se calcolato
sulla base asta complessiva (39.073,96 / 954.883,79). Nessuna incongruenza tra il valore degli
oneri sicurezza nel quadro economico e nei computi di dettaglio: [[C.05_Computo_Metrico_Sicurezza]]
e [[C.06_Elenco_Prezzi_Sicurezza]] riportano lo stesso identico importo (€ 39.073,96) su base voce
per voce (12 voci di apprestamento cantiere).

## Prezzario di riferimento

**Regione Campania 2025** (prefisso codici tariffa `CAM25_`), confermato in
[[C.02_Elenco_Prezzi_Unitari]], [[C.03_Analisi_dei_Prezzi]], [[C.04_Stima_Incidenza_Manodopera]],
[[C.06_Elenco_Prezzi_Sicurezza]]. Da riportare in `PROJECT_CONFIG.json → gara.prezzario_riferimento`:
`{ regione: "Campania", anno: "2025" }` (non ancora compilato da questa invocazione — segnalato
per l'orchestratore).

## CONTRADDIZIONE — Opere opzionali C4/C5 (valore economico dichiarato vs computo)

`03_criteria/criteria_matrix.md` e `PROJECT_CONFIG.json` dichiarano:
- **[[C4]]** (B1 — barriere architettoniche, voci 01, 02, 04) → **€ 67.000,00**
- **[[C5]]** (B2 — sistemazione e decoro esterno, voci 03, 05, 06, 07, 08) → **€ 46.000,00**

[[COMPUTO_OPERE_OPZIONALI]] (fonte contabile, verificata voce per voce) da' invece:
- Voci 01+02+04 (Ascensore 46.000 + Rimozione scala 8.000 + Abbattimento barriere 19.000) =
  **€ 73.000,00** (scostamento **+6.000 €** rispetto al dichiarato)
- Voci 03+05+06+07+08 (Pulizia verde 6.000 + Pavimentazione 12.000 + Illuminazione 12.000 +
  Segnaletica 3.000 + Ripristini 7.000) = **€ 40.000,00** (scostamento **-6.000 €** rispetto al
  dichiarato)

Il totale complessivo (€ 113.000,00) coincide in entrambi i casi — la contraddizione riguarda
esclusivamente la ripartizione tra i due criteri tabellari, non il totale. Poiche' C4 e C5 sono
criteri on/off in cui "la proposta deve corrispondere alle specifiche dell'atto contabile delle
opzioni" (art. 18.2 disciplinare, vedi `modification_limits` in `criterion_C4.md`/`criterion_C5.md`),
questa discrepanza e' **CONTRADDIZIONE: verifica manuale richiesta** prima dell'analisi dei
criteri C4/C5. Dettaglio completo in [[COMPUTO_OPERE_OPZIONALI]].

## CONTRADDIZIONE — non economica, segnalata da Fase B (fuori scope di questa pagina)

Per completezza di riferimento incrociato: e' stata rilevata anche una contraddizione tra R.01
(Relazione Generale, EPgl,nren post-operam = 19,9614 kWh/m²anno) e R.03 (APE, EPgl,nren post-operam
= 25,8212 kWh/m²anno). Non e' una contraddizione economica e non e' processata da questa pagina:
va gestita dalla Fase B (documenti testuali) e dalla Fase E (contraddizioni) sui nodi
[[R.01_Relazione_Generale_e_Tecnica_Illustrativa]] e [[R.03_Attestato_di_Prestazione_Energetica]].

## Come usare questa pagina

Gli agenti a valle (`strategy-auditor`, `criterion-agent`, `evidence-auditor`) leggono questa
pagina PRIMA di qualsiasi valutazione di sostenibilita' economica di una proposta migliorativa.
Per C4/C5 in particolare: NON usare i valori di `criteria_matrix.md` senza prima segnalare la
contraddizione sopra riportata al professionista.
