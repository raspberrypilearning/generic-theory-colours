A cor de um objeto depende da cor da luz que o objeto reflete ou emite. A luz pode ter diferentes comprimentos de onda, assim como sua cor depende do comprimento de onda que ela possui. A cor da luz, de acordo com seu comprimento de onda, pode ser conferido abaixo. Você talvez possa identificar algumas como as cores do arco-íris.

![Visible spectrum](images/linear-visible-spectrum.png)

Os humanos enxergam cores devido a células especiais presentes em nossos olhos. Essas células são chamas *cones*. Nós temos três tipos de células cônicas, onde cada uma é responsável por detectar a cor vermelha, azul ou verde. Assim, todas as cores que enxergamos são combinações das cores vermelho, azul e verde.

![Additive colour mixing](images/additive-colour-mixing.png)

In additive colour mixing, three colours (red, green, and blue) are used to make other colours. In the image above, there are three spotlights of equal brightness, one for each colour. In the absence of any colour the result is black. If all three colours are mixed, the result is white. When red and green combine, the result is yellow. When red and blue combine, the result is magenta. When blue and green combine, the result is cyan. It's possible to make even more colours than this by varying the brightness of the three original colours used.

Computers store everything as 1s and 0s. These 1s and 0s are often organised into sets of 8, called **bytes**.

A single byte can represent any number from 0 up to 255.

When we want to represent a colour in a computer program, we can do this by defining the amounts of red, blue, and green that make up that colour. These amounts are usually stored as a single byte and therefore as a number between 0 and 255.

Here's a table showing some colour values:

| Vermelho | Verde | Azul | Cor      |
| -------- | ----- | ---- | -------- |
| 255      | 0     | 0    | Vermelho |
| 0        | 255   | 0    | Verde    |
| 0        | 0     | 255  | Azul     |
| 255      | 255   | 0    | Amarelo  |
| 255      | 0     | 255  | Magenta  |
| 0        | 255   | 255  | Ciano    |

You can find a nice [colour picker to play with at w3schools](https://www.w3schools.com/colors/colors_rgb.asp){:target="_blank"}.