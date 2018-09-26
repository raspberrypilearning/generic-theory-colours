Culoarea unui obiect depinde de culoarea luminii pe care o reflectă sau o emite. Lumina poate avea diferite lungimi de undă, iar culoarea luminii depinde de lungimea de undă pe care o are. Culoarea luminii în funcție de lungimea de undă a acesteia poate fi văzută în diagrama de mai jos. S-ar putea să le recunoașteți ca fiind culorile curcubeului.

![Spectru vizibil](images/linear-visible-spectrum.png)

Oamenii văd culorile datorită unor celule speciale din ochii noștri. Aceste celule sunt numite *conuri*. Avem trei tipuri de celule conice și fiecare tip detectează fie lumina roșie, albastră sau verde. Prin urmare, toate culorile pe care le vedem sunt doar amestecuri ale culorilor roșu, albastru și verde.

![Combinarea culorilor](images/additive-colour-mixing.png)

În combinarea culorilor, trei culori (roșu, verde și albastru) sunt folosite pentru a obține alte culori. În imaginea de mai sus, există trei spoturi de luminozitate egală, câte una pentru fiecare culoare. În absența tuturor culorilor rezultatul este negru. Dacă toate cele trei culori sunt amestecate, rezultatul este alb. Când roșu și verde se combină, rezultatul este galben. Când roșu și albastru se combină, rezultatul este purpuriu. Când albastru și verde se combină, rezultatul este turcoaz. Este posibil să obțineți chiar şi mai multe culori prin modificarea luminozității celor trei culori utilizate original.

Computerele stochează totul ca 1 și 0. Aceste 1 și 0 sunt adesea organizate în seturi de 8, numite **bytes**.

Un singur byte poate reprezenta orice număr de la 0 până la 255.

Când vrem să reprezentăm o culoare într-un program de calculator, putem face acest lucru prin definirea cantităților de roșu, albastru și verde care alcătuiesc acea culoare. Aceste sume sunt de obicei stocate ca un singur byte și, prin urmare, ca un număr între 0 și 255.

Iată un tabel care prezintă valorile a câteva culori:

| Roșu | Verde | Albastru | Culoare  |
| ---- | ----- | -------- | -------- |
| 255  | 0     | 0        | Roșu     |
| 0    | 255   | 0        | Verde    |
| 0    | 0     | 255      | Albastru |
| 255  | 255   | 0        | Galben   |
| 255  | 0     | 255      | Purpuriu |
| 0    | 255   | 255      | Turcoaz  |

Puteți găsi un bun [selector de culoare la W3Schools](https://www.w3schools.com/colors/colors_rgb.asp){:target="_blank"}.