Culoarea unui obiect depinde de culoarea luminii pe care o reflectă sau o emite. Lumina poate avea diferite lungimi de undă, iar culoarea luminii depinde de lungimea de undă pe care o are. Culoarea luminii în funcție de lungimea de undă a acesteia poate fi văzută în diagrama de mai jos. S-ar putea să recunoașteți acest lucru ca pe culorile curcubeului.

![Spectru vizibil](images/linear-visible-spectrum.png)

Oamenii văd culoarea din cauza celulelor speciale în ochii noștri. Aceste celule sunt numite *conuri*. Avem trei tipuri de celule conice și fiecare tip detectează lumină roșie, albastră sau verde. Prin urmare, toate culorile pe care le vedem sunt doar amestecuri de culori roșu, albastru și verde.

![Aditivarea amestecului de culori](images/additive-colour-mixing.png)

În amestecarea culorilor adiționale, trei culori (roșu, verde și albastru) sunt folosite pentru a realiza alte culori. În imaginea de mai sus, există trei spoturi de luminozitate egală, câte una pentru fiecare culoare. În absența oricărei culori rezultatul este negru. Dacă toate cele trei culori sunt amestecate, rezultatul este alb. Când combinați roșu și verde, rezultatul este galben. Când combinați roșu și albastru, rezultatul este purpuriu. Când se combină albastru și verde, rezultatul este cyan. Este posibil să faceți chiar mai multe culori decât acest lucru prin modificarea luminozității celor trei culori originale utilizate.

Computerele stochează totul ca 1s și 0s. Aceste 1s și 0s sunt adesea organizate în seturi de 8, numite **octeți**.

Un singur octet poate reprezenta orice număr de la 0 până la 255.

Când vrem să reprezentăm o culoare într-un program de calculator, putem face acest lucru prin definirea cantităților de roșu, albastru și verde care alcătuiesc acea culoare. Aceste sume sunt de obicei stocate ca un singur octet și , prin urmare , ca un număr între 0 și 255.

Iată un tabel care prezintă câteva valori de culoare:

| Roșu | Verde | Albastru | Culoare  |
| ---- | ----- | -------- | -------- |
| 255  | 0     | 0        | Roșu     |
| 0    | 255   | 0        | Verde    |
| 0    | 0     | 255      | Albastru |
| 255  | 255   | 0        | Galben   |
| 255  | 0     | 255      | Purpuriu |
| 0    | 255   | 255      | Cyan     |

Puteți găsi un frumos [selector de culoare pentru a juca la W3Schools](https://www.w3schools.com/colors/colors_rgb.asp){: target = "_ blank"}.