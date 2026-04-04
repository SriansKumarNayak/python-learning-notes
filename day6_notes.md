# Python Notes (Day 6) 🐍

## Topics Covered
- Lists
- List Operations
- List Methods

---

## 📌 Lists

- Lists are used to store multiple items in a single variable
- Ordered and mutable (can be changed)

### Example:
```python
numbers = [1, 2, 3, 4, 5]
print(numbers)
```

---

📌 Accessing Elements

 - Index starts from 0

### Example:
```python
fruits = ["apple", "banana", "mango"]

print(fruits[0])   # apple
print(fruits[-1])  # mango
```

---

📌 List Slicing

 - Extract parts of a list

### Example:
```python
nums = [10, 20, 30, 40, 50]

print(nums[1:4])  # [20, 30, 40]
print(nums[:3])   # [10, 20, 30]
print(nums[2:])   # [30, 40, 50]
```

---

📌 List Operations
### Example:
```python
a = [1, 2, 3]
b = [4, 5]

print(a + b)   # [1, 2, 3, 4, 5]
print(a * 2)   # [1, 2, 3, 1, 2, 3]
```

---

📌 List Methods
Common Methods:
```python
nums = [1, 2, 3]

nums.append(4)     # add element
nums.insert(1, 10) # insert at index
nums.remove(2)     # remove element
nums.pop()         # remove last element

print(nums)
```

---

📌 Looping through List
### Example:
```python
fruits = ["apple", "banana", "mango"]

for fruit in fruits:
    print(fruit)
```

---

🔑 Key Points

 - Lists are mutable
 - Indexing starts from 0
 - Many useful built-in methods

 ---


🚀 Practice
```python
# Create a list and print elements
nums = [1, 2, 3, 4, 5]

for i in nums:
    print(i)

# Find sum of list
total = 0
for num in nums:
    total += num

print("Sum:", total)
```

---


🧠 What I Learned

 - How to create and use lists
 - Indexing and slicing
 - Basic list methods