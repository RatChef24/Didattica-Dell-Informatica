---
title: Titolo Materiale Didattico
author: Riccardo Benedetti
date: 01/04/24
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

La lezione è rivolta agli studenti delle classi terze e quarte del liceo scientifico o dell'istituto tecnico ad indirizzo informatico. L'attività si colloca prevalentemente nell'ambito della disciplina di Informatica, con un focus particolare su reti e sicurezza informatica.

In quale specifica disciplina scolastica (o le discipline, ovviamente
l'informatica deve essere la disciplina prevalente) si colloca
l'attività?

- Per la scuola dell'infanzia / primaria / scuole \"medie\" si può fare riferimento a una delle discipline nelle Indicazioni Nazionali, nei Nuovi Scenari, e/o alla disciplina Informatica dalla Proposta CINI
- Per le scuole secondarie di secondo grado (superiori), fare riferimento ai documenti ministeriali (e secondariamente alla Proposta CINI)

Può essere---adattata---rivolta a studenti di diverse età e indirizzi?


## Motivazione e Finalità
Spiegare brevemente (una sola frase) di che attività si tratta.

Perché è importante svolgere questa attività nella scuola?

La lezione propone un'attività di cybersecurity gamificata, dove gli studenti, organizzati in squadre, competono per raggiungere specifici traguardi: ottenere l'IP della macchina target, identificare i servizi attivi sulla macchina target, e ottenere l'accesso root alla stessa. È importante poiché introduce in modo pratico e coinvolgente i concetti di sicurezza informatica e il funzionamento degli strumenti di penetration testing.

## Innovatività
Perché questa proposta è innovativa? Cosa è già presente su questo tema nella ricerca in Didattica dell'Informatica o nelle risorse disponibili online (è obbligatorio cercare risultati scientifici e risorse didattiche già presenti, e descriverli brevemente) e in cosa si differenzia/cosa mantiene/cosa va a migliorare questa proposta?

Questa proposta è innovativa in quanto integra l'elemento della gamification, rendendo l'apprendimento della sicurezza informatica più coinvolgente e pratico rispetto a metodi tradizionali. Rispetto alle risorse didattiche esistenti, che spesso si limitano a lezioni frontali o laboratoriali senza competizione, questa lezione aggiunge un elemento competitivo che stimola la partecipazione attiva e l'applicazione pratica delle conoscenze teoriche.

## Prerequisiti
Elencare i contenuti che si suppone siano già stati svolti e appresi dagli studenti

Gli studenti dovrebbero avere una conoscenza di base dei concetti di rete, dei protocolli di comunicazione (come TCP/IP), e una familiarità preliminare con l'ambiente Linux e comandi di shell. È utile anche una conoscenza introduttiva dei concetti di sicurezza informatica e vulnerabilità.
### Percorso
Se si ipotizza che questa attività sia parte di un percorso ampio (troppo ampio per entrare tutto nella relazione) sullo stesso tema, descrivere qui il percorso in modo schematico/sintetico.
Indicare su quali parti del percorso si concentrerà la relazione.

L'attività si inserisce in un percorso più ampio sulla sicurezza informatica, che può includere lezioni su crittografia, gestione delle chiavi, e protezione dei dati. In questa particolare lezione, ci si concentra sulla fase di penetration testing.eeee

## Contenuti (spiegati a un informatico)
Se si tratta di contenuti banalmente chiari per un informatico (e.g. riguardanti esami obbligatori della triennale), elencarli semplicemente.
Se l'attività riguarda contenuti specifici o particolari (es. elaborazione immagini, crittografia, computazione quantistica, specifiche tecniche di IA, ...) illustrarli brevemente o fornire link, avendo in mente (solo in questa breve sezione) di spiegarli ad un informatico.

Gli studenti utilizzeranno Kali Linux e Metasploit, due strumenti fondamentali nel penetration testing. Kali Linux è una distribuzione basata su Linux progettata per la sicurezza informatica, con una vasta gamma di strumenti preinstallati per testare la sicurezza dei sistemi. Metasploit è un framework che fornisce informazioni sugli exploit noti e consente di eseguire test di sicurezza.
## Grandi idee
Se ha senso per il materiale proposto, descrivere brevemente (qualche frase) quali sono le "grandi idee" (come spiegato a lezione) che questa attività vuole insegnare.

L'attività insegna le grandi idee del penetration testing etico, dell'analisi delle vulnerabilità, e dell'importanza di testare la sicurezza dei sistemi informatici per prevenire attacchi malevoli.
## Traguardi e Obiettivi
Nelle varie sottosezioni, vanno elencati traguardi e obiettivi di apprendimento che si vuole raggiungere con le attività proposte

### Traguardi/obiettivi generali dai documenti ministeriali/proposte
Indicare quali traguardi/obiettivi generali presenti nei documenti rilevanti vengono
raggiunti (es. Indicazioni nazionali per il primo ciclo,
Proposta CINI numerata, Indicazioni nazionali / linee guida per scuola
secondaria di secondo grado).

Traguardi/obiettivi generali dai documenti ministeriali/proposte

    1.Comprensione e utilizzo delle tecniche di base di sicurezza informatica.
    2.Applicazione delle conoscenze teoriche a situazioni pratiche.
    3.Sviluppo delle capacità di problem solving e pensiero critico.

### Traguardi/obiettivi generali
E' possibile (ma non obbligatorio e non sempre necessario) aggiungere i propri traguardi e obiettivi generali

### Obiettivi specifici in forma operativa
Gli obiettivi vanno scritti ipotizzando che inizino tutti con "Lo studente/la studentessa è in grado di...",
seguendo la tassonomia di Bloom rivisitata (o le altre tassonomie mostrate),
e facendo attenzione a non cadere negli errori tipici, come spiegato in classe.

1.Lo studente è in grado di identificare e utilizzare gli strumenti di Kali Linux e Metasploit.
2.Lo studente è in grado di effettuare una scansione di rete per identificare indirizzi IP e servizi attivi.
3.Lo studente è in grado di eseguire un attacco controllato per ottenere accesso root su una macchina target.

## Metodologie didattiche
Indicare quali metodologie didattiche si utilizzano - sia quelle più generali (es. lezione frontale, dialogata, cooperative learning, flipped classroom) sia quelle specifiche (es. unplugged, pair-programming) citate o discusse a lezione - e spiegarle brevemente.


Massima libertà di introdurre altre metodologie non spiegate a lezione, debitamente corredate di chiara spiegazione e riferimenti bibliografici.

Se si parla di didattica della programmazione, fare anche riferimento ai relativi concetti (macchina concettuale, misconcezioni, visualizzazione, program comprehension, ...) spiegati a lezione.

La lezione utilizza un approccio di gamification, in cui gli studenti competono in squadre per completare obiettivi specifici. Questo metodo stimola l'apprendimento attivo e collaborativo, con elementi di apprendimento basato su progetti (PBL). Le spiegazioni teoriche saranno integrate con esercitazioni pratiche.
## Tempi
Un'idea generale e indicativa dei tempi richiesti

La lezione è progettata per essere svolta in un arco di tempo di 4-5 ore, includendo una breve introduzione teorica, esercitazioni pratiche guidate, e una fase di competizione.
## Spazi
Classe, laboratorio, cortile...

L'attività richiede l'uso di un laboratorio informatico equipaggiato con computer in grado di eseguire Kali Linux, o una configurazione di macchine virtuali adeguata.aa

## Materiali e Strumenti
Quali materiali e strumenti (hardware e software, di ogni tipo, non solo informatico) sono necessari?

1.Computer con Kali Linux installato o accesso a macchine virtuali con Kali Linux.
2.Accesso a internet per aggiornamenti e ricerche.
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

# Bibliografia
Citare le fonti utilizzate (si consiglia ad esempio bibtex o biblatex).
Scegliere lo stile preferito, e mantenerlo coerente ([esempio](https://www.acm.org/publications/authors/reference-formatting))

# Licenza del documento
Specificare la licenza del documento.

Sono caldeggiate licenze libere (es. [Creative Commons](https://creativecommons.org/licenses/by-sa/4.0/deed.it)), così da poter
condividere (es. pubblicazione sul Wiki) il documento con futuri
colleghi o insegnanti.

NB: non basta specificare una licenza, bisogna anche rispettarla (es. non includere testi o immagini con licenze non compatibili con quella scelta, non copiare lunghi pezzi di testo senza rendere chiaro che si tratta di una citazione)

# Meta-sezione (da rimuovere): consigli

Per ricercare articoli scientifici, potete usare [Scholar](https://scholar.google.com/). Se connessi da rete UniBO o da casa tramite un [proxy](https://sba.unibo.it/it/almare/servizi-e-strumenti-almare/ezproxy), potete accedere alle banche dati degli editori. Per esempio, potete cercare sulla [Digital Library dell'ACM](https://dl.acm.org/), eventualmente [specializzando la ricerca](https://dl.acm.org/sig/sigcse) ai soli paper relativi al gruppo di interesse per la didattica dell'Informatica (NB: non utilizzare i suggerimenti che compaiono mentre si digita il testo da cercare, pena la perdita del filtro sui soli paper SIGCSE. Notare che, comunque, paper di Didattica dell'Informatica sono pubblicati anche al di fuori di SIGCSE, ad esempio in conferenze e riviste di Human-Computer interaction).

Per tutto il documento, seguire le buone regole su come evitare il plagio ([esempio dal MIT](https://integrity.mit.edu/handbook/writing-original-work))

Per tutto il documento, seguire le regole sulla scrittura in italiano, da pag. 6 [qui](https://corsi.unibo.it/magistrale/semiotica/prova-finale/indicazioni-per-la-redazione-della-tesi-di-laurea-semiotica.pdf/@@download/file/Indicazioni%20per%20la%20redazione%20della%20tesi%20di%20laurea%20Semiotica.pdf) (se usate bibtex, potete ignorare la dolorosa gestione manuale dei riferimenti bibliografici)

La struttura (sezioni e sottosezioni) qui fornita va rispettata con precisione.

La tabella iniziale (titolo, autore, data) non va riprodotta in formato tabellare: sono campi utili per inserire nel documento formattato le relative informazioni (es. finiranno nei corrispettivi campi per titolo, autore, data se si converte questo documento con pandoc per generare latex o html).

I docenti non valutano la relazione il base alla sua lunghezza: meglio una relazione breve e non ripetitiva, ma che dice esattamente le cose che mostrano comprensione dei contenuti del corso. Attenzione però ad inserire sufficienti dettagli affinché un insegnante possa replicare l'attività.
