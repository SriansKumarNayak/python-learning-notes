# Python Notes (Day 3) 🐍

## Topics Covered
- Conditional Statements
- if, elif, else
- Nested Conditions

---

## 📌 Conditional Statements

- Used to make decisions in code
- Executes code based on conditions

---

## 📌 if Statement

- Executes block if condition is True

### Example:
```python
age = 18

if age >= 18:
    print("You are eligible to vote")
```    

📌 if-else Statement

 - Executes one block if True, another if False

### Example:
```python
age = 16

if age >= 18:
    print("Eligible")
else:
    print("Not Eligible")
```    

📌 if-elif-else Statement

 - Used for multiple conditions


### Example:
```python
marks = 75

if marks >= 90:
    print("Grade A")
elif marks >= 70:
    print("Grade B")
elif marks >= 50:
    print("Grade C")
else:
    print("Fail")
```

📌 Nested if

 - if inside another if

### Example:
```python
age = 20
citizen = True

if age >= 18:
    if citizen:
        print("You can vote")

```        

🔑 Key Points

 - Conditions return True or False
 - Indentation is important in Python
 - elif is used for multiple conditions
 - Nested if can be used for complex logic

🚀 Practice
```python
num = int(input("Enter a number: "))

if num % 2 == 0:
    print("Even Number")
else:
    print("Odd Number")

marks = int(input("Enter marks: "))

if marks >= 90:
    print("A")
elif marks >= 70:
    print("B")
else:
    print("C or below")

```    

🧠 What I Learned

 - How to use if, elif, else
 - How to make decisions in code
 - Nested conditions