# Matrice di rilevanza documenti-criteri

Data: 2026-05-04
Agente: document-indexer

Legenda: P = primario | S = secondario | - = non rilevante

---

## Riepilogo per criterio

| Criterio | Documenti primari | Documenti secondari | Totale pertinenti |
|----------|------------------|---------------------|-------------------|
| C1 — Qualita' tecnica proposte migliorative (35 pt) | 9 | 14 | 23 |
| C2 — Cantiere a basso impatto ambientale (25 pt) | 10 | 10 | 20 |
| C3 — Sostenibilita' aziendale e certificazioni (15 pt) | 1 | 2 | 3 |

---

## Matrice sintetica (soli documenti con almeno una rilevanza P o S)

| ID | Tipo | C1 | C2 | C3 |
|----|------|----|----|----|
| D001 | disciplinare | P | P | P |
| D002 | elenco elaborati | S | - | - |
| D028 | tavola architettura | - | S | - |
| D032 | tavola architettura | S | - | - |
| D035 | tavola architettura | S | - | - |
| D036 | tavola architettura | S | - | - |
| D040 | tavola | S | - | - |
| D041 | tavola | S | - | - |
| D044 | relazione elettrica | S | - | - |
| D054 | relazione | S | S | - |
| D055 | relazione | S | - | - |
| D057 | relazione | S | - | - |
| D060 | relazione | P | P | - |
| D061 | relazione | P | P | - |
| D062 | computo | P | S | - |
| D063 | elenco prezzi | P | - | - |
| D064 | elenco prezzi | P | - | - |
| D065 | capitolato | P | S | - |
| D066 | PSC | S | P | - |
| D067 | allegato | - | S | - |
| D068 | relazione | - | S | - |
| D069 | cronoprogramma | - | P | - |
| D073 | relazione | - | S | - |
| D075 | relazione | P | P | - |
| D076 | allegato | - | - | S |
| D077 | relazione | S | - | - |
| D080 | capitolato | P | S | - |
| D081 | schema contratto | - | - | S |
| D082 | relazione | S | S | - |
| D083 | relazione | - | P | - |
| D086 | relazione | S | - | - |
| D087 | relazione | - | S | - |
| D093 | tavola cantiere | - | P | - |
| D094 | tavola cantiere | - | P | - |
| D095 | tavola cantiere | - | P | - |

---

## Documenti primari per sottocriterio

### C1.1 — Piano gestione ambientale cantiere / riduzione rifiuti C&D (12 pt)
Documenti primari: D001, D060, D061, D075
Documenti secondari: D066, D062, D065

### C1.2 — Finiture esterne SRI >= 40 e/o EPD/Ecolabel (8 pt)
Documenti primari: D001, D060, D065, D080, D064
Documenti secondari: D055, D057, D032, D035, D036, D040, D041

### C1.3 — Finiture interne basse VOC e/o riciclato certificato (8 pt)
Documenti primari: D001, D060, D065, D080, D064
Documenti secondari: D055, D040, D041, D082

### C1.4 — Analisi LCA componenti / GWP (7 pt)
Documenti primari: D001, D062, D063, D064, D065
Documenti secondari: D054, D075, D077, D086, D044, D060

### C2.1 — Macchine Fase V / elettriche / ibride plug-in (8 pt)
Documenti primari: D001, D066, D093, D094, D095
Documenti secondari: D054, D069

### C2.2 — Materiali riciclati aggiuntivi oltre CAM (8 pt)
Documenti primari: D001, D060, D061
Documenti secondari: D062, D065, D080

### C2.3 — Piano mitigazione impatti cantiere (9 pt)
Documenti primari: D001, D066, D069, D075, D083, D093, D094, D095
Documenti secondari: D054, D067, D068, D073, D082, D087, D028

### C3.1 — ISO 14001 + ISO 45001 (5 pt)
Documenti primari: D001
Note: dipende da certificazioni aziendali; nessun documento progettuale e' rilevante

### C3.2 — Attestazione ESG (5 pt)
Documenti primari: D001
Note: dipende da attestazione aziendale rilasciata da organismo accreditato UNI CEI EN ISO/IEC 17029

### C3.3 — Rating di legalita' (5 pt)
Documenti primari: D001
Note: dipende da rating AGCM in corso di validita'

---

## Note metodologiche

1. La classificazione primario/secondario e' basata su nome file e contenuto testuale dei documenti estratti.
2. I documenti grafici (tavole) sono classificati in base al nome file; il contenuto testuale estratto e' minimo.
3. Per C3 l'unico documento primario e' il disciplinare perche' tutti i sottocriteri richiedono documentazione aziendale esterna alla gara.
4. I documenti classificati come "-" per tutti i criteri (es. D003–D011, D012–D027, D042–D053, ecc.) restano comunque nel registro come riferimento per verifica di compatibilita' delle proposte migliorative.
5. Il documento D001 (Disciplinare) e' primario per tutti i criteri in quanto contiene le definizioni prescrittive dei criteri stessi.
