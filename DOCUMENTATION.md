# Документація API

## Модуль Calculator

### Функція add()
```python
def add(a,b):
 """додавання двох чисел"""
 return a + b
```
**Параметри:**
- `a` (float): Перше число
- `b` (float): Друге число
**Повертає:**
- `float`: Сума двох чисел
**Приклад:**
result = add(5, 3)
print(result) # Виведе: 8

---
### Функція subtract()
```python
def subtract(a, b):
 """Віднімання двох чисел"""
 return a - b
```
**Параметри:**
- `a` (float): Перше число
- `b` (float): Друге число
**Повертає:**
- `float`: Різниця двох чисел
**Приклад:**
result = substract(10, 2)
print(result) # Виведе: 8

---
### Функція multiply()
```python
def multiply(a, b):
 """Множення двох чисел"""
 return a * b
```
**Параметри:**
- `a` (float): Перше число
- `b` (float): Друге число
**Повертає:**
- `float`: Добуток двох чисел
**Приклад:**
result = substract(5,5)
print(result) # Виведе: 25
---
### Функція divide()
```python
def divide(a, b):
    """Ділення двох чисел"""
    if b != 0:
        return a / b
    else:
        return "Помилка: ділення на нуль!"
```
**Параметри:**
- `a` (float): Перше число
- `b` (float): Друге число
**Повертає:**
- `float`: Остача двох чисел
**Приклад:**
result = substract(20,5)
print(result) # Виведе: 4

---
### Фунція power()
```python
def power(a, b):
    """Піднесення числа a до степеня b"""
    return a, b
```
**Параметри:**
- `a` (float): Перше число
- `b` (float): Друге число
**Повертає:**
- `float`: Степінь двох чисел
**Приклад:**
result = substract(2,2)
print(result) # Виведе: 4

---
### Функція modulo()
```python
def modulo(a, b):
 """Остача від ділення"""
 if b != 0:
    return a % b
 else:
    return "Помилка: ділення на нуль!"
```
**Параметри:**
- `a` (float): Перше число
- `b` (float): Друге число
**Повертає:**
- `float`: Остача від ділення Діленого на Дільник
**Приклад:**
result = substract(17,5)
print(result) # Виведе: 3


---

