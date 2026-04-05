# Python Notes (Day 7) 🐍

## Topics Covered
- Dictionaries
- Accessing Data
- Dictionary Methods

---

## 📌 Dictionaries

- Used to store data in key-value pairs  
- Unordered, mutable  

### Example:
```python
student = {
    "name": "Srians",
    "age": 18,
    "course": "Python"
}

print(student)
```

---

📌 Accessing Values

 - Access values using keys

### Example:
```python
student = {
    "name": "Srians",
    "age": 18
}

print(student["name"])   # Srians
print(student.get("age"))  # 18
```

---

📌 Adding & Updating

### Example:
```python
student = {
    "name": "Srians",
    "age": 18
}

student["age"] = 19        # update
student["city"] = "Rourkela"  # add new key

print(student)
```

---

📌 Removing Elements

### Example:
```python
student = {
    "name": "Srians",
    "age": 18
}

student.pop("age")   # removes key
print(student)
```

---

📌 Dictionary Methods

### Example:
```python
student = {
    "name": "Srians",
    "age": 18
}

print(student.keys())    # all keys
print(student.values())  # all values
print(student.items())   # key-value pairs
```

---

📌 Looping through Dictionary

### Example:
```python
student = {
    "name": "Srians",
    "age": 18
}

for key, value in student.items():
    print(key, ":", value)
```

---

🔑 Key Points

 - Data stored as key-value pairs
 - Keys must be unique
 - Dictionaries are mutable

 ---

🚀 Practice

```python
# Create dictionary and print values
person = {
    "name": "John",
    "age": 25
}

print(person["name"])

# Loop and print
for key in person:
    print(key, person[key])

```

---

🧠 What I Learned

 - How dictionaries work
 - Accessing and updating values
 - Looping through dictionary