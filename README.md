# Dev Notes

A personal collection of developer notes and Python code snippets.

---

## 1. Variables in Python
Variables are used to store data values.

```python
x = 5
y = "Hello, World!"
print(x, y)
```

---

## 2. If Statements
If statements control the flow of your program.

```python
age = 18
if age >= 18:
    print("You are an adult!")
```

---

## 3. Loops
Loops let you repeat actions efficiently.

```python
for i in range(5):
    print(i)
```

---

## 4. Functions
Functions organize code into reusable blocks.

```python
def greet(name):
    return f"Hello, {name}!"
```

---

## 5. Lists
Lists store multiple items in a single variable.

```python
fruits = ["apple", "banana", "cherry"]
print(fruits)
```

---

## 6. Dictionaries
Dictionaries store key-value pairs.

```python
person = {"name": "Alice", "age": 25}
print(person["name"])
```

---

## 7. Error Handling
Use `try`–`except` blocks to handle runtime errors gracefully.

```python
try:
    print(10 / 0)
except ZeroDivisionError:
    print("You can't divide by zero!")
```

---

## 8. File Handling
You can read and write files using `open()`.

```python
with open("test.txt", "w") as f:
    f.write("Hello File!")
```

---

## 9. Modules
Modules let you reuse code from other files.

```python
import math
print(math.sqrt(16))
```

---

## 10. Final Thoughts
Learning GitHub commits is easy once you practice a few times!
