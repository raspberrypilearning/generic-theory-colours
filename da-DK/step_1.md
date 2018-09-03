Farven på et objekt afhænger af farven på det lys, det reflekterer eller udsender. Lyset kan have forskellige bølgelængder, og lysets farve afhænger af den bølgelængde, den har. Lysets farve ifølge dens bølgelængde kan ses i diagrammet nedenfor. Du kan måske genkende dette som regnbuens farver.

![Synligt spektrum](images/linear-visible-spectrum.png)

Mennesker ser farve på grund af specielle celler i vores øjne. Disse celler kaldes *kegler*. Vi har tre typer af kegleceller, og hver type opdager enten rødt, blåt eller grønt lys. Derfor er alle de farver, vi ser, bare blandinger af farverne røde, blå og grønne.

![Additiv farveblanding](images/additive-colour-mixing.png)

I additiv farveblanding bruges tre farver (rød, grøn og blå) til at lave andre farver. På billedet ovenfor er der tre spotlights med ensartet lysstyrke, en for hver farve. I mangel af nogen farve er resultatet sort. Hvis alle tre farver blandes, er resultatet hvidt. Når rød og grøn kombineres, er resultatet gul. Når rød og blå kombineres, er resultatet magenta. Når blå og grøn kombineres, er resultatet cyan. Det er muligt at lave endnu flere farver end dette ved at variere lysstyrken af ​​de tre originale farver, der bruges.

Computere gemmer alt som 1s og 0s. Disse 1s og 0s er ofte organiseret i sæt af 8, kaldet **bytes**.

En enkelt byte kan repræsentere ethvert tal fra 0 op til 255.

Når vi vil repræsentere en farve i et computerprogram, kan vi gøre dette ved at definere mængderne af rød, blå og grøn, der udgør den farve. Disse beløb gemmes normalt som en enkelt byte og derfor som et tal mellem 0 og 255.

Her er et bord med nogle farveværdier:

| Rød | Grøn | Blå | Farve   |
| --- | ---- | --- | ------- |
| 255 | 0    | 0   | Rød     |
| 0   | 255  | 0   | Grøn    |
| 0   | 0    | 255 | Blå     |
| 255 | 255  | 0   | Gul     |
| 255 | 0    | 255 | Magenta |
| 0   | 255  | 255 | Cyan    |

Du kan finde en flot [farvevælger til at spille hos w3schools](https://www.w3schools.com/colors/colors_rgb.asp){: target = "_ blank"}.