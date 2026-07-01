# Data Types

## What are Data Types?

A data type tells Python what kind of value a variable stores.

Different types of data are used for different purposes.

---

## Why do we use Data Types?

Data types help Python understand:

- What kind of data is being stored.
- What operations can be performed on it.
- How much memory is needed.

---

## Common Data Types

### 1. Integer (`int`)

Stores whole numbers.

Example:

```python
age = 17
marks = 95
```

---

### 2. Float (`float`)

Stores decimal numbers.

Example:

```python
height = 5.9
price = 99.99
```

---

### 3. String (`str`)

Stores text.

Strings are written inside quotes.

Example:

```python
name = "Harshit"
city = "Hyderabad"
```

---

### 4. Boolean (`bool`)

Stores only two values.

```python
True
False
```

Example:

```python
is_student = True
```

---

## Example Program

```python
age = 17
height = 5.9
name = "Harshit"
is_student = True

print(age)
print(height)
print(name)
print(is_student)
```

Output:

```
17
5.9
Harshit
True
```

---

## Checking the Data Type

Use the `type()` function.

Example:

```python
age = 17

print(type(age))
```

Output:

```
<class 'int'>
```

---

## Common Mistakes

### 1. Forgetting quotation marks for strings

Wrong:

```python
name = Harshit
```

Correct:

```python
name = "Harshit"
```

---

### 2. Storing numbers inside quotes

```python
age = "17"
```

This is **not** an integer.

It is a string.

---

## Interview Questions

### Q1. What are the four basic data types in Python?

- int
- float
- str
- bool

---

### Q2. What is the difference between:

```python
17
```

and

```python
"17"
```

**Answer:**

`17` is an integer.

`"17"` is a string.

---

## Mini Challenge

Predict the output.

```python
name = "Python"

print(type(name))
```

Answer:

```
<class 'str'>
```

---

Predict the output.

```python
marks = 98.5

print(type(marks))
```

Answer:

```
<class 'float'>
```

---

## Summary

- Python stores different kinds of data using data types.
- `int` → Whole numbers.
- `float` → Decimal numbers.
- `str` → Text.
- `bool` → True or False.
- Use `type()` to check a variable's data type.
