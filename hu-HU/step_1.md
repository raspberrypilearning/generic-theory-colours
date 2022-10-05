Egy tárgy színe az általa visszavert vagy kibocsátott fény színétől függ. A fény különböző hullámhosszú lehet, és a fény színe a hullámhosszától függ. A fény hullámhossza szerinti színét az alábbi ábrán láthatjuk. Ez ismerős lehet a szivárvány színeiből.

![Látható spektrum](images/linear-visible-spectrum.png)

Az emberek színesen látnak, mivel speciális sejtek vannak a szemünkben. Ezeket a sejteket *csap*nak hívjuk. Háromféle csap sejtünk van, és mindegyik típus a vörös, kék vagy zöld fényt érzékeli. Ezért minden olyan szín, amelyet látunk, csak a piros, kék és zöld színek keveréke.

![Additív színkeverés](images/additive-colour-mixing.png)

Az additív (összeadó) színkeverésnél három színt (vörös, zöld és kék) használnak más színek létrehozására. A fenti képen három egyenlő fényerejű fénysugárzó látható, mindhárom színből egy. Szín hiányában az eredmény fekete. Ha mindhárom szín keveredik, az eredmény fehér. Amikor a vörös és a zöld szín kombinálódik, az eredmény sárga. Amikor vörös és kék kombinálódik, az eredmény bíbor. Amikor kék és zöld kombinálódik, az eredmény cián. Ennél még több színt lehet keverni, ha változtatjuk az eredeti három szín fényerejét.

A számítógépek mindent 1-esek és 0-k formájában tárolnak. Ezeket az 1-eseket és 0-kat gyakran 8-as csoportokba rendezzük, amelyeket **bájt**nak nevezünk.

Egy bájt bármelyik számot ábrázolhatja 0-tól 255-ig.

Ha egy számítógépes programban egy színt akarunk ábrázolni, akkor ezt úgy tehetjük meg, hogy meghatározzuk a színt alkotó vörös, kék és zöld mennyiségeket. Ezeket az értékeket általában egyetlen bájtban tárolják, így az értékük 0 és 255 között lehet.

Íme egy táblázat, amely néhány színértéket mutat be:

| Vörös | Zöld | Kék | Szín       |
| ----- | ---- | --- | ---------- |
| 255   | 0    | 0   | Vörös      |
| 0     | 255  | 0   | Zöld       |
| 0     | 0    | 255 | Kék        |
| 255   | 255  | 0   | Sárga      |
| 255   | 0    | 255 | Bíborvörös |
| 0     | 255  | 255 | Cián       |

Kísérletezhetsz a színkeveréssel a [w3schools színválasztó oldalán](https://www.w3schools.com/colors/colors_rgb.asp){:target="_blank"}.
