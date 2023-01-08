# MergeSortHomerwork

[16,21,11,8,12,22] -> Merge Sort

Temel prensip parçalara ayırıp tek eleman kalana kadar bölmek ve sıralamak.

--> [16,21,11] ve [8,12,22] olarak böldük. 
--> [16] , [21,11] , [8] ve [12,22] olarak ayırdık.
--> [16] , [21] , [11] , [8] , [12] ve [22] şeklinde tek elemana kadar ayırdık
     -        \    /      -       \    /
    [16],   [11,21]       [8],   [12,22]  şeklinde sıraladık.
        \   /                \  /
         [11,16,21]  ve     [8,12,22]     her iki dizinin sadece baş elemanları karşılaştırıldı ve küçük olan başa yazıldı.
         
     Son olarak da [8,11,12,16,21,22] haline geldi.
     
   
--> Dizinin Big-O gösterimi O(nlogn' dir.

#patika.dev ödevidir.
