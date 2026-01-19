ctrl + s per salvare





Sintassi:
comando -opzione1 -opzione2 --opzioneFull argomento1 argomento2 -> richiede l'esecuzione di un programma


clear





i comandi utili per interfacciarci con il file system del sistema operativo:

Ogni file (e ogni directory) è univocamente individuato tramite un path (percorso).
Sono presenti path:
- assoluti
- relativi

Inoltre sono presenti delle keyword particolari (alias per le directory):
- . in questa directory (nella directory in cui mi trovo attualmente)
- .. la directory parent


Ogni utente del sistema operativo ha una sua directory home

Comandi per le directory:
    pwd print working directory
    ls list
    cd pathDellaDirectory         change directory
    mkdir nomeDellaDirectory      make directory
    mv pathDellaDirectorySrc pathDellaDirectoryDest     move
    cp -r pathDellaDirectorySrc pathDellaDirectoryDest    copy recursive
    rm -r pathDellaDirectory                              remove recursive

Comandi per i file:
    touch pathDelFile   crea un file vuoto
    cat pathDelFile
    mv pathDelFileSrc pathDelFileDest
    cp pathDelFileSrc pathDelFileDest
    rm pathDelFile





Editor di testo di default su unix si chiama vim 
vim pathDelFile

Vim ha 2 modalità di funzionamento:
- command mode
- insert mode

All'apertura vim si trova in modalità command mode

Per passare dalla command mode alla insert mode bisogna premere il tasto i
Per passare dalla insert mode alla command mode bisogna premere il tasto esc
I comandi disponibili:
    :wq     write quit
    :q      quit
    :q!     quit force






Problematiche:
1) come faccio a trovare la pubblicazione scientifica???
2) come faccio a trasferire la pubblicazione scientifica???
3) come faccio a leggerla (interpretarla)???

WWW è un insieme di 3 tecnologie:
1) URI Uniform resource identifier (caso particolare URL Uniform resource locator - collocazione)
2) protocollo HTTP (regole di comunicazione)
3) linguaggio HTML (documenti ipertestuali)


La sintassi dell'URL "più generico":
protocollo://username:password@dominio:porta/path?queryString#idAnchor

La queryString è composta da:
name1=value1&name2=value2&name3=value3&...

http    ://     127.0.0.1     :   8080      /index.html
http    ://     localhost     :   8080      /index.html
http    ://     localhost                   /index.html
https   ://     it.wikipedia.org            /wiki/Ciao
https   ://     www.youtube.com             /watch      ?    v = k9ynZnEBtvw  &  list = RDk9ynZnEBtvw & start_radio = 1
eric.cartman    @   gmail.com


Se il protocollo è:
- http allora la porta di default è la 80
- https allora la porta di default è la 443

Architettura Client - Server
Due programmi posso assumere il ruolo uno di client e l'altro di server
Solo il programma client può avviare la comunicazione con il programma server (il client effettua una richiesta al server).
Il server può solo rispondere alla richiesta del client.

Non può mai accadere che il server avvii la comunicazione con il client



Un protocollo rappresenta regole di comunicazione
Il protocollo HTTP hypertext transfer protocol si basa su una architettura client server
Nel protocollo HTTP sono presenti:
- richiesta HTTP
- risposta HTTP

Attualmente, il protocollo HTTP è utilizzato per scambiare una risorsa qualsiasi:
- un documento HTML
- CSS, JS
- immagini
- video
- streaming video

HTML hypertext markup language cioè un linguaggio di formattazione (struttura logica) per ipertesti
ipertesto è un testo + link