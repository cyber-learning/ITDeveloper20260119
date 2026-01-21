Sintassi elemento HTML
<tagname attribute1="value1" attribute2="value2">content</tagname>

Attributi globali:
- id identificare in modo univoco un elemento HTML all'interno di una pagina
- class (sinonimo di insieme) utile per raggruppare più elementi HTML
- style
- on...



Commenti:
    alt + shift + a su Windows
    ctrl + k e ctrl + c
    command + shift + 7 su macOS

headings tag
h1
h2
...
h6

Paragrafo
p

Link
a




Anticipo CSS:
Box Model è una descrizione di quanto spazio occupa un elemento HTML sulla pagina


Block Level Elements:
Gli elementi di tipo block:
- "si allargano il più possibile"
- sono impilati in verticale (cioè uno sotto l'altro)

body
div division cioè una generica divisione della pagina - contenitore per eccellenza degli elementi block
h1, h2, ..., h6
p
ol li
ul li


Inline Level Elements:
Gli elementi di tipo inline:
- sono larghi (width) tanto quanto basta a contenere il proprio contenuto
- sono impilati in orizzontale (cioè uno di fianco all'altro)

span contenitore per eccellenza degli elementi inline
strong
a
img (è anche un self closing tag)





Elementi HTML innestati (nested):
Tra elementi HTML innestati nascono relazioni parent-child.

Regole tra elementi HTML innestati
Un elemento block può presentare al suo interno (come elementi HTML innestati):
- altri elementi block
- altri elementi inline
- puro testo

Un elemento inline può presentare al suo interno (come elementi HTML innestati):
- altri elementi inline
- puro testo

All'interno di un elemento inline NON posso inserire un block!!!

Eccezione alla regola sugli elementi HTML innestati:
- gli elementi h1, h2, ..., h6 e i paragrafi NON possono contenere al loro interno altri elementi block



Self closing tags elementi HTML che non potendo avere del contenuto allora non è presente il tag di chiusura




# Esercizio - AboutMe
Creare una fantastica pagina web di presentazione personale, stile anni '90,
che punta al vostro account Instagram o TikTok o entrambi usando gli heading, paragraph e links

Inoltre aggiungere:
- una vostra immagine
- una lista di cose che vi piace fare






La sintassi dell'URL "più generico":
protocollo://username:password@dominio:porta/path?queryString#idAnchor



Tag Semantici (HTML 5) cioè contenitori block (al pari di un div) con un ruolo semantico ben specifico da un punti di vista SEO
    nav un contenitore per uno o più link di navigazione
    header un contenitore utile per introdurre l'informazione presente all'interno dell'elemento parent
    main il contenuto principale della pagina
    article
    section
    aside un contenitore per delle informazioni indirettamente collegate al contenuto dell'elemento parent
    footer un contenitore per delle informazioni di secondaria importanza relative all'elemento parent


article un contenitore per del contenuto informativo:
- indipendente dal contenuto di altri article
- self contained cioè l'informazione è tutta racchiusa al suo interno
Ogni article deve avere un titolo


section un contenitore utilizzato per raggruppare una "categoria" di contenuti legati tra di loro a livello tematico
Ogni section deve avere un titolo
Una section deve essere utilizzata solo se non è possibile utilizzare altri tag semantici più specifici


References:
https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/nav
https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/article
https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/section





# Esercizio
vai sulla pagina dell'ansa https://www.ansa.it/?refresh_ce e prova a strutturare la pgina tramite tag semantici.



