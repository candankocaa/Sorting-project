Insertion Sort A�amalar�  

Verilen dizi: `[22,27,16,2,18,6]`  

-Ad�m Ad�m Insertion Sort
1. `[22, 27, 16, 2, 18, 6]` (Ba�lang��)  
2. `[2, 27, 16, 22, 18, 6]` (Dizideki en k���k say� olan 2 ile 22 yer de�i�tirilir.)  
3. `[2, 6, 16, 22, 18, 27]` (2 sabit kald� kalan elemanlar aras�ndan en k���k olan 6 ile 27 yer de�i�tirilir.)  
4. `[2, 6, 16, 22, 18, 27]` (Kalan elemanlar aras�nda en k���k zaten 16 oldu�undan b�yle kal�r.)  
5. `[2, 6, 16, 18, 22, 27]` (Kalan elemanlar aras�nda en k���k 18 oldu�undan 18 ve 22 yer de�i�tirilir.)  
5. `[2, 6, 16, 18, 22, 27]` (Kalan iki eleman aras�nda en k���k 22 oldu�undan 22 yerinde kal�r ve insertion sort tamamlan�r.)  


-Big-O G�sterimi  
- Insertion Sort en k�t� durumda (O(n�)); en iyi durumda ise (O(n)) �al���r.  

-18 Say�s�n�n Zorluk Durumu  
Average Case olmal� ��nk� 18 ortalarda yer al�yor.  

---

Selection Sort ile �lk 4 Ad�m
Dizi: `[7,3,5,8,2,9,4,15,6]`  
1. `[2,3,5,8,7,9,4,15,6]` (En k���k 2 ba�a al�nd�)  
2. `[2,3,5,8,7,9,4,15,6]` (3 zaten do�ru yerde)  
3. `[2,3,4,8,7,9,5,15,6]` (4 ve 5 yer de�i�tirir)  
4. `[2,3,4,5,7,9,8,15,6]` (5 ve 8 yer de�i�tirir)  
