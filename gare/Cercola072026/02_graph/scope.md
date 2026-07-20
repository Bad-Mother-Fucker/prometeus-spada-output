---
type: scope
gara: "Procedura aperta telematica per l'affidamento dell'appalto dei lavori di \"Intervento di efficientamento energetico dell'Istituto Comprensivo 'De Luca Picione Caravita' sito alla Via Nuova\""
date: 2026-07-19
ai-first: true
fonte_lavorazioni: "[[C.01_Computo_Metrico_Estimativo]]"
fonte_vincoli: ["[[C1]]", "[[C2]]", "[[C3]]", "[[C4]]", "[[C5]]", "[[C6]]", "disciplinare artt. 3.5, 3.7, 16, 18.1, 18.2"]
confidence: parziale
---

## Per Claude futuro

Questa e' la pagina di perimetro (scope) della gara "efficientamento energetico Istituto
Comprensivo De Luca Picione Caravita" (Cercola, NA) (CIG BC3ECFAA55). Definisce COSA e' incluso nel progetto a base d'appalto (tabella lavorazioni, da
[[C.01_Computo_Metrico_Estimativo]]) e QUALI sono i limiti di modifica imposti dal disciplinare per
ciascun criterio (sezione dedicata, dai campi `modification_limits`/`fuori_scope_risks` delle
pagine criterio). Confidence: `verificato` — sia il riepilogo per categorie sia il dettaglio
voce-per-voce del computo sono estratti e riconciliati (101 voci, totale ricostruito
€ 915.809,83 = totale stampato; re-ingest del 2026-07-20). Prima di proporre una miglioria che
tocchi una lavorazione specifica, verificare in questa pagina se rientra nel perimetro validato;
il dettaglio della singola voce (codice tariffa, quantita', prezzo unitario, importo) e' ora
disponibile direttamente in [[C.01_Computo_Metrico_Estimativo]], senza riaprire il PDF.

## Tabella lavorazioni (fonte: [[C.01_Computo_Metrico_Estimativo]], riepilogo per categorie)

| Codice | Categoria | Importo (€) | Incidenza % | Confidence |
|---|---|---|---|---|
| OG1-001 | Isolamento Termico Superfici Opache Verticali | 109.542,62 | 11,961% | verificato |
| OG1-002 | Isolamento Termico Superfici Opache Orizzontali | 165.770,44 | 18,101% | verificato |
| OG1-003 | Sostituzione Chiusure Trasparenti (infissi) | 158.811,91 | 17,341% | verificato |
| OG1-008 | Finiture di Opere Generali | 159.846,43 | 17,454% | verificato |
| OG1-010 | Rifiuti | 7.278,00 | 0,795% | verificato |
| **OG1 totale** | **Edifici Civili e Industriali** | **601.249,40** | **65,652%** | verificato |
| OG9-004 | Impianto Elettrico | 23.401,78 | 2,555% | verificato |
| OG9-005 | Impianto Termico (quota OG9) | 2.413,25 | 0,264% | verificato |
| OG9-006 | Impianto Fotovoltaico | 57.139,96 | 6,239% | verificato |
| **OG9 totale** | **Impianti Produzione Energia Elettrica** | **82.954,99** | **9,058%** | verificato |
| OG11-005 | Impianto Termico (quota OG11) | 119.521,32 | 13,051% | verificato |
| OG11-007 | Impianto Idro-Sanitario | 57.639,89 | 6,294% | verificato |
| OG11-009 | Illuminazione | 54.444,23 | 5,945% | verificato |
| **OG11 totale** | **Impianti Tecnologici** | **231.605,44** | **25,290%** | verificato |
| | **TOTALE LAVORI A MISURA (base d'appalto)** | **915.809,83** | 100,000% | verificato |
| — | Dettaglio voce-per-voce (101 voci, pag. 1-26/26 del computo) | 915.809,83 | 100,000% | verificato — estratto integralmente, totale riconciliato col computo stampato |

**Opere opzionali (fuori dal computo a base d'appalto, fonte [[COMPUTO_OPERE_OPZIONALI]]):**

| Codice | Descrizione | Importo (€) | Criterio collegato | Confidence |
|---|---|---|---|---|
| O.OP.01 | Ascensore (impianto elevatore MRL) | 46.000,00 | [[C4]] (dichiarato: voci 01,02,04 = 67.000 — CONTRADDIZIONE, vedi `02_graph/economic_framework.md`) | verificato |
| O.OP.02 | Rimozione scala esterna di emergenza | 8.000,00 | [[C4]] | verificato |
| O.OP.03 | Pulizia generale aree a verde | 6.000,00 | [[C5]] (dichiarato: voci 03,05,06,07,08 = 46.000 — CONTRADDIZIONE) | verificato |
| O.OP.04 | Abbattimento barriere architettoniche (rampa, corrimano) | 19.000,00 | [[C4]] | verificato |
| O.OP.05 | Pavimentazione esterna | 12.000,00 | [[C5]] | verificato |
| O.OP.06 | Illuminazione esterna | 12.000,00 | [[C5]] | verificato |
| O.OP.07 | Segnaletica (orizzontale e verticale) | 3.000,00 | [[C5]] | verificato |
| O.OP.08 | Ripristini (graffiti, tinteggiatura, opere metalliche) | 7.000,00 | [[C5]] | verificato |
| | **TOTALE OPERE OPZIONALI** | **113.000,00** | — | verificato |

## Limiti di modifica imposti dal disciplinare (per criterio)

### C1 (A1) — Efficientamento energetico, materiali, caratteristiche tecniche
- Le migliorie implicano la redazione dell'Allegato tecnico (Relazione energetica ex L.10 + APE
  post operam), riferito congiuntamente a C1-C2-C3 (art. 16 lett. m)
- Vietata qualunque quantificazione economica nella relazione tecnica, pena esclusione (art. 16)
- Rispetto delle caratteristiche minime di progetto, principio di equivalenza (art. 16)
- Max 6 facciate A4 per il sub-criterio (art. 16 lett. j)
- Rischio fuori scope: alterazione sostanziale delle opere gia' validate (variante non ammessa,
  art. 3.5) o inserimento anche indiretto di riferimenti economici

### C2 (A2) — Fornitura e posa infissi
- Stessi vincoli espliciti di C1 (Allegato tecnico condiviso, divieto riferimenti economici,
  principio di equivalenza, max 6 facciate A4)
- Rischio fuori scope: infissi che non rispettano le caratteristiche minime di progetto violano il
  principio di equivalenza

### C3 (A3) — Impianto fotovoltaico
- Stessi vincoli espliciti di C1/C2 (Allegato tecnico condiviso, divieto riferimenti economici,
  max 6 facciate A4)
- Rischio fuori scope: proposte che aumentano l'ingombro dei pannelli a parita' di potenza vanno
  contro l'elemento premiante esplicito (minor spazio occupato)

### C4 (B1) — Barriere architettoniche (voci 01, 02, 04 opere opzionali)
- La proposta deve corrispondere ESATTAMENTE alle specifiche dell'atto contabile (voci 01, 02, 04):
  criterio on/off, nessuna discrezionalita' (art. 18.2)
- Vietata qualunque quantificazione economica nella relazione tecnica (art. 16)
- **ATTENZIONE**: valore economico dichiarato nel disciplinare (€ 67.000) discorda dalla somma
  delle voci nel computo (€ 73.000) — vedi CONTRADDIZIONE in `02_graph/economic_framework.md`. Verificare
  manualmente prima di validare proposte su questo criterio
- Rischio fuori scope: proposte che eccedono o non corrispondono esattamente alle voci 01,02,04

### C5 (B2) — Sistemazione e decoro esterno (voci 03, 05, 06, 07, 08 opere opzionali)
- La proposta deve corrispondere ESATTAMENTE alle specifiche dell'atto contabile (voci
  03,05,06,07,08): criterio on/off (art. 18.2)
- Vietata qualunque quantificazione economica nella relazione tecnica (art. 16)
- **ATTENZIONE**: valore economico dichiarato (€ 46.000) discorda dalla somma delle voci nel
  computo (€ 40.000) — vedi CONTRADDIZIONE in `02_graph/economic_framework.md`
- Rischio fuori scope: proposte che eccedono o non corrispondono esattamente alle voci indicate

### C6 (B2, probabile refuso B3) — Certificazione UNI/PdR 125:2022
- Vietata qualunque quantificazione economica nella relazione tecnica (art. 16)
- Rischio fuori scope: ambiguita' del disciplinare su comprova/tempistica del possesso della
  certificazione (rischio di interpretazione difforme dalla Commissione)

## Regola d'uso per gli agenti

1. Prima di valutare la fattibilita' di una proposta migliorativa su una lavorazione specifica,
   verificare in questa pagina se la categoria e' coperta dal computo a base d'appalto o dalle
   opere opzionali.
2. Per C4/C5, NON usare acriticamente i valori €67.000/€46.000 di `criteria_matrix.md` senza
   segnalare al professionista la contraddizione documentata in `02_graph/economic_framework.md`.
3. Per il dettaglio della singola lavorazione (codice tariffa, quantita', prezzo unitario,
   importo) leggere direttamente [[C.01_Computo_Metrico_Estimativo]] e
   [[C.02_Elenco_Prezzi_Unitari]]: sono estratti integralmente, non serve riaprire il PDF.
4. Attenzione al perimetro di confronto col prezzario: solo le 73 righe con codice `CAM25_*`
   (66,44% dell'importo) sono confrontabili. I 12 nuovi prezzi `NP.*` (28,41%) e i 16 codici a
   sei cifre (5,15%) non hanno riscontro nel prezzario regionale: per gli `NP.*` la composizione
   e' in [[C.03_Analisi_dei_Prezzi]].
