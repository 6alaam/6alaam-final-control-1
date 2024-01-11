# 6alaam-final-control-1

описание задачи

Задача алгоритмически не самая сложная, однако для полноценного выполнения проверочной работы необходимо:

1. Создать репозиторий на GitHub
2. Нарисовать блок-схему алгоритма (можно обойтись блок-схемой основной содержательной части, если вы выделяете её в отдельный метод)
3. Снабдить репозиторий оформленным текстовым описанием решения (файл README.md)
4. Написать программу, решающую поставленную задачу
5. Использовать контроль версий в работе над этим небольшим проектом (не должно быть так, что всё залито одним коммитом, как минимум этапы 2, 3, и 4 должны быть расположены в разных коммитах)

Задача: Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

Примеры:
[“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”]
[“1234”, “1567”, “-2”, “computer science”] → [“-2”]
[“Russia”, “Denmark”, “Kazan”] → []

РЕШЕНИЕ

Согласно условию задачи, создан заданный массив (array1) типа стринг
Далее создается второй массив (array2) такого же типа, а так же длинной равной длине 1 массива
Далее создан void метод SecondArrayWithIF принимающий на вход два стринговых массива, и 
который через цикл копирует элемент, удовлетворяющий условию из первого массива в массив который создали.
Далее еще один войд метод который распечатывает в консоль массив.
Для наглядности вывел оба массива .
Задачу решил самым простым методом удовлетворяющим всем условиям.





