* **index()** - возвращает индекс первого вхождения элемента или вызывает `ValueError`, если элемент не найден.

Синтаксис:
 ```
arr.index(s, [start],[end])
```
Пример.
```
arr = [5, 2, 1, 4, 5, 2, 3, 4, 2, 0]
print(arr.index(1))  # 2
print(arr.index(5))  # 0
print(arr.index(10))  # ValueError: 10 is not in list
```
Также мы можем проверить, существует ли элемент в массиве или нет, используя ключевое слово `in`. 
```
words = ["apple", "kiwi", "banana", "peach"]
print("apple" in words) # True
print("apples" in words) # False
```
Пример. Найти индекс первого нуля в массиве.
```
# 1 способ:
arr = [2, 12, 0, 4, 0, 2, 0]
print(arr.index(0))  # 2 (вызовет ошибку, если в массиве не окажется элемента со значением 0)

# 2 способ:
arr = [2, 12, 0, 4, 0, 2, 0]
if 0 in arr:
    print(arr.index(0)) 
else:
    print("No such element in list")

# 3 способ:
arr = [2, 12, 0, 4, 0, 2, 0]
for i, el in enumerate(arr):
    if el == 0:
        print(i)
        break
else:
    print("No such element in list")
```
##### Задания
1.