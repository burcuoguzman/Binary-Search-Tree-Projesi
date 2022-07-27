# Patika.dev Linkim
https://app.patika.dev/burcuoguzman

# Binary-Search-Tree-Projesi
1- [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

# Soru 1
root: 7
5<7 olduğu için 5 7'nin solunda yer alır.

      7
     /
    5
    
1<7 olduğu için 1 7'nin soluna, 1<5 olduğu için 5'in de soluna yerleşecektir.

        7
       /
      5
     /
    1
  
8>7 olduğu için 8 7'nin sağına yerleşecektir.

        7
       / \
      5   8
     /
    1
 
3<7 olduğu için 3 7'nin soluna, 3<5 olduğu için 5'in soluna, 3>1 olduğu için 1'in sağına yerleşecektir.

        7
       / \
      5   8
     /
    1
     \
      3
  
 6<7 olduğu için 6 7'nin soluna, 6>5 olduğu için 5'in sağına yerleşecektir.
 
        7
       / \
      5   8
     / \
    1   6
     \
      3
  
  0<7 olduğu için 0 7'nin soluna, 0<5 olduğu için 5'in soluna, 0<1 olduğu için 1'in soluna yerleşecektir.
  
          7
         / \
        5   8
       / \
      1   6
     / \
    0   3

9>7 olduğu için 9 7'nin sağına, 9>8 olduğu için 8'in de sağına yerleşecektir.

          7
         / \
        5   8
       / \   \
      1   6   9
     / \
    0   3

4<7 olduğu için 7'nin soluna, 4<5 olduğu için 5'in soluna, 4>1 olduğu için 1'in sağına, 4>3 olduğu için 3'ün sağına yerleşecektir.

          7
         / \
        5   8
       / \   \
      1   6   9
     / \
    0   3
         \
          4
      
2<7 olduğu için 7'nin soluna, 2<5 olduğu için 5'in soluna, 2>1 olduğu için 1'in sağına, 2<3 olduğu için 3'ün soluna yerleşecektir.

          7
         / \
        5   8
       / \   \
      1   6   9
     / \
    0   3
       / \
      2   4
      

  
