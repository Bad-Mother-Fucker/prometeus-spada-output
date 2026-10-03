# Issue aperte — Cineteatro «Sala Polifunzionale Periz», Castello di Bella (PZ)

**Aggiornato il:** 2026-10-03 13:25 CEST
**Agente:** context-monitor
**Fase:** chiusura Fase 1 — STOP OBBLIGATORIO #1 aperto
**Issue aperte:** 15 · con scadenza di gara: 3 (OI-01, OI-03, OI-04)

> ALERT — SCADENZE. **OI-01** richiesta sopralluogo obbligatorio entro **lun 05/10/2026 ore 12:00** (pena inammissibilità). **OI-03 / OI-04** quesiti alla SA entro **mar 06/10/2026 ore 12:00** (risposte entro gio 08/10/2026). Offerte entro **mer 14/10/2026 ore 12:00**.

---

## 1. Registro

| ID | Issue | Priorità | Scadenza | Blocca | Chi agisce | Riferimento |
|---|---|---|---|---|---|---|
| OI-01 | Richiesta di sopralluogo obbligatorio non ancora registrata come inviata | CRITICO | lun 05/10/2026 ore 12:00 | ammissibilità dell'offerta | professionista / impresa (PAD) | disciplinare art. 11 pp. 16-17; gara_brief «Scadenze operative» |
| OI-02 | STOP #1: sezione «Indicazioni strategiche del professionista» di `strategy_audit.md` vuota (6 domande chiave + direttive) | CRITICO | prima di STOP #2 | menu criteri e intera Fase 2 | professionista → main loop scrive le risposte | [strategy_audit](../03_criteria/strategy_audit.md) |
| OI-03 | Quesiti Q1-Q5 già redatti: da decidere quali inviare | CRITICO | mar 06/10/2026 ore 12:00 | baseline C2.3, C4.2, C4.1, C1.2 | professionista (invio via PAD «Sezione chiarimenti») | [economic_framework](../02_graph/economic_framework.md) §10.1; index §7.4 |
| OI-04 | Quesiti candidati **non coperti da Q1-Q5**, nessun testo redatto: oneri sicurezza (domanda chiave 1); edizione della tariffa Basilicata (domanda chiave 2); comprova di C6.1 e C7.1 in Busta B; schede C5.1 dentro o fuori le 30 facciate; C5.1 arco temporale, lavori in RTI o subappalto | ALTO | mar 06/10/2026 ore 12:00 | C5-C7 (10 pt), budget facciate, Analisi 2 | professionista decide; main loop redige i testi se richiesto | strategy_audit domande 1-2; gara_brief «Domande aperte» n. 4 (b)-(d); criteria_matrix N7, N8 |
| OI-05 | 7 contraddizioni irrisolte (dettaglio §2) | ALTO | quesiti 06/10; sopralluogo | baseline di 4 sottocriteri (24 pt) | professionista + risposte SA | index §7.1; economic_framework §10 |
| OI-06 | 3 orfani da decidere con `/resolve_orphan` (dettaglio §3) | MODERATO | prima della Fase 2 su C1 e C3 | vincoli fisici di C1.3 e C3.3 | professionista | index §6 |
| OI-07 | 5 tavole `alta` non lette: PI-00a, PI-00 (C2.1, C2.3), PA-05 (C3.1), SIC-02 (C3.3), PA-03 (C4.1); archi solo inferiti tranne PI-00a | ALTO | prima dell'analisi del criterio collegato | evidenza su C2.1 (15 pt), C3.1, C3.3, C4.1 | main loop → drawing-reader (Fase 2 passo 2) | index §3, §8, §9 |
| OI-08 | Edizione/anno della tariffa Basilicata non dichiarati negli elaborati (il disciplinare cita il «Listino regionale vigente», p. 7) | MODERATO | prima di riaprire l'Analisi 2 | confronto prezzi | professionista (quesito SA o altra fonte) | economic_framework §11, §13; strategy_audit domanda 2 |
| OI-09 | Analisi 2 «gap prezzi» rinviata (DEC-001) → Analisi 4 «investimento migliorativo» NON CALCOLABILE: nessuna misura del margine per le migliorie | ALTO | prima della stesura delle migliorie | dimensionamento migliorie; verifica anomalia art. 23 | professionista (prezzario) → `/run_strategy_audit` | strategy_audit §2, §4; decision_log DEC-001 |
| OI-10 | Artifact HTML in `11_view/` non generati automaticamente: l'hook è legato alla cartella di progetto della sessione | MODERATO | dopo ogni modifica di un `.md` in whitelist | allineamento degli artifact condivisi | main loop: `node scripts/render/md_to_html.js --all` poi `--check` | CLAUDE.md §6.1; decision_log SYS-007 |
| OI-11 | Requisiti tabellari C5-C7 (10 pt) non verificati: numero di interventi analoghi documentabili (max 6), L. 68/1999 ultimo triennio, UNI/PdR 125:2022; forma di partecipazione; eventuale avvalimento premiale (contratto in Busta A) | ALTO | prima dell'analisi di C5-C7 | 10 pt «a costo zero» | professionista / impresa | gara_brief «Domande aperte» n. 1; criteria_matrix N7, N8 |
| OI-12 | Indirizzi, pareri o prescrizioni della Soprintendenza Basilicata assenti da tutti gli elaborati; PI-00a non firmata, fuori Elenco Elaborati, cartiglio «Agosto 2026» | ALTO | prima dell'analisi di C2 | C2.1 (15 pt) | professionista | gara_brief «Domande aperte» n. 3; index §7.5; sintesi tutela_castello_e_impatto_visivo |
| OI-13 | Budget sicurezza BASSO (3,41%); misure del PSC senza voce negli oneri: gru (montaggio gru a torre PSC p. 36), protezione attrezzature esistenti, monitoraggio vibrazioni e polveri, regolazione del traffico, interferenze con visitatori | MODERATO | prima dell'analisi di C3 | C3.3, C4.2, sostenibilità | professionista | strategy_audit §1 e domanda 1 |
| OI-14 | Documenti richiamati ma assenti da `00_input/`: relazione ex L. 10/91 e abaco serramenti (baseline C1.1), «preventivo allegato» poltrone, «Elaborato B3» CAM, «elaborato C1» di G-08 | MODERATO | prima dell'analisi di C1 e C4 | baseline C1.1, C1.2, C4.2 | professionista (quesito o richiesta alla SA) | index §7.5 |
| OI-15 | `vincoli_offerta_tecnica.md` Sezione B non compilata (budget facciate per sottocriterio, criteri esclusi, priorità) | BASSO | prima di offer-writer | stesura offerta | professionista | vincoli_offerta_tecnica.md |

## 2. Contraddizioni irrisolte (OI-05)

| Rif. | Contraddizione | Sottocriterio | Quesito | Verifica al sopralluogo |
|---|---|---|---|---|
| D13 | Accumulo di progetto 15 kWh (computo, RS-00, RS-01, PI-00) vs 20 kWh (G-08, PSC, RS-03, G-09); lettura della soglia «>20 kWh» | C2.3 (7 pt) | Q1 — alta | no |
| D11 | CAM D.M. 24.11.2025 (disciplinare, «Elaborato B3» inesistente) vs D.M. 23/06/2022 (G-09, capitolato) vs DM 11/10/2017 (elenco prezzi); «minimi CAM» indeterminati | C4.2 (5 pt) | Q2 — alta | no |
| D14 | Ascensore 8 pers. / 6 fermate / corsa 18 m (computo, elenco prezzi) vs 6 pers. / 3 fermate / corsa 9 m (G-08, PSC); «elettrico a fune» vs idraulico | C4.1 (5 pt) | Q3 — media | sì |
| D18 | Poltrone 134 (computo, G-08, PSC, RS-03) vs 128 (tavole VV.F. approvate) / 129 (PI-03) / 130 (PI-05) | C1.2 (7 pt) | Q4 — media | sì |
| D4 | Manodopera 0,00 su tutte le voci NP (G-05) vs ≥ 13.708,57 € in G-03 e NP 16; PSC 773 uomini-giorno | trasversale (anomalia art. 23) | Q5 — bassa, facoltativo | no |
| D2 | IVA lavori 59.428,23 € «al 22%» nel QE (= 15,07%); causa non ricostruibile | nessun impatto sull'offerta | nessuno | no |
| D16 | Importo presunto lavori nel PSC 391.795,41 € vs QE 381.364,99 / 394.370,46 € | nessun impatto sull'offerta | nessuno | no |

Nota operativa (inferito): la SA comunica data e ora del sopralluogo con almeno 2 giorni di preavviso (art. 11 p. 17), quindi è probabile che il sopralluogo avvenga **dopo** il termine quesiti del 06/10. La verifica in sito di D14 e D18 non sostituisce Q3 e Q4 se serve una risposta scritta della SA.

## 3. Orfani (OI-06)

| Documento | Valutazione del grafo | Proposta per `/resolve_orphan` |
|---|---|---|
| IT-00-ESEC-01 Inquadramento su IGM | orfano giustificato (contesto territoriale, già coperto da IT-02 e IT-03) | lasciare orfano |
| PI-06-ESEC-01 Impianto idrico antincendio | orfano non del tutto giustificato: vincolo fisico (posizione naspi) | collegare come vincolo: C1 bassa (C1.3) e C3 bassa (C3.3), `confidence: inferito` |
| VVF-PI-01-00 Planimetria generale VV.F. | orfano in gran parte giustificato | facoltativo: C3 bassa (C3.3), `confidence: inferito` |

## 4. Issue chiuse in questa fase

Nessuna issue di stato precedente: primo snapshot della gara (08_state era vuota).
