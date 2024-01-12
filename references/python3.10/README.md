# Python 3.10+

[python.org](http://python.org)


See also [Python 3.7](../python3.7/)

## Run these examples yourself

### docker

```
./launch python
```

### macOS
```
brew install python
python
```

# Pattern matching

Python 3

```python
def fib(n):
    if n == 0: return 0
    if n == 1: return 1
    return fib(n - 1) + fib(n - 2)
```

Python 3.10+

```
def fib(n):
    match n:
        case 0:
            return 0
        case 1:
            return 1
        case _:
            return fib(n - 1) + fib(n - 2)
```


And for more fun: 

```
def sum(a, b):
    match (a, b): 
        case (2, 2): return 5
        case _: return a + b
```
