---
type: document
subtype: tavola
gara: "Lavori di adeguamento ed efficientamento energetico del Cineteatro “Sala Polifunzionale Periz” ubicato nel Castello di Bella (PZ)"
date: 2026-10-03
ai-first: true
codice: "PI-02-ESEC-01"
file: "PI_02_ESEC_01_PROGETTO CON INDICAZIONE CLASSI RESISTENZA AL FUOCO.pdf.p7m"
file_originale: "00_input/p7m/progetto.esecutivo.a.base.di.gara/pdf firmati/PI_02_ESEC_01_PROGETTO CON INDICAZIONE CLASSI RESISTENZA AL FUOCO.pdf.p7m"
pdf_leggibile: "01_extracted/p7m_extracted/PI-02-ESEC-01_PROGETTO_CON_INDICAZIONE_CLASSI_RESISTENZA_AL_FUOCO.pdf"
section: "PI"
version_group: "PI-02"
is_latest: true
status: non_estratto
extracted_md: "nessuno — tavola grafica, non estratta per regola (lettura on-demand via drawing-reader)"
confidence: inferito
descrizione_ufficiale: "PROGETTO CON INDICAZIONE DELLE CLASSI DI REAZIONE AL FUOCO"  # fonte: elenco elaborati G-00-ESEC-01 — confidence: inferito; il nome file dice RESISTENZA
in_elenco_elaborati: true
firmato: true  # firma CMS Martone Carmen 2026-04-24 (manifest)
pagine: 4
formato: "A1"
supports_criteria:
  - { criterion: "[[C1]]", priority: media, confidence: inferito, reason: "C1.3 materiali interni: classi di reazione al fuoco richieste per finiture e pannellature — vincolo per MDF e rivestimenti fonoassorbenti (checklist C1 «verificare i requisiti di reazione al fuoco per finiture e pannellature … tavole prevenzione incendi»). Inferito dal titolo" }
  - { criterion: "[[C4]]", priority: media, confidence: inferito, reason: "C4.2 CAM avanzati: lastre di cartongesso e silicati antincendio con riciclato EPD oltre i minimi — la tavola indica verosimilmente dove sono previsti elementi con classe di resistenza/reazione al fuoco (perimetro della miglioria). Inferito dal titolo" }
related_documents:
  - { doc: "[[G-00-ESEC-01_ELENCO_ELABORATI]]", type: referenced_by, confidence: verificato, reason: "L'elenco elaborati G-00-ESEC-01 lo elenca per codice (p. 2) come «PROGETTO CON INDICAZIONE DELLE CLASSI DI REAZIONE AL FUOCO»: fonte della descrizione ufficiale" }
  - { doc: "[[RS-02-ESEC-01_RELAZIONE_TECNICA_IMPIANTO_IDRICO_ANTINCENDIO]]", type: tavola_di, confidence: inferito, reason: "Tavola antincendio (classi di reazione/resistenza al fuoco) abbinata alla sola relazione antincendio del progetto, che tratta solo i naspi: classi e compartimentazioni non hanno relazione testuale dedicata — abbinamento per disciplina, contenuto grafico non letto" }
---

# PI-02-ESEC-01 — Progetto con indicazione delle classi di reazione (o resistenza) al fuoco

## Per Claude futuro
Questa e' la tavola PI-02-ESEC-01 della gara Cineteatro «Sala Polifunzionale Periz» — Castello di Bella (PZ), CIG BCF01395AF.
Rappresenta le piante di progetto con l'indicazione delle classi al fuoco dei materiali/elementi (4 fogli, scala 1:50) per la sezione PI (progetto impianti) — componente dell'adeguamento antincendio.
Lettura approfondita differita a drawing-reader on-demand. Confidence: inferito (descrizione da elenco elaborati e cartiglio; contenuto grafico non letto).

## Identificazione

| Campo | Valore | Fonte | Confidence |
|---|---|---|---|
| Descrizione ufficiale | PROGETTO CON INDICAZIONE DELLE CLASSI DI **REAZIONE** AL FUOCO | [[G-00-ESEC-01_ELENCO_ELABORATI]] | inferito |
| Titolo nel cartiglio | PROGETTO CON INDICAZIONE DELLE CLASSI DI **RESISTENZA** AL FUOCO — PI-02-ESEC-01 aprile 2026 | cartiglio, pdftotext p. 1 | verificato |
| Sottotitolo nel cartiglio | PIANTA CON INDICAZIONE DELLE CLASSI DI **REAZIONE** AL FUOCO | cartiglio | verificato |
| Scala | 1:50 | cartiglio | verificato |
| Fogli / formato | 4 / A1 | pdfinfo | verificato |

## Criteri collegati
- [[C1]] — priorita' media, arco inferito — sub C1.3 (vincolo reazione al fuoco sui materiali acustici).
- [[C4]] — priorita' media, arco inferito — sub C4.2 (cartongesso e silicati antincendio).

## Anomalie
- **Discrepanza «reazione» / «resistenza» al fuoco:** l'elenco elaborati dice «classi di REAZIONE al fuoco», il nome file e il titolo del cartiglio «classi di RESISTENZA al fuoco», il sottotitolo del cartiglio di nuovo «REAZIONE». Sono grandezze diverse (reazione: comportamento dei materiali di finitura, es. classi B-s1,d0; resistenza: prestazione degli elementi costruttivi, es. EI 60). Per C1.3 conta la reazione, per C4.2 (silicati antincendio) entrambe: verificare con drawing-reader quali classi la tavola riporta davvero.

## Note
- Elaborati correlati probabili (Fase D): serie [[VVF-PI-02-00_PIANTA_PIANO_TERRA]] … VVF-PI-05-00, `RS-03-ESEC-01` (relazione acustica), `G-09-ESEC-01` (relazione CAM).

Lettura approfondita disponibile on-demand via `drawing-reader`.
