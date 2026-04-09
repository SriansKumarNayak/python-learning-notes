# Python Notes (Day 10) 🐍

## Topics Covered
- Functions Practice
- List + Loop Problems
- Basic Logic Building

---

## 📌 Functions Practice

- Using functions to organize code

### Example:
```python
def greet(name):
    return "Hello " + name

print(greet("Srians"))
```

---

📌 List + Loop Practice
### Example:
```python
nums = [1, 2, 3, 4, 5]

# Print all elements
for num in nums:
    print(num)

# Print square of each number
for num in nums:
    print(num * num)
```

---

📌 Basic Problems
1. Find Maximum in List
```python
nums = [10, 25, 5, 40, 15]

max_num = nums[0]

for num in nums:
    if num > max_num:
        max_num = num

print(max_num)   # 40
```

---

2. Count Even Numbers
```python
nums = [1, 2, 3, 4, 5, 6]

count = 0

for num in nums:
    if num % 2 == 0:
        count += 1

print(count)   # 3
```

---

3. Reverse a String
```python
text = "python"

rev = ""

for char in text:
    rev = char + rev

print(rev)   # nohtyp
```

---

🔑 Key Points
 - Functions make code reusable
 - Lists + loops are powerful
 - Logic improves with practice

 ---

🧠 What I Learned
 - Writing functions for tasks
 - Solving problems using loops
 - Improving logical thinking

 ---