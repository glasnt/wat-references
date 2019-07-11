# Python2

## Run these examples yourself

### docker

```
# Run the launch helper for the current directory
. ../launch ${PWD##*/}
```

### macOS

```
brew install python
python2
```

## '8' < 8

[Originally learnt from Trey Hunner](https://github.com/treyhunner/python-oddities/blob/master/index.html#L579)

[Python 2 Comparisons - docs.python.org](https://docs.python.org/2/library/stdtypes.html#comparisons)

> "Objects of different types [..] never compare equal; such objects are ordered consistently but arbitrarily (so that sorting a heterogeneous array yields a consistent result)."

> "CPython implementation detail: Objects of different types except numbers are ordered by their type names; objects of the same types that don’t support proper comparison are ordered by their address."

[Specific location in Python 2.7.14c2 code, github.com](https://github.com/python/cpython/blob/v2.7.14rc1/Objects/object.c#L785)

[Related writeup by Luke Lee on Pluralsight](https://www.pluralsight.com/guides/comparing-unrelated-types)

