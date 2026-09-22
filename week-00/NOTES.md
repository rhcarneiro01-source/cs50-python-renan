# Week 00 — Study Notes

## 1. Functions
A function is a reusable block of code that performs a task.

```python
print("Hello, world!")
```

## 2. Variables
Variables store values that can be used later.

```python
name = "Renan"
```

## 3. Input
`input()` receives text from the user.

```python
name = input("What's your name? ")
```

## 4. Strings
Strings represent text.

Useful methods to explore:
- `.strip()`
- `.title()`
- `.lower()`
- `.upper()`
- `.replace()`

## 5. Numbers
`int` represents integers.
`float` represents numbers with decimal places.

```python
x = int(input("x: "))
y = int(input("y: "))
print(x + y)
```

## 6. Operators
Examples:
- `+`
- `-`
- `*`
- `/`
- `%`
- `**`

## 7. Creating your own functions

```python
def greet(name):
    return f"Hello, {name}"
```

## 8. Scope
A variable created inside a function is normally local to that function.

## 9. Comments
Use `#` to leave short explanations in your source code.

## 10. Pseudocode
Before coding, describe the logic in simple steps.

Example:
1. Ask the user for a name.
2. Clean the input.
3. Display a greeting.

## Study rule
Try to understand each exercise before searching for an answer.
Use debugging and small tests to learn how Python behaves.
