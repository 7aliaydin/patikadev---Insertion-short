# patikadev---Insertion-short
1—> Verilen dizinin sort türüne göre aşamalarını yazınız.

Başlangıç
[22,27,16,2,18,6]
— Listedeki en küçük elemanı bul en başa yaz.
[2,27,16,22,18,6]
— 2. Sıradaki eleman için en küçüğü bul ve 2. Sıraya yaz.
[2,6,16,22,18,27]
—3. Sıradaki eleman için listenin kalanında en küçüğü arıyor değişiklik yok aynen kalsın
[2,6,16,22,18,27]
—4. Sıradaki eleman için en küçüğü bul ve 4. Sıraya yaz.
[2,6,16,18,22,27]
—3. Sıradaki eleman için listenin kalanında en küçüğü arıyor değişiklik yok aynen kalsın
[2,6,16,18,22,27]
2—>Big-O gösterimini yazınız.

1. Adımda n elemanı kontrol etti 
2.adımda (n-1) elamanı kontrol etti.
			.
			.
			.
		       +1
Liste bu hale gelene kadar (n) + (n-1) + (n -2) + … + 1 olarak devam etti bunların toplamıda

n(n - 1)
———    =  (n^2) -n / 2 bu durumda Big-O gösterimi O(n^2) —> n kare olara ifade edilir.
     2

3—>	Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Dizi sıralandıktan sonra 18 sayısı dizinin ortasında kaldığı için Average case kapsamına girer


Başlangıç
[7,3,5,8,2,9,4,15,6]
— Listedeki en küçük elemanı bul en başa yaz.
[2,3,5,8,7,9,4,15,6]
— 2. Sıradaki eleman için en küçüğü bul kalan e küçük zate ikinci sırada aynen bırak diğer adıma geç
[2,3,5,8,7,9,4,15,6]
—3. Sıradaki eleman için listenin kalanında en küçüğü arıyor bulduğunla 3.sıradakinin yerini değiştir.
[2,3,4,8,7,9,5,15,6]
—4. Sıradaki eleman için listenin kalanında en küçüğü arıyor bulduğunla 4.sıradakinin yerini değiştir.[2,3,4,5,7,9,8,15,6]
