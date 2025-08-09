# Day 01: Python Basics – Band Name Generator Project

## 🎯 Project Overview

Build a simple interactive Python program that generates a fun band name by combining:

- The city the user grew up in
- The name of their pet

This project introduces user input, variables, string manipulation, and formatted output—core building blocks of Python programming.

---

## 🧱 Key Concepts Introduced

| Concept               | Description                                 |
|-----------------------|---------------------------------------------|
| `print()`             | Displays messages to the user               |
| `input()`             | Captures user input from the console        |
| Variable assignment   | Stores user input in named containers       |
| String concatenation  | Combines multiple strings into one          |
| Output formatting     | Ensures clean and readable interaction      |

---

## 🖥️ Step-by-Step Breakdown

### 1. ✅ Welcoming the User

Use the `print()` function to greet the user and explain the program.

```python
print("Welcome to the Band Name Generator!")
```

---

### 2. 📥 Capturing User Input

Prompt the user for their city and pet name using `input()`.

```python
city = input("What's the name of the city you grew up in?\n")
pet = input("What's your pet's name?\n")
```

> **Note:** The `\n` ensures the cursor moves to the next line for better UX.

---

### 3. 🎸 Generating the Band Name

Use string concatenation to combine the inputs into a band name.

```python
band_name = city + " " + pet
print("Your band name could be: " + band_name)
```

---

## 🔍 Example Output

```
Welcome to the Band Name Generator!
What's the name of the city you grew up in?
Chennai
What's your pet's name?
Simba
Your band name could be: Chennai Simba
```

---

## 💡 Best Practices

- ✅ Use descriptive variable names (`city`, `pet`) for clarity.
- ✅ Add spacing between strings (`" "`) to avoid merged words.
- ✅ Use `\n` in prompts for cleaner input flow.
- ✅ Keep the program modular—each step should be clear and purposeful.

---

## 🧪 Suggested Exercises

- Modify the program to ask for a favorite color and include it in the band name.
- Add input validation to ensure the user doesn’t leave fields blank.
- Use f-strings for cleaner output formatting:

```python
print(f"Your band name could be: {city} {pet}")
```

---

## 🧠 Reflection & Practice

Try building the Band Name Generator from scratch without looking at the solution. Once done, compare your version with the provided one and note any improvements or differences.