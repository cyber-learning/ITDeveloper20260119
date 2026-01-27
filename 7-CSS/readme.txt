Combinazione di selettori:
- descendant selector   space
- child selector        >

Group selectors          ,

Class selectors Multipli



# Esercizio GlassMorphism
Creare una pagina di login usando le form ed il GlassMorphism molto di moda nel 2023
Potrebbe essere utile sfruttare un generatore https://css.glass/ Cercate di capire cosa state utilizzando!
E' presente una proprietà che non vi è stata spiegata cioè backdrop-filter.
La proprietà backdrop-filter permette di applicare degli effetti grafici, come il blur (sfocato), al background dell'elemento.

Inoltre:
    il font utilizzato è il Montserrat preso da Google Fonts
    i colori utilizzati per il gradiente sono #FC466B e #3F5EFB



Viewport virtuale avente width di 980px
Viewport reale: browser voglio utilizzare una Viewport che ha width = alla width dello schermo del dispositivo


Responsive design: sviluppare pagine web che ben siano mostrate su dispositivi aventi larghezze di schermo differenti
Il responsive design prevede 2 approcci:
- mobile first => media query con min-width
- desktop first => media query con max-width


Nel responsive design con approccio mobile first:
1) sviluppare la pagina prima in modo che sia ben mostrata su mobile
2) il numero "MINIMOOOO" di modifiche al CSS affinchè la pagina sia ben mostrata per larghezze di schermo via via crescenti


@media condizione {
    
}



@media screen and (min-width: 600px) {
    p {
        background-color: blue;
    }
}


if(screen && width >= 600px) {
    p {
        background-color: blue;
    }
}



# References
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Media_queries
https://icons.getbootstrap.com/
