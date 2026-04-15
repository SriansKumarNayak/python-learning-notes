# Python Notes (Day 15) 🐍

## Topics Covered
- File Reading Methods
- read(), readline(), readlines()
- Writing Multiple Lines

---

## 📌 File Reading Methods

- Python provides multiple ways to read files  

---

## 📌 read()

- Reads entire file content  

### Example:
```python
with open("test.txt", "r") as f:
    data = f.read()
    print(data)
```

---

📌 readline()

 - Reads one line at a time
 
### Example:
```python
with open("test.txt", "r") as f:
    print(f.readline())
    print(f.readline())
```

---

📌 readlines()

 - Reads all lines and returns a list

### Example:
```python
with open("test.txt", "r") as f:
    lines = f.readlines()
    print(lines)
```

---

📌 Writing Multiple Lines

### Example:
```python
with open("test.txt", "w") as f:
    f.write("Line 1\n")
    f.write("Line 2\n")
```

---

📌 Loop Through File

### Example:
```python
with open("test.txt", "r") as f:
    for line in f:
        print(line)
```

---

🔑 Key Points

 - read() → full content
 - readline() → one line
 - readlines() → list of lines
 - Looping through file is memory efficient

🚀 Practice

```python
# Count number of lines
count = 0

with open("test.txt", "r") as f:
    for line in f:
        count += 1

print("Lines:", count)
```

---

🧠 What I Learned

 - Different ways to read files
 - Working with lines
 - Efficient file handling

---