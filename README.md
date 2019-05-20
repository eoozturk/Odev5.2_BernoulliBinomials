<p align="left">
<a href="https://colab.research.google.com/drive/1YWFTjK4xxRr2ddzlfn2rCR7q1yDNABj8" target="_blank">
 <img src="https://colab.research.google.com/assets/colab-badge.svg" width="110" height="50" border="10"  />
</a>
 
<a href="https://colab.research.google.com/drive/12cEMUiXhcIGe_80oT2iqCIFxN4TAiiRs" target="_blank">
 <img src="https://colab.research.google.com/assets/colab-badge.svg" width="110" height="50" border="10" align="right"/>
</a>
</p>   

# Bernoulli ve Binomials
Bernoulli ve Binomials ile İlgili Soru ve Çözümü, <a href="http://content.lms.sabis.sakarya.edu.tr/Uploads/48396/27636/13._%C3%B6zel_olas%C4%B1l%C4%B1k_da%C4%9F%C4%B1l%C4%B1mlar%C4%B1.pdf" target="_blank">Soru Kaynağı</a>

## Soru 1: Bernoulli
Bir öğrenci istatistik dersinden geçme olasılığının 0.7 olduğuna inanmaktadır. Olasılık dağılımının fonksiyonunu yazınız. Beklenen Değer "E[X]" ve Varyansını "Var[X]" hesaplayınız.

### Çözüm:
Öğrenci dersten geçerse X rassal değişkeni k = 1 ve kalırsa k = 0 değerini alsın:

P (k=1) = 0.7 ve P (k=0) = 0.3 ise,

P(X=1)= 0.7^1 x (1-0.7)^0= 0.7^1 x 0.3^0= 0.7

P(X=0)= 0.7^0 x (1-0.7)^1= 0.7^0 x 0.3^1= 0.3

E[X] = p = 0.7

Var[X]= p (1 – p) = 0.7 x 0.3= 0.21

Soruda ilk olarak başarı ve başarısızlık durumları p ve q belirlenir. Daha sonra bernoulli kuralına göre başarı ve başarısızlığın olasılık dağılım fonksiyonları P(X=1) ve P(X=0) yazılır. Daha sonra ise yine bernoulli kuralına göre beklenen değer "E[X]" ve varyans "Var[X]" hesaplanır.

### Açıklama:
Bir deneyde başarı ve başarısızlık diye nitelendirilen iki sonuçla ilgilenildiğinde bu deneye (iki sonuçlu) Bernoulli deneyi ya da Bernoulli denemesi denir.

Başarı olasılığı: p ,  Başarısızlık olasılığı: 1-p= q

P(X=k)= p^k (1-p)^1-x, k=0,1

E[X]= p

Var[X]= pq

Soruda ilk olarak başarı ve başarısızlık durumları p ve q belirlenir. Daha sonra bernoulli kuralına göre başarı ve başarısızlığın olasılık dağılım fonksiyonları P(X=1) ve P(X=0) yazılır. Daha sonra ise yine bernoulli kuralına göre beklenen değer "E[X]" ve varyans "Var[X]" hesaplanır.

## Soru 2: Binomials
Bir madeni para N kere atılmaktadır. 0 tane,1 tane,2 tane ve 3 tane yazı gelme olasılıkları sırasıyla nedir? Beklenen değer(Aritmetik ortalama) ve Varyansını hesaplayınız. 

### Çözüm:
N=4 için:

0 tane Yazı Gelme Olasılığı:

P(X=0) = 4!/(4-0)!x0! x 0.5^0x0.5^4 = 0.0625

1 tane Yazı Gelme Olasılığı:

P(X=1) = 4!/(4-1)!x1! x 0.5^1x0.5^3 = 0.25

2 tane Yazı Gelme Olasılığı:

P(X=2) = 4!/(4-2)!x2! x 0.5^2x0.5^2 = 0.375

3 tane Yazı Gelme Olasılığı:

P(X=3) = 4!/(4-3)!x3! x 0.5^3x0.5^1 = 0.25

E[X] = nxp = 4x0.5 = 2

Var[X] = nxpx(1-p) = 4x0.5 x (1-0.5)= 1

### Açıklama:

Başarı olasılığı p olan bir Bernoulli deneyinin aynı şartlar altında (bağımsız olarak) n kez tekrarlanması ile oluşan deneylerdir.

P(X=k)= C(n,k) p^k(1-p)^n-k , k= 0,1,2......,n

E[X]= np

Var[X]= np(1-p)

Hesaplamalar sırasında kullanılacak olan paranın yazı gelme olasılığı "p=0.5" olarak alınır. Soruda istenilene göre ilk önce 0, 1 ,2, ve 3 tane yazı gelme olasılıkları sırası ile binomials kuralına göre hesaplanır. Daha sonra beklenen değer "E[X]" ve son olarak da binomials kuralına göre varyans "Var[X]" hesaplanır.
