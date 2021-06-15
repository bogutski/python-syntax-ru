**`str.replace(old, new[, count])`**  - возвращает копию строки, в которой все подстроки `old` заменяются на подстроку `new`. Если задан необязательный аргумент `count`, то заменяются только первые `count` вхождений подстроки `old`

Пример 1. Заменить все слова "is" на слова "was"
```
s = "Sky is blue and the weather is beautiful"
new_s = s.replace("is", "was")
print(new_s) #  "Sky was blue and the weather was beautiful"
```
Пример 2. Заменить первые 4  точки на запятые.
```
s = "Apples. bananas. limes. peaches. plums. Buy now. Low prices."
new_s = s.replace(".", ",", 4)
print(new_s)  # "Apples, bananas, limes, peaches, plums. Buy now. Low prices."
```
Пример 3. Удалить в строке все пробелы.
```
s = "I like school"
s = s.replace(" ", "")  # заменяем все пробелы пустой строкой
print(s)  # "Ilikeschool"
```
##### Задания
1. Создайте строку, присвойте ей значение "Summer is my favorite time of year". Замените слово "Summer" на слово "Winter".
1. Создайте переменную  s и присвойте ей значение строки, состоящей только из lowercase букв. Удалить в этой строке все гласные буквы. Например, s = “we like python”. Результат должен быть “w lk pythn”.
1. С помощью команды input введите строку. Введите слово, которое надо заменить. Введите заменяющее слово. Выведите результат. Например, введены: строка "Have a good day", слово "good", слово "nice". Результат должен быть: "Have a nice day".