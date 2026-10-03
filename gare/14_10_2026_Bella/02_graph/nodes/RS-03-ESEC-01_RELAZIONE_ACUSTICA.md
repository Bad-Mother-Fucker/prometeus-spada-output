---
type: document
subtype: relazione_tecnica
gara: "Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)"
date: 2026-10-03
ai-first: true
codice: "RS-03-ESEC-01"
file: "RS-03-ESEC-01_RELAZIONE_ACUSTICA.pdf"
section: "RS"
version_group: "RS-03"
is_latest: true
status: estratto
extracted_md: "01_extracted/text/RS-03-ESEC-01_RELAZIONE_ACUSTICA.md"
confidence: verificato
descrizione_ufficiale: "RELAZIONE ACUSTICA (elenco elaborati G-00-ESEC-01)"
pagine: 18
data_documento: "aprile 2026 (rev. ESEC-01; ESEC-00 febbraio 2025)"
supports_criteria:
  - { criterion: "[[C1]]", priority: alta, reason: "Baseline numerica di C1.3: T60 di progetto (Sabine) 0,79 s a 500 Hz su V = 986 m3, superfici e coefficienti di assorbimento per materiale (MDF a listelli 99,35 m2 alfa500 = 0,20; sipario cotone 64,56 m2; 134 posti), verifica in opera al collaudo (pp. 15-18); unico parametro calcolato e' il T60 (nessun STI/C50/C80). C1.2: poltroncine in cotone, 134 posti, considerate nel calcolo (pp. 8, 16). C1.1: finestre 7 m2 (p. 15)" }
  - { criterion: "[[C2]]", priority: bassa, reason: "Dichiara 'impianto fotovoltaico da 6 kWh' e 'batterie di accumulo da 20 kWh' (pp. 8-9): uno dei valori in conflitto per la capacita' di accumulo di progetto rilevante per C2.3" }
related_documents:
  - { doc: "[[G-00-ESEC-01_ELENCO_ELABORATI]]", type: referenced_by, confidence: verificato, reason: "L'elenco elaborati G-00-ESEC-01 lo elenca per codice (p. 2) come «RELAZIONE ACUSTICA»: fonte della descrizione ufficiale" }
  - { doc: "[[G-09-ESEC-01_RELAZIONE_CAM]]", type: referenced_by, confidence: verificato, reason: "La relazione CAM G-09 vi rinvia per il criterio 2.4.11 prestazioni e comfort acustici (p. 31)" }
  - { doc: "[[PA-00-ESEC-01_PIANTE_stato_di_progetto]]", type: relazione_di, confidence: inferito, reason: "Piante della sala: superfici di platea e galleria, 134 posti, rivestimenti MDF usati nel calcolo del T60 (pp. 15-16) — abbinamento per disciplina, contenuto grafico non letto" }
  - { doc: "[[PA-02-ESEC-01_SEZIONI_stato_di_progetto]]", type: relazione_di, confidence: inferito, reason: "Sezioni della sala da cui deriva il volume di 986 m3 (platea 862 + galleria 124) del calcolo T60 (p. 15) — abbinamento per disciplina, contenuto grafico non letto" }
parametri_acustici:
  volume_m3: 986              # confidence: verificato, p. 15 (platea 862 + galleria 124)
  T60_500Hz_s: 0.79           # confidence: verificato, p. 17 (0,7877853)
  metodo: "Sabine, foglio di calcolo, valori medi"   # confidence: verificato, pp. 13, 17
  posti: 134                  # confidence: verificato, p. 16
  STI: TBD                    # confidence: TBD, non calcolato nella relazione
---

# RS-03-ESEC-01 — Relazione acustica

> **# ATTENZIONE (Fase E, 2026-10-03): valori in contrasto con fonti prevalenti** (testo descrittivo comune con G-08 e G-09) — «batterie di accumulo da 20 kWh» (p. 9) → prevale 15 kWh del computo [[G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO]] voce 78 (D13, quesito SA Q1); «impianto fotovoltaico da 6 kWh» (p. 8) → 6 kWp e «pompe di calore» (p. 9) → caldaia a condensazione (D17); «impianti sprinkler» (p. 8) → non previsti (D15). Il calcolo del T60 con 134 posti (p. 16) è coerente col computo voce 102, ma le tavole VV.F. approvate riportano 128 posti (D18, quesito SA Q4): il T60 a sala piena andrebbe ricalcolato se il numero cambiasse (inferito). Vedi [[economic_framework]] §10.

## Per Claude futuro

Questa e' la relazione acustica `RS-03-ESEC-01` della gara Cineteatro "Sala Polifunzionale Periz" — Castello di Bella (PZ). Descrizione ufficiale: "RELAZIONE ACUSTICA". 18 pagine: contesto storico (pp. 5-7, identico a G-09 e SIC-00), descrizione del progetto (pp. 7-9), teoria (pp. 9-14) e valutazione previsionale del tempo di riverbero T60 con formula di Sabine (pp. 14-18). Risultato: **T60 = 0,79 s a 500 Hz** su un volume di 986 m3, "praticamente coincidente" con l'ottimo per sala polifunzionale; verifica rinviata al collaudo con misure in opera. E' la baseline numerica del sub-criterio C1.3 (8 punti). Confidence: verificato (simboli greci delle formule resi come caratteri sostitutivi nell'estrazione).

## Contenuto chiave

### Riferimenti normativi e obiettivo (pp. 3-4)
- Valutazione previsionale delle prestazioni e del comfort acustico secondo **D.M. 23 giugno 2022 (CAM edilizia)**, da verificare al collaudo con misure in opera di un Tecnico Competente in Acustica <!-- p. 3 -->.
- Norme: L. 447/1995, D.P.C.M. 5/12/1997, UNI TR 11175, UNI EN ISO 717-1/-2, UNI EN 12354-1/-2/-3/-6 <!-- p. 4 -->.

### Scelte progettuali dichiarate (pp. 7-9)
- **Pavimento** autolivellante in resina epossidica con quarzo, 2-3 mm, esteso al palco <!-- p. 7 -->.
- **Rivestimenti murari: pannelli di MDF** sulle pareti, scelta estetica e acustica <!-- p. 7 -->; nella tabella superfici il materiale e' "LISTELLI IN LEGNO" <!-- p. 16 -->.
- **Sedute**: poltroncine in tessuto azzurro petrolio, contribuiscono all'assorbimento <!-- p. 8 -->.
- Scala a chiocciola palco-camerini nascosta da separe' curvo in listellare di legno <!-- p. 8 -->.

### Calcolo del T60 (pp. 14-18)
- Volumi: platea 862 m3 + galleria 124 m3 = **986 m3**; porte 2,94 m2, finestre 7 m2 <!-- confidence: verificato, p. 15 -->.

| Superficie | Area (m2) | Materiale | alfa 500 Hz |
|---|---|---|---|
| Palco | 51,1 | legno verniciato | 0,12 |
| Pareti c.a. rivestite in MDF | 99,35 | listelli in legno | 0,20 |
| Soffitto | 79,02 | cemento | 0,03 |
| Controsoffitto | 14,88 | cartongesso | 0,05 |
| Pavimento | 175,42 | resina | 0,02 |
| Pareti c.a. tinteggiate | 15,93 | c.a. tinteggiato | 0,04 |
| Porte | 2,94 | — | 0,01 |
| Sipario palco e dietroscena | 64,56 | 100% cotone | 0,10 |
| Poltroncine | — | 100% cotone | 0,09 |
| Pubblico seduto | 134 posti | — | 1,10 (per persona) |
| Finestre | 7 | — | 0,15 |
<!-- confidence: verificato, pp. 16 (Figure 11-12) -->

- Assorbimento equivalente totale: 91,46 / 146,0 / 206,2 / 249,1 / 292,1 / 264,5 m2 a 125 / 250 / 500 / 1000 / 2000 / 4000 Hz <!-- p. 17 -->. Contributo dominante: il pubblico (152,9 m2 su 206,2 a 500 Hz).
- **T60 di progetto**: 1,77 s (125 Hz) · 1,11 s (250 Hz) · **0,79 s (500 Hz)** · 0,65 s (1 kHz) · 0,56 s (2 kHz) · 0,61 s (4 kHz) <!-- confidence: verificato, p. 17 (Figura 14) -->.
- Conclusione: T60 a 500 Hz "praticamente coincidente" con l'ottimo per sala polifunzionale (curva di Figura 15) — **nessun valore numerico di T ottimale esplicitato** <!-- pp. 17-18 -->.

### Lettura per C1.3 (inferita)
- Il calcolo e' fatto **a sala piena** (134 persone): le basse frequenze restano lunghe (1,77 s a 125 Hz) e il comportamento a sala vuota/parzialmente occupata non e' valutato <!-- confidence: inferito -->.
- Superfici ancora riflettenti: soffitto in cemento 79 m2 (alfa 0,03), pavimento in resina 175 m2 (alfa 0,02), pareti tinteggiate 16 m2: margine per pannellature/controsoffitti fonoassorbenti o diffondenti <!-- confidence: inferito -->.
- Non sono calcolati STI/RASTI, C50/C80, D50, ne' isolamento acustico di facciata o rumore impianti: possibili indicatori misurabili per la miglioria <!-- confidence: verificato per assenza, inferito per uso -->.

## Incoerenze (contenuti da descrizione generica condivisa con G-08/G-09)
- "Sistemi di rilevazione incendi e impianti sprinkler" (p. 8) — non presenti in [[RS-02-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_IDRICO_ANTINCENDIO]] (solo naspi).
- "Impianto fotovoltaico da 6 kWh" (unita' errata) e "batterie di accumulo da 20 kWh" (pp. 8-9) vs 15 kWh in RS-00/RS-01 → `02_graph/synthesis/fotovoltaico_e_accumulo.md`.
- "Impianti di climatizzazione ad alta efficienza con pompe di calore" (p. 9) vs caldaia a condensazione di [[RS-00-ESEC-01_RELAZIONE_TECNICA_IMPIANTI]] p. 12.
- "LED integrati con sensori di presenza" (p. 9): non descritti altrove nel sottoinsieme.

## Riferimenti a altri elaborati
- Nessun codice di elaborato citato nel testo.
- Citata (senza codice) da [[G-09-ESEC-01_RELAZIONE_CAM]] p. 31 (criterio CAM 2.4.11: "i risultati ... sono contenuti nella relazione acustica, elaborato ulteriore del progetto esecutivo").

## Sintesi tematiche collegate
`02_graph/synthesis/acustica_sala.md` · `02_graph/synthesis/fotovoltaico_e_accumulo.md`
