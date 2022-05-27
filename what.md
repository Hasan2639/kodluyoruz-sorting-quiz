# Merge Sort

|16,21,11,8,12,22| dizisini sıralacağız.

* Diziyi yarıya bölüyoruz           |16,21,11| --- |8,12,22|
* Teker teker parçalara bölüyoruz   |16,21| -- |11| --- |8,12| -- |22|
* Her eleman tek kalıncaya kadar    |16|-|21|--|11|---|8|-|12|--|22|
* Parçalara göre sıralı birleştirme |16,21|--|11|---|8,12|--|22|
* Sıradaki adım                     |11,16,21| --- |8,12,22|
* Son birleştirme adımı             |8,11,12,16,21,22|


Big-O notation ---> O(nlog(n))