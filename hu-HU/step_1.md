Az objektum színe attól függ, hogy a fény milyen tükrözi vagy kibocsát. A fény különböző hullámhosszakkal rendelkezik, és a fény színe a hullámhosszától függ. A fény hullámhossza szerinti színét az alábbi ábrán láthatjuk. Ezt fel lehet ismerni a szivárvány színeinek.

![Látható spektrum](images/linear-visible-spectrum.png)

Az emberek különleges színeket látnak a szemünkben. Ezeket a sejteket *kúp*hívják. Háromféle kúpos cellánk van, és mindegyik típus piros, kék vagy zöld fényt érzékel. Ezért minden olyan szín, amit látunk, csak a piros, kék és zöld színek keveréke.

![Adalék színkeverés](images/additive-colour-mixing.png)

Az adalékanyag színkeveréshez három színt (piros, zöld és kék) használnak más színek készítéséhez. A fenti képen három fénysugárzó egyenlő fényerővel rendelkezik, egy színenként. Szín hiányában az eredmény fekete. Ha mindhárom szín keveredik, az eredmény fehér. Amikor a vörös és a zöld szín kombinálódik, az eredmény sárga. Amikor vörös és kék kombinálódik, az eredmény bíbor. Amikor kék és zöld kombinálódik, az eredmény cián. Ezzel még több színt lehet készíteni, mint a három eredeti szín fényerejét.

A számítógépek mindent 1-et és 0-t tárolnak. Ezeket az 1-eseket és a 0 -kat gyakran 8-as készleteknek, **byte-nak nevezik**.

Egyetlen byte lehet bármely szám 0-tól 255-ig.

Ha egy számítógépes programban színt akarunk képviselni, akkor ezt úgy tehetjük meg, hogy meghatározzuk a színt alkotó piros, kék és zöld mennyiségeket. Ezeket az összegeket általában egyetlen bájt tárolják, és így 0 és 255 közötti számként.

Íme egy táblázat, amely néhány színértéket mutat be:

| Piros | Zöld | Kék | Szín       |
| ----- | ---- | --- | ---------- |
| 255   | 0    | 0   | Piros      |
| 0     | 255  | 0   | Zöld       |
| 0     | 0    | 255 | Kék        |
| 255   | 255  | 0   | Sárga      |
| 255   | 0    | 255 | Bíborvörös |
| 0     | 255  | 255 | Cián       |

Megtalálhatsz egy szép [színválasztót, amellyel játszhatsz a w3schools](https://www.w3schools.com/colors/colors_rgb.asp){: target = "_ blank"}.