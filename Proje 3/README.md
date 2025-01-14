Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

1. Adım\
Root 7'dir.

2. Adım\
5<7, 7'nin soluna eklenir.

3. Adım\
1<7 ve 1<5, 7 ve 5'in soluna eklenir.

4. Adım\
8>7, 7'nin sağına eklenir.

5. Adım\
3<7, 3<5 ama 3>1. 7 ve 5'in soluna, 1'in sağına eklenir.

6. Adım\
6<7 ama 6>5. 7'nin soluna, 5'in sağına eklenir.

7. Adım\
0<7, 0<5, 0<1. 1'in soluna eklenir.

8. Adım\
9>7 ve 9>8, 8'in sağına eklenir.

9. Adım\
4<7, 4<5 ama 4>1 ve 4>3. 3'ün sağına eklenir

10. Adım\
2<7, 2<5 ama 2>1 ve 2<3. 3'ün soluna eklenir.

Son Hali\
       7
      / \
     5   8
    / \   \
   1   6   9
  / \
 0   3
    / \
   2   4
