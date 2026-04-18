# Python Notes (Day 18) 🐍

## Topics Covered
- Functions as Variables
- Higher Order Functions
- Lambda Functions
- map(), filter(), reduce()
- sort() with key

---

## 📌 Functions as Variables

- Functions are objects in Python  
- Can be assigned to variables  

### Example:
```python
def greet():
    return "Hello"

func = greet
print(func())
```

---

📌 Higher Order Functions

 - Functions that take other functions as arguments
 - Or return functions

### Example:
```python
def greet(name):
    return "Hello " + name

def display(func):
    print(func("Srians"))

display(greet)
```

---

📌 Lambda Functions

 - Anonymous (one-line) functions
 - Can only have a single expression (no multiple statements)

### Example:
```python
square = lambda x: x * x
print(square(5))
```

---

📌 map()

 - Applies function to all elements

### Example:
```python
nums = [1, 2, 3, 4]

result = list(map(lambda x: x * 2, nums))
print(result)
```

---

📌 filter()

 - Filters elements based on condition

### Example:
```python
nums = [1, 2, 3, 4]

result = list(filter(lambda x: x % 2 == 0, nums))
print(result)
```

---

📌 reduce()

 - Reduces list to single value
 - Found in functools module

### Example:
```python
from functools import reduce

nums = [1, 2, 3, 4]

result = reduce(lambda x, y: x + y, nums)
print(result)
```

---

📌 sort() with key

 - Sort list with custom logic using key functions

### Example:
```python
nums = [5, 2, 8, 1]

nums.sort()
print(nums)

# sort based on square
nums.sort(key=lambda x: x * x)
print(nums)
```

---

🔑 Key Points

 - Functions can be stored and passed
 - Higher order functions increase flexibility
 - Lambda → short functions
 - map → transform
 - filter → select
 - reduce → combine
 - sort(key=) → custom sorting
 - map(), filter(), return iterators (need to convert using list())

🚀 Practice

```python
# Double numbers using map
nums = [1, 2, 3]
print(list(map(lambda x: x * 2, nums)))

# Filter odd numbers
print(list(filter(lambda x: x % 2 != 0, nums)))

# Sum using reduce
from functools import reduce
print(reduce(lambda x, y: x + y, nums))
```

---

🧠 What I Learned

 - Functions are first-class objects
 - Writing shorter and cleaner code
 - Functional programming basics

---