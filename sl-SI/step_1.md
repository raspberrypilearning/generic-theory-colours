Barva predmeta je odvisna od barve svetlobe, ki jo lahko vpija ali odbija. Svetloba ima lahko različne valovne dolžine. Barva svetlobe je odvisna od njene valovne dolžine. Barvo svetlobe glede na njeno valovno dolžino lahko vidimo v spodnjem diagramu. To lahko prepoznate kot barve mavrice.

![Vidni spekter](images/linear-visible-spectrum.png)

Ljudje vidimo barvo zaradi posebnih celic v naših očeh. Te celice imenujemo *čepnice*. Obstajajo tri vrste čepnic. Vsaka zazna eno od barv: rdečo, modro ali zeleno. Zato so vse barve, ki jih vidimo, le mešanice rdeče, modre in zelene.

![Mešanje barv z dodajanjem](images/additive-colour-mixing.png)

Pri aditivnem mešanju barv se za izdelavo drugih barv uporabljajo tri barve (rdeča, zelena in modra). Na sliki zgoraj so trije reflektorji enake svetlosti, vsak za eno barvo. Če ni prisotne nobene od barv, oko zazna črno barvo. Če so vse tri barve zmešane, je rezultat bele barve. Če zmešamo rdečo in zeleno, dobimo rumeno barvo. Če zmešamo rdečo in modro, dobimo vijolično barvo. Ko se modra in zelena združita, je rezultat cian. Še več barv je mogoče zmešati tako, da spremenite jakost treh osnovnih barv.

Računalniki shranjujejo vse kot ničle (0) in enice (1). Te 1s in 0s so pogosto organizirane v množice po 8, imenovane **bajti**.

En bajt lahko predstavlja poljubno število od 0 do 255.

Ko želimo predstaviti barvo v računalniškem programu, lahko to naredimo tako, da določimo količine rdeče, zelene in modre barve, ki tvorijo to barvo. Te veličine so običajno shranjene kot en sam bajt, z vrednostjo med 0 in 255.

Tukaj je tabela z nekaj barvnimi vrednostmi:

| Rdeča | Zelena | Modra | Barva   |
| ----- | ------ | ----- | ------- |
| 255   | 0      | 0     | Rdeča   |
| 0     | 255    | 0     | Zelena  |
| 0     | 0      | 255   | Modra   |
| 255   | 255    | 0     | Rumena  |
| 255   | 0      | 255   | Magenta |
| 0     | 255    | 255   | Cian    |

Na w3school lahko najdete [izbirnik barv](https://www.w3schools.com/colors/colors_rgb.asp){:target="_blank"}.