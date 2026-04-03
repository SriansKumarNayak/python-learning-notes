# Python Notes (Day 5) 🐍

## Topics Covered
- Functions
- Parameters & Arguments
- Return Statement

---

## 📌 Functions

- A function is a block of code that runs when called
- Helps to reuse code

### Example:
```python
def greet():
    print("Hello")

greet()
```
---

📌 Parameters & Arguments

 - Parameters → variables in function definition
 - Arguments → values passed to function

### Example:
```python
def greet(name):
    print("Hello", name)

greet("Srians")
```

---


📌 Return Statement
 - Used to return a value from a function

### Example:
```python
def add(a, b):
    return a + b

result = add(2, 3)
print(result)
```

---

📌 Default Parameters
 - You can give default values to parameters

### Example:
```python
def greet(name="User"):
    print("Hello", name)

greet()
greet("Srians")
```

---


📌 Keyword Arguments
 - Pass values using parameter names

### Example:
```python
def student(name, age):
    print(name, age)

student(age=18, name="Srians")
```

---


🔑 Key Points
 - Functions help avoid repetition
 - Use return to get values
 - Parameters make functions flexible

 ---

🚀 Practice
```python
# Function to check even or odd
def check(num):
    if num % 2 == 0:
        return "Even"
    else:
        return "Odd"

print(check(10))

# Function to find square
def square(n):
    return n * n

print(square(5))
```

---

🧠 What I Learned
 - How to create functions
 - Difference between parameters and arguments
 - Use of return statement