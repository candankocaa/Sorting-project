Insertion Sort Aþamalarý  

Verilen dizi: `[22,27,16,2,18,6]`  

-Adým Adým Insertion Sort
1. `[22, 27, 16, 2, 18, 6]` (Baþlangýç)  
2. `[2, 27, 16, 22, 18, 6]` (Dizideki en küçük sayý olan 2 ile 22 yer deðiþtirilir.)  
3. `[2, 6, 16, 22, 18, 27]` (2 sabit kaldý kalan elemanlar arasýndan en küçük olan 6 ile 27 yer deðiþtirilir.)  
4. `[2, 6, 16, 22, 18, 27]` (Kalan elemanlar arasýnda en küçük zaten 16 olduðundan böyle kalýr.)  
5. `[2, 6, 16, 18, 22, 27]` (Kalan elemanlar arasýnda en küçük 18 olduðundan 18 ve 22 yer deðiþtirilir.)  
5. `[2, 6, 16, 18, 22, 27]` (Kalan iki eleman arasýnda en küçük 22 olduðundan 22 yerinde kalýr ve insertion sort tamamlanýr.)  


-Big-O Gösterimi  
- Insertion Sort en kötü durumda (O(n²)); en iyi durumda ise (O(n)) çalýþýr.  

-18 Sayýsýnýn Zorluk Durumu  
Average Case olmalý çünkü 18 ortalarda yer alýyor.  

---

Selection Sort ile Ýlk 4 Adým
Dizi: `[7,3,5,8,2,9,4,15,6]`  
1. `[2,3,5,8,7,9,4,15,6]` (En küçük 2 baþa alýndý)  
2. `[2,3,5,8,7,9,4,15,6]` (3 zaten doðru yerde)  
3. `[2,3,4,8,7,9,5,15,6]` (4 ve 5 yer deðiþtirir)  
4. `[2,3,4,5,7,9,8,15,6]` (5 ve 8 yer deðiþtirir)  
