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

[Amy Hanlon "Investigating Python Wats", PyCon US 2015](https://www.youtube.com/watch?v=sH4XF6pKKmk)

https://github.com/python/cpython/blob/main/Include/internal/pycore_global_objects.h#L44C7-L44C72

```
PyLongObject small_ints[_PY_NSMALLNEGINTS + _PY_NSMALLPOSINTS];
```


Equality is not Identity

# And just for fun...

```python
>>> not True & False
True
>>> not True and False
False
```

Just like Ruby. Because `&` (or `&&`) is bitwise, and bitwise is higher than negation is higher than logical. - RKM 2019


# Put your grapheme down, flip it and reverse it

```
>>> "hello world"[::-1]
'dlrow olleh'
>>> "🇦🇺"[::-1]
'🇺🇦'
>>> [c for c in "🇦🇺"]
['🇦', '🇺']
```

ISO-3166 `AU` -> Australia. National animal: Kangaroo 🦘
ISO-3166 `UA` -> Ukraine. National animal: Common nightingale 🐦 

(both in Eurovision, tho)

[How to reverse a string in Python - Michael Farrell](https://youtu.be/q2VmIUaOS9o?t=1723)

[grapheme on pypi](https://pypi.org/project/grapheme/)


```
>>> e = "🇦🇺🐨"
>>> [c for c in e]
['🇦', '🇺', '🐨']

>>> import grapheme
>>> list(grapheme.graphemes(e))
['🇦🇺', '🐨']
```