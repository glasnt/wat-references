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

