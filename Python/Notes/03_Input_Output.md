# Input and Output

## What is Input?

Input is the information entered by the user into a program.

Python uses the `input()` function to take input from the user.

Example:

```python
name = input("Enter your name: ")
```

---

## What is Output?

Output is the information displayed by the program to the user.

Python uses the `print()` function to display output.

Example:

```python
print("Welcome!")
```

---

## Why do we use Input and Output?

Input allows the user to interact with the program.

Output shows the result of the program.

---

## Syntax

### Input

```python
variable = input("Message")
```

### Output

```python
print(variable)
```

---

## Example Program

```python
name = input("Enter your name: ")

print("Hello", name)
```

Example Output:

```
Enter your name: Harshit

Hello Harshit
```

---

## Taking Number Input

The `input()` function always returns text (string).

To use numbers, convert the input using `int()`.

Example:

```python
age = int(input("Enter your age: "))
```

---

## Common Mistakes

### 1. Forgetting `int()`

Wrong:

```python
age = input("Enter age: ")
```

If you want to perform mathematical operations, this may cause problems.

Correct:

```python
age = int(input("Enter age: "))
```

---

### 2. Forgetting to print the result

Wrong:

```python
name = input("Enter your name: ")
```

Nothing is displayed after taking input.

Correct:

```python
print(name)
```

---

## Interview Questions

### Q1. What is the difference between `input()` and `print()`?

**Answer:**

- `input()` receives data from the user.
- `print()` displays data to the user.

---

### Q2. Why do we use `int(input())`?

**Answer:**

Because `input()` returns text by default.

`int()` converts it into an integer.

---

## Mini Challenge

Predict the output.

```python
name = input("Enter name: ")

print("Welcome", name)
```

If the user enters:

```
Harshit
```

Output:

```
Welcome Harshit
```

---

## Summary

- `input()` takes input from the user.
- `print()` displays output.
- `input()` returns a string.
- Use `int(input())` when working with integers.
