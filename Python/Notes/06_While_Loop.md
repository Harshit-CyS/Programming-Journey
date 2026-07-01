# While Loop

## What is a While Loop?

A `while` loop repeatedly executes a block of code **as long as a condition is True**.

---

## Why do we use While Loops?

We use a while loop when:

- We want to repeat a task.
- We don't know exactly how many times the loop should run.
- The loop depends on a condition.

---

## Syntax

```python
while condition:
    # code
```

The loop stops automatically when the condition becomes **False**.

---

## Example 1: Counting from 1 to 5

```python
count = 1

while count <= 5:
    print(count)
    count = count + 1
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

## Example 2: Countdown

```python
count = 5

while count >= 1:
    print(count)
    count = count - 1

print("Blast Off!")
```

Output

```
5
4
3
2
1
Blast Off!
```

---

## Infinite Loop

An infinite loop happens when the condition never becomes False.

Example

```python
count = 1

while count <= 5:
    print(count)
```

Since `count` never changes, the loop runs forever.

---

## Common Mistakes

### 1. Forgetting to update the variable

Wrong

```python
count = 1

while count <= 5:
    print(count)
```

Correct

```python
count = 1

while count <= 5:
    print(count)
    count = count + 1
```

---

### 2. Wrong Condition

```python
count = 5

while count <= 1:
    print(count)
```

The loop never runs because the condition is already False.

---

## Interview Questions

### Q1. When should you use a while loop?

Use a while loop when the number of repetitions depends on a condition.

---

### Q2. What is an infinite loop?

A loop that never stops because its condition always remains True.

---

### Q3. How do you stop a while loop?

Make the condition become False or use the `break` statement.

---

## Practice Questions

### Predict the output

```python
count = 3

while count >= 1:
    print(count)
    count = count - 1
```

Answer

```
3
2
1
```

---

### Predict the output

```python
count = 1

while count < 4:
    print("Python")
    count = count + 1
```

Answer

```
Python
Python
Python
```

---

## Summary

- `while` repeats code while a condition is True.
- Update the loop variable inside the loop.
- Infinite loops occur when the condition never becomes False.
- Use `break` to exit a loop early.
