# Patika.devProje
www.patika.dev
# Proje1
# [22,27,16,2,18,6] - Insertion Sort
# 1.Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
 * [22,27,16,2,18,6]    n 
  
 * [2,27,16,22,18,6]    n-1
  
 * [2,6,16,22,18,27]    n-2
  
 * [2,6,16,18,22,27]    1 
  
# 2.Big-O gösterimini yazınız.
 * (n.(n+1))/2
 * (n^2+n)/2
 *  O(n^2)
   
# 3.Time Complexity:
 * Average case: Aradığımız sayının ortada olması,
 * Worst case: Aradığımız sayının sonda olması,
 * Best case: Aradığımız sayının dizinin en başında olması.
 
# 4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
 * Dizimizin sıralanmış hali - [2,6,16,18,22,27] 
 * Dizi sıralandıktan sonra 18 sayısı dizinin ortasında bulunduğu için Average Case kapsamına girer.
 
# [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
 * [7,3,5,8,2,9,4,15,6]    n
 
 * [2,3,5,8,7,9,4,15,6]    n-1
 
 * [2,3,4,8,7,9,5,15,6]    n-2
 
 * [2,3,4,5,7,9,8,15,6]    n-3
 
# Proje2
# [16,21,11,8,12,22] - Merge Sort

# Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
 * Merge Sort olduğu için dizi parçalara bölünür 
  
             [16,21,11,8,12,22]
              /              \
     [16,21,11]              [8,12,22]
     
      /      \                /      \
     [16]   [21,11]          [8]    [12,22]
       /      \                /      \
     [16]   [11,21]          [8]    [12,22]
          \                       /   
     [11,16,21]              [8,12,22] 
          \                       /  
             [8,11,12,16,21,22]
# Big-O gösterimini yazınız.
