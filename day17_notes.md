# Python Notes (Day 17) 🐍

## Topics Covered
- Abstract Classes
- Objects as Arguments
- Duck Typing

---

## 📌 Abstract Classes

- Used to define a blueprint for other classes  
- Cannot create object of abstract class  
- Must be inherited  
- Must implement abstract methods in child class

### Example:
```python
from abc import ABC, abstractmethod

class Shape(ABC):
    @abstractmethod
    def area(self):
        pass

class Square(Shape):
    def area(self):
        return 4 * 4

obj = Square()
print(obj.area())
```

---

📌 Objects as Arguments

 - Passing objects to functions or methods

### Example:
```python
class Student:
    def __init__(self, name):
        self.name = name

class Course:
    def show(self, student):
        print("Student:", student.name)

s = Student("Srians")
c = Course()

c.show(s)
```

---

📌 Duck Typing

 - If an object has required methods, it can be used (no need of same class)

### Example:
```python
class Dog:
    def speak(self):
        print("Bark")

class Cat:
    def speak(self):
        print("Meow")

def make_sound(animal):
    animal.speak()

d = Dog()
c = Cat()

make_sound(d)
make_sound(c)
```

---

🔑 Key Points

 - Abstract class → blueprint
 - Must implement abstract methods in child class
 - Objects can be passed as arguments
 - Duck typing focuses on behavior, not type
 - Python is dynamically typed (supports duck typing)

🚀 Practice

```python
# Duck typing practice
class Bird:
    def fly(self):
        print("Flying")

class Airplane:
    def fly(self):
        print("Flying machine")

def start(obj):
    obj.fly()

start(Bird())
start(Airplane())
```

---

🧠 What I Learned

 - Abstract classes and their usage
 - Passing objects between classes
 - Concept of duck typing

---