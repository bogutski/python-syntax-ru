Можно получить доступ к части элементов списка, используя оператор нарезки (slicing operator). Для обращения к части списка после имени списка надо в квадратных скобках указать начальный и конечный индекс элемента, причем первый индекс включается в диапазон, а последний не включается.

![](https://github.com/bogutski/jsp/blob/master/Python/arr-slice.png?raw=true)

```
arr = ["a", "b", "c", "d", "e", "f"]
print(len(arr)) # 6 (длина списка)

print(arr[0:3])   # ["a", "b", "c"] (элементы с индексами от 0 до 2 )
print(arr[:3])    # ["a", "b", "c"] (элементы от начала списка до индекса 2, индекс 0 можно опускать)
print(arr[2:4])   # ["c", "d"] (элементы с индексами от 2 до 3)
print(arr[3:])    # ["d", "e", "f"] (элементы с индексами от 3 до конца списка)
print(arr[:-1])   # ["a", "b", "c", "d", "e"] (все элементы, кроме последнего)
print(arr[1:-1])  # ["b", "c", "d", "e"] (все элементы, кроме первого и последнего)
print(arr[::-1])  # ["f", "e", "d", "c", "b", "a"] (элементы списка в обратном порядке - от последнего до первого.)
```
