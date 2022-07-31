# patika.dev-bst-Projesi

# Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.


root= 7 değeri alınmıştır.

7'den küçük olan değerleri  sol tarafa ekleriz.

         7
       /
      5
 
Sıradaki 1 değeri, 7'den küçük olduğu için 7'nin soluna, 5 den de küçük olduğu için 5'in de soluna eklenir.

         7
       /
      5
     /
    1
    
Sıradaki 8 değeri, 7'den büyük olduğu için 7'nin sağına eklenir.  
       
       7
      / \
     5   8
    /
   1   
  
Sıradaki 3 değeri 7 den küçük olduğu için soluna, 5'den küçük olduğu için soluna, 1'den büyük olduğu için sağına yazılır.
   
       7
      / \
     5   8
    /
   1
    \
     3
     
Sıradaki 6 değeri 7 den küçük olduğu için soluna, 5'den büyük olduğu için sağına yazılır.
   
        7
       / \
      5   8
     / \
    1   6
     \
      3
      
Sıradaki 0 değeri 7 den küçük olduğu için soluna, 5'den küçük olduğu için soluna, 1'den küçük olduğu için soluna yazılır.
      
        7
       / \
      5   8
     / \
    1   6
   / \
  0   3
 
 Sıradaki 9 değeri 7 den büyük olduğu için sağına, 8'den büyük olduğu için sağına yazılır.
 
         7
       / \
      5   8
     / \   \
    1   6   9
   / \
  0   3
  
  Sıradaki 4 değeri 7 den küçük olduğu için soluna, 5'den küçük olduğu için soluna, 1'den büyük olduğu için sağına, 3'den büyük olduğu için sağına yazılır.
  
         7
        / \
       5   8
      / \   \
     1   6   9
    / \
   0   3
        \
         4

Son sıradaki 2 değeri 7 den küçük olduğu için soluna, 5'den küçük olduğu için soluna, 1'den büyük olduğu için sağına, 3'den küçük olduğu için soluna yazılır.

         7
        / \
       5   8
      / \   \
     1   6   9
    / \
   0   3
      / \
     2   4
