# $\mathcal{Kartezyen\ Koordinat\ Sistemi}$
<p align="center">
    <img src="img/wtfamidoing.png">
</p>

## $\mathbb{R}^2 \text{ Düzlemi}$
Kartezyen koordinat sistemi $x$ ve $y$'de sonsuz sayı ile oluşur.
Kartezyen çarpımıyla ortaya çıkar:
$$\mathbb{R} \times \mathbb{R} = \mathbb{R}^2 \text{ düzlemi}$$
Burada $x$ ve $y$ her biri reel sayıları temsil eden sayı düzlemleridir
ve kartezyen işlemi sıralı ikili oluşturur.
$$(x,y) \text{ koordinat denir bunlara da}$$
$x$ ekseninin diğer ismi apsisler ekseni,
$y$ ise ordinatlar eksenidir.

## $\text{Bu sistemin diğer isimleri de vardır:}$
* Kartezyen Koordinat Sistemi
* Koordinat Düzlemi
* Analitik Düzlem

Bu sıralı ikililer bu düzlemdeki noktaları temsil eder:
* $A(1, 3)$
* $B(-2, 4)$
* $C(x, y)$

Sıralı ikilide $x$, $y$ eksenine olan uzaklığı gösterir
ve $y$ de $x$ eksenine olan uzaklığı gösterir.
Orjin ise $(0, 0)$ noktasıdır.

## $\text{İki Nokta Arası Uzaklık}$
Verilen iki nokta $A$ ve $B$ için aralarındaki uzaklık:
$$|AB| = \sqrt{(x_1 - x_2)^2 + (y_1 - y_2)^2}$$

## $\text{Orta Nokta Bulma Formülü}$
$$\text{Orta Nokta} = \left(\frac{x_1+x_2}{2}, \frac{y_1+y_2}{2}\right)$$

## $\text{Eğim Nedir?}$
Bir düzlem üzerindeki noktanın yatay düzlemdeki uzunluğuyla dikey düzlemdeki uzunluğuna oranıdır.
Dik kenarların birbirine oranı kısacası:
$$\text{eğim} = \frac{\text{dikeydeki uzunluk}}{\text{yataydaki uzunluk}}$$
$\text{-- doğrularda eğim sabittir}$

## $\text{Eğim Bulma Yöntemleri}$
Eğim bulmak için 3 temel yöntem vardır:

### $\text{1. Bir doğrunun üzerinde iki nokta verilmişse:}$
$$m = \frac{y_2 - y_1}{x_2 - x_1}$$
$\text{y'ler farkı / x'ler farkı al ve bitir}$

### $\text{2. Doğrunun denklemi biliniyorsa:}$
$ax+by+c=0$ VEYA $y=mx+n$

$y$ yalnız bırakıldığında ve katsayısı 1 olduğunda $x$'in katsayısı eğimdir.
Yani $y = mx + n$ durumunda eğim direkt olarak $m$'dir.

$ax+by+c=0$ durumunda ise:
$by = -ax-c$
$y = -\frac{a}{b}x - \frac{c}{b}$

Ve burada $y = mx + n$ olduğu için eğim yani $m$:
$$m = -\frac{a}{b} \text{ olur.}$$

### $\text{3. Doğrunun x ekseni ile yaptığı açı biliniyorsa:}$
$$m = \tan\alpha \text{ ile direkt olarak eğim bulunur}$$
Ve $\tan\alpha$ özelliğinden dolayı DİK açıların eğimi yoktur.

## $\text{Doğru Denklemi Yazma}$
Doğrunun denklemini yazmak için iki şey bilmemiz lazım:
1. Doğrunun eğimi = $m$
2. Doğrunun geçtiği bir nokta $(x_0, y_0)$

$$y - y_0 = m \cdot (x - x_0)$$

Doğrunun eksenleri kestiği noktaları biliyorsan kısa yoldan onun denklemini yazabilirsin:
$$\frac{x}{a} + \frac{y}{b} = 1$$
Burada $a$ ve $b$ sırasıyla doğrunun $x$ ve $y$ eksenlerini kestiği noktalardır.

## $\text{Üç Nokta Doğrusal mı?}$
$A$, $B$, $C$ olmak üzere 3 nokta olsun.
$|AB|$ nin eğimi $|BC|$ nin eğimine eşitse doğrusaldır.

## $\text{Doğruların Kesişme Noktası}$
Doğruların kesişme noktalarını bulmak için iki doğrunun da denklemlerini bulman gerekiyor:
$$y = a_1x + b_1$$
$$y = a_2x + b_2$$

Daha sonra bunları alt alta yazıp, $x$ veya $y$'yi yok edecek şekilde işlem yaparsın.

## $\text{Doğruların Özel Durumları}$
Doğrular birbirlerine dik ise eğimleri çarpımı $-1$ dir:
$$m_1 \cdot m_2 = -1$$

Çakışık olma durumları için ise doğrular aynı olmalı:
$$a_1x + b_1y + c_1 = 0$$
$$a_2x + b_2y + c_2 = 0$$

Çakışık doğrular için:
$$\frac{a_1}{a_2} = \frac{b_1}{b_2} = \frac{c_1}{c_2}$$

Yani doğrular birbirlerinin aynısı ama katsayılar oranı farklı olabilir.

Örnek verelim:
$$x + y = 4$$
$$3x + 3y = 12$$

Aynı doğru yani çakışıktır, çünkü:
$$\frac{1}{3} = \frac{1}{3} = \frac{-4}{-12} = \frac{1}{3}$$
