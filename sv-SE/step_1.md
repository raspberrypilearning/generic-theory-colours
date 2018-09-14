Färgen på ett objekt beror på ljusets färg som den reflekterar eller avger. Ljus kan ha olika våglängder, och ljusets färg beror på våglängden den har. Lysets färg enligt dess våglängd kan ses i diagrammet nedan. Du kanske känner igen det som regnbågens färger.

![Synligt spektrum](images/linear-visible-spectrum.png)

Människor ser färg på grund av speciella celler i våra ögon. Dessa celler kallas *koner*. Vi har tre typer av konceller, och varje typ upptäcker antingen rött, blått eller grönt ljus. Därför är alla färger som vi ser bara blandningar av färgerna röda, blåa och gröna.

![Additiv färgblandning](images/additive-colour-mixing.png)

I additiv färgblandning används tre färger (röd, grön och blå) för att göra andra färger. I bilden ovan finns tre strålkastare med samma ljusstyrka, en för varje färg. I avsaknad av någon färg är resultatet svart. Om alla tre färgerna blandas är resultatet vit. När rött och grönt kombineras är resultatet gult. När rött och blått kombineras är resultatet magenta. När blå och grön kombineras är resultatet cyan. Det är möjligt att göra ännu fler färger än detta genom att ändra ljusstyrkan hos de tre ursprungliga färgerna som används.

Datorer lagrar allt som ettor och nollor. Dessa ettor och nollor organiseras ofta i uppsättningar av 8, som kallas **byte**.

En enda byte kan representera ett tal från 0 upp till 255.

När vi vill representera en färg i ett datorprogram kan vi göra det genom att definiera mängderna röda, blåa och gröna som utgör den färgen. Dessa belopp lagras vanligtvis som en enda byte och därmed som ett tal mellan 0 och 255.

Här är ett bord som visar några färgvärden:

| Röd | Grön | Blå | Färg    |
| --- | ---- | --- | ------- |
| 255 | 0    | 0   | Röd     |
| 0   | 255  | 0   | Grön    |
| 0   | 0    | 255 | Blå     |
| 255 | 255  | 0   | Gul     |
| 255 | 0    | 255 | Magenta |
| 0   | 255  | 255 | cyan    |

Du kan hitta en fin [färgplockare att spela med på w3schools](https://www.w3schools.com/colors/colors_rgb.asp){: target = "_ blank"}.