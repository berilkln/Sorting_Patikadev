## Binary Search Tree

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

1. ilk olarak root 7'dir. Sırasıyla 5 7'den küçüktür, sola eklenir.

```
     7
    /
   5 
```

2. 1 sayısı 7'den küçük sola, 5'den küçük sola
```
     7
    / 
   5
  /
 1
```

3. 8 sayısı 7'den büyük sağa eklenir.
```
      7
    /  \
   5    8
  /
 1
```
4. 3 sayısı 7'den küçük sola, 5'ten küçük sola, 1'den büyük 1'in sağına eklenir.
```
      7
     /  \
    5    8
   /
  1
   \
    3
```
5. 6 sayısı 7'den küçük sola, 5'ten büyük 5'in sağına eklenir.
```
      7
     /  \
    5    8
   / \
  1   6
   \
    3
```
6. 0 sayısı 7'den küçük sola, 0 5'ten küçük sola, 1'den küçük sola ekliyoruz.
```
       7
      /  \
     5    8
    / \
   1   6
  / \
 0   3
```   
7. 9 sayısı içinde aynı şekilde devam edersek
```
       7
      /  \
     5    8
    / \    \
   1   6    9
  / \
 0   3
``` 
8. adım
```
       7
      /  \
     5    8
    / \    \
   1   6    9
  / \
 0   3
      \
       4
``` 
9. adım
```
       7
      /  \
     5    8
    / \    \
   1   6    9
  / \
 0   3
    / \
   2   4
``` 



