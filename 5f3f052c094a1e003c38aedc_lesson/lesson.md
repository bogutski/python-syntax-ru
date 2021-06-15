Списки мутабельны, это означает, что элементы списка можно изменить, добавить или удалить.

**Изменение элементов списка**

Для изменения значения элемента списка используется оператор присваивания.
```
arr = [10, 2, 30]
arr[1] = 20
print(arr)  # [10, 20, 30]
```
Можно изменить некоторый диапазон значений элементов.
```
lst = [1, 0, 0, 0, 5, 6]
lst[1:4] = [2, 3, 4]
print(lst)  # [1, 2, 3, 4, 5, 6]
```
**Конкатенация (сложение) списков**

Для объединения двух списков в один можно использовать оператор `+`.
```
arr1 = [1, 2, 3]
arr2 = [4, 5, 6]
arr = arr1 + arr2
print(arr)  # [1, 2, 3, 4, 5, 6]
```
**Умножение списка на число (повторение списка)**

Оператор `*` позволяет повторить список заданное число раз.
```
lst = ["a", "b"] * 3
print(lst)  #  ["a", "b", "a", "b", "a", "b"]
```
**Добавление элементов в конец списка**

Мы можем добавить один элемент в конец списка, используя метод `append()`.
```
arr = [1]
arr.append(2)
print(arr)  # [1, 2]
```
Метод `extend()` позволяет добавлять несколько элементов в конец списка.
```
arr = ["apple"]
arr.extend(["banana", "peach"])
print(arr) # ["apple", "banana", "peach"]
```
**Вставка элементов в список**

 Чтобы добавить один элемент не в конец списка, а  в определенное место, используют метод `insert()`. У функции insert() два аргумента: первый аргумент – это индекс элемента, перед которым нужно вставить новый элемент, второй аргумент – это сам новый элемент.
```
arr = [1, 2, 3]
arr.insert(1, 10)
print(arr) # [1, 10, 2, 3]
```
Пример 1. Дан список слов. Отфильтровать список, получив список слов, длина которых меньше 5 символов.
```
words = ['Apricot', 'Cat', 'Dog', 'Ocelot', 'Zebra', 'Bat', 'Orange']
short_words = []
for word in words:
    if len(word) < 5:
        short_words.append(word)
print(short_words)  # ['Cat', 'Dog', 'Bat']     
```
##### Задания.
1. Дан список чисел. Замените все элементы списка на противоположные по знаку элементы. 
1. Дан список чисел. Все четные элементы замените нулем, а нечетные увеличьте на 1.
1. Дан числовой список . Элементы с четными индексами возвести в квадрат, а элементы с нечетными индексами - в куб.
1. Дан смешанный список . Получить массив чисел.
1. Дан список слов. Отфильтровать список , получив список слов, которые начинаются с гласной буквы.
1. Дан список целых чисел. Получить список четных чисел.
1. Дан список целых чисел. Получить список чисел, которые имеют четное число цифр.
1. Дан числовой список . Получить список чисел, которые являются квадратами целых чисел. Например, `arr = [4, 1, 2, 9, 16, 13, 36]`. Получить список `[4, 1, 9, 16, 36]`.
1. Дано два списка одинаковой размерности: `arr1 = [1, 2, 3, 4, 5, 6]`, `arr2 = ["a", "b", "с", "d", "e", "f"]`. Получить список :
`arr3 = [1, "a", 2, "b", 3, "с", 4, "d", 5, "e", 6, "f"]`
1. Дан список слов. Найти максимальную и минимальную длину слов.
1. Дан список слов. Вывести слово максимальной длины.
1. Дан список слов. Получить среднюю длину слова (среднее арифметическое длин слов).

##### Задачи 
* Метод insert: https://www.codewars.com/kata/5413759479ba273f8100003d/train/python