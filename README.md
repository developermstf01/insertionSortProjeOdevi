# insertionSortProjeOdevi
Patika dev için hazırladığım ödev. www.patika.dev

İnsertion Sort Aşaması:
[22,27,16,2,18,6] -> [2,27,16,22,18,6] -> [2,6,16,22,18,27] -> [2,6,16,18,22,27]

Merge Sort Aşaması:
[22,27,16,2,18,6] -> [22,27,16] [2,18,6] -> [22] [27,16] [2] [18,6] -> [22] [27] [16] [2] [18] [6] -> [16,22,27] [2,6,18] -> [2,6,16,18,22,27]

Quick Sort Aşaması:
[22,27,16,2,18,6] -> Pivot [16] -> [2,6] [16] [18,22,27] -> Pivot [2] ve [22] -> [6] [18] [27]

[22,27,16,2,18,6] dizisinin Big-O gösterimi (insertion sort olarak) -> 6^2

Dizi sıralandıktan sonra 18 sayısını aramamız Average Case kapsamına girer.

[7,3,5,8,2,9,4,15,6] dizisinin insertion sorta göre ilk 4 adımı -> [7,3,5,8,2,9,4,15,6] -> [2,3,5,8,7,9,4,15,6] -> [2,3,4,8,7,9,5,15,6] -> [2,3,4,5,7,9,8,15,6] -> [2,3,4,5,6,9,8,15,7]
