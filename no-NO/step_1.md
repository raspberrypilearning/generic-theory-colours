Fargen på et objekt avhenger av fargen på lyset som det reflekterer eller sender ut. Lys kan ha ulike bølgelengder, og lysets farge vil avhenge av bølgelengen lyset har. Lysets farge i henhold til dets bølgelengde kan ses i diagrammet nedenfor. Du gjenkjenner kanskje dette som regnbuens farger.

![Synlig spektrum](images/linear-visible-spectrum.png)

Mennesker kan se farge på grunn av spesielle celler i øynene våre. Disse cellene kalles *tapper*. Vi har tre typer tapper, og hver type oppfatter enten rødt, blått eller grønt lys. Derfor vil alle fargene vi ser, være en blanding av fargene rød, blå og grønn.

![Additiv farveblanding](images/additive-colour-mixing.png)

I additiv fargeblanding brukes tre farger (rød, grønn og blå) til å lage andre farger. I bildet ovenfor er det tre spotlighter med lik lysstyrke, en for hver farge. I fravær av farge vil resultatet være svart. Hvis alle tre farger blandes, blir resultatet fargen hvit. Når rød og grønn kombineres, blir resultatet gult. Når rød og blå kombineres, er resultatet magenta. Når blå og grønn kombineres, er resultatet cyan. Det er mulig å lage enda flere farger enn dette ved å variere lysstyrken til de tre originale fargene.

Datamaskiner lagrer alt som 1'ere og 0'er. Disse 1'erne og 0'ene er ofte organisert i sett med 8, kalt **bytes**.

En enkel byte kan representere et tall fra 0 til 255.

Når vi ønsker å representere en farge i et dataprogram, kan vi gjøre dette ved å definere mengden rød, blå og grønn som utgjør den ønskelige fargen. Disse mengdene lagres vanligvis som en enkel byte og derfor som et tall mellom 0 og 255.

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