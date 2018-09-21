Objekti värv sõltub selle valguse värvusest, mida see peegeldab või kiirgab. Valgusel võivad olla erinevad lainepikkused ja valguse värvus sõltub selle lainepikkusest. Lainepikkusele vastavat valguse värvust võib näha alljärgneval skeemil. Selles võib ära tunda vikerkaarevärvid.

![Nähtava valguse spekter](images/linear-visible-spectrum.png)

Inimesed näevad värve tänu erilistele rakkudele meie silmades. Neid rakke nimetatakse *cones*. Meil on kolme tüüpi koonusrakud ja iga tüüp tuvastab kas punase, sinise või rohelise valguse. Seepärast on kõik värvid, mida me näeme, kõigest punase, sinise ja rohelise värvi segu.

![Lisandite värvide segamine](images/additive-colour-mixing.png)

Aditiivse värvi segamisel kasutatakse teisi värve valmistamiseks kolme värvi (punane, roheline ja sinine). Ülaltoodud pildil on kolm võrdväärse heledusega täppi, üks iga värvi kohta. Kui värv puudub, on tulemuseks must. Kui kõik kolm värvi on segatud, on tulemus valge. Kui punane ja roheline kombineeritakse, on tulemus kollased. Kui punane ja sinine ühendada, on tulemuseks magenta. Kui sinine ja roheline kombineerida, on tulemuseks sinine. Võimalik on teha veelgi rohkem värve kui see, kui muudate kasutatud kolme originaalse värvuse heledust.

Arvutid hoiavad kõike 1s ja 0s. Need 1s ja 0s on tihti korrastatud kogumitesse 8, mida nimetatakse **baitiks**.

Ühe baidi võib esindada mis tahes arvu vahemikus 0 kuni 255.

Kui me tahame arvutiprogrammi värvi esindada, saame seda teha, määratledes selle värvi moodustavate punaste, sinise ja rohelise hulga. Neid koguseid hoitakse tavaliselt ühe baidise ja seega numbrina vahemikus 0 kuni 255.

Siin on tabel, mis näitab värviväärtusi:

| Punane | Roheline | Sinine | Värv     |
| ------ | -------- | ------ | -------- |
| 255    | 0        | 0      | Punane   |
| 0      | 255      | 0      | Roheline |
| 0      | 0        | 255    | Sinine   |
| 255    | 255      | 0      | Kollane  |
| 255    | 0        | 255    | Magenta  |
| 0      | 255      | 255    | Tsüaan   |

Võite leida kena [värvivalija mängida w3schools](https://www.w3schools.com/colors/colors_rgb.asp){: target = "_ blank"}.