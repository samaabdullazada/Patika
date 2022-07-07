# Project 1: Insertion Sort

##  [22,27,16,2,18,6] verilen dizinin sort türüne göre aşamalarını yazınız.
 1. 2 ile 22-nin yerlerini değiştiriyoruz:
      [ 2 , 27 , 16 , 22 , 18 , 6 ] 
 2. 6 ile 27-nin yerlerini değiştiriyoruz:
      [ 2 , 6 , 16 , 22 , 18 , 27 ]
 3. Değişme yok:     
      [ 2 , 6 , 16 , 22 , 18 , 27 ]
 4. 22-le 18-in yerini değiştiriyoruz:
      [ 2 , 6 , 16 , 18 , 22 , 27 ]
 5. Değişme yok:     
      [ 2 , 6 , 16 , 18 , 22 , 27 ]
      
## Big-O gösterimini yazınız.
O(n^2)

## Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
 Tüm case-lerde O(n^2)
 
## Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
 Average case
 
## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
1. 7 ile 2-nin yerlerini değiştiriyoruz:  
    [ 2 , 3 , 5 , 8 , 7 , 9 , 4 , 15 , 6 ]
2. Değişme yok:   
    [ 2 , 3 , 5 , 8 , 7 , 9 , 4 , 15 , 6 ]
3. 5 ile 4-ün yerlerini değiştiriyoruz:  
    [ 2 , 3 , 4 , 8 , 7 , 9 , 5 , 15 , 6 ]
4. 8 ile 5-in yerlerini değiştiriyoruz:  
    [ 2 , 3 , 4 , 8 , 7 , 9 , 5 , 15 , 6 ]
