Appendice A – Requisiti di sicurezza eleggibili
===============================================

Nelle tabelle che seguono sono elencati alcuni requisiti di sicurezza che le
amministrazioni possono inserire nei propri capitolati di gara. L’elenco non è
esaustivo, ha solo lo scopo di offrire alcuni esempi significativi e di favorire
un lessico comune nell’esprimere requisiti di sicurezza.

Per ragioni di sintesi, il testo di alcuni requisiti (ad esempio di R1) è stato
generalizzato in modo da renderlo un modello per una “famiglia di requisiti”, da
declinare ed eventualmente suddividere in più requisiti elementari, a seconda
del contesto della singola acquisizione.

.. table:: Requisiti generali (indipendenti dalla tipologia di fornitura)
   :name: requisiti-generali

   +-----+------------------------------------------------------------------+
   | R1  | Il fornitore deve adottare al proprio interno le procedure e     |
   |     | politiche di sicurezza definite dall’amministrazione             |
   |     | committente, con particolare riferimento alle modalità di        |
   |     | accesso ai sistemi dell’amministrazione, all’hardening (esempio  |
   |     | installazione di soluzioni di end point security) dei            |
   |     | dispositivi utilizzati dal fornitore, alla gestione dei dati     |
   |     | dell’amministrazione.                                            |
   +-----+------------------------------------------------------------------+
   | R2  | Il fornitore deve possedere la certificazione ISO/IEC 27001 e    |
   |     | mantenerla per tutta la durata della fornitura.                  |
   +-----+------------------------------------------------------------------+
   | R3  | (alternativo al precedente) Anche se il fornitore non è          |
   |     | certificato ISO/IEC 27001, almeno deve usare un Sistema di       |
   |     | Gestione della Sicurezza delle Informazioni (SGSI) aggiornato    |
   |     | nel tempo.                                                       |
   +-----+------------------------------------------------------------------+
   | R4  | Il fornitore deve far eseguire annualmente un audit sul proprio  |
   |     | sistema di sicurezza, a proprie spese e da una società           |
   |     | specializzata scelta previa approvazione della stazione          |
   |     | appaltante. NB: Qualora applicabile, tale attività si incrocia   |
   |     | con il requisito R2 (le verifiche dell’Ente Certificatore hanno  |
   |     | cadenza pressoché annuale).                                      |
   +-----+------------------------------------------------------------------+
   | R5  | L’amministrazione può, con un preavviso di 20 giorni solari,     |
   |     | richiedere ulteriori attività di auditing secondo modalità       |
   |     | concordate con il fornitore. Le risultanze di tali audit         |
   |     | verranno comunicate all’amministrazione.                         |
   +-----+------------------------------------------------------------------+
   | R6  | L’amministrazione, direttamente o tramite terzi incaricati, può  |
   |     | eseguire verifiche relative alla conformità della prestazione    |
   |     | dei servizi rispetto a quanto stabilito nel capitolato tecnico   |
   |     | oltre che nell’offerta tecnica se migliorativa.                  |
   +-----+------------------------------------------------------------------+
   | R7  | Il personale del fornitore che presta supporto operativo         |
   |     | nell’ambito dei servizi di sicurezza dovrà possedere             |
   |     | certificazione su specifici aspetti della sicurezza.             |
   +-----+------------------------------------------------------------------+
   | R8  | Il fornitore deve disporre di una struttura per la prevenzione e |
   |     | gestione degli incidenti informatici con il compito              |
   |     | d’interfacciarsi con le analoghe strutture dell’amministrazione  |
   |     | e con le strutture centrali a livello governativo.               |
   +-----+------------------------------------------------------------------+
   | R9  | Il fornitore deve dotarsi delle misure minime di sicurezza per   |
   |     | limitare il rischio di attacchi informatici (riferimento DR-5)   |
   +-----+------------------------------------------------------------------+
   | R10 | Il SOC del fornitore deve sovrintendere alla gestione operativa  |
   |     | e continuativa degli incidenti informatici sui servizi erogati   |
   |     | nell’ambito della fornitura\ `. <https://it.wikiped              |
   |     | ia.org/wiki/Security_Operation_Ce nter>`__                       |
   +-----+------------------------------------------------------------------+
   | R11 | Il fornitore deve garantire il rispetto di quanto richiesto      |
   |     | dalla normativa vigente in materia di sicurezza cibernetica,     |
   |     | anche in riferimento ai contenuti del GDPR.                      |
   +-----+------------------------------------------------------------------+
   | R12 | Sulle reti messe a disposizione dal fornitore devono essere      |
   |     | presenti di dispositivi di sicurezza perimetrale con funzioni di |
   |     | sicurezza (ad esempio Firewall e sistemi di Network Detection ed |
   |     | Event & Log Monitoring, SIEM, ecc.) necessari a rilevare e       |
   |     | contenere eventuali incidenti di sicurezza ICT e in grado di     |
   |     | gestire gli IoC (Indicator of Compromise).                       |
   +-----+------------------------------------------------------------------+
   | R13 | Il fornitore deve usare protocolli cifrati e meccanismi di       |
   |     | autenticazione nell’ambito dei servizi erogati.                  |
   +-----+------------------------------------------------------------------+
   | R14 | Qualora il fornitore subisca un attacco, in conseguenza del      |
   |     | quale vengano compromessi sistemi del committente da lui         |
   |     | gestiti, deve farsi carico delle bonifiche del caso, e riportare |
   |     | i sistemi in uno stato di assenza di vulnerabilità.              |
   +-----+------------------------------------------------------------------+
   | R15 | Il fornitore si impegna a trattare, trasferire e conservare le   |
   |     | eventuali repliche dei dati oggetto di fornitura, ove            |
   |     | autorizzate dalle amministrazioni, sempre all’interno del        |
   |     | territorio dell’UE.                                              |
   +-----+------------------------------------------------------------------+
   | R16 | Il fornitore deve dare disponibilità a far parte di un Comitato  |
   |     | di Direzione Tecnica, eventualmente aperto anche a soggetti      |
   |     | terzi, che tratti il tema della sicurezza, sia nell’ottica di    |
   |     | favorire la risoluzione di temi aperti sia per introdurre        |
   |     | eventuali varianti al contratto per fronteggiare nuove minacce o |
   |     | altro.                                                           |
   +-----+------------------------------------------------------------------+
   | R17 | Il fornitore deve condividere le informazioni necessarie al fine |
   |     | di garantire il corretto monitoraggio della qualità e della      |
   |     | sicurezza, eventualmente pubblicando le stesse nel portale della |
   |     | fornitura.                                                       |
   +-----+------------------------------------------------------------------+
   | R18 | Il fornitore si impegna a sottoscrivere una clausola di non      |
   |     | divulgazione (NDA) sui dati e sulle informazioni                 |
   |     | dell’amministrazione.                                            |
   +-----+------------------------------------------------------------------+
   | R19 | Le soluzioni e i servizi di sicurezza proposti dal fornitore     |
   |     | devono essere aggiornati dal punto di vista tecnologico, con     |
   |     | riferimento all’evoluzione degli standard e del mercato; devono  |
   |     | essere conformi alle normative e agli standard di riferimento    |
   |     | applicabili; devono venire adeguati nel corso del contratto,     |
   |     | senza oneri aggiuntivi, alle normative che l’UE o l’Italia       |
   |     | rilasceranno in merito a servizi analoghi.                       |
   +-----+------------------------------------------------------------------+


.. table:: Requisiti specifici per forniture di servizi di sviluppo applicativo
   :name: requisiti-specifici-sviluppo-applicativo

   +-----+-----------------------------------------------------------------+
   | R20 | Il fornitore deve attenersi alla politica di sicurezza          |
   |     | dell’amministrazione committente, con particolare riferimento   |
   |     | all’accesso ai dati dell’amministrazione, che avverrà           |
   |     | esclusivamente sui sistemi di sviluppo e test.                  |
   +-----+-----------------------------------------------------------------+
   | R21 | In fase di analisi, il fornitore deve definire le specifiche di |
   |     | sicurezza (non funzionali) a partire dai requisiti espressi     |
   |     | dall’amministrazione.                                           |
   +-----+-----------------------------------------------------------------+
   | R22 | In fase di progettazione codifica, il fornitore deve            |
   |     | implementare le specifiche di sicurezza nel codice e nella      |
   |     | struttura della basedati.                                       |
   +-----+-----------------------------------------------------------------+
   | R23 | Al termine del progetto, il fornitore deve rilasciare tutta la  |
   |     | documentazione necessaria all’amministrazione per gestire       |
   |     | correttamente quanto rilasciato anche sotto l’aspetto della     |
   |     | sicurezza.                                                      |
   +-----+-----------------------------------------------------------------+


.. table:: Requisiti specifici per forniture di oggetti connessi in rete
   :name: requisiti-specifici-oggetti-in-rete

   +-----+-----------------------------------------------------------------+
   | R24 | Supporto di protocolli sicuri e cifrati (HTTPS, SSH v2, ecc.).  |
   +-----+-----------------------------------------------------------------+
   | R25 | Filtraggio di indirizzi IP.                                     |
   +-----+-----------------------------------------------------------------+
   | R26 | Supporto di protocolli di autenticazione (ad esempio RADIUS,    |
   |     | IEEE 802.1X, ecc.).                                             |
   +-----+-----------------------------------------------------------------+
   | R27 | Gestione di più profili con privilegi diversi.                  |
   +-----+-----------------------------------------------------------------+
   | R28 | Funzionalità di “richiesta creazione o cambio della password al |
   |     | primo accesso”.                                                 |
   +-----+-----------------------------------------------------------------+
   | R29 | Blocco dell’utenza dopo un numero definito (fisso o variabile)  |
   |     | di tentativi falliti di accesso.                                |
   +-----+-----------------------------------------------------------------+
   | R30 | Gli accessi degli utenti devono essere registrati su un         |
   |     | archivio (log) non cancellabile con il reset.                   |
   +-----+-----------------------------------------------------------------+
   | R31 | Gestione dei log di sistema (accessi, allarmi, ecc.).           |
   +-----+-----------------------------------------------------------------+
   | R32 | Il fornitore (anche in collaborazione con il produttore della   |
   |     | tecnologia) deve offrire processi, unità organizzative e        |
   |     | strumenti dedicati alla gestione di vulnerabilità scoperte sui  |
   |     | prodotti oggetto della fornitura.                               |
   +-----+-----------------------------------------------------------------+
   | R33 | Per gli apparati proposti deve essere disponibile               |
   |     | documentazione tecnica (schede tecniche, manuali, guide         |
   |     | operative) relativa alla corretta configurazione e gestione     |
   |     | degli aspetti di sicurezza.                                     |
   +-----+-----------------------------------------------------------------+
   | R*  | Il fornitore (anche in collaborazione con il produttore         |
   |     | della tecnologia) è tenuto a fornire indicazione delle          |
   |     | certificazioni di sicurezza (Common Criteria, FIPS, etc) che il |
   |     | prodotto oggetto della fornitura ha ottenuto da laboratori      |
   |     | indipendenti in Italia e all'estero.                            |      
   +-----+-----------------------------------------------------------------+
   | R*  | Il prodotto oggetto della fornitura dispone di un ambiente di   |
   |     | esecuzione attendibile (Trusted Execution Environment) a        |
   |     | livello hardware (System on Chip) per fornire una sicurezza     |
   |     | avanzata applicabile al Sistema Operativo, ai Servizi erogati   |
   |     | dalla piattaforma ed alle applicazioni di terze parti.          |                   
   +-----+-----------------------------------------------------------------+
.. table:: Requisiti specifici per forniture di servizi di gestione remota
   :name: requisiti-specifici-gestione-remota

   +-----+-----------------------------------------------------------------+
   | R34 | I meccanismi di autenticazione devono essere basati su          |
   |     | meccanismi di crittografia asimmetrica, a chiave pubblica; la   |
   |     | lunghezza delle chiavi va impostata sulla base della criticità  |
   |     | della comunicazione da cifrare (ad esempio 256 bit per le meno  |
   |     | critiche, 512 bit per le più critiche). La gestione e           |
   |     | distribuzione delle chiavi e dei certificati è a carico del     |
   |     | fornitore.                                                      |
   +-----+-----------------------------------------------------------------+
   | R35 | Autorizzazione: sulla base delle credenziali fornite            |
   |     | dall’utente, si devono individuare i diritti e le               |
   |     | autorizzazioni che l’utente possiede e permetterne l’accesso    |
   |     | alle risorse limitatamente a tali autorizzazioni.               |
   +-----+-----------------------------------------------------------------+
   | R36 | Confidenzialità nella trasmissione dei dati: le comunicazioni   |
   |     | tra la componente di gestione remota centralizzata e la         |
   |     | componente locale installata presso la sede                     |
   |     | dell’amministrazione devono essere cifrate.                     |
   +-----+-----------------------------------------------------------------+
   | R37 | Fornire meccanismi che permettano di garantire l'integrità di   |
   |     | quanto trasmesso (ad esempio meccanismi di hashing).            |
   +-----+-----------------------------------------------------------------+
   | R38 | Il fornitore deve descrivere nel dettaglio le soluzioni         |
   |     | tecniche utilizzate (dispositivi hardware e software impiegato, |
   |     | modalità operative, politiche di sicurezza, …) per soddisfare i |
   |     | requisiti di sicurezza dell’amministrazione committente.        |
   +-----+-----------------------------------------------------------------+
   | R39 | In fase di attivazione del servizio, il fornitore deve          |
   |     | concordare con l’amministrazione le modalità operative e le     |
   |     | politiche di sicurezza, i livelli di gravità degli incidenti,   |
   |     | le attività e le contromisure che dovranno essere svolte per    |
   |     | contrastare le minacce.                                         |
   +-----+-----------------------------------------------------------------+
   | R40 | Il fornitore dovrà attenersi alle politiche di sicurezza        |
   |     | definite dalla committente, con particolare riferimento alla    |
   |     | definizione di ruoli e utenze per l’accesso ai sistemi gestiti. |
   +-----+-----------------------------------------------------------------+
   | R41 | In caso di necessità, da parte degli operatori, di accesso a    |
   |     | Internet, il fornitore deve utilizzare un proxy centralizzato e |
   |     | dotato di configurazione coerente con la politica di sicurezza  |
   |     | definita dall’amministrazione.                                  |
   +-----+-----------------------------------------------------------------+
   | R42 | In caso di rilevazione di un incidente di gravità elevata (con  |
   |     | scala da definire a inizio fornitura), il fornitore deve dare   |
   |     | immediata notifica, tramite canali concordati con               |
   |     | l’amministrazione, dell’incidente rilevato e delle azioni da    |
   |     | intraprendere, al Responsabile della Sicurezza indicato         |
   |     | dall’amministrazione e al CERT-PA.                              |
   +-----+-----------------------------------------------------------------+
   | R43 | Per ogni incidente di sicurezza, il fornitore s’impegna a       |
   |     | consegnare all’amministrazione, entro il giorno successivo, un  |
   |     | report che descriva la tipologia di attacco subito, le          |
   |     | vulnerabilità sfruttate, la sequenza temporale degli eventi e   |
   |     | le contromisure adottate.                                       |
   +-----+-----------------------------------------------------------------+
   | R44 | Su richiesta dell’amministrazione, il fornitore deve consegnare |
   |     | i log di sistema generati dai dispositivi di sicurezza          |
   |     | utilizzati, almeno in formato CSV o TXT. Tali log dovranno      |
   |     | essere inviati all’amministrazione entro il giorno successivo a |
   |     | quello in cui è avvenuta la richiesta.                          |
   +-----+-----------------------------------------------------------------+
   | R45 | Il fornitore deve monitorare la pubblicazione di                |
   |     | upgrade/patch/hotfix necessari a risolvere eventuali            |
   |     | vulnerabilità presenti nei dispositivi utilizzati per erogare i |
   |     | servizi e nelle infrastrutture gestite. Entro il giorno         |
   |     | successivo al rilascio dell’upgrade/patch/hotfix, il fornitore  |
   |     | deve avviare una valutazione, da rilasciarsi entro un numero    |
   |     | giorni da stabilirsi, propedeutica all’installazione delle      |
   |     | stesse sui dispositivi di sicurezza, che ad esempio identifichi |
   |     | la possibilità di applicare la patch immediatamente, o la       |
   |     | necessità di apportare MEV o integrazioni prima di procedere    |
   |     | alle installazioni.                                             |
   +-----+-----------------------------------------------------------------+

.. discourse::
   :topic_identifier: 9706
