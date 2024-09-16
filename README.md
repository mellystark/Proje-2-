# Proje-2

İlk olarak, diziyi ikiye böleriz:

[16, 21, 11] ve [8, 12, 22]
Daha sonra her bir parçayı tekrar böleriz:

[16, 21, 11] -> [16] ve [21, 11]
[21, 11] -> [21] ve [11]
[8, 12, 22] -> [8] ve [12, 22]
[12, 22] -> [12] ve [22]
Parçaları Sıralama ve Birleştirme:

[21] ve [11] parçalarını birleştirerek sıralarız:

[11, 21]
[12] ve [22] parçalarını birleştirerek sıralarız:

[12, 22]
[8] ve [12, 22] parçalarını birleştirerek sıralarız:

[8, 12, 22]
[16] ve [11, 21] parçalarını birleştirerek sıralarız:

[11, 16, 21]
Son olarak, [8, 12, 22] ve [11, 16, 21] parçalarını birleştirerek sıralarız:

[8, 11, 12, 16, 21, 22]
Sıralı Dizi: [8, 11, 12, 16, 21, 22]

O(n log n)
