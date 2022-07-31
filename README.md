# Merge-Sort
[16,21,11,8,12,22] -> Merge Sort

a) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

b) Big-O gösterimini yazınız.




a)          [16,21,11,8,12,22]
            /              \ 
   [16,21,11]              [8,12,22]           "array'i ikiye ayırma"
     /        \                /     \
  [16,21]   [11]           [8,12]   [22]        "array'i ikiye ayırma"
  /   \      |             /   \      |
 [16] [21]   [11]          [8] [12]  [22]        "array'i ikiye ayırma"
   \  /      |              \  /      |
 [16,21]   [11]           [8,12]   [22]        "sıralayarak birleştirme"
    \      /                 \     /
   [11,16,21]               [8,12,22]          "sıralayarak birleştirme"
             \            /
            [8,11,12,16,21,22]                  "sıralayarak birleştirme"
            
           

b) O(nlogn) -> Big-O Notation

[Merge Sort.txt](https://github.com/seymagulsen/Merge-Sort/files/9229406/Merge.Sort.txt)
