**`str.isalpha()`**  - возвращает True, если все символы в строке алфавитные, и строка содержит хотя бы один символ, в противном случае False.

Пример.
```
s = "sky"
print(s.isalpha()) # True
s = "7up"
print(s.isalpha()) # False
s = "Nice!"
print(s.isalpha()) # False
```
**`str.isdigit()`** - возвращает True, если все символы в строке являются цифрами, и строка содержит хотя бы один символ, в противном случае False.

Пример.
```
year = "2020"
print(year.isdigit()) # True
print("23,5".isdigit()) # False
```
**`str.isalnum()`** - возвращает True, если все символы в строке являются цифро-буквенными, и строка содержит хотя бы один символ, в противном случае False.

Пример.
```
date = "May 9"
print(date.isalnum()) # False
print("May9".isalnum()) # True
```
**`str.islower()`** - возвращает True, если все символы в строке являются строчными (lowercase), и строка содержит хотя бы один символ, в противном случае False.

Пример.
```
city = "Paris"
print(city.islower()) # False
print("street".islower()) # True
```
**`str.isupper()`** - возвращает True, если все символы в строке являются заглавнми (uppercase), и строка содержит хотя бы один символ, в противном случае False.

Пример.
```
state = "CA"
print(state.isupper()) # True
print("Avenuee".isupper()) # False
```
##### Задания.
1. Введите строку `word`.  Напечатайте:
* " has only digits" , если строка содержит только цифры
* " has lowercase letters" , если строка содержит только lowercase буквы
* " has uppercase letters", если строка содержит только uppercase буквы
* " has lowercase and uppercase letters", если строка содержит uppercase and lowercase буквы, но не содержит цифр 
* " has digits and lowercase letters", если строка содержит цифры и только lowercase буквы
* " has digits and uppercase letters", если строка содержит цифры и только uppercase буквы
* " has upper and lowercase letters and digits ", если строка содержит цифры и uppercase и lowercase буквы  
