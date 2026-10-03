# Censimento elaborati — liste per graph-builder

Gara: Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ) — CIG BCF01395AF
Prodotto da: graph-builder, invocazione 1 (Fasi 0-2) — 2026-10-03
Fonti: `find 00_input` (56 file .pdf/.p7m), `00_input/_manifest_input.md` (56 righe), elenco elaborati `G-00-ESEC-01` (40 elaborati, letto da `01_extracted/p7m_extracted/G-00-ESEC-01_ELENCO_ELABORATI.pdf`).

**Uso per le invocazioni successive:** Fase A legge la lista ECONOMICI, Fase B la lista TESTUALI, Fase C la lista TAVOLE. La lista ALTRO non e' assegnata a nessuna fase (vedi nota in fondo). Le colonne `codice`, `subtype`, `is_latest`, `version_group` sono quelle da riportare nel frontmatter delle pagine nodo; il nome file nodo e' `02_graph/nodes/[codice]_[descrizione].md` con `[descrizione]` = parte del nome del PDF leggibile dopo il codice.

## Riepilogo

| Lista | N. | Codici |
|---|---|---|
| ECONOMICI | 8 | G-01-ESEC-01, G-01-ESEC-02, G-02-ESEC-01, G-03-ESEC-01, G-04-ESEC-01, G-04-ESEC-02, G-05-ESEC-01, SIC-03-ESEC-01 |
| TESTUALI | 14 | G-00-ESEC-01, G-06-ESEC-01, G-06-ESEC-02, G-07-ESEC-01, G-08-ESEC-01, G-09-ESEC-01, G-10-ESEC-01, G-11-ESEC-01, RS-00-ESEC-01, RS-01-ESEC-01, RS-02-ESEC-01, RS-03-ESEC-01, SIC-00-ESEC-01, SIC-01-ESEC-01 |
| TAVOLE | 30 | SIC-02-ESEC-01, IT-00-ESEC-01, IT-01-ESEC-00, IT-02-ESEC-00, IT-03-ESEC-00, RIL-00-ESEC-01, RIL-01-ESEC-01, RIL-02-ESEC-01, PA-00-ESEC-01, PA-01-ESEC-01, PA-02-ESEC-01, PA-03-ESEC-01, PA-04-ESEC-01, PA-05-ESEC-01, PI-00-ESEC-01, PI-00a-ESEC-01, PI-01-ESEC-01, PI-02-ESEC-01, PI-03-ESEC-01, PI-04-ESEC-01, PI-05-ESEC-01, PI-06-ESEC-01, VVF-PI-01-00, VVF-PI-02-00, VVF-PI-03-00, VVF-PI-04-00, VVF-PI-05-00, VVF-PI-06-00, VVF-PI-07-00, VVF-PI-08-00 |
| ALTRO | 4 | COM-PZ.REGISTRO-UFFICIALE.2026.0007341, disciplinare.di.gara, bando, norme.tecniche |
| **Totale** | **56** | = file censiti in `00_input/` |

## Convenzione sezioni di questo progetto

Il progetto NON usa la numerazione 08/09 degli esempi degli agenti. La sezione si legge dal prefisso del codice:

| Prefisso | Contenuto | Tipo prevalente |
|---|---|---|
| G-00 … G-11 | Elaborati generali, economici e contrattuali (G-01 QE, G-02 elenco prezzi, G-03 analisi NP, G-04 computo, G-05 manodopera, G-06 capitolato, G-07 rel. fotografica, G-08 rel. generale, G-09 rel. CAM, G-10 piano manutenzione, G-11 schema contratto) | testuali / economici |
| RS | Relazioni specialistiche (impianti, FV, idrico antincendio, acustica) | testuali |
| SIC | SIC-00 PSC, SIC-01 cronoprogramma, SIC-02 layout cantiere (tavola), SIC-03 costi sicurezza | testuali / economico / tavola |
| IT | Inquadramento territoriale | tavole |
| RIL | Rilievo stato di fatto | tavole |
| PA | Progetto architettonico | tavole |
| PI | Progetto impianti (incl. PI-00a-ESEC-01 fotovoltaico integrato, richiamata dal criterio C2.1) | tavole |
| VVF-PI | Tavole della Pratica VV.F. 21079 | tavole |
| COM-PZ… | Protocollo/parere Comando VV.F. Potenza | altro |
| disciplinare, bando, norme.tecniche | Documenti di gara / piattaforma | altro |

## Lista ECONOMICI — Fase A (8)

| codice | file pdf leggibile | file testo estratto | subtype | lista | is_latest | version_group | pp. | descrizione ufficiale (elenco G-00) | note |
|---|---|---|---|---|---|---|---|---|---|
| G-01-ESEC-01 | 01_extracted/p7m_extracted/G-01-ESEC-01_QUADRO_ECONOMICO.pdf | 01_extracted/text/G-01-ESEC-01_QUADRO_ECONOMICO.md | quadro_economico | ECONOMICI | false | G-01 | 2 | QUADRO ECONOMICO | SUPERATO da G-01-ESEC-02 (cartiglio apr. 2026). Non usare per economic_framework; serve alla Fase E. |
| G-01-ESEC-02 | 01_extracted/p7m_extracted/G-01-ESEC-02_QUADRO_ECONOMICO.pdf | 01_extracted/text/G-01-ESEC-02_QUADRO_ECONOMICO.md | quadro_economico | ECONOMICI | true | G-01 | 2 | QUADRO ECONOMICO (descrizione della voce G-01-ESEC-01 in elenco; la revisione ESEC-02 e' successiva all'elenco) | is_latest (cartiglio mag. 2026, cartella «Integrazione 2026»). Migliaia separate da spazio. |
| G-02-ESEC-01 | 01_extracted/p7m_extracted/G-02-ESEC-01_ELENCO_PREZZI.pdf | 01_extracted/text/G-02-ESEC-01_ELENCO_PREZZI.md | elenco_prezzi | ECONOMICI | true | G-02 | 11 | ELENCO PREZZI | Nessuna ESEC-02: verificare coerenza con G-04-ESEC-02. |
| G-03-ESEC-01 | 01_extracted/p7m_extracted/G-03-ESEC-01_ANALISI_NUOVI_PREZZI.pdf | 01_extracted/text/G-03-ESEC-01_ANALISI_NUOVI_PREZZI.md | elenco_prezzi | ECONOMICI | true | G-03 | 16 | ANALISI NUOVI PREZZI | Analisi nuovi prezzi (NP). Nessuna ESEC-02. |
| G-04-ESEC-01 | 01_extracted/p7m_extracted/G-04-ESEC-01_COMPUTO_METRICO_ESTIMATIVO.pdf | 01_extracted/text/G-04-ESEC-01_COMPUTO_METRICO_ESTIMATIVO.md | computo_metrico | ECONOMICI | false | G-04 | 25 | COMPUTO METRICO ESTIMATIVO | SUPERATO da G-04-ESEC-02 (25 → 35 pp.). Serve alla Fase E. |
| G-04-ESEC-02 | 01_extracted/p7m_extracted/G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO.pdf | 01_extracted/text/G-04-ESEC-02_COMPUTO_METRICO_ESTIMATIVO.md | computo_metrico | ECONOMICI | true | G-04 | 35 | COMPUTO METRICO ESTIMATIVO (descrizione della voce G-04-ESEC-01 in elenco; la revisione ESEC-02 e' successiva all'elenco) | is_latest. Separatore migliaia «´» (es. 119´150,77). |
| G-05-ESEC-01 | 01_extracted/p7m_extracted/G-05-ESEC-01_QUADRO_INCIDENZA_MANODOPERA.pdf | 01_extracted/text/G-05-ESEC-01_QUADRO_INCIDENZA_MANODOPERA.md | quadro_manodopera | ECONOMICI | true | G-05 | 12 | QUADRO INCIDENZA MANODOPERA | Nessuna ESEC-02: verificare coerenza con G-04-ESEC-02. |
| SIC-03-ESEC-01 | 01_extracted/p7m_extracted/SIC-03-ESEC-01_COSTI_PER_LA_SICUREZZA.pdf | 01_extracted/text/SIC-03-ESEC-01_COSTI_PER_LA_SICUREZZA.md | stima_sicurezza | ECONOMICI | true | SIC-03 | 3 | COSTI PER LA SICUREZZA | Stima costi sicurezza. Copia interna anche in SIC-00 pp. 256-258. |

## Lista TESTUALI — Fase B (14)

| codice | file pdf leggibile | file testo estratto | subtype | lista | is_latest | version_group | pp. | descrizione ufficiale (elenco G-00) | note |
|---|---|---|---|---|---|---|---|---|---|
| G-00-ESEC-01 | 01_extracted/p7m_extracted/G-00-ESEC-01_ELENCO_ELABORATI.pdf | 01_extracted/text/G-00-ESEC-01_ELENCO_ELABORATI.md | altro | TESTUALI | true | G-00 | 2 | ELENCO ELABORATI | Elenco elaborati: fonte autoritativa delle descrizioni ufficiali (40 elaborati). Messo in TESTUALI per avere una pagina nodo (subtype altro). |
| G-06-ESEC-01 | 01_extracted/p7m_extracted/G-06-ESEC-01_CAPITOLATO_SPECIALE_D_APPALTO.pdf | 01_extracted/text/G-06-ESEC-01_CAPITOLATO_SPECIALE_D_APPALTO.md | capitolato | TESTUALI | false | G-06 | 261 | CAPITOLATO SPECIALE D'APPALTO | SUPERATO da G-06-ESEC-02. Paginazione diversa (261 vs 260 pp.). |
| G-06-ESEC-02 | 01_extracted/p7m_extracted/G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO.pdf | 01_extracted/text/G-06-ESEC-02_CAPITOLATO_SPECIALE_D_APPALTO.md | capitolato | TESTUALI | true | G-06 | 260 | CAPITOLATO SPECIALE D'APPALTO (descrizione della voce G-06-ESEC-01 in elenco; la revisione ESEC-02 e' successiva all'elenco) | is_latest (cartiglio mag. 2026). |
| G-07-ESEC-01 | 01_extracted/p7m_extracted/G-07-ESEC-01_RELAZIONE_FOTOGRAFICA.pdf | 01_extracted/text/G-07-ESEC-01_RELAZIONE_FOTOGRAFICA.md | relazione_tecnica | TESTUALI | true | G-07 | 13 | RELAZIONE FOTOGRAFICA | Prevalentemente fotografie: 9 pp. interne < 150 car. → confidence parziale sul contenuto visivo. |
| G-08-ESEC-01 | 01_extracted/p7m_extracted/G-08-ESEC-01_RELAZIONE_GENERALE.pdf | 01_extracted/text/G-08-ESEC-01_RELAZIONE_GENERALE.md | relazione_generale | TESTUALI | true | G-08 | 27 | RELAZIONE GENERALE |  |
| G-09-ESEC-01 | 01_extracted/p7m_extracted/G-09-ESEC-01_RELAZIONE_CAM.pdf | 01_extracted/text/G-09-ESEC-01_RELAZIONE_CAM.md | relazione_tecnica | TESTUALI | true | G-09 | 48 | RELAZIONE SUI CRITERI AMBIENTALI CAM | Il disciplinare (Premesse) cita «Elaborato B3 – Relazione sui CAM»: corrispondenza da verificare (nota N11 criteria_matrix). |
| G-10-ESEC-01 | 01_extracted/p7m_extracted/G-10-ESEC-01_PIANO_DI_MANUTENZIONE.pdf | 01_extracted/text/G-10-ESEC-01_PIANO_DI_MANUTENZIONE.md | relazione_tecnica | TESTUALI | true | G-10 | 227 | PIANO DI MANUTENZIONE | 227 pp.; p. 227 senza testo. |
| G-11-ESEC-01 | 01_extracted/p7m_extracted/G-11-ESEC-01_SCHEMA_DI_CONTRATTO.pdf | 01_extracted/text/G-11-ESEC-01_SCHEMA_DI_CONTRATTO.md | altro | TESTUALI | true | G-11 | 20 | SCHEMA DI CONTRATTO | Schema di contratto (subtype altro: nessun subtype contrattuale nello schema). |
| RS-00-ESEC-01 | 01_extracted/p7m_extracted/RS-00-ESEC-01_RELAZIONE_TECNICA_IMPIANTI.pdf | 01_extracted/text/RS-00-ESEC-01_RELAZIONE_TECNICA_IMPIANTI.md | relazione_tecnica | TESTUALI | true | RS-00 | 13 | RELAZIONE TECNICA IMPIANTI |  |
| RS-01-ESEC-01 | 01_extracted/p7m_extracted/RS-01-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_FOTOVOLTAICO.pdf | 01_extracted/text/RS-01-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_FOTOVOLTAICO.md | relazione_tecnica | TESTUALI | true | RS-01 | 7 | RELAZIONE TECNICA IMPIANTO FOTOVOLTAICO | pp. 3-5 solo immagini (8 car./pag.) → confidence parziale su quei contenuti (stima PVGIS). |
| RS-02-ESEC-01 | 01_extracted/p7m_extracted/RS-02-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_IDRICO_ANTINCENDIO.pdf | 01_extracted/text/RS-02-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_IDRICO_ANTINCENDIO.md | relazione_tecnica | TESTUALI | true | RS-02 | 22 | RELAZIONE TECNICA IMPIANTO IDRICO ANTINCENDIO |  |
| RS-03-ESEC-01 | 01_extracted/p7m_extracted/RS-03-ESEC-01_RELAZIONE_ACUSTICA.pdf | 01_extracted/text/RS-03-ESEC-01_RELAZIONE_ACUSTICA.md | relazione_tecnica | TESTUALI | true | RS-03 | 18 | RELAZIONE ACUSTICA | Simboli greci nelle formule resi come U+FFFD. |
| SIC-00-ESEC-01 | 01_extracted/p7m_extracted/SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO.pdf | 01_extracted/text/SIC-00-ESEC-01_PIANO_DI_SICUREZZA_E_COORDINAMENTO.md | PSC | TESTUALI | true | SIC-00 | 260 | PSC | Contiene copie interne: cronoprogramma (copertina SIC-01 a p. 85, pp. 86-87), Allegato A valutazione rischi (da p. 88), fascicolo dell'opera (indice p. 254), costi sicurezza (copertina SIC-03 a p. 256, pp. 257-258), pp. 259-260 con solo testo grafico di planimetria (es. «AREA MOVIMENTAZIONE MEZZI», «percorso pedonale»): verosimile copia del layout SIC-02, da verificare. Confrontare con SIC-01/SIC-03 autonomi in Fase E. |
| SIC-01-ESEC-01 | 01_extracted/p7m_extracted/SIC-01-ESEC-01_CRONOPROGRAMMA.pdf | 01_extracted/text/SIC-01-ESEC-01_CRONOPROGRAMMA.md | cronoprogramma | TESTUALI | true | SIC-01 | 2 | CRONOPROGRAMMA | Cronoprogramma (2 pp.). Copia interna anche in SIC-00 pp. 85-87. |

## Lista TAVOLE — Fase C (30)

| codice | file pdf leggibile | file testo estratto | subtype | lista | is_latest | version_group | pp. | descrizione ufficiale (elenco G-00) | note |
|---|---|---|---|---|---|---|---|---|---|
| SIC-02-ESEC-01 | 01_extracted/p7m_extracted/SIC-02-ESEC-01_LAYOUT_DI_CANTIERE.pdf | — (tavola: non estratta) | tavola | TAVOLE | true | SIC-02 | 2 | LAYOUT DI CANTIERE | Layout di cantiere (tavola A1). Verosimile copia interna in SIC-00 pp. 259-260 (da verificare). |
| IT-00-ESEC-01 | 01_extracted/p7m_extracted/IT-00-ESEC-01_INQUADRAMENTO_SU_IGM.pdf | — (tavola: non estratta) | tavola | TAVOLE | true | IT-00 | 1 | INQUADRAMENTO SU IGM |  |
| IT-01-ESEC-00 | 01_extracted/p7m_extracted/IT-01-ESEC-00_INQUADRAMENTO_SU_CTR.pdf | — (tavola: non estratta) | tavola | TAVOLE | true | IT-01 | 1 | INQUADRAMENTO SU CTR | Nome file «ESEC_00», elenco e cartiglio «IT-01-ESEC-01» (apr. 2026): stesso elaborato, codice dal nome file. |
| IT-02-ESEC-00 | 01_extracted/p7m_extracted/IT-02-ESEC-00_INQUADRAMENTO_SU_ORTOFOTO.pdf | — (tavola: non estratta) | tavola | TAVOLE | true | IT-02 | 1 | INQUADRAMENTO SU ORTOFOTO | Nome file «ESEC_00», elenco e cartiglio «IT-02-ESEC-01» (apr. 2026): stesso elaborato, codice dal nome file. |
| IT-03-ESEC-00 | 01_extracted/p7m_extracted/IT-03-ESEC-00_INQUADRAMENTO_SU_DTM_CURVE_DI_LIVELLO.pdf | — (tavola: non estratta) | tavola | TAVOLE | true | IT-03 | 1 | INQUADRAMENTO SU DTM_CURVE DI LIVELLO | Nome file «ESEC_00», elenco e cartiglio «IT-03-ESEC-01» (apr. 2026): stesso elaborato, codice dal nome file. |
| RIL-00-ESEC-01 | 01_extracted/p7m_extracted/RIL-00-ESEC-01_PLANIMETRIA_stato_di_fatto.pdf | — (tavola: non estratta) | tavola | TAVOLE | true | RIL-00 | 1 | PANIMETRIA - stato di fatto |  |
| RIL-01-ESEC-01 | 01_extracted/p7m_extracted/RIL-01-ESEC-01_PIANTE_stato_di_fatto.pdf | — (tavola: non estratta) | tavola | TAVOLE | true | RIL-01 | 5 | PIANTE - stato di fatto |  |
| RIL-02-ESEC-01 | 01_extracted/p7m_extracted/RIL-02-ESEC-01_PROSPETTI_stato_di_fatto.pdf | — (tavola: non estratta) | tavola | TAVOLE | true | RIL-02 | 1 | PROSPETTI -stato di fatto |  |
| PA-00-ESEC-01 | 01_extracted/p7m_extracted/PA-00-ESEC-01_PIANTE_stato_di_progetto.pdf | — (tavola: non estratta) | tavola | TAVOLE | true | PA-00 | 5 | PIANTE- progetto |  |
| PA-01-ESEC-01 | 01_extracted/p7m_extracted/PA-01-ESEC-01_PROSPETTI_stato_di_progetto.pdf | — (tavola: non estratta) | tavola | TAVOLE | true | PA-01 | 1 | PROSPETTI - progetto |  |
| PA-02-ESEC-01 | 01_extracted/p7m_extracted/PA-02-ESEC-01_SEZIONI_stato_di_progetto.pdf | — (tavola: non estratta) | tavola | TAVOLE | true | PA-02 | 1 | SEZIONI - progetto |  |
| PA-03-ESEC-01 | 01_extracted/p7m_extracted/PA-03-ESEC-01_PARTICOLARI_COSTRUTTIVI_scala_e_ascensore.pdf | — (tavola: non estratta) | tavola | TAVOLE | true | PA-03 | 1 | PARTICOLARI COSTRUTTIVI - CORPO SCALA E ASCENSORE |  |
| PA-04-ESEC-01 | 01_extracted/p7m_extracted/PA-04-ESEC-01_PARTICOLARI_COSTRUTTIVI_collegamenti_verticali.pdf | — (tavola: non estratta) | tavola | TAVOLE | true | PA-04 | 1 | PARTICOLARI COSTRUTTIVI - COLLEGAMENTI VERTICALI CON IL PALCO |  |
| PA-05-ESEC-01 | 01_extracted/p7m_extracted/PA-05-ESEC-01_cupola_e_impermeabilizzazione.pdf | — (tavola: non estratta) | tavola | TAVOLE | true | PA-05 | 1 | PARTICOLARI COSTRUTTIVI - CUPOLA E IMPERMEABILIZZAZIONE |  |
| PI-00-ESEC-01 | 01_extracted/p7m_extracted/PI-00-ESEC-01_PROGETTO_IMPIANTO_FOTOVOLTAICO.pdf | — (tavola: non estratta) | tavola | TAVOLE | true | PI-00 | 1 | PROGETTO IMPIANTO FOTOVOLTAICO |  |
| PI-00a-ESEC-01 | 00_input/p7m/progetto.esecutivo.a.base.di.gara/PI-00a-ESEC-01_PLANIMETRIA  DI INSIEME CON FOTOVOLTAICO INTEGRATO E FOTOINSERIMENTI -- dettaglio offerta tecnica.pdf | — (tavola: non estratta) | tavola | TAVOLE | true | PI-00a | 1 | — (non in elenco elaborati) | NON in elenco, NON firmato. Richiamato dal disciplinare per il sub-criterio C2.1 (BIPV, 15 pt): tavola di riferimento per la miglioria. |
| PI-01-ESEC-01 | 01_extracted/p7m_extracted/PI-01-ESEC-01_SISTEMA_EVACUAZIONE_FUMI_FORZATO.pdf | — (tavola: non estratta) | tavola | TAVOLE | true | PI-01 | 1 | PROGETTO SISTEMAZIONE EVACUAZIONE FUMI FORZATO |  |
| PI-02-ESEC-01 | 01_extracted/p7m_extracted/PI-02-ESEC-01_PROGETTO_CON_INDICAZIONE_CLASSI_RESISTENZA_AL_FUOCO.pdf | — (tavola: non estratta) | tavola | TAVOLE | true | PI-02 | 4 | PROGETTO CON INDICAZIONE DELLE CLASSI DI REAZIONE AL FUOCO | Elenco: classi di «REAZIONE» al fuoco; nome file: classi di «RESISTENZA» al fuoco. |
| PI-03-ESEC-01 | 01_extracted/p7m_extracted/PI-03-ESEC-01_PROGETTO_IMPIANTO_IRAI.pdf | — (tavola: non estratta) | tavola | TAVOLE | true | PI-03 | 4 | PROGETTO IMPIANTO IRAI |  |
| PI-04-ESEC-01 | 01_extracted/p7m_extracted/PI-04-ESEC-01_INTERVENTI_TERMICI.pdf | — (tavola: non estratta) | tavola | TAVOLE | true | PI-04 | 1 | INTERVENTI TERMICI |  |
| PI-05-ESEC-01 | 01_extracted/p7m_extracted/PI-05-ESEC-01_INTERVENTI_ELETTRICI.pdf | — (tavola: non estratta) | tavola | TAVOLE | true | PI-05 | 1 | INTERVENTI ELETTRICI |  |
| PI-06-ESEC-01 | 01_extracted/p7m_extracted/PI-06-ESEC-01_IMPIANTO_IDRICO_ANTINCENDIO.pdf | — (tavola: non estratta) | tavola | TAVOLE | true | PI-06 | 3 | IM PIANTO IDRICO ANTINCENDIO |  |
| VVF-PI-01-00 | 01_extracted/p7m_extracted/VVF-PI-01-00_PLANIMETRIA_GENERALE.pdf | — (tavola: non estratta) | tavola | TAVOLE | true | VVF-PI-01 | 1 | — (non in elenco elaborati) |  |
| VVF-PI-02-00 | 01_extracted/p7m_extracted/VVF-PI-02-00_PIANTA_PIANO_TERRA.pdf | — (tavola: non estratta) | tavola | TAVOLE | true | VVF-PI-02 | 1 | — (non in elenco elaborati) |  |
| VVF-PI-03-00 | 01_extracted/p7m_extracted/VVF-PI-03-00_PIANTA_PIANO_PRIMO.pdf | — (tavola: non estratta) | tavola | TAVOLE | true | VVF-PI-03 | 1 | — (non in elenco elaborati) |  |
| VVF-PI-04-00 | 01_extracted/p7m_extracted/VVF-PI-04-00_PIANTA_PIANO_SECONDO.pdf | — (tavola: non estratta) | tavola | TAVOLE | true | VVF-PI-04 | 1 | — (non in elenco elaborati) |  |
| VVF-PI-05-00 | 01_extracted/p7m_extracted/VVF-PI-05-00_PIANTA_PIANO_TERZO.pdf | — (tavola: non estratta) | tavola | TAVOLE | true | VVF-PI-05 | 1 | — (non in elenco elaborati) |  |
| VVF-PI-06-00 | 01_extracted/p7m_extracted/VVF-PI-06-00_COPERTURA.pdf | — (tavola: non estratta) | tavola | TAVOLE | true | VVF-PI-06 | 1 | — (non in elenco elaborati) |  |
| VVF-PI-07-00 | 01_extracted/p7m_extracted/VVF-PI-07-00_PROSPETTO_E_SEZIONE.pdf | — (tavola: non estratta) | tavola | TAVOLE | true | VVF-PI-07 | 1 | — (non in elenco elaborati) |  |
| VVF-PI-08-00 | 01_extracted/p7m_extracted/VVF-PI-08-00_AREE_A_RISCHIO_SPECIFICO.pdf | — (tavola: non estratta) | tavola | TAVOLE | true | VVF-PI-08 | 1 | — (non in elenco elaborati) |  |

## Lista ALTRO — nessuna fase assegnata (4)

| codice | file pdf leggibile | file testo estratto | subtype | lista | is_latest | version_group | pp. | descrizione ufficiale (elenco G-00) | note |
|---|---|---|---|---|---|---|---|---|---|
| COM-PZ.REGISTRO-UFFICIALE.2026.0007341 | 00_input/p7m/progetto.esecutivo.a.base.di.gara/COM-PZ.REGISTRO UFFICIALE.2026.0007341_Marcato.pdf | 01_extracted/text/COM-PZ.REGISTRO-UFFICIALE.2026.0007341_Marcato.md | altro | ALTRO | true | COM-PZ.REGISTRO-UFFICIALE.2026.0007341 | 2 | — (non in elenco elaborati) | Protocollo Comando VV.F. Potenza U.0007341 del 20/04/2026, Pratica PI 21079 — «PARERE FAVOREVOLE» sulla valutazione del progetto (att. 65.1.B, locale di spettacolo 100-200 persone; condizionato a RTO DM 3/8/2015, RTV15, RTV13; SCIA prima dell'esercizio) — confermato in lettura, p. 1. Non firmato, non in elenco. Estratto. |
| disciplinare.di.gara | 00_input/disciplinare/disciplinare.di.gara.pdf | 01_extracted/text/disciplinare.di.gara.md | altro | ALTRO | true | disciplinare.di.gara | 36 | — (non in elenco elaborati) | Documento di gara (manifest: tipo disciplinare). Fonte dei criteri, gia' analizzato da disciplinare-analyst. Non e' un elaborato di progetto. |
| bando | 01_extracted/p7m_extracted/bando.pdf | 01_extracted/text/bando.md | altro | ALTRO | true | bando | 4 | — (non in elenco elaborati) | Documento di gara (manifest: tipo bando). Non e' un elaborato di progetto. |
| norme.tecniche | 00_input/elaborati/norme.tecniche.pdf | — (non estratto) | altro | ALTRO | true | norme.tecniche | 88 | — (non in elenco elaborati) | Norme d'uso piattaforma telematica (TuttoGare/ASMECOMM), non norme di progetto. Non estratto. |

## Gruppi di versione

| version_group | is_latest: false | is_latest: true | criterio d'ordinamento (graph-schema) |
|---|---|---|---|
| G-01 | G-01-ESEC-01 | G-01-ESEC-02 | regola 2: numero di revisione ESEC-02 > ESEC-01 (confermato da cartiglio mag. 2026 vs apr. 2026) |
| G-04 | G-04-ESEC-01 | G-04-ESEC-02 | idem |
| G-06 | G-06-ESEC-01 | G-06-ESEC-02 | idem |

Tutti gli altri documenti sono unici nel proprio gruppo (`is_latest: true`). `PI-00a-ESEC-01` e `PI-00-ESEC-01` sono codici diversi (gruppi distinti); le tavole `VVF-PI-xx-00` sono una serie distinta dalle `PI-xx-ESEC-01`.

## Riconciliazione

**Filesystem ↔ manifest** (`find 00_input -type f \( -iname '*.pdf' -o -iname '*.p7m' \)` = 56; manifest = 56 righe):
- `orphan_input` (nel filesystem, non nel manifest): **nessuno**
- `missing` (nel manifest, non nel filesystem): **nessuno**

**Filesystem ↔ elenco elaborati G-00-ESEC-01** (40 elaborati):
- `missing` (in elenco, non trovati): **nessuno**. IT-01/IT-02/IT-03-ESEC-01 dell'elenco corrispondono ai file `IT_0x_ESEC_00_…` (codice ESEC-00 nel nome file, ESEC-01 nel cartiglio): stesso elaborato, non mancante.
- `orphan_input` (presenti ma non in elenco), 16 file:
  - revisioni successive all'elenco (apr. 2026): G-01-ESEC-02, G-04-ESEC-02, G-06-ESEC-02 (cartella «Progetto esecutivo_Integrazione 2026»)
  - tavola non firmata richiamata dal disciplinare: PI-00a-ESEC-01
  - Pratica VV.F. 21079: VVF-PI-01-00 … VVF-PI-08-00 (8 tavole) e protocollo COM-PZ.REGISTRO-UFFICIALE.2026.0007341
  - documenti di gara, non elaborati di progetto: disciplinare.di.gara, bando, norme.tecniche

## Note per le invocazioni successive

- **Lista ALTRO**: nessuna fase A/B/C la copre. Proposta (da decidere nel main loop): `COM-PZ…0007341` (testo estratto, parere VV.F.) puo' essere trattato in Fase B come documento testuale con subtype `altro`; disciplinare e bando sono gia' la fonte di `03_criteria/` e non richiedono pagina nodo; `norme.tecniche` non e' pertinente al progetto.
- **Estrazione parziale**: RS-01-ESEC-01 pp. 3-5 e G-07-ESEC-01 (foto) hanno contenuto solo grafico → per quei contenuti `confidence: parziale`.
- **Duplicati interni al PSC**: SIC-00 contiene copie di cronoprogramma, costi sicurezza e layout (vedi note). Per la Fase E: confrontare gli importi di SIC-00 pp. 256-258 con SIC-03-ESEC-01, e con l'importo sicurezza del QE G-01-ESEC-02 (riga A.4: 13 005,47 €, letto dal testo estratto).
- **Economici senza ESEC-02**: G-02, G-03, G-05 restano ESEC-01 mentre computo e QE sono passati a ESEC-02 → verifica di coerenza prezzi/manodopera vs G-04-ESEC-02 in Fase E.
- **Formati numerici**: QE con migliaia separate da spazio (`381 364,99 €`); computo con `´` (`119´150,77`).
