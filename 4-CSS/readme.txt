
selector {
    proprietà: valore;
    proprietà: valore;
    proprietà: valore;
}



Ereditarietà: alcune proprietà CSS (font, liste) applicate ad un elemento HTML posso essere ereditate agli elementi HTML discendenti


rgb(rr, gg, bb)         0 <= rr, gg, bb <= 255
rgba(rr, gg, bb, aa)         0 <= rr, gg, bb <= 255  0.0 <= aa <= 1.0 (alpha - trasparenza)


#rrggbb         00 <= rr, gg, bb <= FF
#rrggbbaa         00 <= rr, gg, bb, aa <= FF




La viewport è la porzione di documento HTML visibile agli occhi dell'utente

Unità di misura:
- assolute: px
- relative

Unità di misura relative per i layout:
    % rispetto alla width dell'elemento parent. Eccezione: il % utilizzato per specificare l'altezza dell'elemento si riferirà alla HEIGHT dell'elemento parent e NON alla width!!!
    vw vh   viewport width e viewport height

Unità di misura relative per i font: ??????


Box Model è un insieme di proprietà CSS utili a descrivere quanto spazio occupa un elemento HTML sulla pagina



Il browser applica sugli elementi HTML uno style di default!!!


La proprietà box-sizing specifica a cosa width e height si riferiscono
Di default, la proprietà box-sizing assume il valore content-box cioè width e height si riferiscono al contenuto dell'elemento
La proprietà box-sizing al valore border-box è tale per cui  width e height si riferiscono al bordo dell'elemento (spessore del bordo e padding incluso)




Block Level Elements:
Gli elementi di tipo block:
- width 100%
- sono impilati in verticale (cioè uno sotto l'altro)


Inline Level Elements:
Gli elementi di tipo inline:
- sono larghi (width) tanto quanto basta a contenere il proprio contenuto
- sono impilati in orizzontale (cioè uno di fianco all'altro)

Gli elementi inline non rispettano il box model


Un elemento inline-block è un elemento block su cui posso applicare tutte le proprietà del box-model