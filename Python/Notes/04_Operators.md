# Operators

## What are Operators?

Operators are symbols used to perform operations on values and variables.

They help us perform calculations and compare values.

---

## Why do we use Operators?

Operators allow us to:

- Perform mathematical calculations.
- Compare two values.
- Make decisions in programs.

---

# Arithmetic Operators

These operators perform mathematical calculations.

| Operator | Meaning | Example |
|----------|---------|---------|
| + | Addition | 10 + 5 = 15 |
| - | Subtraction | 10 - 5 = 5 |
| * | Multiplication | 10 * 5 = 50 |
| / | Division | 10 / 5 = 2.0 |
| % | Modulus (Remainder) | 10 % 3 = 1 |

---

## Example

```python
a = 10
b = 5

print(a + b)
print(a - b)
print(a * b)
print(a / b)
print(a % b)
```

Output

```
15
5
50
2.0
0
```

---

# Comparison Operators

Comparison operators compare two values.

They always return either:

- True
- False

| Operator | Meaning |
|----------|---------|
| == | Equal to |
| != | Not Equal to |
| > | Greater than |
| < | Less than |
| >= | Greater than or Equal to |
| <= | Less than or Equal to |

---

## Example

```python
marks = 90

print(marks >= 35)
```

Output

```
True
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

### 2. Forgetting that `/` gives a decimal answer

```python
print(10 / 2)
```

Output

```
5.0
```

Not

```
5
```

---

## Interview Questions

### Q1. What is the difference between `=` and `==`?

`=` assigns a value.

`==` compares two values.

---

### Q2. Which operator gives the remainder?

Answer:

```
%
```

(Modulus Operator)

---

## Mini Challenge

Predict the output.

```python
print(20 % 6)
```

Answer

```
2
```

---

Predict the output.

```python
print(8 >= 10)
```

Answer

```
False
```

---

## Summary

- Arithmetic operators perform calculations.
- Comparison operators compare values.
- `=` assigns values.
- `==` compares values.
- `%` gives the remainder.
