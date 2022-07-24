#Patika Insertion Sort Projesi
---
##[22,27,16,2,18,6]
##1-Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

1-[|2|,27,16,22,18,6] (n)
2-[|2,6|,16,22,18,27] (n-1)
3-[|2,6,16|,22,18,27] (n-2)
4-[|2,6,16,18|,22,27] (n-3)
5-[|2,6,16,18,22|,27] (n-4)

##2-Big-O gösterimini yazınız.
Worst Case: O(n^2^) = n+(n-1)+(n-2)...+1
Average Case: O(n^2^)
Best Case: O(n)

##3-Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
Dizimiz küçükten büyüğe sıralandıktan sonra [2,6,16,18,22,27] şeklini alır ve 18 sayısı bu dizinin ortanca değeridir. Yani average case diyebiliriz.

##4-[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1- [|2|,3,5,8,7,9,4,15,6]
2- [|2,3|,5,8,7,9,4,15,6]
3- [|2,3,4|,8,7,9,5,15,6]
4- [|2,3,4,5|,7,9,8,15,6]

[Patika.Dev](https://www.patika.dev)
