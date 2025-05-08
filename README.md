# 🔁 If, Else, Elif – Basic Decision-Making in Python

Python lets you make decisions using `if`, `else`, and `elif` (short for "else if").  
This allows your program to react differently based on conditions.

---

## 💡 When to Use

* Run a block of code only if a condition is true  
* Add different outcomes using `else`  
* Add more than two options using `elif`

---

## 💻 Example with Explanation

```python
age = 17

if age >= 18:
    print("You're an adult.")
elif age >= 13:
    print("You're a teenager.")
else:
    print("You're a kid.")
```

### 🔈 Output

```
You're a teenager.
```

---

### 📌 Key Notes

* Each condition is checked **top to bottom**  
* Only the **first matching** condition runs  
* Use `:` at the end of each condition line  
* Use **indentation** (4 spaces) to show what belongs inside the condition

---

## 🧪 Try It Yourself

```python
score = 85

if score >= 90:
    print("Grade: A")
elif score >= 80:
    print("Grade: B")
elif score >= 70:
    print("Grade: C")
else:
    print("Keep trying!")
```

### 🔈 Expected Output

```
Grade: B
```

---

🐍 This is part of the **Pythonly** beginner series.  
Learn Python one line at a time. Follow **@Pythonly** for more.

---


