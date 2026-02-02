<h1 align="center"> 🐍 DAY 3: PYTHON REFRESHER FOR DATA SCIENCE </h1>

<br>

<h2 align="left"> ❓ Why Python for Data Science? </h2>

Data Science ke liye Python meri pehli choice hai kyunki:
* **Easy Syntax**: Iska code English jaisa lagta hai, toh logic par zyada focus kar sakte hain.
* **Massive Libraries**: NumPy, Pandas, aur Scikit-learn jaise powerful tools available hain.
* **Community Support**: Agar koi error aaye, toh solution turant mil jata hai.

---

<h2 align="left"> 📑 Variables & Data Types </h2>

Python ek **Dynamically Typed** language hai, yaani variable ka type declare karne ki zaroorat nahi padti.

| Data Type | Example | Description |
| :--- | :--- | :--- |
| **Integer** | `x = 10` | Whole numbers |
| **Float** | `y = 10.5` | Decimal numbers |
| **String** | `name = "Gemini"` | Text data |
| **Boolean** | `is_ready = True` | True or False values |

---

<h2 align="left"> ➗ Operators & Precedence </h2>

Maine aaj Python ke core operators ko explore kiya:

1. **Arithmetic**: `+`, `-`, `*`, `/`, `%` (Remainder), `**` (Power), `//` (Floor Division).
2. **Comparison**: `==`, `!=`, `>`, `<`, `>=`, `<=`.
3. **Logical**: `and`, `or`, `not`.

### ⚡ Operator Precedence (BODMAS for Python)
Python mein jab ek line mein kai operators hote hain, toh wo is order mein solve hote hain:
1. **Parentheses** `()`
2. **Exponentiation** `**`
3. **Multiplication, Division, etc.** `*`, `/`, `//`, `%`
4. **Addition & Subtraction** `+`, `-`

---

<h2 align="left"> ⌨️ Input & Output Methods </h2>

User se data lene aur dikhane ke liye:

```python
# Output Method
print("Welcome to Day 3")

# Input Method (Always returns a string by default)
age = int(input("Enter your age: ")) 
print(f"Your age is {age}") # Using f-string for formatting
