Barva predmeta je odvisna od barve svetlobe, ki jo odraža ali oddaja. Svetloba ima lahko različne valovne dolžine in barva svetlobe je odvisna od valovne dolžine, ki jo ima. Barva svetlobe glede na njegovo valovno dolžino lahko vidimo v spodnjem diagramu. To lahko prepoznate kot barve mavrice.

![Vidni spekter](images/linear-visible-spectrum.png)

Ljudje vidijo barvo zaradi posebnih celic v naših očeh. Te celice imenujemo *stožcev*. Imamo tri vrste stožničnih celic, vsak tip zazna rdečo, modro ali zeleno svetlobo. Zato so vse barve, ki jih vidimo, le mešanice barv rdeče, modre in zelene.

![Mešanje barv dodatka](images/additive-colour-mixing.png)

Pri dodatnem mešanju barv se za izdelavo drugih barv uporabljajo tri barve (rdeča, zelena in modra). Na sliki zgoraj so trije reflektorji enake svetlosti, po eno za vsako barvo. Če ni barve, je rezultat črn. Če so vse tri barve mešane, je rezultat bele barve. Ko se rdeča in zelena združita, je rezultat rumen. Ko se rdeča in modra združita, je rezultat magenta. Ko se modro in zeleno združita, je rezultat cian. Še več barv je mogoče narediti s tem, da spremenite svetlost treh prvotnih barv.

Računalniki shranjujejo vse kot 1s in 0s. Te 1s in 0s so pogosto organizirane v množice 8, imenovane **bajtov**.

En sam bajt lahko predstavlja poljubno število od 0 do 255.

Ko želimo predstaviti barvo v računalniškem programu, lahko to naredimo tako, da določimo količine rdeče, modre in zelene barve, ki tvorijo to barvo. Ti zneski so običajno shranjeni kot en sam bajt in zato kot število med 0 in 255.

Tukaj je tabela z nekaj barvnimi vrednostmi:

| rdeča | Zelena | Modra | Barva   |
| ----- | ------ | ----- | ------- |
| 255   | 0      | 0     | rdeča   |
| 0     | 255    | 0     | Zelena  |
| 0     | 0      | 255   | Modra   |
| 255   | 255    | 0     | Rumena  |
| 255   | 0      | 255   | Magenta |
| 0     | 255    | 255   | Cijan   |

Najdete lepo [izbirnik barv za igro na w3schools](https://www.w3schools.com/colors/colors_rgb.asp){: target = "_ blank"}.