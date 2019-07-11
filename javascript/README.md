# JavaScript

## Run these examples yourself

### docker

```
# Run the launch helper for the current directory
. ../launch ${PWD##*/}
```

### macOS

```
brew install jsc
jsc
```

Also: Google Chrome developer console (⌘ + shift + c)


# Implicit Type Coercion

```
> 4 - "2"
2
```

[Implicit Strings and Numbers. Safari Books](https://www.safaribooksonline.com/library/view/you-dont-know/9781491905159/ch04.html#implicitly-strings----numbers)

> The `-` operator is defined only for numeric subtraction, so [4 - "2"] forces ["2"]'2 value to be coerced to a number

```
> 4 + "2"
42
```

> According to the ES5 spec, section 11.6.1, the + algorithm (when an object
> value is an operand) will concatenate if either operand is either already a
> string ...


```
> 1 == "1"
True
```

[Loose Equals, vs Stritch Equals, Safari Books](https://www.safaribooksonline.com/library/view/you-dont-know/9781491905159/ch04.html#loose-equals-vs-strict-equals)

> == allows coercion in the equality comparison and === disallows coercion.


[More information, 2ality.com](http://2ality.com/2012/01/object-plus-object.html)

# Addition Operator

[ECMA262, Addition Operator](http://www.ecma-international.org/ecma-262/9.0/index.html#sec-addition-operator-plus)

[ECMA262, Blocks](https://tc39.github.io/ecma262/#prod-Block)

[ECMA262, Unary Plus operator](https://tc39.github.io/ecma262/#sec-unary-plus-operator)

[Explaination from Daniel Ehrenbeg, Twitter](https://twitter.com/littledan/status/1036991541154394115)


