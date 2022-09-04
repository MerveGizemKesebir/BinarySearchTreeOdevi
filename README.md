## Binary Search Tree Projesi

# Proje 3

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.


# Yanıt


Bir düğüm her iki tarafa da referans verebiliyor. Sağ ve sol olarak. Sağ tarafında kendinden büyük elemanlar, sol tarafında ise kendinden küçük elemanlar bulunacak.


Dizinin Root'u : 7.

Birinci Adım:
5 sayısı 7'den küçük olduğu için 7'nin soluna aldık.

İkinci Adım:
1 sayısı hem 7'den hem de 5'ten daha küçüktür. Bu yüzden ikisinin de soluna aldık.

Üçüncü Adım:
8 sayısına geldik ve sayımız 7'den büyük. Bu yüzden 7'nin sağına yazdık.

Dördüncü Adım:
3 sayısı 7'den ve 5'ten küçük; 1'den ise büyük. Bu yüzden 3'ü 7 ve 5'in soluna; 1'in ise sağına yazdık.

Beşinci adım:
6 sayısı 7'den küçük, 5'ten ise büyük. Bu yüzden 7'nin solunda; 5'in ise sağında yer almalı.

Altıncı Adım:
0 hem 7,5,3 ve 1'den küçük. Bu yüzden 1'in soluna yazılmalı.

Yedinci Adım:
9, 7'den büyük. Sağ tarafta olmalı. 8'den de büyük olduğu için 8'in sağına ekledik.

Sekizinci Adım:
4, 7'den ve 5'ten küçük. Bu yüzden bu sayıların solunda olmalı. Daha sonra 1'i görüyoruz. 1'den büyük olduğundan sağda olmalı. 1'in sağında 3 var. Sayımız 3'ten de büyük olduğu için 4'ü 3'ün sağına ekledik.

Dokuzuncu Adım:
Son sayımız 2. 7 ve 5'ten küçük bu yüzden solda olmalı. 1'den büyük olduğu için 1'in sağında yer almalı. 3'ten ise küçük. Bu yüzden 2'yi 3'ün sol tarafına yazıyoruz.


                                     7
                                     
                                /         \
                             5              8
                         /      \                \
                     1             6                9
                 /      \
             0            3
                        /    \
                      2        4

