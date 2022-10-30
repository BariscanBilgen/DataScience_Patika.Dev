# Insertion Sort 
```
[22,27,16,2,18,6] -> Insertion Sort ile alakalı soruların cevapları aşağıdadır.
```
## 1.Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

```
[22, 27, 16, 2, 18, 6] - n
[2, 27, 16,22, 18, 6] - n-1
[2,6, 16, 22, 18, 27] - n-2
[2,6, 16,18, 22, 27] - n-3
```

## 2. Big-O gösterimini yazınız.

```
(n*(n+1)/2) = (n^2 + n)/2 = n^2/2 + n/2
O(n^2)
```

## 3. Tanım
```
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
```

## 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

```
 - Average Case
```

## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

```
7 3 5 8 2 9 4 15 6
3 7 5 8 2 9 4 15 6
3 5 7 8 2 9 4 15 6 
2 3 5 7 8 9 4 15 6 
2 3 4 5 7 8 9 15 6
2 3 4 5 6 7 8 9 15
```

[patika.dev](https://app.patika.dev/) -> Başlangıç Seviye Veri Bilimi Patikası -> Veri Yapıları ve Algoritmalar