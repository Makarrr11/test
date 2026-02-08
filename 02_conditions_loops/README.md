# Условия и циклы

## Условные операторы (if/elif/else)

```python
age = 18

if age < 18:
    print("Несовершеннолетний")
elif age == 18:
    print("Ровно 18")
else:
    print("Взрослый")
```

## Цикл while

Выполняется, пока условие истинно:

```python
count = 0
while count < 5:
    print(count)
    count += 1
```

## Цикл for

Используется для перебора элементов:

```python
# Перебор чисел
for i in range(5):  # 0, 1, 2, 3, 4
    print(i)

# Перебор с шагом
for i in range(0, 10, 2):  # 0, 2, 4, 6, 8
    print(i)

# Перебор строки
for char in "Python":
    print(char)
```

## Операторы управления циклом

- `break` - выход из цикла
- `continue` - переход к следующей итерации

```python
for i in range(10):
    if i == 5:
        break  # Выход на 5
    if i % 2 == 0:
        continue  # Пропуск четных
    print(i)
```

## Задания

1. `task_1_conditions.py` - Условные операторы
2. `task_2_while.py` - Цикл while
3. `task_3_for.py` - Цикл for
