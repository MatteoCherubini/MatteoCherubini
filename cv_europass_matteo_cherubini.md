# CURRICULUM VITAE

### Formato Europass

---

## INFORMAZIONI PERSONALI

**Matteo Cherubini**\
Data e luogo di nascita: 27 marzo 1997, Firenze (Italia)\
Nazionalità: italiana\
Indirizzo: via Santa Gonda 108, 59100 Prato (PO), Italia\
Telefono: (+39) 327 6615664 · E-mail: cherubinimatte@gmail.com\
GitHub: [github.com/MatteoCherubini](https://github.com/MatteoCherubini) · Medium: [medium.com/@cherubinimatte](https://medium.com/@cherubinimatte)\
Patenti A e B, automunito

---

## PROFILO PROFESSIONALE

Sviluppatore front-end (Angular, con sviluppo di API in NodeJS) con tre anni di esperienza presso una software house italiana leader nella digitalizzazione dell'editoria scolastica, del patrimonio culturale e della ricerca (Gruppo Meta/ETT, poi Deda Next). Ha contribuito, lato front-end, a piattaforme di rilievo nazionale ed europeo — dalla principale piattaforma didattica per le scuole italiane (HUB Scuola, Mondadori Education) a progetti per istituzioni culturali e infrastrutture di ricerca del CNR legate alla European Open Science Cloud — con forte attenzione all'accessibilità (a11y). In quel ruolo ha operato sia in team strutturati sia in autonomia sulle funzionalità affidategli, con occasioni di confronto diretto con i clienti. Da maggio 2026 consulente ICT indipendente su AI applicata e knowledge management: sviluppo di sistemi che integrano sicurezza, LLM locali, automazione e revisione umana. Inglese C1 (autovalutazione QCER). Approccio fondato su un metodo algoritmico e su una marcata capacità di self-direction: darsi obiettivi, scegliere le fonti e portarli a termine senza supervisione, integrandosi nel gruppo quando il lavoro lo richiede.

---

## ESPERIENZA PROFESSIONALE

**Consulente ICT — attività professionale autonoma (P.IVA)**\
_1 maggio 2026 – oggi · Prato / da remoto_

Consulente tecnologico indipendente su AI applicata e knowledge management: sistemi local-first in cui l'automazione è affiancata da un modello di sicurezza e dalla revisione umana.

- Progetto pilota presso uno studio di commercialisti: gestione della conoscenza e dei flussi documentali assistita da AI, basata sui sistemi descritti di seguito, e piccoli interventi sulla rete. La collaborazione non è proseguita oltre la fase pilota.
- **Pipeline OCR:** trasformazione di documenti scansionati e digitali in testo strutturato e ricercabile, a monte delle automazioni.
- **Wiki dinamiche:** documentazione che un agente LLM mantiene aggiornata all'arrivo di nuove fonti, così che la conoscenza sia compilata una volta e mantenuta nel tempo, anziché ricostruita a ogni interrogazione come nel paradigma RAG.
- **Knowledge Genome Orchestrator:** il sistema sviluppato in proprio alla base di questa attività — base di conoscenza distribuita, cifrata e multi-dominio (senza database vettoriale, pipeline di embedding né server di retrieval), pensata per l'estensione ai domini ambientale, agronomico e finanziario. Architettura agente a due fasi con un confine di fiducia esplicito: l'agente svolge solo il lavoro semantico, un post-processore deterministico e testato ne valida l'output prima che tocchi il filesystem.
- **Modello di sicurezza e qualità:** cifratura AES-256 per dominio (git-crypt) con chiavi iniettate a runtime da un password manager e mai scritte su disco; revisione umana tramite pull request; suite di test deterministica, indipendente da modello, GPU e rete; architettura multi-dominio su submodule Git, orchestrata tramite webhook e inferenza LLM locale.
- **Infrastruttura self-hosted:** stack Docker Compose (scelto rispetto a Kubernetes per semplicità operativa e rapidità di ripristino) con reverse proxy e gestione SSL, hosting Git privato (Forgejo), automazione dei flussi (n8n con PostgreSQL e Redis), accesso esterno sicuro tramite Cloudflare Tunnel e inferenza LLM locale (Ollama) su GPU NVIDIA; stack riproducibili e distribuibili in modo indipendente.
- Strumenti: TypeScript su Bun, Docker Compose, Proxmox, Forgejo, n8n, Ollama, git-crypt, Vaultwarden, Obsidian; sistemi co-progettati con LLM di ultima generazione.

**Sviluppatore Front-End — Gruppo Meta / M.E.T.A. S.r.l. (Gruppo ETT), poi Deda Next S.r.l. (Dedagroup)**\
_Software house specializzata in digitalizzazione dell'editoria scolastica, del patrimonio culturale e della ricerca; partner tecnologico di editori, biblioteche nazionali ed enti di ricerca_\
_24 gennaio 2023 – 1 maggio 2026 · sedi di Firenze (Le Murate) e Pisa, con lavoro agile parziale · contratto a tempo indeterminato (CCNL Metalmeccanici industria, impiegato)_

- Membro del team front-end (Angular); referente operativo sul cliente principale **Mondadori Education** per la piattaforma **HUB Scuola**, la principale piattaforma di didattica digitale per le scuole italiane: applicazione del nuovo stile grafico alle applicazioni Hub ed evolutive gestite in autonomia (nuove funzionalità, in particolare quiz ed esercizi interattivi integrati negli e-book).
- Interpretazione di mock grafici come componenti Angular; progettazione e scrittura di interi nuovi flussi applicativi di varia complessità; interventi di qualità con focus su accessibilità (a11y, in linea con la direttiva UE 2016/2102), refactoring, debugging e unit testing.
- Ammodernamento e refactoring su larga scala di progetti legacy (visori per file editoriali complessi e dinamici), in autonomia dal team di sviluppo e a stretto contatto con il team grafico/UX; studio applicato di regole di accessibilità e composizione del layout.
- Sviluppo front-end su progetti per **istituzioni culturali e di ricerca di rilievo nazionale ed europeo**: la digitalizzazione delle collezioni della **Biblioteca Nazionale Centrale di Roma** (suite metaCMS, interoperabile con _Europeana_) e piattaforme per le infrastrutture di ricerca del **CNR** nelle Digital Humanities nell'ambito del progetto **H2IOSC** — finanziato da NextGenerationEU/PNRR e tassello italiano della **European Open Science Cloud** — tra cui ambienti di apprendimento e visualizzatori.
- Partecipazione alle call di allineamento con il cliente, anche su progetti per **enti pubblici regionali**: proposte tecniche e, nei casi urgenti, interlocuzione diretta con il cliente.
- Sviluppo e integrazione di API in NodeJS in collaborazione col team back-end; visualizzatori di dati (grafici e tabelle).
- Esperienza infrastrutturale e di collaborazione con il back office: Docker, Postman, Tailscale; ecosistemi IT quali Proxmox (VM), Bitwarden (sicurezza), Obsidian (wiki/documentazione), n8n (automazione); repository strutturati con submodule.
- Lavoro regolarmente in presenza tra le due sedi aziendali — Firenze (Le Murate) e Pisa (sede principale) — alternato a lavoro agile: contesto collaborativo con occasioni di contatto diretto con i clienti, pur operando come sviluppatore all'interno dei team tecnici.

---

## ISTRUZIONE E FORMAZIONE

**Laurea triennale in Informatica (L-31 — Scienze e tecnologie informatiche)**\
Università degli Studi di Firenze, Scuola di Scienze Matematiche, Fisiche e Naturali\
Durata ufficiale del corso: 3 anni · conseguita il **7 giugno 2022** · votazione 84/110\
Tesi: _Progressive Web Application e Sistemi Operativi Web_ (relatore prof. R. Pugliese, correlatore prof. F. Tiezzi) — sviluppo di una PWA con Node.js, Ionic, Vue.js e Firebase.

Esami a scelta dal percorso magistrale: **Progettazione e Produzione Multimediale** e Computer Forensics. Studio autonomo trasversale su sistemi operativi, interfacce/UX e accessibilità; approfondimenti personali in ambito finanziario e geopolitico.

**Program for Intensive English (PIE) — Level 5 di 7 completato**\
Indiana University–Purdue University Indianapolis (IUPUI), IU School of Liberal Arts — Indianapolis (Stati Uniti)\
**22 agosto – 12 ottobre 2022** · sessione Fall 1, minimo 140 ore di lezione in aula\
Level 5 di 7 completato in Reading–Writing e Listening–Speaking, media 88/100 (PIE Letter of Achievement, 13 ottobre 2022). Scrittura accademica, presentazione orale e discussione, in un contesto studentesco internazionale.

---

## COMPETENZE PERSONALI

**Lingua madre:** italiano\
**Inglese:** C1 (Quadro Comune Europeo, autovalutazione) — ascolto, lettura, scrittura, produzione e interazione orale. Formazione: _Program for Intensive English_, Indiana University–Purdue University Indianapolis (IUPUI), 22 agosto – 12 ottobre 2022: Level 5 di 7 completato in Reading–Writing e Listening–Speaking.

**Competenze digitali**

| Area                     | Competenze                                                                                                                                                                           |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Front-end                | Angular · sviluppo componenti da mock · accessibilità (a11y) · unit testing · refactoring legacy · Vue/Ionic (PWA)                                                                   |
| Back-end e API           | NodeJS · sviluppo e integrazione API · Postman · TypeScript (tipizzazione forte) su Bun · SQLite                                                                                     |
| Dati                     | Visualizzazione dati · grafici e tabelle                                                                                                                                             |
| Infrastruttura e DevOps  | Docker Compose (stack multi-servizio) · Proxmox (VM) · Tailscale · n8n · Cloudflare Tunnel · Forgejo · Git avanzato (submodule, hook, PR-gated Git Flow) · Makefile/bash · test bats |
| Sicurezza                | git-crypt (AES-256) · Bitwarden/Vaultwarden · gestione chiavi runtime zero-disk · validazione fail-closed · consapevolezza NIS2/GDPR                                                 |
| Intelligenza artificiale | Workflow e co-progettazione con LLM · hosting ed esercizio di modelli locali (Ollama, quantizzazione) · architetture agente a due fasi · pattern LLM-wiki oltre il RAG · OCR         |
| Design                   | Figma · Adobe XD                                                                                                                                                                     |
| Documentazione           | Obsidian (wiki, Dataview, Marp) · documentazione tecnica di livello produttivo                                                                                                       |

**Competenze organizzative e trasversali**

- Metodo algoritmico: ottimizzazione dei flussi di lavoro, semplificazione di problemi complessi, gestione simultanea di collegamenti, progetti, idee e tempistiche.
- **Autonomia e lavoro in team, entrambi comprovati:** capacità di condurre un progetto end-to-end in totale indipendenza — dall'analisi dei requisiti alla consegna, come nei progetti personali auto-avviati — e di integrarsi in gruppi di lavoro strutturati (team front-end, back-end, grafico/UX) quando il compito lo richiede. La scelta tra i due modi è dettata dalle esigenze del progetto, non da una preferenza.
- Spirito imprenditoriale: concezione, architettura e realizzazione autonoma di progetti complessi non commissionati (vedi progetti personali); avvio di un'attività professionale indipendente.
- Qualità del codice come standard personale: eleganza, pulizia, attenzione all'accessibilità.
- Documentazione sistematica dei progetti (wiki, versionamento).

---

## ULTERIORI INFORMAZIONI

**Progetti personali:** _NETKIT_ (strumento di network auditing in sviluppo, con workflow di consenso legale e attenzione ai requisiti GDPR/NIS2; motore in TypeScript su Bun e SQLite, interfaccia da completare). Knowledge Genome Orchestrator e infrastruttura self-hosted sono descritti nell'esperienza di consulente ICT. Repository su GitHub.

**Sviluppo professionale autonomo:** apprendimento continuo e auto-diretto sui propri ambiti di interesse (tecnologia, finanza, agronomia, cultura) attraverso canali e community internazionali — pubblicazioni tecniche, blog di settore, video, professionisti esteri — con selezione critica delle fonti. Pubblicazione di contenuti propri (Medium).

**Esperienze all'estero:** soggiorno di studio negli Stati Uniti (Indianapolis, 22 agosto – 12 ottobre 2022) — Program for Intensive English, IUPUI.

**Contesto imprenditoriale familiare:** amministratore delegato e legale rappresentante di **Casal de' Cherubini S.r.l.**, società agricola familiare che gestisce terreni agricoli e immobili in locazione in Umbria. Ruolo di firma esercitato in accordo con gli altri membri della famiglia, senza impegno operativo quotidiano.

**Interessi (in coerenza con l'agenda ambientale, agroalimentare e di finanza sostenibile):**

- **Agricoltura ecosostenibile ed etica e filiera agroalimentare di qualità** — tema vissuto anche dall'interno, attraverso la società agricola familiare (terreni e immobili); sostenitore di Slow Food e dei modelli produttivi non intensivi che valorizzano piccoli produttori e allevatori.
- **Biodiversità viticola** — appassionato del progetto G.R.A.S.P.O., l'associazione di ricerca ampelografica per il recupero di vitigni antichi e rari, in collaborazione con università, CREA e CNR.
- **Cultura del vino** — socio AIS Toscana, prossimo al secondo livello del percorso da sommelier.
- **Finanza etica e sostenibile** — interesse per il microcredito e l'inclusione finanziaria (Banca Etica), per i fondi ESG e per l'investimento responsabile.
- **Caffè specialty**, geopolitica, accessibilità e diritti, cultura del software di qualità.

---

_Autorizzo il trattamento dei miei dati personali ai sensi del Regolamento (UE) 2016/679 (GDPR) e del D.Lgs. 196/2003._
