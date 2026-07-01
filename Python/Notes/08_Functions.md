# Functions

## What is a Function?

A function is a reusable block of code that performs a specific task.

Instead of writing the same code again and again, we write it once inside a function and call it whenever needed.

---

## Why do we use Functions?

Functions help us to:

- Avoid repeating code.
- Make programs easier to read.
- Make programs easier to debug.
- Break large programs into smaller parts.

---

## Syntax

```python
def function_name():
    # code
```

Example:

```python
def greet():
    print("Hello")
```

---

## Calling a Function

A function does **nothing** until it is called.

Example:

```python
def greet():
    print("Hello")

greet()
```

Output

```
Hello
```

---

## Functions with Parameters

A parameter is a variable written inside the parentheses while defining a function.

Example

```python
def greet(name):
    print("Hello", name)

greet("Harshit")
```

Output

```
Hello Harshit
```

---

## Functions with Multiple Parameters

```python
def add(a, b):
    print(a + b)

add(10, 20)
```

Output

```
30
```

---

## The `return` Statement

`return` sends a value back to the place where the function was called.

Example

```python
def add(a, b):
    return a + b

answer = add(10, 20)

print(answer)
```

Output

```
30
```

---

## `print()` vs `return()`

### `print()`

- Displays the result.
- Cannot be reused later.

Example

```python
def add(a, b):
    print(a + b)
```

---

### `return()`

- Gives the result back.
- The value can be stored and reused.

Example

```python
def add(a, b):
    return a + b

answer = add(5, 10)

print(answer)
```

---

## Why do we write

```python
answer = add(first, second)
```

When Python sees:

```python
add(first, second)
```

it **does not understand the word "add" as addition**.

It simply looks for a function named `add()`.

If it finds:

```python
def add(a, b):
    return a + b
```

it executes the code inside that function.

So `add` is just the **name of the function**, not a Python keyword.

---

## Common Mistakes

### 1. Forgetting to call the function

Wrong

```python
def greet():
    print("Hello")
```

Nothing happens.

Correct

```python
greet()
```

---

### 2. Forgetting `return`

Wrong

```python
def add(a, b):
    a + b
```

Correct

```python
def add(a, b):
    return a + b
```

---

### 3. Confusing `print()` with `return`

Remember:

- `print()` shows the result.
- `return` gives the result back to the program.

---

## Interview Questions

### Q1. What is a function?

A function is a reusable block of code that performs a specific task.

---

### Q2. What is the difference between parameters and arguments?

Parameters are written while defining a function.

```python
def greet(name):
```

Arguments are the actual values passed while calling it.

```python
greet("Harshit")
```

---

### Q3. What is the difference between `print()` and `return()`?

- `print()` displays the result.
- `return` sends the result back so it can be reused.

---

## Practice Questions

### Predict the output

```python
def greet():
    print("Python")

greet()
```

Answer

```
Python
```

---

### Predict the output

```python
def square(x):
    return x * x

print(square(4))
```

Answer

```
16
```

---

## Summary

- Functions help avoid repeating code.
- A function must be called to execute.
- Parameters receive values.
- Arguments are the values passed to parameters.
- `print()` displays output.
- `return` sends a value back for further use.
