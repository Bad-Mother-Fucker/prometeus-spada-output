---
type: document
subtype: relazione_tecnica
gara: "Procedura aperta telematica per l'affidamento dell'appalto dei lavori di \"Intervento di efficientamento energetico dell'Istituto Comprensivo 'De Luca Picione Caravita' sito alla Via Nuova\""
date: 2026-07-19
ai-first: true
codice: "R.02.1"
file: "sub_15018144789641292957_R.02.1 - RELAZIONE DNSH.PDF"
section: "02"
version_group: "R.02.1"
is_latest: true
status: estratto
extracted_md: "01_extracted/text/sub_15018144789641292957_R.02.1 - RELAZIONE DNSH.md"
confidence: parziale
supports_criteria: []
# Nessun criterio agganciato: documento di compliance PNRR/DNSH, non un elaborato migliorativo.
# Non inferire rilevanza su C1-C6: definisce vincoli di scope (vedi corpo pagina), non supporta
# direttamente la valutazione discrezionale di alcun criterio. Orfano intenzionale — non un errore.
related_documents:
  - { doc: "[[S.04_Piano_Sicurezza_Coordinamento]]", type: referenced_by, reason: "S.04 segnala una contraddizione sulla presenza di caldaie a gas rispetto a questo documento (vedi anche R.01, R.04)" }
---

## Per Claude futuro

Questa è la Relazione DNSH (R.02.1) — verifica del principio "Do No Significant Harm" (Regolamento UE
852/2020) obbligatoria per l'accesso ai finanziamenti PNRR/RRF. Non supporta direttamente nessuno dei
criteri di gara C1-C6: è un documento di compliance, non un elaborato tecnico migliorativo. È rilevante
come **vincolo di scope**: le proposte su C1/C2/C3 non devono violare i vincoli DNSH qui elencati.
Contiene una **contraddizione potenzialmente rilevante** sulla dichiarata esclusione delle caldaie a gas
(vedi sotto). Confidence: parziale (10/27 pagine lette — contenuto tecnico e checklist completi, restano
non lette presumibili pagine di allegati/dichiarazioni).

## ANOMALIA — CIG diverso da PROJECT_CONFIG

Frontespizio: **CIG: B9C7EAF75F** vs PROJECT_CONFIG.json **BC3ECFAA55**. Stesso CUP. Identica anomalia in
`[[R.02_Relazione_CAM]]`.

## ATTENZIONE — Contraddizione: esclusione caldaie a gas

La checklist Art.5 (Item 0) dichiara: **"È stata verificata l'esclusione dall'intervento delle caldaie
a gas? → SI"**.

Tre elaborati indipendenti descrivono invece la presenza di caldaie nell'impianto di progetto:
- `[[R.01_Relazione_Generale_e_Tecnica_Illustrativa]]` §7.4: "impianto ibrido factory-made... 2 caldaie
  a condensazione da ~33,80 kW cad."
- `[[R.04_Relazione_Energetica_Ex_L10]]`: "caldaia a metano (194,80 kW utile, rendimento 97,90%/106,70%)"
- `[[S.04_Piano_Sicurezza_Coordinamento]]`: fase di lavorazione "Installazione di caldaia per impianto
  termico (autonomo)"

Possibile spiegazione (non verificabile dal testo): il documento stesso prevede una deroga per caldaie a
gas che rientrano in un più ampio programma di efficientamento con riduzione significativa delle
emissioni, costo ≤20% del programma, e investimenti in rinnovabili — condizioni che il progetto
(impianto ibrido PdC+caldaia+FV) potrebbe soddisfare, ma la relazione non lo esplicita in corrispondenza
dell'Item 0. **Non risolvibile senza chiarimento del progettista.** Rilevante per l'ammissibilità PNRR
del progetto, non solo come nota tecnica.

## Contenuto chiave

- Regime applicabile: **Regime 1** (mitigazione cambiamenti climatici) — soglia richiesta: risparmio
  EPgl,tot ≥30% rispetto all'ante-operam. Verifica quantitativa della soglia NON effettuabile con i
  dati incrociati nel grafo (metriche EP non omogenee tra i documenti, vedi nota in R.04 estratto).
- Rispetto dei CAM Edilizia (DM 23/06/2022) assolve automaticamente i vincoli DNSH 4-10 (risparmio
  idrico, rifiuti, disassemblaggio, amianto, REACH, legno).
- Checklist: 14 item "SI", 8 item "NON APPLICABILE" (investimento <10 mln €, o assolti da CAM), 1 item
  "NO" (relazione finale rifiuti 70% — fisiologicamente non disponibile in fase di gara, documento
  ex-post).

## Riferimenti a altri elaborati (per Fase D — archi)
- APE ex ante/ex post → R.03
- Simulazione energetica ex post, DM 26/06/2015 → R.01, R.04
- CAM Edilizia → R.02
- Conferma fase "installazione caldaia" → S.04
