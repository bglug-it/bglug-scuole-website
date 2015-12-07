# Linux va a scuola

Il progetto **Linux va a scuola** ha come obiettivo supportare le scuole che
intendono creare o migrare i laboratori di informatica al sistema operativo
**GNU/Linux** ed al *software* **libero** e **_opensource_**.

Questo progetto è condotto dal [Bergamo Linux Users Group](http://www.bglug.it) in collaborazione con [LibreItalia](http://www.libreitalia.it).

Perché questa strana unione, Linux e la scuola? Al BgLUG, ma più in generale
in tutte le *community* che partecipano ai vari progetti *opensource*, c'è la
convinzione che **non può esistere conoscenza senza condivisione**, quindi ci
è sembrato logico mettere in contatto due mondi che fanno della condivisione e
della diffusione della conoscenza la filosofia portante del loro essere:
l'*opensource* e la scuola.

Perché una scuola dovrebbe essere interessata ad aderire al progetto oltre a
quanto sopra citato? Sarebbe facile dire per motivi economici, vista la
situazione delle casse scolastiche e visto che molte soluzioni *opensource*
sono gratuite, ma c'è molto di più. Alcuni dei motivi più importanti sono:

- **qualità**: le soluzioni offerte sono di altissima qualità ed utilizzate in
  ambiti scientifici (CERN di Ginevra, NASA), aziendali (Google, Facebook) e
istituzionali (Ministero Difesa Italiana, vari Ministeri francesi).  A titolo
di esempio un breve elenco dei programmi utilizzabili a scopo didattico:
    - editor di testi: *LibreOffice Writer*
    - fogli di calcolo: *LibreOffice Calc*
    - presentazioni: *LibreOffice Impress*
    - disegno artistico e fotoritocco: *GIMP*, *Pensil*, *Tux Paint*
    - disegno tecnico: *LibreCAD*, *QCAD*
    - diagrammi di flusso e mappe mentali: *Dia*, *Vym*
    - editor di grafica vettoriale: *Inkscape*
    - matematica e geometria: *Geogebra*
    - *desktop publishing* per realizzare volantini, giornalini ed altro:
      *Scribus*
    - elettronica: *Fritzing*
    - serie didattica per la scuola dell'infanzia: *GCompris*
    - astronomia: *Stellarium* (software utilizzato anche dal parco
      astronomico [La Torre del Sole](http://www.latorredelsole.it/) di
Brembate Sopra (BG))
- **sicurezza**: da sempre punto di forza di Linux, non richiede l'utilizzo di
  antivirus, troppo spesso poco aggiornati su altri sistemi operativi
- **aggiornamenti costanti**: gli aggiornamenti del sistema operativo e dei
  programmi installati sono costanti ed automatici, evitando che le soluzioni
installate diventino obsolete come spesso accade per quelle proprietarie se
non si pagano gli adeguamenti di livello
- **libertà**: libertà di scelta e uso tra una grande varietà di *software*,
  che permette di sperimentare e analizzare quale sia il software più adatta
alle proprie esigenze
- **legalità**: il software *opensource* è perfettamente licenziato e legale
- **recupero computer datati**: con Linux è possibile riutilizzare computer
  non recentissimi perché richiede meno risorse *hardware* rispetto alle
ultime versioni dei sistemi operativi proprietari. Attenzione: obsoleti non
significa del Mesozoico ;-)
- **aiuto per le famiglie**: gli stessi strumenti utilizzati a scuola potranno
  essere scaricati ed utilizzati dagli alunni a casa senza gravare sulle spese
delle famiglie
- **adeguamento tecnologico**: ad oggi molti laboratori delle scuole usano
  ancora il vecchissimo Windows XP che è stato dichiarato *morto* (non più
aggiornato) dalla Microsoft già dall'Aprile 2014
- **rispetto della legge**: l'Art. 68 della Direttiva Stanca (*Analisi
  comparativa delle soluzioni*) prevede che le Pubbliche Amministrazioni,
nella scelta dei programmi informatici, debbano seguire una precisa sequenza
in cui il **software libero** è prioritario rispetto a quello proprietario.

## Implementazione del progetto

Il progetto è stato dettagliato in due parti principali, una **formativa** e
una **tecnica**.

### Parte formativa

Per un progetto di migrazione al software libero/*opensource* come questo, è
importante realizzare che la migrazione comporta un cambiamento delle attività
formative legate all'informatica, a cui si aggiunge la comune assenza di
esperienza su sistemi operativi liberi. Per i docenti e per gli alunni,
equivale a trovarsi di fronte un laboratorio che nessuno saprebbe utilizzare.

Per questo il BgLUG ha previsto, già dalle prime fasi di attuazione del suo
progetto, una parte importante di formazione, che viene svolta con il
personale scolastico che si occupa della didattica (docenti) e con chi si
incaricherà di mantenere operativo il laboratorio.

In particolare, sono stati previsti i seguenti corsi:

* **Corso base**, di durata di circa 16 ore e curato dal BgLUG, che ha come
  destinatari tutti i docenti che utilizzeranno il laboratorio e ha
l'obiettivo di spiegare come utilizzare un sistema operativo libero e come
utilizzare le peculiarità della nostra implementazione per poter lavorare
meglio.
* __Corso di *office automation*__, di durata di circa 20 ore e curato da
  [LibreItalia](http://www.libreitalia.it/), che ha come destinatari tutti i
docenti e come obiettivo l'uso corretto e consapevole della *suite* di
produttività d'ufficio [LibreOffice](http://www.libreoffice.org).
* **Corso specifico** di durata di circa 2 ore per ciascun programma e curato
  dal BgLUG, che ha come destinatari i docenti che faranno richiesta di
approfondire l'utilizzo di un programma specifico. Il BgLUG si impegnerà
pertanto a studiare ed analizzare il programma richiesto, così da poter
essere di supporto alla didattica.
* **Corso tecnico**, della durata di circa 10 ore e curato dal BgLUG, i cui
  destinatari saranno i responsabili del laboratorio, in cui si formeranno
tali persone per gestire correttamente la manutenzione del laboratorio e la
risoluzione dei principali problemi che potrebbero riscontrarsi.

Resta inteso che il BgLUG ritiene di primaria importanza la parte formativa
del progetto: all'interno dello stesso BgLUG erano già stati proposti
interventi di migrazione che però non sono stati mediati e finalizzati con una
parte formativa e il loro risultato, per questi motivi, non è stato sempre
positivo.

### Parte tecnica

L'implementazione tecnica del progetto include le seguenti fasi:

* Sopralluogo per verifica delle caratteristiche *hardware* delle macchine in
  laboratorio. Verifica delle condizioni di network per il laboratorio;
* Determinazione dello scenario di installazione migliore per l'infrastruttura
  del laboratorio a disposizione;
* Conclusione dei lavori pendenti di adeguamento della struttura del
  laboratorio secondo i requisiti del singolo scenario;
* Installazione e configurazione del server, necessario per le attività di
  laboratorio e sulla base dello scenario determinato al punto precedente;
* Installazione e configurazione dei client, dove possibile in maniera
  semi-automatica;
* Verifica degli obiettivi tecnici del progetto.

L'installazione e la configurazione del server, dei client e della rete del
laboratorio viene portata a termine solitamente prima dell'inizio della parte
formativa, per poter aver a disposizione il laboratorio nella sua forma
definitiva già in fase di formazione.

Il progetto prevede due possibilità di installazione, che noi chiamiamo
*scenari* (installazione client/server o installazione basata su *Terminal
Server*); hanno tuttavia obiettivi tecnici comuni:

* **Autenticazione centralizzata**
  Ricalcando quanto succede in ambienti *enterprise*, dove gli accessi alle
risorse disponibili a tutti all'interno di una infrastruttura sono gestiti da
un singolo punto, alla stessa maniera la nostra soluzione prevede la
possibilità di gestire da un unico punto la creazione di una utenza del
laboratorio, la sua modifica e il cambio della password da parte
dell'amministratore, oltre alla concessione di permessi sull'intera
infrastruttura o su parte di essa;

* **Condivisione dei file**
  La condivisione è parte integrante del nostro progetto e una caratteristica
fondamentale nel contesto della classe. La nostra soluzione permette la
condivisione dei file utilizzando protocolli ispirati a quelli in uso nelle
aziende e compatibili con altri sistemi operativi proprietari, proprio per
permettere maggiormente la condivisione dei file;

* **Filtraggio web efficace**
  È importante consapevolizzare gli studenti sulla natura non sempre positiva
e istruttiva dei siti disponibili sul web. Riteniamo fondamentale mettere a
disposizione un ambiente sicuro e fidato per la didattica in laboratorio,
attivando sistemi di filtraggio del traffico web che tengano in debito conto
le indicazioni di legge e delle necessità specifiche della singola classe. La
nostra soluzione prevede infatti alcuni filtri web che sono personalizzabili
con pochi clic dall'amministratore della rete;

* **Ottimizzazione della banda della connettività**
  Considerando che spesso la connettività a disposizione delle scuole risulta
essere insufficiente alle esigenze di navigazione dei suoi studenti, la nostra
soluzione implementa un sistema di ottimizzazione del consumo di banda in
uscita;

* **Backup efficiente dei dati del laboratorio**
  Sappiamo tutti quanto siano importanti le copie di salvataggio dei propri
file e di quanto questa pratica possa essere fondamentale per conservare i
propri dati. La nostra soluzione implementa sistemi di backup efficiente e di
semplice utilizzo per l'amministratore, in modo da aiutarlo nell'importante
compito di gestione del laboratorio.

La soluzione, pur essendo ad elevato contenuto tecnologico, è stata studiata in modo che il laboratorio possa essere gestito anche da persone senza particolari competenze tecniche.

## Come aderire e cosa serve

Qualunque scuola voglia aderire, può scriverci una mail all'indirizzo
[<tt>info(at)bglug.it</tt>](mailto:info[at]bglug.it), oppure venire a trovarci
qualunque mercoledì sera (dopo le ore 21:00) presso lo [Spazio
Polaresco](http://giovani.bg.it/spazio-polaresco/) di Bergamo.

Cosa serve? Tanta buona volontà, al resto ci pensiamo quando ci si incontra.

## Vuoi partecipare?

Sei un genitore, un insegnante, un appassionato di Linux o comunque un
cittadino volenteroso e vuoi darci una mano? Vieni a trovarci il mercoledì e
parliamone ;-)
...lo spirito del progetto è anche questo!!!

