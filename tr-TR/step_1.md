Bir nesnenin rengi, yansıttığı veya yaydığı ışığın rengine bağlıdır. Işık farklı dalga boylarına sahip olabilir ve ışığın rengi de sahip olduğu bu dalga boyuna bağlıdır. Işığın sahip olduğu dalga boyuna göre rengi aşağıdaki şemada görülebilir. Bu renkleri gök kuşağının renklerinden tanıyabilirsin.

![Görünür spektrum](images/linear-visible-spectrum.png)

İnsanoğlu renkleri gözlerindeki özel hücreler sayesinde algılayabilir. Bu hücreler *konik hücre* olarak isimlendirilir. Üç tür konik hücreye sahibiz ve bu hücreler her tür kırmızı, mavi veya yeşil ışığı algılar. Dolayısıyla gördüğümüz tüm renkler aslında sadece kırmızı, mavi ve yeşil renklerin karışımıdır.

![İlave renk karışımı](images/additive-colour-mixing.png)

Renk karışımlarında diğer renkleri elde etmek için üç renk (kırmızı, yeşil ve mavi) kullanılır. Yukarıdaki resimde, her bir renk için eşit parlaklığa sahip üç spot ışık vardır. Herhangi bir rengin yokluğunda sonuç siyahtır. Üç rengin tamamı karıştırıldığında, sonuç beyaz olur. Kırmızı ve yeşil birleştirildiğinde sonuç sarıdır. Kırmızı ve mavi birleştiğinde, sonuç eflatun olur. Mavi ve yeşil birleştirildiğinde sonuç camgöbeğidir. Kullanılan üç orijinal rengin parlaklığını değiştirerek bundan daha fazla renk elde etmek mümkündür.

Bilgisayarlar her şeyi 1 ve 0 olarak depolar. Bu 1'ler ve 0'lar, ** byte olarak adlandırılan 8 kümeye ayrılmıştır. **.

Bir  bayt  0 ile 255 arasında herhangi bir sayıyı temsil edebilir.

Bir bilgisayar programında bir rengi ifade etmek istediğimizde bunu, rengi oluşturan kırmızı, mavi ve yeşil miktarlarını tanımlayarak yapabiliriz. Bu miktarlar genellikle tek bir byte olarak depolanır ve bu, 0 ile 255 arasında bir sayı olmalıdır.

İşte bazı renk değerlerini gösteren bir tablo:

| Kırmızı | Yeşil | Mavi | Renk      |
| ------- | ----- | ---- | --------- |
| 255     | 0     | 0    | Kırmızı   |
| 0       | 255   | 0    | Yeşil     |
| 0       | 0     | 255  | Mavi      |
| 255     | 255   | 0    | Sarı      |
| 255     | 0     | 255  | Eflatun   |
| 0       | 255   | 255  | Camgöbeği |

[W3schools'da oynayabileceğiniz güzel bir renk seçici bulabilirsiniz.](https://www.w3schools.com/colors/colors_rgb.asp) {:target="_blank"}.