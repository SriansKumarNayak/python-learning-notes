# Python Notes (Day 13) 🐍

## Topics Covered
- Encapsulation (Deep)
- Access Modifiers
- Polymorphism (Basics)

---

## 📌 Encapsulation (Deep)

- Hiding internal data and allowing controlled access  
- Achieved using private/protected variables  

### Example:
```python
class Bank:
    def __init__(self, balance):
        self.__balance = balance   # private variable

    def deposit(self, amount):
        self.__balance += amount

    def get_balance(self):
        return self.__balance

obj = Bank(1000)
obj.deposit(500)
print(obj.get_balance())
```

---

📌 Access Modifiers

 - Control access to variables and methods

Types:
 - Public → accessible anywhere
 - Protected → `_var` (internal use)
 - Private → `__var` (restricted access)
 
### Example:
```python
class Test:
    def __init__(self):
        self.a = 10      # public
        self._b = 20     # protected
        self.__c = 30    # private

obj = Test()
print(obj.a)   # works
print(obj._b)  # works (but not recommended)
# print(obj.__c)  # error
```

---

📌 Polymorphism (Basics)

 - Same function name behaves differently

### Example:
```python
def add(a, b):
    return a + b

print(add(2, 3))        # 5
print(add("Hi ", "Bro"))  # Hi Bro
```

---

🔑 Key Points

 - Encapsulation hides data
 - Use private variables for security
 - Polymorphism = many forms
 - Same function, different behavior

🚀 Practice

```python
# Encapsulation practice
class Student:
    def __init__(self, marks):
        self.__marks = marks

    def get_marks(self):
        return self.__marks

s = Student(90)
print(s.get_marks())

# Polymorphism practice
def multiply(a, b):
    return a * b

print(multiply(2, 3))
print(multiply("Hi ", 3))
```

---

🧠 What I Learned

 - Deep understanding of encapsulation
 - Access modifiers in Python
 - Basic polymorphism concept

 ---