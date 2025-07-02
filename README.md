# BinarySearchTreeProjesi
Binary Search Tree Projesi
Proje 3

İSTENENLER

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.


YANITLAR
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] -> Binary-Search-Tree

1. Eleman: Root 7'dir.
2. Eleman: 5 < 7 ------- 7’nin soluna 5 yazılır.
3. Eleman:
- 1 < 7 -------- sola git
- 1 < 5 → sola git ------- 5’in soluna 1 yazılır.
4. Eleman: 8 > 7  ---------  7’nin sağına 8 yazılır.
5. Eleman:
- 3 < 7 ------- sola
- 3 < 5 ------- sola
- 3 > 1 ------- 1’in sağına 3 yazılır.
6. Eleman:
- 6 < 7 ------- sola
- 6 > 5 ------- 5’in sağına 6 yazılır.
7. Eleman:
- 0 < 7 ----- sola
- 0 < 5 ----- sola
- 0 < 1 ----- 1’in soluna 0 yazılır.
8. Eleman:
- 9 > 7 ------ sağa
- 9 > 8 ----- 8’in sağına 9 yazılır.
9. Eleman:
- 4 < 7 ------ sola
- 4 < 5 -----sola
- 4 > 1 ------ sağa
- 4 > 3 ------ 3’ün sağına 4 yazılır.
10. Eleman:
- 2 < 7 ------ sola
- 2 < 5 ------- sola
- 2 > 1 -------- sağa
- 2 < 3 -------- 3’ün soluna 2 yazılır.


                7
              /   \
            5       8
          /   \       \
        1       6       9
      /   \
     0     3
         /   \
        2     4

* Root 7'dir.
* 7’nin solunda 5, sağında 8 vardır.
* 5’in solunda 1, sağında 6 vardır.
* 1’in solunda 0, sağında 3 bulunur.
* 3’ün solunda 2, sağında 4 vardır.
* 8’in sağında 9 yer alır.

