Insertion Sort Projesi
Proje 1

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

1.İlk eleman sıralı [22,27,16,2,18,6]
2.22>27 old. için yerinde kalır [22,27,16,2,18,6]
3.16 sola kaydırılır [16,22,27,2,18,6]
4.2 en başa kaydırılır [2,16,22,27,18,6]
5.18 doğru yere yerleştirilir [2,16,18,22,27,6]
6.6 doğru yere yerleştirilir [2,6,16,18,22,27]

Big-O gösterimini yazınız.
Best case: O(n) liste zaten sıralıdır.
Average case: O(n2) liste rastgele sıralıdır.
Worst case:O(n2) liste ters sıralıdır.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

- 18 sayısı listede sona doğru yer aldığı ama tam sonda yer almadıgı için Average case olarak tanımlayabiliriz.
  Average case: Aradığımız sayının ortada olması
  Worst case: Aradığımız sayının sonda olması
  Best case: Aradığımız sayının dizinin en başında olması.
  .

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
dizideki minimum elemanı bul ve baştaki ile kıyasla baştakinden küçükse yer değiştir.

1. minimum eleman (2) ilk eleman (7) ile yer değiştirir.[2,3,5,8,7,9,4,15,6]
2. kalan [3,5,8,7,9,4,15,6] içinde minimum 3`tür ve aynen kalır.
3. kalan [5,8,7,9,4,15,6] içinde minimum 4'tür. 5 ile yer değiştirir.[2,3,4,8,7,9,5,15,6]
4. kalan [8,7,9,5,15,6] içinde minimum 5'tir. 5 ile 8 yer değiştirir. [2,3,4,5,7,9,8,15,6]
