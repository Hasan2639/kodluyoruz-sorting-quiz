# Insertion Sort

Insertion Sort algoritması dizi elemanlarını sırasıyla gezer ve sıradaki elemanı sondan başa kıyaslayarak, olması gereken yere koyar. 

22,27,16,2,18,6 -- bu diziyi sıralayacağız


* Initial state      |22,27,16,2,18,6|
* 27 karşılaştırması |22,27,16,2,18,6|
* 16 karşılaştırması |16,22,27,2,18,6|
* 2 karşılaştırması  |2,16,22,27,18,6|
* 18 karşılaştırması |2,16,18,22,27,6|
* 6 karşılaştırması  |2,6,16,18,22,27|

Big-O gösterimi O(n)'dir.

* Best-Case O(n)
* Average Case O(n^2)
* Worst Case O(n^2) Sırayla eleman gezme ve taşıma işlemi

18 sayısı Average Case kapsamı


* |7,3,5,8,2,9,4,15,6|
* |3,7,5,8,2,9,4,15,6|
* |3,5,7,8,2,9,4,15,6|
* |3,5,7,8,2,9,4,15,6|