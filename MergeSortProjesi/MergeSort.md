
Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.




---CEVAPLAR---
---Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
 [16,21,11,8,12,22]

İlk adım olarak verilen diziyi ikiye bölüyoruz. Daha sonra her iki dizide de tek eleman kalana kadar bölmeye devam ediyoruz.
    
   
 -        [16, 21, 11, 8, 12, 22] 
 [[16, 21, 11]                   [8, 12, 22]]  
[[[16], [21, 11]]               [[8], [12, 22]]]  
[[[[16]], [[21], [11]]]      [[[8]], [[12],[22]]]]  
 
 2. bu aşamada küçük parçaları karşılaştırarak sıralıyoruz.

       [[[[16]], [[21], [11]]], [[[8]], [[12], [22]]]] 
[[[16], [11, 21]]                             [[8], [12, 22]]]  
 [[11, 16, 21]                                 [8, 12, 22]]  


SONUÇ: [8, 11, 12, 16, 21, 22]  



---Big-O gösterimini yazınız.


(n log n) 
