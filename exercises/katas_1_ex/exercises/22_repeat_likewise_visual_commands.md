### Repeat likewise visual commands

Suppose we have this Python code:

```python
def fib(n):
    a, b = 0, 1
    while a < n:
print a,
a, b = b, a+b
fib(42)
```

The result should look like this:

```python
def fib(n):
    a, b = 0, 1
    while a < n:
        print a,
        a, b = b, a+b
fib(42)
```
