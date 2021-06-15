Оператор if else используется, когда необходимо выполнить различные действия в зависимости от условия.  

**Краткая** запись команды if :
```
if условие:
    команды
```
Пример 1. Ввести число. Напечатать "positive", если число положительное.
```
num = int(input("Enter number: ")
if num > 0:
    print("positive")
```
**Полная форма команды** выглядит следующим образом:
```
if условие:
    команды_1 
else:
    команды_2
```
Оператор if получает `условие` и вычисляет его. Если результат этого вычисления - True, то выполнятся `команды_1` (блок, следующий сразу за условием). Необязательный блок else и его `команды_2` выполняется, если `условие` ложно (False).

Пример 2. Ввести число. Напечатать "Even", если число четное, и "Odd" - в противном случае (т.е. если число нечетное).
```
num = int(input("Enter number: "))
if num % 2 == 0:
    print("Even")
else:
    print("Odd")
```

Пример 3. Ввести слово. Проверить, начинается ли слово с буквы "A".
```
word = input("Enter word: ")
if word[0] == "A":
    print("Yes")
else:
    print("No")
```
Если требуется выполнять множественные проверки условий, применяют команду: **if...elif...else**
Синтаксис команды выглядит следующим оразом:
```
if условие_1:
    команды, которые выполняются если условие_1 истинно
elif условие_2:
    команды, которые выполняются если условие_2 истинно
elif условие_3:
    команды, которые выполняются если условие_3 истинно
else: 
    команды, которые выполняются, если все вышестоящие условия ложны
```

Пример 4. Ввести число num. Напечатать "positive", если число положительное, "negative", если число отрицательное, и "zero" - если число равно 0.
```
num = int(input("Enter number: ")
if num > 0:
    print("positive")
elif num < 0:
    print("negative")
else:
    print("zero")
```
##### Задания
1. В переменную `word` введите слово. В переменную `n` введите индекс символа. Напечатайте символ с этим индексом, если такой индекс есть в слове. Иначе напечатайте "Index is not valid".
1. В переменную `char` введите символ. Определите, является ли этот символ гласной буквой.
1. В переменную `name` введите имя. Определите, начинается ли имя с гласной буквы.
1. В переменную `string` введите строку. Определите, является ли последний символ строки цифрой от 0 до 9.
1. С помощью команды  input введите имя пользователя `name`. Если имя содержит более 5 букв, напечатайте "Your name is long!". В противном случае напечатайте  "Your name is short!"
1. С помощью команды  input в переменную `answer` введите ответ пользователя на вопрос: "Are you ok?". Если ответ "No" или "no", напечатайте "Get better!". В противном случае напечатайте  "Cool!"
1. Ввести два числа a, b. Определить, делится ли  число  a на число b.
1. С помощью команды  input введите имя пользователя `name` и время `time` в часах от 0 до 24.  
* Если время от 0 до 6 (включительно), напечатайте "Good night, `name`";
* если время от 7 до 11 (включительно), напечатайте "Good morning, `name`";
* если время от 12 до 18 (включительно), напечатайте "Good day, `name`");
* если время от 19 до 24 (включительно), напечатайте "Good night, `name`");
* иначе напечатайте "Wrong time".
9. Введите значения переменных `a`, `b` (числа) и строку `operation` , содержащую знак арифметической операции (+, -, \*, /, %, //). Найдите и напечатайте результат выполнения данной операции над числами a, b в виде:  "`a` `operation` `b` = `result`".
9. Введите цену товара `price`.
* Если price >= 300, вы получаете скидку 30%;
* иначе если price >= 200, вы получаете скидку 20%;
* иначе если price >= 100, вы получаете скидку 10%;
* если цена меньше 100, скидки нет. Найдите итоговую стоимость товара.
11.   Введите возраст человека `age`. 
* Если age<16 напечатайте "children";
* иначе если age<50 напечатайте "young man"; 
* иначе напечатайте "senior".
12. В переменную current_color введите цвет сигнала светофора ('red','yellow','green'). Напечатайте следующий цвет сигнала светофора (если вы не водитель, то смена цветов такая: 'red' ---> 'green', 'green' ---> 'yellow', 'yellow' ---> 'red').

