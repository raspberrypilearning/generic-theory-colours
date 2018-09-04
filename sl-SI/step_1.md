Barva predmeta je odvisna od barve svetlobe, ki jo lahko vpija ali odbija. Svetloba ima lahko različne valovne dolžine. Barva svetlobe je odvisna od njene valovne dolžine. Barvo svetlobe glede na njeno valovno dolžino lahko vidimo v spodnjem diagramu. To lahko prepoznate kot barve mavrice.

![Vidni spekter](images/linear-visible-spectrum.png)

Ljudje vidimo barvo zaradi posebnih celic v naših očeh. Te celice imenujemo *čepnice*. Obstajajo tri vrste čepnic. Vsaka zazna rdečo, modro ali zeleno svetlobo. Zato so vse barve, ki jih vidimo, le mešanice rdeče, modre in zelene.

![Aditivno mešanje barv](images/additive-colour-mixing.png)

Pri aditivnem mešanju barv se za izdelavo drugih barv uporabljajo tri barve (rdeča, zelena in modra). Na sliki zgoraj so trije reflektorji enake svetlosti, vsak za eno barvo. Če ni barve, je rezultat črn. Če so vse tri barve zmešane, je rezultat bele barve. Ko se rdeča in zelena združita, je rezultat rumen. Ko se rdeča in modra združita, je rezultat magenta. Ko se modra in zelena združita, je rezultat cian. Še več barv je mogoče narediti s tem, da spremenite svetlost treh prvotnih barv.

Računalniki shranjujejo vse kot 1s in 0s. Te 1s in 0s so pogosto organizirane v množice po 8, imenovane **bajti**.

En bajt lahko predstavlja poljubno število od 0 do 255.

Ko želimo predstaviti barvo v računalniškem programu, lahko to naredimo tako, da določimo količine rdeče, zelene in modre barve, ki tvorijo to barvo. Ti zneski so običajno shranjeni kot en sam bajt in zato kot število med 0 in 255.

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