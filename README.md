# Proje1
www.patika.dev

[22,27,16,2,18,6] --> Insertion Sort

1)[22,27,16,2,18,6] --> [2,27,16,22,18,6] --> [2,6,16,22,18,27]--> [2,6,16,18,22,27]
2)İlk işlem + ikinci işlem derken n + (n-1) + (n-2) + ...+1 ==> Yani 1'den n'e kadar işlem yapılır.
1'den n'e kadar olan sayıların toplamı n(n+1)/2 Bu da (n*2 + n)/2 demektir. Big-O Notation'da önemli olan sayı baskın olduğu için n*2'dir.
Bu yüzden Bi-O Notation = O(n*2)

3)Soruyu tam anlamadım ama sanırım sorunun cevabı şu:
Best Case --> 16'dır. Çünkü yer değiştirmesine gerek kalmamıştır.
Average Case --> 18'dir. Çünkü nispeten daha az yer değiştirmiştir.
Worst Case --> Geriye kalanlar.

4)18 Average Case'tir.

Diğer soru: [7,3,5,8,2,9,4,15,6] -> [2,3,5,8,7,9,4,15,6](yer değiştirme yok pas geçeriz) -> [2,3,4,8,7,9,5,15,6]-> [2,3,4,5,7,9,8,15,6] ->[2,3,4,5,6,9,8,15,7]
