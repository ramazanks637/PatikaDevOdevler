# Patika_Insertion_Sort

Proje
[22,27,16,2,18,6] -> Insertion Sort

- A)Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
- B)Big-O gösterimini yazınız.
- C)Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
- D)Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

A-Verilen dizinin sort türüne göre aşamaları
 > - [22|,27,16,2,18,6];
 > - [22,27|,16,2,18,6];
 > - [16,22,27|,2,18,6];
 > - [2,16,22,27|,18,6];
 > - [2,16,18,22,27|,6];
 > - [2,6,16,18,22,27];
 > - Dizinin sıralanmış hali [2,6,16,18,22,27];
 
B-Big O Gösterimi
 > - O(n^2);
 
C-Time Complexity:
 > - Best Case  = [2,6,16,18,22,27];
 > - Worst Case = [27,22,18,16,6,2];

Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?
Sıralandıktan sonra 18 orta kısımda olduğu için average case kapsamındadır.
 
## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
> - [7|,3,5,8,2,9,4,15,6];
> - [3,7|,5,8,2,9,4,15,6];
> - [3,5,7|,8,2,9,4,15,6];
> - [3,5,7,8|,2,9,4,15,6];
  
 
