Objekti värvus sõltub selle valguse värvusest, mida see peegeldab või kiirgab. Valgusel võivad olla erinevad lainepikkused ja valguse värvus sõltub selle lainepikkusest. Lainepikkusele vastavat valguse värvust võib näha alljärgneval skeemil. Sellel võib ära tunda vikerkaarevärvid.

![Nähtava valguse spekter](images/linear-visible-spectrum.png)

Inimesed näevad värve tänu erilistele rakkudele meie silmades. Neid rakke nimetatakse * koonusteks *. Meil on kolme tüüpi koonusrakku ja iga tüüp tuvastab ühe kolmest värvist, punase, sinise või rohelise valguse. Seepärast on kõik värvid, mida me näeme, kõigest punase, sinise ja rohelise värvuse segu.

![Aditiivne värvide segamine](images/additive-colour-mixing.png)

Aditiivse värvide segamise puhul kasutatakse teiste värvuste saamiseks kolme värvust (punane, roheline ja sinine). Ülaltoodud pildil on kolm võrdse heledusega prožektorit, üks iga värvuse kohta. Kui värvus üldse puudub, on tulemuseks must. Kui kõik kolm värvust on kokku segatud, on tulemuseks valge. Punase ja rohelise kombineerimisel on tulemuseks kollane. Punase ja sinise kombineerimisel on tulemuseks purpur. Kui sinine ja roheline kombineerida, on tulemuseks tsüaansinine. Kasutatud kolme algvärvuse heledust muutes on võimalik saada veel rohkem värvusi kui eelpool mainitud.

Arvutid salvestavad kõike arvude 1 ja 0 abil. Need 1-d ja 0-d on tihti korrastatud 8-liikmelistesse hulkadesse, mida nimetatakse **bytes**.

Üksainus  bait  võib esindada mis tahes numbrit vahemikus 0 kuni 255.

Kui me tahame arvutiprogrammis mingit värvust kujutada, saame me seda teha, määratledes selle värvuse moodustavate punase, sinise ja rohelise värvuse hulga. Neid koguseid salvestatakse tavaliselt ühe byte ja seega numbrina vahemikus 0 kuni 255.

Siin on tabel, kus on näha mõningad värviväärtused:

| Punane | Roheline | Sinine | Värvus       |
| ------ | -------- | ------ | ------------ |
| 255    | 0        | 0      | Punane       |
| 0      | 255      | 0      | Roheline     |
| 0      | 0        | 255    | Sinine       |
| 255    | 255      | 0      | Kollane      |
| 255    | 0        | 255    | Purpur       |
| 0      | 255      | 255    | Tsüaansinine |

Võite leida kena [värvivalija w3schools keskkonnast](https://www.w3schools.com/colors/colors_rgb.asp){:target="_blank"}.