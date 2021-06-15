Чтобы обратиться к элементу словаря, надо записать имя словаря, затем указать в квадратных скобках ключ элемента. Ключ-строку нужно поместить в кавычки.

Пример 1. Дан словарь mountains. Вывести на экран название горной вершины с высотой 4810 м (элемент в словаре mountains с ключом 4810).

```
mountains = {
	     4810: 'Mont Blanc',
	     8848: 'Mount Everest',
	     4317: 'Mount Shasta'
 }
print(mountains[4810])    #  'Mont Blanc'
```
Пример 2. Дан объект user с ключами first_name и last_name. Получить в переменной full_name полное имя пользователя.
```
user = {
  'first_name': 'Bob',
  'last_name': 'Smith'
  'city': 'NY',
}
full_name = user['first_name'] + ' ' + user['last_name']
print(full_name)  # 'Bob Smith'
```
##### Задания
1. Создайте объект person, у которого есть ключи "name" со значением "Alice", "is_student" со значением True.
Присвойте переменной first_name значение ключа "name" объекта person.