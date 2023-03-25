Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.


****************************************************************************************
ÇÖzÜM:

1) İnsertion sort

[22,27,16,2,18,6] -> dizisini insertion sort ile küçükten büyüğe doğru sıraladığımızda

Algoritmamız çalıştığında 

1.adım [22,27,16,2,18,6] -> [2,27,16,22,18,6] 6 elemana bakarak en küçüğünü bulup 1.sıraya

2.adım [2,27,16,22,18,6] -> [2,6,16,22,18,27] kalan 5 eleman arasından en küçüğünü bulup 2. sıraya

3.adım [2,6,16,22,18,27] -> [2,6,16,22,18,27] kalan 4 eleman arasından en küçüğü 16 ve aynı yerde kaldı

4.adım [2,6,16,22,18,27] -> [2,6,16,18,22,27] kalan 3 eleman arasından en küçüğü 18 i 22 ile yer değiştirdi

5.adım [2,6,16,18,22,27] -> [2,6,16,18,22,27] kalan iki eleman sıralı olduğu için aynı kaldı

ve böylelikle 5 adımda dizimiz sıralanmış oldu.


2) Big O Gösterimi O(n^2)




Time Complexity: 18 sayısı dizinin ortasında ve bu durumda avarege case olur.


3-)[7,3,5,8,2,9,4,15,6] dizisini Selection sort ile sıralamak istediğimizde ilk 4 adım aşağıdaki gibi olacaktır.

[7,3,5,8,2,9,4,15,6]   mevcut olan dizi 

1.Adım: [2,3,5,8,7,9,4,15,6]
2.Adım: [2,3,4,8,7,9,5,15,6]
3.Adım: [2,3,4,5,7,9,8,15,6]
4.Adım: [2,3,4,5,6,9,8,15,7]

