Proje 1

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.
.



[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
1) Insertion Sort Adımları

Dizi: [22,27,16,2,18,6]

Başlangıç: [22, 27, 16, 2, 18, 6]

27, 22’den büyük → yerinde kalır → [22, 27, 16, 2, 18, 6]

16, 27’den küçük → sola kaydır → [22, 16, 27, 2, 18, 6]
16, 22’den küçük → sola kaydır → [16, 22, 27, 2, 18, 6]

2, 27’den küçük → sola kaydır → [16, 22, 2, 27, 18, 6]
2, 22’den küçük → sola kaydır → [16, 2, 22, 27, 18, 6]
2, 16’dan küçük → sola kaydır → [2, 16, 22, 27, 18, 6]

18, 27’den küçük → sola kaydır → [2, 16, 22, 18, 27, 6]
18, 22’den küçük → sola kaydır → [2, 16, 18, 22, 27, 6]

6, 27’den küçük → sola kaydır → [2, 16, 18, 22, 6, 27]
6, 22’den küçük → sola kaydır → [2, 16, 18, 6, 22, 27]
6, 18’den küçük → sola kaydır → [2, 16, 6, 18, 22, 27]
6, 16’dan küçük → sola kaydır → [2, 6, 16, 18, 22, 27]

Sonuç: [2, 6, 16, 18, 22, 27]

2) Big-O Gösterimi

Best Case (zaten sıralı dizi): O(n)

Worst Case (ters sıralı dizi): O(n²)

Average Case: O(n²)

Burada genel Big-O → O(n²)

3) Time Complexity’de 18’in Konumu

Sıralanmış dizi: [2, 6, 16, 18, 22, 27]

18, dizinin ortasında bulunduğu için → Average Case

4) Selection Sort İlk 4 Adım

Dizi: [7,3,5,8,2,9,4,15,6]

Başlangıç: [7, 3, 5, 8, 2, 9, 4, 15, 6]

1. adım: En küçük eleman 2 → 7 ile yer değiştir → [2, 3, 5, 8, 7, 9, 4, 15, 6]

2. adım: Kalan [3,5,8,7,9,4,15,6] içinde en küçük 3 → yerinde kalır → [2, 3, 5, 8, 7, 9, 4, 15, 6]

3. adım: Kalan [5,8,7,9,4,15,6] içinde en küçük 4 → 5 ile yer değiştir → [2, 3, 4, 8, 7, 9, 5, 15, 6]

4. adım: Kalan [8,7,9,5,15,6] içinde en küçük 5 → 8 ile yer değiştir → [2, 3, 4, 5, 7, 9, 8, 15, 6]
