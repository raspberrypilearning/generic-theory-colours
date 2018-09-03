Fargen på et objekt avhenger av fargen på lyset som det reflekterer eller sender ut. Lyset kan ha forskjellige bølgelengder, og lysets farge avhenger av bølgelengden det har. Lysets farge i henhold til dets bølgelengde kan ses i diagrammet nedenfor. Du kan kanskje gjenkjenne dette som regnbuens farger.

![Synlig spektrum](images/linear-visible-spectrum.png)

Mennesker ser farge på grunn av spesielle celler i våre øyne. Disse cellene kalles *tapper*. Vi har tre typer tapper, og hver type oppfatter enten rødt, blått eller grønt lys. Derfor er alle fargene vi ser, bare blandinger av fargene rød, blå og grønn.

![Additiv farveblanding](images/additive-colour-mixing.png)

I additiv fargeblanding brukes tre farger (rød, grønn og blå) til å lage andre farger. I bildet ovenfor er det tre spotlighter med lik lysstyrke, en for hver farge. I fravær av farge er resultatet svart. Hvis alle tre farger er blandet, er resultatet hvit. Når rød og grønn kombineres, blir resultatet gult. Når rød og blå kombineres, er resultatet magenta. Når blå og grønn kombineres, er resultatet cyan. Det er mulig å lage enda flere farger enn dette ved å variere lysstyrken til de tre originale fargene som brukes.

Datamaskiner lagrer alt som 1'ere og 0'er. Disse 1'erne og 0'ene er ofte organisert i sett med 8, kalt **bytes**.

En enkelt byte kan representere et tall fra 0 til 255.

Når vi ønsker å representere en farge i et dataprogram, kan vi gjøre dette ved å definere mengden rød, blå og grønn som utgjør fargen. Disse beløpene lagres vanligvis som en enkelt byte og derfor som et tall mellom 0 og 255.

Her er en tabell som viser noen fargeverdier:

| Rød | Grønn | Blå | Farge   |
| --- | ----- | --- | ------- |
| 255 | 0     | 0   | Rød     |
| 0   | 255   | 0   | Grønn   |
| 0   | 0     | 255 | Blå     |
| 255 | 255   | 0   | Gul     |
| 255 | 0     | 255 | Magenta |
| 0   | 255   | 255 | Cyan    |

Du kan finne en fin [fargevelger til å leke med på w3schools](https://www.w3schools.com/colors/colors_rgb.asp){: target = "_ blank"}.