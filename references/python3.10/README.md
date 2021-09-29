# Python

[python.org](http://python.org)

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


# a is b

```python
>>> a = 256
>>> b = 256
>>> a is b
True

>>> a = 257
>>> b = 257
>>> a is b
False

>>> a = 257; b = 257
>>> a is b
True
```
[Amy Hanlon "Investigating Python Wats", PyCon US 2015](www.youtube.com/watch?v=sH4XF6pKKmk)

Equality is not Identity

# And just for fun...

```python
>>> not True & False
True
>>> not True and False
False
```

Just like Ruby. Because `&` (or `&&`) is bitwise, and bitwise is higher than negation is higher than logical. - RKM 2019

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
