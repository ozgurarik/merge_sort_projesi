# Proje 2 - Merge Sort

## 1.Soru
[16, 21, 11, 8, 12, 22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

## Çözüm



|  |  |  |  |  |  |  |  |
| :----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: |
| 1 |  |  |  | [16, 21, 11, 8, 12, 22] |  |  |  |
| 2 |  |  | [16, 21, 11] |  | [8, 12, 22] |  |  |
| 3 |  | [16, 21] | 11 |  | [8, 12] | 22 |  |
| 4 | 16 | 21 | 11 |  | 8 | 12 | 22 |
| 5 |  | [16, 21] | 11 |  | [8, 12] | 22 |  |
| 6 |  |  | [11, 16, 21] |  | [8, 12, 22] |  |  |
| 7 |  |  |  | [8, 11, 12, 16, 21, 22] |  |  |  |


## 2.Soru
Big-O gösterimini yazınız.

## Çözüm
Big-O gösterimi 
* 2^x = n
* x = logn

Her bir birleştirme işlemi, en kötü durumda, her elemanın bir kez karşılaştırılmasını gerektirir, bu da birleştirme işleminin lineer zaman karmaşıklığına (n) sahip olacağı anlamına gelir.

* O(n * logn) 'dir.
