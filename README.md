# Insertion Sort
[22,27,16,2,18,6] -> Insertion Sort

## 1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
```bash
 [22,27,16,2,18,6] n
 [2,27,16,22,18,6] n-1
 [2,6,16,22,18,27] n-2
 [2,6,16,18,22,27] 1
```
## 2. Big-O gösterimini yazınız.
O($n^2$)

n+n-1+ n-2+1= $\frac{n*(n-1)}{2}$= $\frac{n^2-n}{2}$ => O($n^2$)

## 3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Time Complexity:O($n^2$)
Avarage Case:O($n^2$)
Worst Case:O($n^2$)
Best Case:O(n)
## 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
Average Case kapsamına girer.
[7,3,5,8,2,9,4,15,6]
dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```bash
 [7,3,5,8,2,9,4,15,6] n
 [2,3,5,8,7,9,4,15,6] n-1
 [2,3,4,8,7,9,5,15,6] n-2
 [2,3,4,5,7,9,8,15,6] n-3
```
