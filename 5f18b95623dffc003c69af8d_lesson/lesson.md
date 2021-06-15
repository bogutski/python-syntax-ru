* **endswith()** - возвращает True, если строка `str` заканчивается указанной подстрокой `suffix`, в противном случае возвращает False. Если указан необязательный аргумент `start`, то поиск начинается с этой позиции. Если указан необязательный аргумент `end`, то поиск заканчивается в этой позиции.
```
str.endswith(suffix[, start[, end]])
```
* **startswith()**  - возвращает True, если строка `str` начинается указанной подстрокой `prefix`, в противном случае возвращает False. Если указан необязательный аргумент `start`, то поиск начинается с этой позиции. Если указан необязательный аргумент `end`, то поиск заканчивается в этой позиции.
```
str.startswith(prefix[, start[, end]])
```
Примеры.
```
print("Hello world".startswith("H")) # True
print("Hello world".startswith("h")) # False
print("Hello world".endswith("rld")) # True
print("Hello world".endswith("!"))   # False
```
##### Задания
1. С помощью функции input в переменную `animal` введите название животного. В переменную `tail` введите строку. Определите, заканчивается ли строка animal строкой tail?
1. С помощью функции input в переменную `greet` введите приветствие. Определите, начинается ли приветствие словом "Hello".

##### Задачи
1. https://www.codewars.com/kata/51f2d1cafc9c0f745c00037d
1. https://www.codewars.com/kata/5a58d889880385c2f40000aa
1. https://www.codewars.com/kata/56f695399400f5d9ef000af5 
