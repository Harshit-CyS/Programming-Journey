# Conditions (if, elif, else)

## What are Conditions?

Conditions allow a program to make decisions based on whether a statement is **True** or **False**.

---

## Why do we use Conditions?

Conditions help us:

- Make decisions.
- Execute different code based on different situations.
- Build interactive programs.

---

## Syntax

```python
if condition:
    # code

elif condition:
    # code

else:
    # code
```

---

## How Python Checks Conditions

Python checks conditions **from top to bottom**.

As soon as it finds a condition that is **True**, it executes that block and skips the rest.

---

## Example

```python
marks = 92

if marks >= 90:
    print("Excellent")
elif marks >= 35:
    print("Pass")
else:
    print("Fail")
```

Output

```
Excellent
```

---

## Another Example

```python
number = -5

if number > 0:
    print("Positive")
elif number == 0:
    print("Zero")
else:
    print("Negative")
```

Output

```
Negative
```

---

## Common Mistakes

### 1. Using `=` instead of `==`

Wrong

```python
if marks = 90:
```

Correct

```python
if marks == 90:
```

---

### 2. Forgetting the colon (`:`)

Wrong

```python
if marks >= 35
```

Correct

```python
if marks >= 35:
```

---

### 3. Incorrect Order

Wrong

```python
if marks >= 35:
    print("Pass")
elif marks >= 90:
    print("Excellent")
```

The `Excellent` block will never run.

Correct

```python
if marks >= 90:
    print("Excellent")
elif marks >= 35:
    print("Pass")
```

Always write conditions from **more specific to more general**.

---

## Interview Questions

### Q1. What is the purpose of `if`?

It checks a condition and executes code if the condition is **True**.

---

### Q2. Why do we use `elif`?

To check another condition if the previous condition is **False**.

---

### Q3. When does the `else` block execute?

When **none** of the previous conditions are **True**.

---

## Practice Questions

### Predict the output

```python
age = 20

if age >= 18:
    print("Adult")
else:
    print("Minor")
```

Answer

```
Adult
```

---

### Predict the output

```python
marks = 40

if marks >= 90:
    print("Excellent")
elif marks >= 35:
    print("Pass")
else:
    print("Fail")
```

Answer

```
Pass
```

---

## Summary

- `if` checks the first condition.
- `elif` checks another condition if needed.
- `else` executes when all previous conditions are False.
- Python checks conditions from top to bottom.
- Arrange conditions from most specific to most general.
