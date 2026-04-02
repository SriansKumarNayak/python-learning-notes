# Python Notes (Day 4) 🐍

## Topics Covered
- Loops
- for loop
- while loop
- break and continue

---

## 📌 Loops

- Used to repeat a block of code multiple times
- Saves time and reduces repetition

---

## 📌 for Loop

- Used to iterate over a sequence (like string, list)

### Example:
```python
for i in range(5):
    print(i)
```
👉Output: 0 1 2 3 4

📌 range()

Generates numbers in a sequence
Example:
```python
print(range(5))        # 0 to 4
print(range(1, 6))     # 1 to 5
print(range(1, 10, 2)) # step of 2
```

📌 while Loop
Runs while condition is True
### Example:
```python
i = 0

while i < 5:
    print(i)
    i += 1
```

📌 break
Stops the loop immediately

### Example:
```python
for i in range(10):
    if i == 5:
        break
    print(i)
```

📌 continue

-Skips current iteration
### Example:
```python
for i in range(5):
    if i == 2:
        continue
    print(i)
```

🔑 Key Points
for loop → fixed iterations
while loop → condition-based
break → exit loop
continue → skip iteration

🚀 Practice
```python
# Print numbers from 1 to 10
for i in range(1, 11):
    print(i)

# Print even numbers
for i in range(1, 11):
    if i % 2 == 0:
        print(i)

# while loop example
num = 1
while num <= 5:
    print(num)
    num += 1
```

🧠 What I Learned
How loops work
Difference between for and while
Use of break and continue