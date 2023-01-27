# Домашние задания по теме #

# Знакомство с языком Python (семинары) #

### Урок 1. Знакомство с Python (11 декабря 2022г.) ###

1. Напишите программу, которая принимает на вход цифру, обозначающую день недели, и проверяет, является ли этот день выходным.

Пример:

* 6 -> да
* 7 -> да
* 1 -> нет

Решение данной задачи в каталоге **Task001**

2. Напишите программу для. проверки истинности утверждения ¬(X ⋁ Y ⋁ Z) = ¬X ⋀ ¬Y ⋀ ¬Z (расшифровка этого выражения not (x[0] or x[1] or x[2] = not x[0] and not x[1] and not x[2]) для всех значений предикат.

Решение данной задачи в каталоге **Task002**

3. Напишите программу, которая принимает на вход координаты точки (X и Y), причём X ≠ 0 и Y ≠ 0 и выдаёт номер четверти плоскости, в которой находится эта точка .

Пример:

* x=34; y=-30 -> 4
* x=2; y=4-> 1
* x=-34; y=-30 -> 3

Решение данной задачи в каталоге **Task003**

4. Напишите программу, которая по заданному номеру четверти, показывает диапазон возможных координат точек в этой четверти (x и y).

Решение данной задачи в каталоге **Task004**

5. Напишите программу, которая принимает на вход координаты двух точек и находит расстояние между ними в 2D пространстве.

Пример:

* A (3,6); B (2,1) -> 5,09
* A (7,-5); B (1,-1) -> 7,21

Решение данной задачи в каталоге **Task005**

### Урок 2. Знакомство с Python. Продолжение (17 декабря 2022г.) ###

1. Напишите программу, которая принимает на вход вещественное число и показывает сумму его цифр.

    Пример:

* 6782 -> 23
* 0,56 -> 11

Решение данной задачи в каталоге **Task006**

2. Напишите программу, которая принимает на вход число N и выдает набор произведений чисел от 1 до N.

    Пример:

* пусть N = 4, тогда [ 1, 2, 6, 24 ] (1, 1*2, 1*2*3, 1*2*3*4)

Решение данной задачи в каталоге **Task007**

3. Задайте список из n чисел последовательности (1+1/n)**n и выведите на экран их сумму.

Решение данной задачи в каталоге **Task008**

4. Задайте список из N элементов, заполненных числами из промежутка [-N, N]. Найдите произведение элементов на указанных позициях. Позиции хранятся в отдельном списке ( пример n=4, lst1=[4,-2,1,3] - список на основе n, а позиции элементов lst2=[3,1].

Решение данной задачи в каталоге **Task009**

5. Реализуйте алгоритм перемешивания списка. (рандомно поменять местами элементы списка между собой)

Решение данной задачи в каталоге **Task010**

### Урок 3. Данные, функции и модули в Python (18 декабря 2022г.) ###

1. Задайте список из нескольких чисел. Напишите программу, которая найдёт сумму элементов списка, стоящих на нечётной позиции.

    Пример:

* [2, 3, 5, 9, 3] -> на нечётных позициях элементы 3 и 9, ответ: 12

Решение данной задачи в каталоге **Task011**

2. Напишите программу, которая найдёт произведение пар чисел списка. Парой считаем первый и последний элемент, второй и предпоследний и т.д.

    Пример:

* [2, 3, 4, 5, 6] => [12, 15, 16];
* [2, 3, 5, 6] => [12, 15]

Решение данной задачи в каталоге **Task012**

3. Задайте список из вещественных чисел. Напишите программу, которая найдёт разницу между максимальным и минимальным значением дробной части элементов.(если получаются длинные числа после запятой, это нормально и особенность данного языка программирования. ваш ответ может не совпадать с примером(может получитя 0,20))

    Пример:

* [1.1, 1.2, 3.1, 5, 10.01] => 0.19

Решение данной задачи в каталоге **Task013**

4. Напишите программу, которая будет преобразовывать десятичное число в двоичное.

    Пример:

* 45 -> 101101
* 3 -> 11
* 2 -> 10

Решение данной задачи в каталоге **Task014**

5. Задайте число. Составьте список чисел Фибоначчи, в том числе для отрицательных индексов.

    Пример:

* для k = 8 список будет выглядеть так: [-21 ,13, -8, 5, −3, 2, −1, 1, 0, 1, 1, 2, 3, 5, 8, 13, 21]

Решение данной задачи в каталоге **Task015**

### Урок 4. Данные, функции и модули в Python. Продолжение (24 декабря 2022г.) ###

1. Вычислить число c заданной точностью d

    Пример:

* при $d = 0.001, π = 3.141.$    $10^{-1} ≤ d ≤10^{-10}$

Решение данной задачи в каталоге **Task016**

2. Задайте натуральное число N. Напишите программу, которая составит список простых множителей числа N.

Решение данной задачи в каталоге **Task017**

3. Задайте последовательность чисел. Напишите программу, которая выведет список неповторяющихся элементов исходной последовательности.

Решение данной задачи в каталоге **Task018**

4. Задана натуральная степень k. Сформировать случайным образом список коэффициентов (значения от 0 до 100) многочлена и записать в файл многочлен степени k.

    Пример:

* k=2 => 2*x² + 4*x + 5 = 0 или x² + 5 = 0 или 10*x² = 0

Решение данной задачи в каталоге **Task019**

5. Даны два файла, в каждом из которых находится запись многочлена. Задача - сформировать файл, содержащий сумму многочленов.

Решение данной задачи в каталоге **Task020**

### Урок 5. Ускоренная обработка данных: lambda, filter, map, zip, enumerate, list comprehension (14 января 2023г.) ###

1. Напишите программу, удаляющую из текста все слова, содержащие ""абв"".

Решение данной задачи в каталоге **Task021**

3. Создайте программу для игры в Крестики-Нолики

Решение данной задачи в каталоге **Task023**

4. Реализуйте RLE алгоритм: реализуйте модуль сжатия и восстановления данных.

Решение данной задачи в каталоге **Task022**

### Урок 6. Ускоренная обработка данных: lambda, filter, map, zip, enumerate, list comprehension. Продолжение (15 января 2023г.) ###

1. Изменил способ заполнени списка с цикла for на list comprehension.

Решение данной задачи в каталоге **Task007**

2. Способ решения задачи сделал более питоновский, а именно использовал list comprehension, map, list, lambda-функцию. Старый код закомментировал.

 Решение данной задачи в каталоге **Task008**

3. Замена цикла for на list comprehension с использованием пользовательской функции

Решение данной задачи в каталоге **Task015**

4. Переботал задачу, результате которой получается список из кортежей: первый элемент кортежа это число, которое раскладываем на простые множители, вторым элементом идёт опять же список из этих простых множителей. Использовал list comprehension и пользовательскую функцию

Решение данной задачи в каталоге **Task017**

5. Упрощена задача, а именно убрал цикл for.

Решение данной задачи в каталоге **Task018**

### Урок 8. Python: от простого к практике. Продолжение (22 января 2023г.) ###

* Задача: Создать информационную систему позволяющую работать с сотрудниками некой компании \ студентами вуза \ учениками школы

Решение данной задачи в каталоге **Task024**

### Урок 7. Python: от простого к практике (21 января 2023г.) ###

* Создать телефонный справочник с возможностью импорта и экспорта данных в нескольких форматах.

Решение данной задачи в каталоге **Task025**
