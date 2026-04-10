# Python Notes (Day 11) 🐍

## Topics Covered
- Inheritance
- Method Overriding
- super() Function
- Method Chaining

---

## 📌 Inheritance

- Allows one class to inherit properties and methods from another class  

### Example:
```python
class Parent:
    def show(self):
        print("This is parent")

class Child(Parent):
    pass

obj = Child()
obj.show()
```

---

📌 Method Overriding

 - Child class modifies the method of parent class

### Example:
```python
class Parent:
    def show(self):
        print("Parent method")

class Child(Parent):
    def show(self):
        print("Child method")

obj = Child()
obj.show()   # Child method
```

---

📌 super() Function

 - Used to call parent class methods inside child class

### Example:
```python
class Parent:
    def show(self):
        print("Parent method")

class Child(Parent):
    def show(self):
        super().show()
        print("Child method")

obj = Child()
obj.show()
```

---

📌 Method Chaining

 - Calling multiple methods in one line
 
### Example:
```python
class Student:
    def step1(self):
        print("Step 1")
        return self

    def step2(self):
        print("Step 2")
        return self

obj = Student()
obj.step1().step2()
```

---

🔑 Key Points

 - Inheritance helps reuse code
 - Method overriding changes behavior
 - super() accesses parent methods
 - Method chaining improves readability

 ---

🚀 Practice
```python
# Example with inheritance and overriding
class Animal:
    def sound(self):
        print("Some sound")

class Dog(Animal):
    def sound(self):
        super().sound()
        print("Bark")

obj = Dog()
obj.sound()
```

---

🧠 What I Learned

 - How inheritance works
 - Overriding methods
 - Using super()
 - Method chaining concept