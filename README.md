# Merge-Sort-Projesi
Patika dev profilim icin [tiklayiniz.](https://app.patika.dev/ailker)

----
[16,21,11,8,12,22] -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

2. Big-O gösterimini yazınız.
-------
## 1.
* [16,21,11,8,12,22]
* [16,21,11]    [8,12,22]
* [16] [21,11]    [8,12] [22]
* [16]    [21]   [11]   [8]   [12]   [22]
* [16,21] [8,11] [12,22]
* [8,11,16,21] [12,22]
* [8,11,12,16,21,22]
-------
## 2.
Dizinin Big-O gösterimi O(n.logn)