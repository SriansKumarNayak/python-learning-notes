# Python Notes (Day 19) 🐍

## Topics Covered
- Modules
- Packages
- Walrus Operator (:=)
- Function References (Revision)

---

## 📌 Modules

- A module is a file containing Python code  
- Helps organize code into separate files  
- Helps in code reusability

### Example:
```python
# file: math_utils.py
def add(a, b):
    return a + b
```

---

### Main File
```python
import math_utils

print(math_utils.add(2, 3))
```

---

📌 Import Methods
### Example:
```python
import math_utils
from math_utils import add
from math_utils import *
import math_utils as mu
```

---

📌 Packages

 - A package is a collection of modules
 - Organized using folders
 
### Structure:
```text
my_package/
    __init__.py
    module1.py
    module2.py
```
### Example:
```python
from my_package import module1
```

---

📌 Walrus Operator (:=)

 - Assigns and returns value in one expression

### Example:
```python
while (data := input("Enter: ")) != "quit":
    print(data)
```

---

📌 Function References

 - Functions can be stored and passed

### Example:
```python
def greet():
    print("Hello")

func = greet
func()
```

---

🔑 Key Points

 - Modules improve code organization
 - Packages group related modules
 - Walrus operator reduces repetition
 - Functions are first-class objects

🚀 Practice
```python
# Module practice
# Create a file and import it

# Walrus operator
while (n := int(input("Enter number: "))) != 0:
    print(n)
```

---

🧠 What I Learned

 - How to organize code using modules
 - Basics of packages
 - Using walrus operator efficiently
 - Reinforcing function concepts

---