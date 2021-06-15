Пример. Заполнить словарь. в котором ключами будут имена людей, а значениями - названия мест, куда эти люди хотят поехать в отпуск. Информацию ввести в цикле с помощью команды input.
```
dct = {}
n = int(input("Enter number of people: "))
for i in range(1, n+1):
    name = input(f"Enter name of {i} person: ")
    vacation = input(f"Where does {name} want to go on vacation? ")
    dct[name] = vacation
print(dct)
```
Результат выполнения программы может быть таким:
```
Enter number of people: 3
Enter name of 1 person: Lara
Where does Lara want to go on vacation? Miami
Enter name of 2 person: Anna
Where does Anna want to go on vacation? Alyaska
Enter name of 3 person: Amelia
Where does Amelia want to go on vacation? China
{'Lara': 'Miami', 'Anna': 'Alyaska', 'Amelia': 'China'}
```
##### Задания
1. Заполните словарь, содержащий имена студентов и их рейтинг (количество баллов за решенные задачи). Информацию ввести в цикле с помощью команды input.
