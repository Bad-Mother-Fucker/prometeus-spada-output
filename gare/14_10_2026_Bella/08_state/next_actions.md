# Prossime azioni — Cineteatro «Sala Polifunzionale Periz», Castello di Bella (PZ)

**Aggiornato il:** 2026-10-03 13:25 CEST
**Agente:** context-monitor
**Fase:** chiusura Fase 1 — prossimo passo del workflow: STOP OBBLIGATORIO #1 (risposte all'audit strategico)
**Giorni alla scadenza offerte:** 11 (mer 14/10/2026 ore 12:00)

> ALERT — In ordine di scadenza: **NA-01 sopralluogo entro lun 05/10/2026 ore 12:00** (pena inammissibilità) · **NA-03 quesiti entro mar 06/10/2026 ore 12:00** · NA-06 controllo risposte SA entro gio 08/10/2026 · offerta entro mer 14/10/2026 ore 12:00.

---

## 1. Azioni con scadenza di gara

| ID | Azione | Entro | Chi | Come | Issue |
|---|---|---|---|---|---|
| NA-01 | Richiedere il **sopralluogo obbligatorio** con nominativo e qualifica dell'incaricato (legale rappresentante, procuratore, direttore tecnico o delegato; un delegato non rappresenta più concorrenti). La richiesta è telematica: farla subito, senza attendere lunedì | lun 05/10/2026 ore 12:00 | professionista / impresa | PAD ASMECOMM, sezione sopralluogo | OI-01 |
| NA-02 | Rispondere a **STOP #1** (6 domande chiave + direttive: tono, priorità C1-C7, vincoli, opportunità). La domanda 5 decide i quesiti di NA-03 | ora (prima di NA-03) | professionista → main loop scrive le risposte in `strategy_audit.md` (Edit della sola sezione) | chat oppure campi compilabili di `11_view/03_criteria/strategy_audit.html` | OI-02 |
| NA-03 | Decidere e inviare i **quesiti alla SA**: Q1 (accumulo, alta), Q2 (CAM, alta), Q3 (ascensore, media), Q4 (poltrone, media), Q5 (manodopera, facoltativo); valutare gli extra di OI-04 (oneri sicurezza, edizione tariffa, comprova C6.1/C7.1, schede C5.1, regole C5.1) | mar 06/10/2026 ore 12:00 | professionista; main loop redige i testi extra se richiesto | PAD «Sezione chiarimenti»; testi Q1-Q5 in [economic_framework](../02_graph/economic_framework.md) §10.1 | OI-03, OI-04 |
| NA-04 | Preparare la **checklist del sopralluogo**: ascensore (tipo, fermate, corsa, D14); numero e disposizione poltrone (D18); serramenti e nodi di posa (C1.1); copertura, terrazzi e cupola (C3.1); dotazioni audio, proiettori e schermo esistenti (C3.2, C3.3); accessi, dimensioni dei mezzi, posizione autogrù, aree di stoccaggio, convivenza con visitatori ed eventi del Castello (logistica) | prima della data comunicata dalla SA (preavviso ≥ 2 giorni) | main loop + professionista | da strategy_audit §3 e domanda 3; index §8 | OI-01, OI-05 |
| NA-05 | Ritirare l'**attestazione di avvenuto sopralluogo** | data fissata dalla SA | incaricato | in sito | OI-01 |
| NA-06 | Controllare le **risposte della SA** e acquisirle nel grafo; segnalare quali baseline (D13, D11, D14, D18) si chiudono | gio 08/10/2026 | main loop | `/update_document` sul chiarimento; poi aggiornare le issue OI-05 | OI-05 |

## 2. Azioni di workflow (sequenza CLAUDE.md §3)

| ID | Azione | Quando | Chi | Comando / agente | Issue |
|---|---|---|---|---|---|
| NA-07 | Presentare **STOP #2** (menu criteri) | solo dopo le risposte a STOP #1 | main loop | — | OI-02 |
| NA-08 | Decidere i **3 orfani**: IT-00 (lasciare orfano), PI-06 (collegare come vincolo a C1.3 e C3.3), VVF-PI-01 (facoltativo, C3.3) | prima della Fase 2 su C1 e C3 | professionista | `/resolve_orphan` | OI-06 |
| NA-09 | Leggere le **5 tavole `alta`** con drawing-reader, priorità PI-00a e PI-00 (C2.1, 15 pt), poi PA-05 (C3.1), SIC-02 (C3.3), PA-03 (C4.1) | Fase 2, passo 2 del criterio collegato | main loop | `drawing-reader`, un'invocazione per tavola in parallelo | OI-07 |
| NA-10 | Analisi dei criteri scelti a STOP #2: pipeline main loop → pdf-reader / drawing-reader → criterion-agent → evidence-auditor → riepilogo e feedback | dopo STOP #2 | main loop | Fase 2; poi `context-monitor` a ogni criterio chiuso | — |
| NA-11 | Raccogliere i **dati impresa per C5-C7** (interventi analoghi max 6 con committente, immobile, destinazione, lavorazioni, importo, periodo, ultimazione; L. 68/1999; UNI/PdR 125:2022; forma di partecipazione; avvalimento premiale) | prima dell'analisi di C5-C7 | professionista / impresa | — | OI-11 |
| NA-12 | Fornire indirizzi o pareri della **Soprintendenza Basilicata**, se disponibili, e orientamento sul BIPV | prima dell'analisi di C2 | professionista | caricamento in `00_input/` + `/update_document` | OI-12 |
| NA-13 | Compilare `vincoli_offerta_tecnica.md` **Sezione B** (budget facciate, criteri esclusi, priorità) | prima di offer-writer | professionista | — | OI-15 |

## 3. Azioni tecniche e di manutenzione

| ID | Azione | Quando | Chi | Comando | Issue |
|---|---|---|---|---|---|
| NA-14 | Rigenerare gli **artifact HTML** dopo ogni modifica di un `.md` in whitelist (hook non attivo su questa cartella) | dopo ogni scrittura | main loop | `node scripts/render/md_to_html.js --all` poi `node scripts/render/md_to_html.js --check` | OI-10 |
| NA-15 | **Pubblicare** gli output su `prometeus-spada-output` (DEC-002), a partire da questo snapshot | ora e a ogni chiusura di fase o criterio | main loop su richiesta | `/sync_output` (`./scripts/setup/sync_output.sh`) | — |
| NA-16 | Riaprire l'**Analisi 2 gap prezzi** quando è disponibile il prezzario Basilicata nell'edizione usata dal progetto | dopo OI-08 risolta | professionista → main loop | `scripts/prezzario/fetch_prezzario.sh` + `/run_strategy_audit` | OI-08, OI-09 |
| NA-17 | Snapshot `context-monitor` | a ogni criterio chiuso con feedback, o alle soglie di contesto | main loop | `/snapshot_context` | — |
