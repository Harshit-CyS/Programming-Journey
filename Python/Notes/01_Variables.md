# Variables

## What is a Variable?

A variable is a **named container** used to store a value.

It allows us to store information and use or change it whenever needed in a program.

---

## Why do we use Variables?

Variables help us to:

- Store data.
- Reuse values without typing them again.
- Make programs easier to understand.
- Update values whenever needed.

Without variables, programs become difficult to write and maintain.

---

## Syntax

```python
variable_name = value
```

Examples:

```python
name = "Harshit"
age = 17
marks = 98.3
```

---

## Assignment Operator (`=`)

The assignment operator (`=`) is used to assign (store) a value to a variable.

Example:

```python
age = 17
```

Here,

- `age` → Variable
- `17` → Value

---

## Comparison Operator (`==`)

The comparison operator (`==`) checks whether two values are equal.

It returns either:

- `True`
- `False`

Example:

```python
age = 17

print(age == 17)
```

Output:

```
True
```

Example:

```python
print(age == 18)
```

Output:

```
False
```

---

## Example Program

```python
name = "Harshit"
age = 17

print(name)
print(age)
```

Output:

```
Harshit
17
```

---

## Variable Naming Rules

A variable name:

- Can contain letters (`a-z`, `A-Z`)
- Can contain numbers (`0-9`)
- Can contain underscores (`_`)
- Cannot start with a number
- Cannot contain spaces
- Should have meaningful names

Correct:

```python
student_name
phone_number
total_marks
```

Wrong:

```python
1name
my name
@marks
```

---

## Common Mistakes

### 1. Using `==` instead of `=`

Correct:

```python
marks = 95
```

Wrong:

```python
marks == 95
```

---

### 2. Using spaces in variable names

Wrong:

```python
my name = "Harshit"
```

Correct:

```python
my_name = "Harshit"
```

---

### 3. Giving meaningless names

Not Recommended:

```python
x = 95
```

Better:

```python
marks = 95
```

---

## Interview Questions

### Q1. What is a variable?

A variable is a named container used to store data.

---

### Q2. What is the difference between `=` and `==`?

`=` assigns a value to a variable.

`==` compares two values and returns either `True` or `False`.

---

### Q3. Can a variable name start with a number?

No.

Example:

```python
1name = "Harshit"
```

This gives an error.

Correct:

```python
name1 = "Harshit"
```

---

## Mini Challenge

### Predict the output.

```python
city = "Hyderabad"

print(city)
```

Answer:

```
Hyderabad
```

---

### Predict the output.

```python
age = 17

print(age == 17)
```

Answer:

```
True
```

---

## Summary

- A variable stores a value.
- `=` assigns a value.
- `==` compares two values.
- Variables make programs easier to read and maintain.
- Always use meaningful variable names.
