# Patika.dev Algoritma Projeleri

# [patika.dev](https://www.patika.dev/tr) , [https://app.patika.dev/emile](https://app.patika.dev/emile)

## Merge Sort Projesi

## [16,21,11,8,12,22] -> Merge Sort

## Soru - 1

### Yukarıdaki dizinin sort türüne göre aşamalarını yazınız

#### Dizimizi ortadan ikiye ayırıyoruz, daha sonra sağdan ve soldan oluşan dizilerimizi tek eleman kalana kadar ayırmaya devam ediyoruz.

|     |     |     | 16  | 21  |  11 | 8   | 12  |  22 |     |     |     |
| --- | :-: | --: | --- | :-: | --: | --- | :-: | --: | --- | --- | --- |
|     |     |  16 | 21  | 11  |     |     |  8  |  12 | 22  |     |     |
|     | 16  |  21 |     | 11  |     |     |  8  |     | 12  | 22  |     |
| 16  |     |  21 |     | 11  |     |     |  8  |     | 12  |     | 22  |

#### Ayırma işlemimiz bitince sağdan ve soldan ikili gruplar halinde dışarıda eleman kalmayana kadar birleştiriyoruz.

| 16  |     |  21 |     | 11  |     |     |  8  |     | 12  |     | 22  |
| --- | :-: | --: | --- | :-: | --: | --- | :-: | --: | --- | --- | --- |
|     | 16  |  21 |     | 11  |     |     |  8  |     | 12  | 22  |     |
|     |     |  11 | 16  | 21  |     |     |  8  |  12 | 22  |     |     |
|     |     |     | 8   | 11  |  12 | 16  | 21  |  22 |     |     |     |

## Soru - 2

### Big-O gösterimini yazınız.

#### n -> dizinin uzunluğu

#### O(n*(logn)) -> O(6*(log6))
