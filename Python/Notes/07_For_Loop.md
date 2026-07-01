# For Loop

## What is a For Loop?

A `for` loop is used to repeat a block of code for every item in a sequence.

Unlike a `while` loop, a `for` loop is commonly used when the number of repetitions is already known.

---

## Why do we use For Loops?

We use a `for` loop to:

- Repeat code multiple times.
- Iterate through numbers.
- Iterate through strings.
- Write cleaner code than using multiple `print()` statements.

---

## Syntax

### Using `range()`

```python
for variable in range(start, stop):
    # code
```

### Iterating through a string

```python
for letter in "Python":
    print(letter)
```

---

## Example 1: Numbers

```python
for number in range(1, 6):
    print(number)
```

Output

```
1
2
3
4
5
```

---

## Example 2: Characters

```python
for letter in "DOG":
    print(letter)
```

Output

```
D
O
G
```

---

## Understanding `range()`

### `range(5)`

Prints:

```
0
1
2
3
4
```

---

### `range(1, 6)`

Prints:

```
1
2
3
4
5
```

---

### `range(3, 8)`

Prints:

```
3
4
5
6
7
```

---

## When should we use a For Loop?

Use a `for` loop when:

- You know how many times the loop should run.
- You want to go through numbers or characters one by one.

---

## While Loop vs For Loop

| While Loop | For Loop |
|------------|----------|
| Runs while a condition is True | Runs through a sequence |
| Usually used when repetitions are unknown | Usually used when repetitions are known |

---

## Common Mistakes

### 1. Forgetting the colon (`:`)

Wrong

```python
for i in range(5)
```

Correct

```python
for i in range(5):
```

---

### 2. Expecting `range(5)` to print 1–5

Wrong expectation:

```
1
2
3
4
5
```

Actual output:

```
0
1
2
3
4
```

---

### 3. Using quotation marks with `range()`

Wrong

```python
range("5")
```

Correct

```python
range(5)
```

---

## Interview Questions

### Q1. When should we use a `for` loop?

When the number of repetitions is known.

---

### Q2. Can a `for` loop iterate through a string?

Yes.

Example:

```python
for letter in "Python":
    print(letter)
```

---

### Q3. What does `range(5)` produce?

```
0
1
2
3
4
```

---

## Practice Questions

### Predict the output

```python
for i in range(2, 5):
    print(i)
```

Answer

```
2
3
4
```

---

### Predict the output

```python
for letter in "CAT":
    print(letter)
```

Answer

```
C
A
T
```

---

## Summary

- A `for` loop repeats code for each item in a sequence.
- `range()` is commonly used with `for` loops.
- A `for` loop can iterate through numbers and strings.
- Use a `for` loop when the number of repetitions is known.
