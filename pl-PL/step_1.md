Kolor obiektu zależy od koloru światła, które odbija lub emituje. Światło może mieć różne długości fal, a kolor światła zależy od długości fali, którą ma. Kolor światła w zależności od jego długości fali można zobaczyć na poniższym schemacie. Możesz rozpoznać to jako kolory tęczy.

![Widoczne widmo](images/linear-visible-spectrum.png)

Ludzie widzą kolor ze względu na specjalne komórki w naszych oczach. Te komórki nazywają się *stożkami*. Mamy trzy typy komórek stożkowych, a każdy z nich wykrywa światło czerwone, niebieskie lub zielone. Dlatego wszystkie kolory, które widzimy, są po prostu mieszaninami kolorów czerwonego, niebieskiego i zielonego.

![Dodawanie mieszania kolorów](images/additive-colour-mixing.png)

W przypadku dodawania kolorów, trzy kolory (czerwony, zielony i niebieski) są używane do tworzenia innych kolorów. Na powyższym obrazku znajdują się trzy reflektory o równej jasności, po jednej dla każdego koloru. W przypadku braku koloru wynik jest czarny. Jeśli wszystkie trzy kolory są zmieszane, wynikiem jest biały. Kiedy czerwień i zieleń łączą się, wynik jest żółty. Kiedy czerwony i niebieski łączą się, wynikiem jest magenta. Kiedy łączą się niebieskie i zielone, wynikiem jest błękitny. Można uzyskać jeszcze więcej kolorów, zmieniając jasność użytych trzech kolorów oryginału.

Komputery przechowują wszystko jako 1s i 0s. Te 1 i 0 są często zorganizowane w zestawy 8, zwane **bajtami**.

Pojedynczy bajt może reprezentować dowolną liczbę od 0 do 255.

Kiedy chcemy reprezentować kolor w programie komputerowym, możemy to zrobić, definiując ilość czerwonego, niebieskiego i zielonego, które tworzą ten kolor. Kwoty te są zwykle przechowywane jako jeden bajt a zatem jako liczba od 0 do 255.

Oto tabela przedstawiająca niektóre wartości kolorów:

| Czerwony | Zielony | niebieski | Kolor     |
| -------- | ------- | --------- | --------- |
| 255      | 0       | 0         | Czerwony  |
| 0        | 255     | 0         | Zielony   |
| 0        | 0       | 255       | niebieski |
| 255      | 255     | 0         | Żółty     |
| 255      | 0       | 255       | Magenta   |
| 0        | 255     | 255       | Cyan      |

Możesz znaleźć fajny selektor [kolorów do grania na w3schools](https://www.w3schools.com/colors/colors_rgb.asp){: target = "_ blank"}.