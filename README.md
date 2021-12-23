# Patika Insertion Sort
Proje 1

[22,27,16,2,18,6] -> Insertion Sort

  1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
  
  2.Big-O gösterimini yazınız.
  
  3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
  
  4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
  
  # 1. Soru
  
  1. Aşama -> [2,27,16,22,18,6]
  2. Aşama -> [2,6,16,22,18,27]
  3. Aşama -> [2,6,16,22,18,27] //16 ve 22 sıralaması normal olduğu için 2. aşama ile aynı sıralamadadır. 
  4. Aşama -> [2,6,16,18,22,27]

# 2. Soru
Big O gösterimi O(n^2) dir. 6 elaman olmasından dolayı O(6^2) = O(36) dır.

# 3. ve 4. Soru
18 sayısı 4. eleman olduğu için Avarage Case kapsamına girer.


# [7,3,5,8,2,9,4,15,6]  dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1. Adım -> [2,3,5,8,7,9,4,15,6]
2. Adım -> [2,3,5,8,7,9,4,15,6] // Bu adımda 3 sayısı yerinde olduğu için aynısı yazılmıştır. Bu yüzden 3. adımda 4 sayısına bakılmıştır.
3. Adım -> [2,3,4,8,7,9,5,15,6]
4. Adım -> [2,3,4,5,7,9,8,15,6
