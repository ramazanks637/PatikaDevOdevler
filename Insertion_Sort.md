# Patika_Insertion_Sort

Proje
[22,27,16,2,18,6] -> Insertion Sort

- A)Yukarý verilen dizinin sort türüne göre aþamalarýný yazýnýz.
- B)Big-O gösterimini yazýnýz.
- C)Time Complexity: Average case: Aradýðýmýz sayýnýn ortada olmasý,Worst case: Aradýðýmýz sayýnýn sonda olmasý, Best case: Aradýðýmýz sayýnýn dizinin en baþýnda olmasý.
- D)Dizi sýralandýktan sonra 18 sayýsý hangi case kapsamýna girer? Yazýnýz.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adýmýný yazýnýz.

A-Verilen dizinin sort türüne göre aþamalarý
 > - [22|,27,16,2,18,6];
 > - [22,27|,16,2,18,6];
 > - [16,22,27|,2,18,6];
 > - [2,16,22,27|,18,6];
 > - [2,16,18,22,27|,6];
 > - [2,6,16,18,22,27];
 > - Dizinin sýralanmýþ hali [2,6,16,18,22,27];
 
B-Big O Gösterimi
 > - O(n^2);
 
C-Time Complexity:
 > - Best Case  = [2,6,16,18,22,27];
 > - Worst Case = [27,22,18,16,6,2];

Dizi sýralandýktan sonra 18 sayýsý hangi case kapsamýna girer?
Sýralandýktan sonra 18 orta kýsýmda olduðu için average case kapsamýndadýr.
 
## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adýmýný yazýnýz.
> - [7|,3,5,8,2,9,4,15,6];
> - [3,7|,5,8,2,9,4,15,6];
> - [3,5,7|,8,2,9,4,15,6];
> - [3,5,7,8|,2,9,4,15,6];
  
 
