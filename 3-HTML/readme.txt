Una form è un contenitore utile per raccogliere i dati in input da parte dell'utente
L'elemento form è un block level element

Un elemento input è un elemento inline ed anche self closing tag
Un elemento input può essere di tipo:
- text
- number
- email
- password
- checkbox
- radio

Un elemento button è un elemento inline



Commenti Windows:
alt + shift + 7

ctrl + k e ctrl + c 


application/x-www-form-urlencoded è il formato con cui sono "impacchettati" i dati
name1=value1&name2=value2&name3=value3

nome=Eric&cognome=Cartman&eta=10&email=eric.cartman%40gmail.com&password=1234






Responsabilità dell'HTML è fornire una struttura logica alla pagina

CSS    Cascade     style sheet cioè un insieme di regole CSS applicate sugli elementi HTML a cascata (dall'alto verso il basso)
Responsabilità del CSS è fornire uno stile agli elementi HTML (rendere belli graficamente gli elementi HTML) - modificare la presentazione gli elementi HTML

Come può essere applicato il CSS?
- inline attraverso l'attributo HTML style
- embedded tramite elemento HTML style
- file esterno



Separation of Concerns (anni 70) -> Single responsability principle


Sintassi CSS:
selector {
    property1: value1;
    property2: value2;
    property3: value3;
}

parentesi graffe windows:
alt gr + shift + è


Selettori CSS utili per selezionare gli elementi HTML che vogliamo stilizzare (ordinati per specificità crescente):
1) * universal selector selezionare TUTTI gli elementi HTML indisciminatamente
2) tag selector selezionare TUTTI gli elementi HTML che hanno quel tag
3) .nomeDellaClasse class selector selezionare TUTTI gli elementi HTML che appartengono ad una certa classe
4) #nomeDellID id selector selezionare un solo elemento HTML tramite id
5) attributo HTML style

Valori per i colori:
- named colors
- rgb(rr, gg, bb) funzione CSS  0 <= rr, gg, bb <= 255
- hex color #rrggbb 0 <= rr, gg, bb <= FF



la font-family permette di specificare una lista di fallback di font

font-weight lo spessore del carattere:
100 lighter
200
300 thin light
400 normal
500
600
700 bold
800
900 bolder



