[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

1. Adım
Sol: [16, 21, 11]
Sağ: [8, 12, 22]

2. Adım
[16, 21] / [11]
[8, 12] / [22]

3. Adım - Diziler daha fazla bölünemez ve sıralıdır. O yüzden birleştirme işlemine geçilir.
[16, 21], [11] birleştirilir → [11, 16, 21]
[8, 12], [22] birleştirilir → [8, 12, 22]

4. Adım
[11, 16, 21], [8, 12, 22] birleştirilir → [8, 11, 12, 16, 21, 22]

Big-O Gösterimi:

En kötü durum (Worst-case): O(n log n)
En iyi durum (Best-case): O(n log n)
Ortalama durum (Average-case): O(n log n)
