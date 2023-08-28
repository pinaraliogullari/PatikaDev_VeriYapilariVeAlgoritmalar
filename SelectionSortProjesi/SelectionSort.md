Proje 1 SELECTION SORT


[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

---CEVAPLAR---

-1. ADIM
22|   27, 16, 2, 18, 6  

-2. ADIM
22, 27| 16, 2, 18, 6 
 
-3. ADIM
22, 16, 27|  2, 18, 6

16, 22, 27|  2, 18, 6 

-4. ADIM

16, 22, 2, 27|   18, 6

16, 2, 22, 27|   18, 6
 
2, 16, 22, 27|   18, 6

-5. ADIM  

2, 16, 22, 18, 27|  6
 
2, 16, 18, 22, 27|  6 

2, 16, 18, 22, 6, 27|  

2, 16, 18, 6, 22, 27| 

2, 16, 6, 18, 22, 27|  

2, 6, 16, 18, 22, 27| 

 -DİZİNİN SON HALİ

[2, 6, 16, 18, 22, 27]




**   n.(n+1)/2 şeklinde hesaplanır.  =(n^2+n)/2
Big-O GÖSTERİMİ: n^2



Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? 

1.  Average case: Aradığımız sayının ortada olması
2.  Worst case: Aradığımız sayının sonda olması
3.  Best case: Aradığımız sayının dizinin en başında olması.

 Average case: Aradığımız sayının ortada olması.


[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.


 1. ADIM
 2|  3, 5, 8, 7, 9, 4, 15, 6

 2. ADIM
 2, 3| 5, 8, 7, 9, 4, 15, 6
 
 3. ADIM
 2, 3, 4|  8, 7, 9, 5, 15, 6
  
 4. ADIM
 2, 3, 4, 5| 7, 9, 8, 15, 6

Soruda ilk 4 adım sorulduğu için dizinin son hali:  
 **[2, 3, 4, 5, 7, 9, 8, 15, 6]**
