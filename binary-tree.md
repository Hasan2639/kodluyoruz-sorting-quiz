# Binary Tree

7, 5, 1, 8, 3, 6, 0, 9, 4, 2 dizisini sıralayacağız.

* root 7dir
* 5, 7 den küçüktür, child olarak sol tarafa gider
* 1, 5 den de küçüktür. 5'in de soluna gider.
* 8, 7 den büyüktür. root'un sağına gider.
* 3, 5 den küçük, 1 den büyüktür. 1'in sağına gider.
* 6, 5 den büyüktür. 5'in sağına gider
* 0, hepsinden küçüktür. 1'in soluna gider.
* 9, 8 den büyüktür. 8'in sağına gider
* 4, 3 den büyüktür. 3'ün sağına gider.
* 2, 1 den büyüktür, 3'den küçüktür. 3'ün soluna gider

                             7
                            / \
                           5   8
                          /\     \
                         1  6     9
                        / \
                       0   3
                          / \
                         2   4