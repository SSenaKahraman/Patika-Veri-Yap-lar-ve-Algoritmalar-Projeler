Proje 1
[22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

2. Big-O gösterimini yazınız.

3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.



CEVAPLAR:

1. SORU

27<22 ? [22, 27, 16, 2, 18, 6]

16<27 ? [22, 16, 27, 2, 18, 6]

16<22 ? [16, 22, 27, 2, 18, 6]

2<27 ? [16, 22, 2, 27, 18, 6]

2<22 ? [16, 2, 22, 27, 18, 6]

2<16 ? [2, 16, 22, 27, 18, 6]

18<27 ? [2, 16, 22, 18, 27, 6]

18<22 ? [2, 16, 18, 22, 27, 6]

18<16 ? [2, 16, 18, 22, 27, 6]

18<2 ? [2, 16, 18, 22, 27, 6]

6<27 ? [2, 16, 18, 22, 6, 27]

6<22 ? [2, 16, 18, 6, 22, 27]

6<18 ? [2, 16, 6, 18, 22, 27]

6<16 ? [2, 6, 16, 18, 22, 27]

6<2 ? [2, 6, 16, 18, 22, 27]

2. SORU: 

O (n^2)

3. SORU: 

Avarage Case: n^2

Worst Case: n^2
   
Best Case: n

4. SORU.

AVERAGE

5. SORU
 
A. [7, 3, 5, 8, 2, 9, 4, 15, 6]

[3, 7, 5, 8, 2, 9, 4, 15, 6]

[3, 5, 7, 8, 2, 9, 4, 15, 6]

[3, 5, 7, 2, 8, 9, 4, 15, 6]
      
[3, 5, 2, 7, 8, 9, 4, 15, 6] 



