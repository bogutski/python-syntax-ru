Чтобы проверить, является ли одна строка частью другой строки, используют оператор `in`.
```
print("a" in "banana")  # True
print("cat" in "cartoon") # False
print("a" in "aeiou") # True
```
Пример. Определить, является ли введенный символ гласной буквой.
```
vowels = "aeuio"
letter = input("Enter letter: ")
print(letter.lower() in vowels) 
```
Пример. Определить, является ли введенный символ согласной буквой.
```
vowels = "aeuio"
letter = input("Enter letter: ")
print(not letter.lower() in vowels) 
```

##### Задания
1. С помощью команды input ввести имя пользователя. Определить, начинается ли имя с гласной буквы.
Вывести сообщение "{name}, your name starts with vowel"  или "{name}, your name starts with consonant"
1. С помощью команды input ввести строку. Определить, заканчивается ли строка цифрой.
1. Введите строку. Определите, есть ли этой строке буква "y".
1. Введите строку в переменную string. Введите слово в переменную word. Определите, содержит ли строка данное слово.
