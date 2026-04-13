# Python Notes (Day 14) 🐍

## Topics Covered
- File Handling
- Reading Files
- Writing Files

---

## 📌 File Handling

- Used to work with files (read/write data)
- Python provides built-in functions for file operations  

---

## 📌 Opening a File

Syntax:
```python
file = open("filename.txt", "mode")
```

---

Modes:

 - "r" → read
 - "w" → write (overwrites file)
 - "a" → append
 - "x" → create file

📌 Reading a File

Example:
```python
file = open("test.txt", "r")

content = file.read()
print(content)

file.close()
```

---

📌 Writing to a File

Example:
```python
file = open("test.txt", "w")

file.write("Hello World")

file.close()
```

---

📌 Appending to a File

Example:
```python
file = open("test.txt", "a")

file.write("\nNew Line")

file.close()
```

---

📌 Using with Statement (Best Practice)

 - Automatically closes file

Example:
```python
with open("test.txt", "r") as file:
    print(file.read())
```

---

🔑 Key Points

 - Always close files after use
 - "w" overwrites file content
 - "a" adds content without deleting
 - with statement is safer and automatically closes file

🚀 Practice

```python
# Write to file
with open("demo.txt", "w") as f:
    f.write("Hello Python")

# Read from file
with open("demo.txt", "r") as f:
    print(f.read())
```

---

🧠 What I Learned

 - How to open and use files
 - Different file modes
 - Importance of closing files
 - Using with statement

---