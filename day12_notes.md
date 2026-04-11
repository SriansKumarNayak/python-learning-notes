# Python Notes (Day 12) 🐍

## Topics Covered
- Constructor (__init__)
- Instance Variables
- Encapsulation (Basics)

---

## 📌 Constructor (__init__)

- A constructor is a special method that runs automatically when an object is created  

### Example:
```python
class Student:
    def __init__(self, name, age):
        self.name = name
        self.age = age

obj = Student("Srians", 18)
print(obj.name)
print(obj.age)
```

---

📌 Instance Variables

 - Variables defined inside a class using self
 - Each object has its own copy
 
### Example:
```python
class Car:
    def __init__(self, brand):
        self.brand = brand

c1 = Car("BMW")
c2 = Car("Audi")

print(c1.brand)
print(c2.brand)
```

---

📌 Encapsulation (Basics)

 - Wrapping data and methods into a single unit (class)
 - Restrict direct access to variables

### Example:
```python
class Bank:
    def __init__(self, balance):
        self._balance = balance   # protected variable

    def show_balance(self):
        print(self._balance)

obj = Bank(1000)
obj.show_balance()
```

---

🔑 Key Points

 - __init__() is called automatically
 - self refers to current object
 - Instance variables store object data
 - Encapsulation improves security

🚀 Practice

```python
# Create a class with constructor
class Person:
    def __init__(self, name):
        self.name = name

p = Person("John")
print(p.name)

# Simple encapsulation
class Test:
    def __init__(self):
        self._x = 10

    def show(self):
        print(self._x)

obj = Test()
obj.show()
```

---

🧠 What I Learned

 - How constructors work
 - Use of self and instance variables
 - Basics of encapsulation

 ---