# Veri Yapları ve Algoritmalar Proje-1-2-3
Bu repo [Patika.dev](https://www.patika.dev/tr) Temel Matematik odev konusunu içerir.

<p align="center" width="100%">
    <img width="25%" src="https://global-uploads.webflow.com/6097e0eca1e87557da031fef/609859a191abe5d64b17fed3_Patika%20logo-p-500.png"> 
</p>

# Content

**Oran-Orantı-Fibonacci**

Doğa matematik tarafından yönetilir ve sanatın başyapıtları doğa ile uyumludur;
doğanın yasalarını ifade ederler ve bu yasalardan hareket ederler. Sonuç olarak, onlar
da matematiğe tabidir [Le Corbusier, 2014, Modulor]

Oranın başlangıcı, saymanın başlangıcı ve tüm matematiğin başlangıcı gibi, bir ile iki
arasındaki geçiştir. Sayma, birimi kendisine ekleyerek başlar; birim tanımı gereği
bölünemez olduğu için, birime eklenecek daha küçük bir şey yoktur. Kendisine bir tane ekleriz ve iki tane alırız (bkz. Şekil 2.1). Bu ilk adımı attığımızda, devam etmenin
iki yolu vardır:

1. İlk ve en belirgin yöntem toplama işlemidir. Birim, en son oluşturulan sayıya
eklenmeye devam edilir ve böylece sayımda kullanılan basit aritmetik dizi elde edilir:
1, 2, 3, 4, 5... Sürekli birim eklenerek oluşturulan bu tür bir ilerleme,
dizi terimlerinin tüm olası toplamlarını içerdiğinden sonsuz derecede esnektir. Ancak
rakamlar büyüdükçe, birim sabit olmaktadır. Ardışık elemanlar arasındaki oranlar her
aşamada azalır, daha az algılanabilir, bütün olarak daha az önemli hale gelir. Elemanların birbirleri ile oranı aynı değildir.

2. Birimi, sürekli olarak oluşturulan son sayıya eklemek yerine, bir sonraki sayıyı
üretmek için her sayı bir sabit ile çarpılabilir. Örneğin, sabit çarpan 2 ise, 1, 2, 4, 8, 16,
vb. bu şekilde geometrik dizi elde edilir.

Geometrik ortalama, daha yüksek ve daha düşük bir terim
arasındaki orta terim, daha yüksek ortalama anlamına gelir. A ve C iki terimdir ve B
geometrik ortalamaları ise, A/B = B/C. İki sayının geometrik ortalaması aynı zamanda
elemanların kareköküne de eşittir: B=√𝐴. 𝐵. 

Aritmetik ortalama, hem toplamlarını
hem de farklarını iki eşit parçaya bölen diğer iki terim arasındaki orta terimdir. B, A
ve C terimi arasındaki aritmetik ortalama ise, B = (A + C) / 2.
Harmonik ortalama, farklarını iki terimin birbirine oranla aynı oranda bölen iki terim
arasındaki orta terimdir. B = 2AC / (A + C) olduğunda A ve C arasındaki harmonik
ortalamadır. Eleman sayısının, elemanların çarpma işlemine göre tersinin toplamına
bölümüne denir.

Kontraharmonik ortalama.
Adından da anlaşılacağı gibi, bu iki uç nokta arasındaki farkı harmonik ortalamanın
tersine böler. A ve C'nin kontraharmonik ortalaması B ise, B = (A2 + C2) / (A + C) 

Fibonacci sayıları özyinelemeli bir matematik dizisi ile üretilir. Fibonacci sayıları 0 ile
başlayarak 1 ile sonuçlanan bir diziden üretilir. Bir önceki elemana 1 eklenir, sonuç 2
sayısıyla sonuçlanır. Bu mantığı takiben, dizide her sayıya kendinden bir önceki sayı
eklenerek bir sonraki sayı elde edilir.

0   1   1   2   3   5   8   13  21  34  55

(0+1) (1+1) (2+1) (3+2) (5+3) (8+5) (13+8) (21+13) (34+21)

<p align="center" width="100%">
    <img width="25%" src=https://upload.wikimedia.org/wikipedia/commons/thumb/1/15/Fibonacci_Squares.svg/1920px-Fibonacci_Squares.svg.png> 
</p>
        
# Installation
Öncelikle projeyi klonlayın.(Buraya sizin reponuzdan aldığınız link gelecek)
```
git clone https://github.com/ilkaysefer/PatikaVeriBilimineGiris.git
```

# Usage

Projeyi klonladıktan sonra Visual Studio Code programında açınız.

Linux için:
```
cd Veri Yapları ve Algoritmalar Proje-1-2-3
code .
```

# Contributing

Pull requestler kabul edilir. Büyük değişiklikler için, lütfen önce neyi değiştirmek istediğinizi tartışmak için bir konu açınız.

# License
[MIT](https://choosealicense.com/licenses/mit/)
