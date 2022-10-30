# Merge Sort 

## [16,21,11,8,12,22] -> Merge Sort le alakalı soruların cevapları aşağıdadır.


## 1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

```
Divide -1  [16,21,11] [8,12,22]
Divide -2  [16] [21,11] [8] [12,22]
Divide -3  [16] [21] [11] [8] [12] [22]
Merge -1  [16] [11,21] [8] [12,22]
Merge -2  [11,16,21] [8,12,22]
Merge -3  [8,11,12,16,21,22]
```


## 2. Big-O gösterimini yazınız.

```
N tane işlem üzerinden big-o gösterimi yapalım. A algoritması input olarak kaç sayfa varsa o kadar işlem yapıyor. B algoritması ise sayfa sayısını azaltmak için alfabetik sıraya göre sağ ve sol olarak yarıya indiriyor.

 O(N*log(N))
```

[patika.dev](https://app.patika.dev/) -> Başlangıç Seviye Veri Bilimi Patikası -> Veri Yapıları ve Algoritmalar