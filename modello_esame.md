---
title: Titolo Materiale Didattico
author: Riccardo Benedetti
date: 23/08/24
---

Esame di Didattica dell'Informatica, A.A. 2023/2024

# Changelog (se necessario)

Se questa relazione è stata già consegnata in precedenza, indicare qui

* i cambiamenti più significativi
* dove trovare un eventuale diff (se ritenuto necessario)
* risposte a eventuali domande/commenti fatti dai docenti sulle versioni precedenti

# Inquadramento del lavoro

## Livello di scuola, classe/i, indirizzo
A chi è rivolta questa attività?

La lezione è rivolta agli studenti del triennio del liceo scientifico o dell'istituto tecnico ad indirizzo informatico. L'attività si colloca prevalentemente nell'ambito della disciplina di Informatica, con un focus particolare su reti e sicurezza informatica.

In quale specifica disciplina scolastica (o le discipline, ovviamente
l'informatica deve essere la disciplina prevalente) si colloca 
l'attività?

- Per la scuola dell'infanzia / primaria / scuole \"medie\" si può fare riferimento a una delle discipline nelle Indicazioni Nazionali, nei Nuovi Scenari, e/o alla disciplina Informatica dalla Proposta CINI
- Per le scuole secondarie di secondo grado (superiori), fare riferimento ai documenti ministeriali (e secondariamente alla Proposta CINI)

L'attività si colloca prevalentemente nell'ambito delle Tecnologie, con un focus particolare su reti e sicurezza informatica.
In particolare, rifacendoci alla proposta CINI le competenze che verranno coperte dalla lezione sono[^1]:
- Ambito Consapevolezza Digitale
    * Sicurezza Informatica: Gli studenti impareranno l'importanza della sicurezza informatica e la protezione dei dati.
    * Uso consapevole della tecnologia: Saranno consapevoli dei modi appropriati/inappropriati, sicuri/pericolosi e responsabili/irresponsabili di usare la tecnologia informatica​
- Ambito Programmazione
    * Durante l'utilizzo di metasploit gli studenti dovranno scrivere comandi che applicano selezioni cicli e variabili.
- Ambito Algoritmi
    * Attraverso la pratica di attacchi e difese, comprenderanno la logica e il funzionamento di algoritmi di rete e sicurezza, applicando ragionamento logico per spiegare il funzionamento di questi algoritmi.
    * Risolveranno problemi complessi scomponendoli in parti più piccole, tipica attività nel processo di penetrazione e testing delle reti.

Può essere---adattata---rivolta a studenti di diverse età e indirizzi?

L'attività può essere modificata se gli studenti possiedono già le competenze necessarie per svolgerla. Idealmente, ci aspettiamo che uno studente idoneo a partecipare frequenti un liceo scientifico o un istituto tecnico con insegnamenti di base in informatica (come l'utilizzo del terminale Linux o della console PowerShell/Windows). Tuttavia, l'attività potrebbe risultare adatta anche a studenti di altri istituti.

[^1]: Proposta CINI per l'insegnamento dell'informatica nelle scuole: https://www.consorzio-cini.it/index.php/it/component/attachments/download/745

## Motivazione e Finalità
Spiegare brevemente (una sola frase) di che attività si tratta.

La lezione propone un'attività di cybersecurity gamificata, dove gli studenti, organizzati in squadre, competono per raggiungere specifici traguardi.

Perché è importante svolgere questa attività nella scuola?

Insegnare questa attività nelle scuole è importante perché introduce in modo pratico e coinvolgente i concetti di sicurezza informatica e l'uso degli strumenti di penetration testing, argomenti che normalmente non fanno parte di un programma di studi tradizionale.
\
La realizzazione dell'attività potrebbe avvicinare sia studenti curiosi sia coloro meno esperti a una disciplina come la cybersecurity, che generalmente non viene insegnata nelle scuole e risulta difficile da comprendere a causa della sua descrizione spesso vaga.
\
Un approccio simulato ma comunque "sul campo", come quello proposto dall'attività, può aiutare a chiarire le idee a uno studente interessato alla cybersecurity, ma che non ha ancora compreso appieno di cosa si tratti.


## Innovatività
Perché questa proposta è innovativa? Cosa è già presente su questo tema nella ricerca in Didattica dell'Informatica o nelle risorse disponibili online (è obbligatorio cercare risultati scientifici e risorse didattiche già presenti, e descriverli brevemente) e in cosa si differenzia/cosa mantiene/cosa va a migliorare questa proposta?

Questa proposta è innovativa in quanto integra l'elemento della gamification, rendendo l'apprendimento della sicurezza informatica più coinvolgente e pratico rispetto a metodi tradizionali.
\
Rispetto alle risorse didattiche esistenti, che spesso si limitano a lezioni frontali o laboratoriali senza competizione, questa lezione aggiunge un elemento competitivo che stimola la partecipazione attiva e l'applicazione pratica delle conoscenze teoriche.

## Prerequisiti
Elencare i contenuti che si suppone siano già stati svolti e appresi dagli studenti

Gli studenti dovrebbero avere una conoscenza molto basilare dei concetti di rete, e una familiarità preliminare con l'utilizzo del terminale di Linux. È utile. ma non richiesta anche una conoscenza introduttiva dei concetti di sicurezza informatica e vulnerabilità.
### Percorso
Se si ipotizza che questa attività sia parte di un percorso ampio (troppo ampio per entrare tutto nella relazione) sullo stesso tema, descrivere qui il percorso in modo schematico/sintetico.
Indicare su quali parti del percorso si concentrerà la relazione.

L'attività potrebbe essere inclusa in un percorso più ampio sulla sicurezza informatica, in questa particolare lezione, ci si concentra sulla fase di penetration testing.

## Contenuti (spiegati a un informatico)
Se si tratta di contenuti banalmente chiari per un informatico (e.g. riguardanti esami obbligatori della triennale), elencarli semplicemente.
Se l'attività riguarda contenuti specifici o particolari (es. elaborazione immagini, crittografia, computazione quantistica, specifiche tecniche di IA, ...) illustrarli brevemente o fornire link, avendo in mente (solo in questa breve sezione) di spiegarli ad un informatico.

Gli studenti utilizzeranno Kali Linux [^2], Metasploit [^3] e Metasploitable2[^4], tre strumenti fondamentali nel penetration testing. Kali Linux è una distribuzione basata su Linux progettata per la sicurezza informatica, con una vasta gamma di strumenti preinstallati per testare la sicurezza dei sistemi. Metasploit è un framework che fornisce informazioni sugli exploit noti e consente di eseguire test di sicurezza. Metasploitable 2 é una distribuzione di Linux intenzionalmente vulnerabile, utilizzata per fare pratica con la sicurezza informatica.

[^2]: "Kali Linux Documentation." https://www.kali.org/docs/
\
[^3]: "Metasploit Framework Documentation." https://docs.metasploit.com/
\
[^4]: "Metasploitable2." https://docs.rapid7.com/metasploit/metasploitable-2//

## Grandi idee
Se ha senso per il materiale proposto, descrivere brevemente (qualche frase) quali sono le "grandi idee" (come spiegato a lezione) che questa attività vuole insegnare.

L'attività insegna le grandi idee del penetration testing etico, dell'analisi delle vulnerabilità, e dell'importanza di testare la sicurezza dei sistemi informatici per prevenire attacchi malevoli.
## Traguardi e Obiettivi
Nelle varie sottosezioni, vanno elencati traguardi e obiettivi di apprendimento che si vuole raggiungere con le attività proposte


E' possibile (ma non obbligatorio e non sempre necessario) aggiungere i propri traguardi e obiettivi generali

Indicare quali traguardi/obiettivi generali presenti nei documenti rilevanti vengono
raggiunti (es. Indicazioni nazionali per il primo ciclo,
Proposta CINI numerata, Indicazioni nazionali / linee guida per scuola
secondaria di secondo grado).

Traguardi/obiettivi generali dai documenti ministeriali/proposte

    1.Comprensione e utilizzo delle tecniche di base di sicurezza informatica.
    2.Applicazione delle conoscenze teoriche a situazioni pratiche.
    3.Sviluppo delle capacità di problem solving e pensiero critico.


### Obiettivi specifici in forma operativa
Gli obiettivi vanno scritti ipotizzando che inizino tutti con "Lo studente/la studentessa è in grado di...",
seguendo la tassonomia di Bloom rivisitata (o le altre tassonomie mostrate),
e facendo attenzione a non cadere negli errori tipici, come spiegato in classe.

1.Lo studente è in grado di identificare e utilizzare alcuni strumenti di Kali Linux e Metasploit.
\
2.Lo studente è in grado di effettuare una scansione di rete per identificare indirizzi IP e servizi attivi.
\
3.Lo studente è in grado di eseguire alcuni attacchi su una macchina virtuale Metasploitable2.
\
4.Lo studente ottiene una panoramica sulla cybersecurity, che apre a possibilitá di approfondimento.

## Metodologie didattiche
Indicare quali metodologie didattiche si utilizzano - sia quelle più generali (es. lezione frontale, dialogata, cooperative learning, flipped classroom) sia quelle specifiche (es. unplugged, pair-programming) citate o discusse a lezione - e spiegarle brevemente.


Massima libertà di introdurre altre metodologie non spiegate a lezione, debitamente corredate di chiara spiegazione e riferimenti bibliografici.

Se si parla di didattica della programmazione, fare anche riferimento ai relativi concetti (macchina concettuale, misconcezioni, visualizzazione, program comprehension, ...) spiegati a lezione.

La lezione utilizza un approccio di gamification, in cui gli studenti competono in squadre per completare obiettivi specifici.


Questo metodo stimola l'apprendimento attivo e collaborativo, con elementi di apprendimento basato su progetti (PBL) Le spiegazioni teoriche saranno integrate con esercitazioni pratiche.

L'apprendimento collaborativo puó inoltre aiutare studenti che possono trovarsi piú in difficoltá, avendo un modo diretto con cui interfacciarsi con i proprio compagni.
## Tempi
Un'idea generale e indicativa dei tempi richiesti

La lezione è progettata per essere svolta in un arco di tempo di 2-3 ore, includendo una breve introduzione teorica, e una fase di competizione.
## Spazi
Classe, laboratorio, cortile...

L'attività richiede l'uso di un laboratorio informatico equipaggiato con computer in grado di eseguire Kali Linux, o una configurazione di macchine virtuali adeguata.
## Materiali e Strumenti
Quali materiali e strumenti (hardware e software, di ogni tipo, non solo informatico) sono necessari?

1.Computer con Kali Linux installato o accesso a macchine virtuali con Kali Linux.
\
2.Accesso a internet per aggiornamenti e ricerche.
\
3.Documentazione su Metasploit e su tecniche di penetration testing.
# Sviluppo dei contenuti
*Questa deve essere la parte più corposa del documento.*

Viene lasciata a voi massima libertà su come organizzarla.
Deve contenere almeno:
1. Guida per gli insegnanti, deve contenere almeno:
    * Indicazione chiara delle varie fasi dell'attività (o delle attività) e consigli su come utilizzare il materiale didattico. E' possibile inframezzarli al materiale didattico per studenti (ma in tal caso rendere esplicito e facile capire cosa è solo per l'insegnante e cosa invece può/deve essere dato agli studenti)
    * Suggerimenti su come valutare il raggiungimento degli obiettivi di apprendimento da voi individuati (focus non tanto sui voti, ma su valutazione formativa e continuativa)
2. Materiale didattico per studenti, se si pensa di fornirlo (es. slide, esercizi, schede, riassunti...)

La descrizione dovrebbe essere sufficientemente completa e dettagliata da consentire ad un insegnante di replicare l'esperienza senza sforzo (anche se poi starà al bravo insegnante eventualmente modificarla e adattarla al proprio contesto).


Per completare la sezione **Sviluppo dei contenuti** del tuo documento in maniera prolissa e precisa, ecco una proposta strutturata in modo tale da fornire agli studenti e agli insegnanti una guida dettagliata per l'attività di cybersecurity. La sezione è divisa in due parti principali: una guida per gli insegnanti e il materiale didattico per gli studenti.



## 1. Guida per gli insegnanti

### 1.1 Fasi dell'attività

#### Fase 1: Introduzione teorica (30 minuti)
L'attività inizia con una lezione frontale introduttiva di circa 30 minuti in cui vengono introdotti i concetti chiave di cybersecurity, l'uso di Kali Linux e Metasploit, e l'importanza del penetration testing. Durante questa fase, gli insegnanti dovrebbero:
- Spiegare brevemente cosa si intende per sicurezza informatica e quali sono le principali minacce (es. malware, phishing, attacchi DDoS).
- Introdurre gli strumenti che verranno utilizzati durante l'attività (Kali Linux, Metasploit, Metasploitable 2) spiegando le loro funzioni principali.
- Mostrare esempi pratici di attacchi informatici e le tecniche di difesa, utilizzando video o dimostrazioni live.

**Consigli per l'insegnante:** Utilizzare presentazioni visive, come slide, per mantenere alta l'attenzione degli studenti. Includere domande interattive per verificare la comprensione.

#### Fase 2: Ambientamento e familiarizzazione con l'ambiente (20 minuti)

In questa fase, gli studenti si familiarizzano con l'ambiente di lavoro preconfigurato, che include Kali Linux e Metasploitable 2. L'obiettivo è permettere loro di acquisire confidenza con gli strumenti che utilizzeranno durante l'attività pratica.

    Obiettivo: Gli studenti esploreranno l'interfaccia di Kali Linux e verificheranno il corretto funzionamento di Metasploit e Metasploitable 2. Saranno guidati nell'uso dei comandi base e delle funzionalità principali di Metasploit.

    Attività guidata:
    Esplorazione dell'interfaccia: L'insegnante guiderà gli studenti attraverso l'interfaccia di Kali Linux, spiegando brevemente le diverse sezioni (es. terminale, menu delle applicazioni, cartelle di sistema).
    Verifica degli strumenti: Gli studenti eseguiranno alcuni comandi base nel terminale di Kali Linux per assicurarsi che tutto funzioni correttamente. Per esempio, verificheranno la connessione alla rete e lanceranno Metasploit per un rapido controllo della sua operatività.
    Prima scansione: Gli studenti eseguiranno una semplice scansione di rete con nmap per vedere in azione uno degli strumenti principali e capire come identificare dispositivi e servizi attivi nella rete.

Consigli per l'insegnante: Fornire un elenco di comandi e funzionalità essenziali con una breve descrizione. Assicurarsi che tutti gli studenti abbiano familiarizzato con l'ambiente prima di procedere alla fase successiva. Se necessario, rispondere a eventuali domande o dubbi che gli studenti potrebbero avere riguardo all'uso degli strumenti.

#### Fase 3: Svolgimento dell'attività pratica (1 ora e 30 minuti)
Gli studenti lavorano in squadre per completare una serie di obiettivi utilizzando Kali Linux e Metasploit. 
Si consigliano degli obiettivi concreti ma non troppo complicati, ad esempio:
- Eseguire una scansione di rete per identificare i dispositivi, i servizi attivi e le loro vulnerabilitá.
- Sfruttare le vulnerabilità di Metasploitable 2 per ottenere l'accesso root.
- Sfruttare le vulnerabilitá dei server presenti nella macchina per ottenerne accesso.

[^1]: "Metasploitable2 Exploitability Guide." https://docs.rapid7.com/metasploit/metasploitable-2-exploitability-guide/
\
Gli studenti, dovranno poi documentare ogni passaggio effettuato, e ne discuteranno con l'insegnante al termine dell'attivitá.


**Consigli per l'insegnante:** Fornire un elenco di vulnerabilità comuni che gli studenti possono cercare di sfruttare. Assicurarsi che ci sia tempo sufficiente per discutere i risultati e risolvere eventuali problemi tecnici. Fornire inoltre una lista di obiettivi da realizzare.

#### Fase 4: Discussione e valutazione (30 minuti)
Alla fine dell'attività, si valutano i risultati e si discutono i passaggi effettuati.

- **Valutazione:** L'insegnante valuta il raggiungimento degli obiettivi di apprendimento basandosi su:
  - Capacità di raggiungere gli obiettivi proposti dal professore
  - Il modo in cui lo studente ha raggiunto gli obiettivi


### 1.2 Suggerimenti per la valutazione

Per valutare il raggiungimento degli obiettivi di apprendimento, si consiglia di utilizzare una valutazione formativa e continuativa. Ecco alcune linee guida:
- **Osservazione continua:** Durante l'attività pratica, l'insegnante osserva come gli studenti lavorano in squadra, come rissolvono i problemi e come applicano le conoscenze teoriche.
- **Valutazione delle presentazioni:** Le presentazioni dei risultati finali sono valutate in base alla chiarezza, alla correttezza tecnica e alla capacità di spiegare i processi utilizzati.

**Consigli per l'insegnante:** Dato che l'attivitá viene svolta simulando una competizione potrebbe essere indicato promuovere positivamente la competitivitá tra le varie squadre, ad esempio creando una classifica finale con i punteggi ottenuti dalle squadre.

## 2. Materiale didattico per studenti

### 2.1 Slide introduttive
Le slide introduttive dovrebbero coprire i seguenti punti:
- **Cos'è la cybersecurity?** Definizione ed importanza.
- **Obiettivi dell'attività:** Cosa gli studenti impareranno e faranno durante l'attività.
- **Strumenti e tecniche:** Introduzione a Kali Linux, Metasploit e Metasploitable 2.



### 2.2 Dispense tecniche
Le dispense tecniche forniscono un "cheatsheet" su come utilizzare i tool richiesti dall'attività, includendo:
- Comandi base di Linux utili per l'attività.
- Breve guida sul funzionamento di Metasploit
- Esempi di attacchi controllati e spiegazione del loro funzionamento.

La presenza delle dispenze tecniche dovrebbero aiutare gli studenti che trovano piú difficoltá nello svolgimento dell'attivitá.


### 2.3 Schede di esercizi da svolgere
Le schede di esercizi contengono attività pratiche che gli studenti devono completare, come:
- Eseguire una scansione di rete e documentare i risultati.
- Tentare un attacco exploit su Metasploitable 2 e spiegare i passaggi seguiti.
- Proporre una difesa per una delle vulnerabilità scoperte.

**Suggerimento:** Gli esercizi dovrebbero essere progressivi, iniziando con compiti semplici e aumentando gradualmente la complessità.
\
Potrebbe inoltre essere opportuno aggiungere degli esercizi "extra", che propongono un livello di difficoltá piú elevato, cosí da offrire una sfida per gli studenti piú competenti.


---

Questa struttura dettagliata assicura che l'attività possa essere replicata con successo da qualsiasi insegnante, fornendo al contempo agli studenti tutte le risorse necessarie per comprendere e applicare i concetti di cybersecurity.

# Bibliografia
Citare le fonti utilizzate (si consiglia ad esempio bibtex o biblatex).
Scegliere lo stile preferito, e mantenerlo coerente ([esempio](https://www.acm.org/publications/authors/reference-formatting))

1. [Metasploit](https://www.metasploit.com/)

2. [Metasploitable 2](https://docs.rapid7.com/metasploit/metasploitable-2/)

3. [Kali Linux](https://www.kali.org/)

4. [Proposta CINI per l'insegnamento dell'informatica nelle scuole](https://www.consorzio-cini.it/index.php/it/component/attachments/download/745/)



# Licenza del documento
Specificare la licenza del documento.

Sono caldeggiate licenze libere (es. [Creative Commons](https://creativecommons.org/licenses/by-sa/4.0/deed.it)), così da poter
condividere (es. pubblicazione sul Wiki) il documento con futuri
colleghi o insegnanti.

NB: non basta specificare una licenza, bisogna anche rispettarla (es. non includere testi o immagini con licenze non compatibili con quella scelta, non copiare lunghi pezzi di testo senza rendere chiaro che si tratta di una citazione)



Questo lavoro è distribuito con Licenza Creative Commons Attribuzione - Non commerciale - Condividi allo stesso modo 4.0 Internazionale (CC BY-NC-SA 4.0). Per visualizzare una copia della licenza, visita [Creative Commons](https://creativecommons.org/licenses/by-nc-sa/4.0/).

