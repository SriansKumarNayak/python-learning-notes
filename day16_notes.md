# Python Notes (Day 16) 🐍

## Topics Covered
- Exceptions
- try, except
- else, finally

---

## 📌 Exceptions

- Errors that occur during program execution  
- Can crash the program if not handled  

---

## 📌 try & except

- Used to handle errors and prevent crashes  

### Example:
```python
try:
    num = int(input("Enter number: "))
    print(10 / num)
except:
    print("Error occurred")
```

---

📌 Specific Exception

 - Handle specific errors

### Example:
```python
try:
    num = int(input("Enter number: "))
    print(10 / num)
except ValueError:
    print("Invalid input")
except ZeroDivisionError:
    print("Cannot divide by zero")
```

---

📌 else Block

 - Runs if no exception occurs

### Example:
```python
try:
    x = int(input("Enter number: "))
except ValueError:
    print("Wrong input")
else:
    print("You entered:", x)
```

---

📌 finally Block

 - Runs no matter what (error or not)

### Example:
```python
try:
    f = open("test.txt")
except:
    print("File not found")
finally:
    print("Execution finished")
```

---

🔑 Key Points

 - try → code that may cause error
 - except → handle errors
 - else → runs if no error
 - finally → always runs
 - Always use specific exceptions when possible

🚀 Practice

```python
# Handle division
try:
    a = int(input("Enter number: "))
    print(100 / a)
except ZeroDivisionError:
    print("Cannot divide by zero")

# Handle invalid input
try:
    n = int(input("Enter number: "))
except ValueError:
    print("Invalid number")
```

---

🧠 What I Learned

 - How to handle errors
 - Prevent program crashes
 - Use of try, except, else, finally

 ---