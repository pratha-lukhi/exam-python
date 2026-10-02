# Interactive Personal Data Collector

## 📌 Project Description

**Interactive Personal Data Collector** is a beginner-friendly Python program that collects basic information from the user.

The program asks the user to enter their:

* Name
* Age
* Height
* Favourite Number

It then displays the entered information and shows the **data type** of each value. It also calculates the approximate birth year from the user's age.


🎥 Project Explanation Video: https://drive.google.com/drive/folders/1yQ8Rf_qxLpnRtEljYPpdu8o6CEvZ1_fl

## 🎯 Objective

The main objective of this project is to understand basic Python concepts such as:

* Taking input from the user
* Variables
* Data types
* Type casting
* `print()` function
* `input()` function
* Basic arithmetic operations

## 🛠️ Technologies Used

* Python 3
* OnlineGDB

## ⚙️ How the Program Works

### 1. Take User's Name

```python
name = input("Please enter your name :-")
```

The `input()` function takes the user's name. The value is stored as a **string (`str`)**.

### 2. Take User's Age

```python
age = int(input("Please enter your age :-"))
```

The `int()` function converts the entered age into an **integer (`int`)**.

### 3. Take User's Height

```python
height = float(input("Please enter your height :-"))
```

The `float()` function converts the entered height into a **floating-point number (`float`)**.

### 4. Take Favourite Number

```python
favnumber = int(input("Please enter your favourite number :-"))
```

The favourite number is converted into an **integer** using `int()`.

### 5. Display Data and Data Types

The program displays the entered information using `print()`.

It also uses the `type()` function to identify the data type.

For example:

```python
print("Name:", name)
print("Type:", type(name))
```

### 6. Calculate Approximate Birth Year

```python
birthyear = 2026 - age
```

The program subtracts the user's age from **2026** to calculate an approximate birth year.

## 🖥️ Sample Output

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

## 📚 Python Concepts Used

| Python Concept          | Purpose                                |
| ----------------------- | -------------------------------------- |
| `print()`               | Displays information                   |
| `input()`               | Takes input from the user              |
| `int()`                 | Converts a value into an integer       |
| `float()`               | Converts a value into a decimal number |
| `type()`                | Checks the data type                   |
| Variables               | Store user information                 |
| Arithmetic operator `-` | Calculates birth year                  |

## ⚠️ Note

The birth year is only **approximate** because the program uses the user's age and does not ask for the exact date of birth.

## 🔗 OnlineGDB

You can find the project code here:
live project link:
https://onlinegdb.com/itC8gYjar

## 👩‍💻 Author

**Pratha**

## 🏁 Conclusion

This project is a simple example of how Python can collect user information, work with different data types, perform type casting, and perform basic calculations. It is useful for beginners to practice the fundamentals of Python programming.

output screenshots:
<img width="611" height="452" alt="image" src="https://github.com/user-attachments/assets/d2d779e0-c311-47e5-864b-06ce07164e30" />
