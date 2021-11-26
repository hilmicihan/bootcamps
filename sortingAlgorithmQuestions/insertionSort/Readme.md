### Insertion Sort Projesi
### Questions
[22,27,16,2,18,6] 
1-Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

2-Big-O gösterimini yazınız.

3-Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

4-Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

### Answers
#### q1-)
[22,16,27,2,18,6] -> [16,22,27,2,18,6] -> [16,22,2,27,18,6] ->  [16,2,22,27,18,6] -> [2,16,22,27,18,6] -> [2,16,22,18,27,6]
-> [2,16,18,22,27,6] -> [2,16,18,22,6,27] -> [2,16,18,6,22,27] -> [2,16,6,18,22,27] -> [2,6,16,18,22,27]

#### q2-)
O(n*n)
#### q3-)
Best -> O(n)

Average -> O(n*n)

Worst -> O(n*n)

#### q4-)
18 is average case 

#### q5-) 
[7,3,5,8,2,9,4,15,6] first 4 steps.

[7,3,5,8,2,9,4,15,6] -> [3,7,5,8,2,9,4,15,6] -> [3,5,7,8,2,9,4,15,6] -> [3,5,7,8,2,9,4,15,6] ->  [3,5,7,2,8,9,4,15,6]



