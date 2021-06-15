Для удаления элемента словаря можно используется оператор **del**, например,

**Пример 1**. Есть словарь с именем user. Удалить элемент "is_Student".
```
user = {
  "name": "Alice",
  "age": 30,
  "is_Student": True,
}
del user["is_Student"]
print(user)  # {'name': 'Alice', 'age': 30} 
```
**Пример 2**. Удалить гору Монблан из словаря, содержащего список самых высоких гор.
```
mountains = {
  4810: "Mont Blanc",
  8848: "Mount Everest",
  4317: "Mount Shasta",
  5881: "Kilimanjaro"
 }
del mountains[4810]
print(mountains) # {8848: 'Mount Everest', 4317: 'Mount Shasta', 5881: 'Kilimanjaro'}
```
##### Задания
1. Создайте словарь student, содержащий элементы: "name" со значением "Peter",  "school" со значением "PASV",
 "isAdult" со значением False. Затем запишите команду, которая удаляет элемент "isAdult".
2. Создайте словарь car, имеющий свойства: "make" со значением "Ford",  "model" со значением "Mustang",
 "year" со значением 2015. Затем запишите команду, которая удаляет элемент "year".