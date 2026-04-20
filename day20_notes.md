# Python Notes (Day 20) 🐍

## Topics Covered
- if __name__ == "__main__"
- zip() Function
- List Comprehension
- Dictionary Comprehension
- time Module (Basics)

---

## 📌 if __name__ == "__main__"

- Ensures code runs only when file is executed directly  
- Prevents execution when imported as module  

### Example:
```python
def greet():
    print("Hello")

if __name__ == "__main__":
    greet()
```

---

📌 zip() Function

 - Combines multiple iterables element-wise
 - Stops when shortest iterable ends

### Example:
```python
names = ["A", "B", "C"]
marks = [90, 80, 85]

for n, m in zip(names, marks):
    print(n, m)
```

---

📌 List Comprehension

 - Short way to create lists

### Example:
```python
nums = [x * 2 for x in range(5)]
print(nums)
```

---

📌 Dictionary Comprehension

 - Short way to create dictionaries

### Example:
```python
nums = [1, 2, 3]

squares = {x: x * x for x in nums}
print(squares)
```

---

📌 time Module (Basics)

 - Used to work with time

### Example:
```python
import time

print("Start")
time.sleep(2)
print("End")
```

---

🔑 Key Points

 - __name__ check improves module usage
 - zip() combines data
 - Comprehensions make code shorter
 - time.sleep() pauses execution

🚀 Practice

```python
# zip practice
a = [1, 2]
b = [3, 4]

for x, y in zip(a, b):
    print(x + y)

# list comprehension
print([x for x in range(5) if x % 2 == 0])
```

---

🧠 What I Learned

 - Controlling execution with __name__
 - Combining data using zip
 - Writing cleaner code using comprehensions
 - Using time module basics

---