Элементы массива, состоящего из строковых значений, можно соединить в строку, используя метод `join()`:
```
arr = ["c", "o", "k", "e"]
word = "".join(arr)
print(word)  # "coke"

arr = ["a", "b", "c"]
print(":".join(arr))  # "a:b:c"

arr = ["We", "like", "Python"]
text = " ".join(arr)
print(text)  # "We like Python"
```