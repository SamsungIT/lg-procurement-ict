Premessa
========

Genesi e ambito del documento
-----------------------------

Il presente documento rappresenta il prodotto finale delle attività di
un tavolo di lavoro promosso dal Nucleo per la Sicurezza Cibernetica
(NSC) del Dipartimento Informazioni per la Sicurezza presso la
Presidenza del Consiglio dei Ministri.

Al tavolo di lavoro, che ha operato dal novembre 2018 al febbraio 2019,
hanno partecipato le seguenti pubbliche amministrazioni centrali:

-  Dipartimento Informazioni per la Sicurezza della PCM;
-  Dipartimento della Protezione Civile della PCM;
-  Ministero degli Affari Esteri;
-  Ministero dell’Interno;
-  Ministero della Giustizia;
-  Ministero della Difesa;
-  Ministero dell’Economia e delle Finanze;
-  Ministero dello Sviluppo Economico;
-  Agenzia per l’Italia Digitale;

oltre alla società Consip, in veste di centrale di committenza delle
pubbliche amministrazioni.

Obiettivo del tavolo di lavoro era definire indicazioni
tecnico-amministrative per garantire, all’interno delle procedure per
l’approvvigionamento di beni e servizi informatici delle pubbliche
amministrazioni, la rispondenza di questi ad adeguati livelli di
sicurezza.

Si ritiene infatti che - durante i processi di acquisizione - i
fornitori, in relazione alla natura dei servizi offerti, possano
accedere al patrimonio informativo delle pubbliche amministrazioni
committenti, introducendo potenziali rischi informatici, con impatto in
particolare su riservatezza, integrità, disponibilità, autenticità e non
ripudio dei dati pubblici. Processi di acquisizione condotti senza
attenzione agli aspetti di sicurezza possono vanificare, o comunque
rendere meno efficaci, le misure prese dalle amministrazioni per
tutelare il proprio patrimonio informativo. Di contro, la necessità di
formalizzare e strutturare il rapporto con i fornitori può
rappresentare, per le amministrazioni, un’opportunità per aggiornare o
rivedere le proprie politiche di sicurezza, anche contando sulle
competenze del fornitore stesso, che può contribuire in modo positivo a
elevare le misure di protezione dell’amministrazione, come si vedrà nei
paragrafi che seguono.

Per quanto sopra, il presente documento - che riguarda certamente il
tema generale della sicurezza informatica - ha un ambito circoscritto, e
si concentra sulla sicurezza nell’approvvigionamento di beni e servizi
informatici, attività indicata nel seguito del testo con “procurement
ICT”.

È utile, in questa premessa, ricordare che la maggioranza dei contratti
pubblici che riguardano l’ICT:

-  derivano da una gara o rappresentano appalti specifici di accordi
   quadro;

-  sono pluriennali (per cui un certo grado di avvicendamento del
   personale del fornitore è inevitabile);

-  comprendono più di un’iniziativa progettuale, in genere numerosi
   progetti distinti, che vengono condotti in parte sequenzialmente, in
   parte in parallelo, non necessariamente dallo stesso gruppo di lavoro
   del fornitore;

Ai fini del presente documento, i contratti ICT si possono classificare
come segue:

a) contratti di sviluppo, realizzazione e manutenzione evolutiva di
   applicazioni informatiche;

b) contratti di acquisizione di prodotti (hardware o software);

c) contratti per attività di operation e conduzione;

d) contratti per servizi diversi da a) e c) (es. supporto, consulenza,
   formazione, help desk, ...);

e) contratti per forniture miste, combinazioni delle precedenti
   tipologie.

A chi è rivolto il documento
----------------------------

Il presente documento è diretto in primo luogo ai dirigenti e ai
funzionari delle pubbliche amministrazioni, con particolare riferimento
alle strutture che si occupano di acquisizioni informatiche, ai RUP
delle gare pubbliche, ai responsabili della transizione al digitale
(definiti dal CAD), ai responsabili dell’organizzazione, pianificazione
e sicurezza. A questi soggetti sono rivolte le indicazioni pratiche, gli
esempi e gli strumenti operativi contenuti nei paragrafi che seguono.

I contenuti del documento vanno intesi in termini di suggerimenti, buone
pratiche e procedure cui allinearsi, anche sulla base della rilevanza e
dei profili di criticità delle varie acquisizioni ICT da condurre, come
illustrato nel dettaglio, per le varie indicazioni, nel capitolo 2.

Il documento è rivolto anche, con un diverso percorso di lettura, agli
operatori di mercato e in particolare ai fornitori della pubblica
amministrazione. Per questi ultimi è opportuno, tra l’altro, essere a
conoscenza delle problematiche legate alla sicurezza nel procurement ICT
delle pubbliche amministrazioni, in modo che siano pronti a recepire le
richieste dei committenti senza impatti rilevanti sulle negoziazioni, e
anzi con spirito di collaborazione. Si ritiene infatti che stabilire un
lessico comune e condividere gli obiettivi di sicurezza possa
rappresentare un vantaggio per i clienti ma anche per i fornitori,
rendendo più efficienti le clausole dei contratti e aprendo nuovi spazi
di mercato.

Finalità del documento
----------------------

Il presente documento non costituisce un manuale tecnico, un compendio o
uno studio accademico sulla tematica della sicurezza. Al contrario, nel
testo si rimanda, per gli eventuali approfondimenti specialistici sulla
materia, alla letteratura tecnica: riferimenti puntuali a studi,
articoli e standard sono presenti nei paragrafi che seguono.

Allo stesso modo, non è scopo del presente documento fornire al lettore
interpretazioni giuridiche, disamine o estensioni di norme e procedure
vigenti in tema di appalti pubblici.

Le finalità del documento sono invece:

-  illustrare in maniera semplice e immediatamente fruibile la
   problematica della sicurezza nel procurement ICT;

-  mettere a sistema (tramite opportuni glossari e classificazioni),
   formalizzare definizioni e concetti legati alla sicurezza nel
   procurement ICT, rendendoli coerenti con la norma e con il contesto
   della pubblica amministrazione;

-  presentare buone prassi, soluzioni già in uso, misure semplici da
   adottare (strumenti operativi, esempi pratici, riferimenti puntuali),
   per verificare il livello di sicurezza degli attuali processi di
   acquisizione ed eventualmente per alzare tale livello senza per
   questo aumentare in modo eccessivo la complessità dei processi e
   l’impegno necessario a condurli.

Definizioni
-----------

Accordo quadro
  Gli Accordi quadro, aggiudicati da una centrale di committenza a più fornitori
  a seguito della pubblicazione di specifici bandi, definiscono le clausole
  generali (ad esempio corrispettivi unitari, SLA, …) che, in un determinato
  periodo temporale, regolano i contratti da stipulare. Nell’ambito dell’Accordo
  quadro, le amministrazioni provvedono poi, attraverso la contrattazione di
  appalti specifici, a negoziare i singoli contratti, personalizzati sulla base
  delle proprie esigenze (ad esempio quantità, caratteristiche specifiche, ...).

Account management
  Gestione account/credenziali accesso.

Appalto specifico
  Vedi Accordo quadro.

Asset management
  Gestione dei beni di proprietà di un’organizzazione.

Audit
  Processo indipendente di valutazione e verifica.

Change management
  Gestione del cambiamento

Code review
  Processo di revisione del codice/istruzioni di programmazione.

Firmware
  Programma, sequenza di istruzioni memorizzata sulla memoria non volatile di un
  componente elettronico.

Fleet management
  Servizio di locazione operativa, gestione e manutenzione di un parco di
  apparecchiature hardware, ad esempio postazioni di lavoro.

Hardening
  Processo che mira, attraverso operazioni di configurazione specifica di un
  dato sistema e dei suoi componenti, a minimizzare l'impatto di possibili
  vulnerabilità, migliorandone quindi la sicurezza complessiva.

Middleware
  Software che svolge funzioni di integrazione tra diverse applicazioni e
  componenti software che sono stati sviluppati con tecnologie diverse e/o
  utilizzano architetture diverse.

Penetration test
  Processo di valutazione della sicurezza di un sistema o di una rete
  attraverso la simulazione di un attacco.

Procurement ICT
  Attività di approvvigionamento di beni e servizi informatici.

Procurement management
  Gestione dei processi di approvvigionamento

Risk management
  Gestione dei rischi

Vulnerability assessment
  Processo di individuazione e classificazione delle vulnerabilità di sicurezza
  di un sistema o di una rete.

Web server
  Applicazione software installata su un server che gestisce le richieste di
  pagine web provenienti dai browser dei client (Browser Web).

Wiping
  Processo di cancellazione definitiva di dati contenuti su un supporto di
  memorizzazione, ad esempio da un Hard Disk.

Categorie di dati personali (dal GDPR)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Dati giudiziari
  Dati relativi alle condanne penali e ai reati o a connesse misure di
  sicurezza.

Dati identificativi
  Dati che possono identificare, direttamente o indirettamente una persona, con
  particolare riferimento a un identificativo come il nome, un numero di
  identificazione, dati relativi all'ubicazione, un identificativo online.

Dati Sensibili
  Dati personali che rivelano l’origine razziale o etnica, le opinioni
  politiche, le convinzioni religiose o filosofiche, l’appartenenza sindacale,
  nonché dati genetici, dati biometrici intesi a identificare in modo univoco
  una persona fisica, dati relativi alla salute o alla vita sessuale o
  all'orientamento sessuale della persona.


Acronimi
--------

BIA
  Business Impact analysis

CVCN
  Centro di valutazione e certificazione nazionale

CED
  Centro Elaborazione Dati

CAD
  Codice Amministrazione Digitale

CC
  Common Criteria

CERT
  Computer Emergency Response Team

CERT-PA
  Computer Emergency Response Team – Pubblica Amministrazione

CMS
  Content management system

CQ
  Contratto Quadro

DPIA
  Data Protection Impact Assessment

DBMS
  Database Management System

DIS
  Dipartimento delle informazioni per la sicurezza

EoL
  End of Life (fine vita)

GDPR
  General Data Protection Regulation - regolamento UE n. 679 del 2016

ICT
  Information and Communications Technology

IOC
  Indicator of Compromise

MEV
  Manutenzione Evolutiva

NSC
  Nucleo per la Sicurezza Cibernetica

OWASP
  Open Web Application Security Project

PCM
  Presidenza Consiglio Ministri

RTI
  Raggruppamento Temporaneo di Impresa

RACI-VS
  Responsible, Accountable, Consulted, Informed – Verifier, Signatory

RA
  Risk Assessment

SGSI
  Sistema di Gestione della Sicurezza delle Informazioni

SOC
  Security Operational Center

SLA
  Service Level Agreement - livelli di servizio

SIEM
  Sistema di gestione delle informazioni e degli eventi di sicurezza

VPN
  Virtual Private Network


Documenti di Riferimento
------------------------

DR-1
  | ISO 22317 - Linee guida per Business Impact Analysis
  | https://www.iso.org/standard/50054.html

DR-2
  | ISO 27001 - Sistema di Gestione della Sicurezza delle Informazioni
  | https://www.iso.org/isoiec-27001-information-security.html

DR-3
  | ISO 31000 Risk Management
  | https://www.iso.org/iso-31000-risk-management.html

DR-4
  | Linee guida sviluppo software sicuro
  | https://www.agid.gov.it/it/sicurezza/cert-pa/linee-guida-sviluppo-del-software-sicuro

DR-5
  | Misure minime di sicurezza AGID
  | https://www.agid.gov.it/it/sicurezza/misure-minime-sicurezza-ict

DR-6
  | ISO 15408 Standard Common Criteria
  | https://www.iso.org/standard/50341.html
