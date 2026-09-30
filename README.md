# Interactive Personal Data Collector

## 📌 Project Description

**Interactive Personal Data Collector** is a simple Python program that collects basic personal information from the user.

The program asks the user to enter:

* Name
* Age
* Height
* Favourite Number

It then displays the entered information along with the **data type** of each value. Finally, it calculates the user's approximate birth year.

## 🎯 Purpose of the Project

The main purpose of this project is to learn and practice:

* `input()` function
* Variables
* `int()` type casting
* `float()` type casting
* `type()` function
* `print()` function
* Basic mathematical calculations

## 🛠️ Technologies Used

* **Python 3**

## 💻 How the Program Works

### 1. Enter Name

The program asks the user to enter their name.

```python
name = input("Please enter your name :-")
```

The `input()` function stores the name as a **string**.

### 2. Enter Age

The program asks for the user's age.

```python
age = int(input("Please enter your age :-"))
```

`int()` converts the entered value into an **integer**.

### 3. Enter Height

The program asks for the user's height.

```python
height = float(input("Please enter your height :-"))
```

`float()` converts the entered value into a **decimal number**.

### 4. Enter Favourite Number

The program asks for the user's favourite number.

```python
favnumber = int(input("Please enter your favourite number :-"))
```

The value is converted into an **integer**.

### 5. Display Information

The program displays each entered value and its data type using the `type()` function.

Example:

```python
print("Name:", name)
print("Type:", type(name))
```

### 6. Calculate Birth Year

The program calculates the approximate birth year using:

```python
birthyear = 2026 - age
```

It subtracts the user's age from the current year.

## ▶️ Example Output

```text
Welcome to the Interactive Personal Data Collecter!

Please enter your name :- Pratha
Please enter your age :- 18
Please enter your height :- 5.4
Please enter your favourite number :- 7

Name: Pratha
Type: <class 'str'>

Age: 18
Type: <class 'int'>

Height: 5.4
Type: <class 'float'>

Favourite Number: 7
Type: <class 'int'>

Your birth year is approximately: 2008
```

## 📚 Concepts Learned

| Concept    | Use                                |
| ---------- | ---------------------------------- |
| `input()`  | Takes input from the user          |
| `int()`    | Converts value into integer        |
| `float()`  | Converts value into decimal number |
| `type()`   | Checks the data type               |
| `print()`  | Displays output                    |
| Variables  | Store information                  |
| Arithmetic | Calculates birth year              |

## ⚠️ Note

The birth year is **approximate** because the program only uses the user's age and does not ask for their date of birth.

## 👩‍💻 Author

**Pratha**
