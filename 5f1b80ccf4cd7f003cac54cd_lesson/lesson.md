**`str.lstrip([chars])`** - возвращает копию строки с удаленными начальными символами. Аргумент chars - это строка, указывающая набор символов, которые должны быть удалены. Если он опущен или отсутствует,  по умолчанию удаляются пробелы в начале строки.

Пример.
```
name = "**Alice"
print(name.lstrip("*"))              # "Alice"
print("     Hello world!". lstrip()) # "Hello world!"
```
**`str.rstrip([chars])`** - возвращает копию строки с удаленными конечными символами. Аргумент chars - это строка, указывающая набор символов, которые должны быть удалены. Если он опущен или отсутствует,  по умолчанию удаляются пробелы в конце строки.

Пример.
```
password = "qwerty!!!"
print(password.rstrip("!"))  # "qwerty"
print("I like Python!    ". rstrip()) # "I like Python!"
```
**`str.strip([chars])`** - возвращает копию строки с удаленными начальными и конечными символами. Аргумент chars - это строка, указывающая набор символов, которые должны быть удалены. Если он опущен или отсутствует,  по умолчанию удаляются пробелы в начале и конце строки.

Пример.
```
message = "___Hello!___"
print(message.strip("_"))  # "Hello!"
print("   Our school is the best!    ". strip()) # "Our school is the best!"
```
##### Задания.
1. Задана строка. В начале и конце строки есть некоторое количество пробелов.  Получить строку, в которой каждое слово написано в заглавной буквы, пробелы в начале строки удалены, в пробелы в конце строки заменены на восклицательные знаки.