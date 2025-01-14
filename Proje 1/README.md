1-[22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

[22,27,16,2,18,6] (n)\
[22,27,16,2,18,6] (n-1)\
[16,22,27,2,18,6] (n-2)\
[2,16,22,27,18,6] (n-3)\
[2,16,18,22,27,6] (n-4)\
[2,6,16,18,22,27] (n-5)

2- Big-O gösterimini yazınız.

En iyi durum (Best Case): O(n) (Dizi zaten sıralı olduğunda)\
En kötü durum (Worst Case): \
O(n^2) (Dizi ters sıralı olduğunda)\
Ortalama durum (Average Case): O(n^2)

3- Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması\
Worst case: Aradığımız sayının sonda olması\
Best case: Aradığımız sayının dizinin en başında olması.

18 dizinin ortalarına denk geldiği için Average Case kapsamına girer.

4-[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

[2, 3, 5, 8, 7, 9, 4, 15, 6]\
[2, 3, 5, 8, 7, 9, 4, 15, 6]\
[2, 3, 4, 8, 7, 9, 5, 15, 6]\
[2, 3, 4, 5, 7, 9, 8, 15, 6]