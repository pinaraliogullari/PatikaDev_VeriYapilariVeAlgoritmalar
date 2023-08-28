Proje 3- BINARY SEARCH TREE

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.


 [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

           7  
          / \
         5    8
        / \   \
       1   6   9 
      / \   
     0   3  
        / \
       2   4  

AÇIKLAMA: 
Root:7
5, root'tan küçük olduğu için sola geçer.
1, 5'ten küçük olduğu için 5'in soluna geçer
8, root'tan büyük olduğu için sağa geçer
3, 1'den büyük 5'ten küçük olduğu için 1'in sağına geçer
6, 5'ten büyük ,7'den küçük olduğu için 5'in sağına geçer
0, 1'den küçük olduğu için 1'in soluna geçer
9, root'tan ve 8'den büyük olduğu için 8'in sağına geçer.
4, 3'ten büyük ,5'ten küçük olduğu için 3'ün sağına geçer.
2, 1'den büyük , 3'ten küçük olduğu için 3'ün soluna geçer.

       
      