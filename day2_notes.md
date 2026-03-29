# Python Notes (Day 2) 🐍

## Topics Covered
- String Basics
- String Methods
- Input and Output

---

## 📌 Strings

- Strings are sequences of characters
- Enclosed in quotes (' ' or " ")

### Example:
name = "Srians"
print(name)

📌 String Indexing
text = "Python"
print(text[0])    #p
print(text[-1])   #n

📌 String Slicing
text = "Python"
print(text[0:4])  # Pyth
print(text[:3])   # Pyt
print(text[3:])   # hon

📌 String Methods
name = "python"

print(name.upper())      # PYTHON
print(name.lower())      # python
print(name.capitalize()) # Python
print(name.strip())      # removes spaces

📌 Taking Input
name = input("Enter your name: ")
print("Hello", name)

📌 Type Casting
age = int(input("Enter age: "))
print(age + 1)

🚀 Practice
name = input("Enter your name: ").strip()
print(name.upper())

text = "Hello World"
print(text[0:5])