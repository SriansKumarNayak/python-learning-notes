# Python Notes (Day 8) 🐍

## Topics Covered
- Tuples
- Tuple Operations
- Sets

---

## 📌 Tuples
- Tuples are used to store multiple items in a single variable  
- Ordered and immutable (cannot be changed)  

### Example:
```python
numbers = (1, 2, 3, 4)
print(numbers)
```

---

📌 Accessing Elements
 - Index starts from 0

### Example:
```python
t = (10, 20, 30)

print(t[0])   # 10
print(t[-1])  # 30
```

---

📌 Tuple Methods
 - Limited methods because tuples are immutable
### Example:
```python
t = (1, 2, 2, 3)

print(t.count(2))   # count occurrences
print(t.index(3))   # index of element
```

---

📌 Sets
 - Unordered collection
 - No duplicate values
### Example:
```python
s = {1, 2, 3, 3, 4}
print(s)   # duplicates removed
```

---

📌 Set Operations
### Example:
```python
a = {1, 2, 3}
b = {3, 4, 5}

print(a.union(b))        # {1,2,3,4,5}
print(a.intersection(b)) # {3}
print(a.difference(b))   # {1,2}
```

---

📌 Adding & Removing in Sets
### Example:
```python
s = {1, 2, 3}

s.add(4)      # add element
s.remove(2)   # remove element

print(s)
```

---

🔑 Key Points
 - Tuples → immutable
 - Sets → no duplicates
 - Lists → mutable

 ---

🚀 Practice
```python
# Tuple example
t = (5, 10, 15)
print(t[1])

# Set example
s = {1, 2, 2, 3}
print(s)

# Union
a = {1, 2}
b = {2, 3}
print(a.union(b))
```

---

🧠 What I Learned
 - Difference between tuple, list, and set
 - Tuple immutability
 - Set operations