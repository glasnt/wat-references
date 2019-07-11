# Go (golang)

[golang.org](https://golang.org/)

## Run these examples yourself

### brower

Interactive golang terminal on [golang.org](https://golang.org/)

### docker

```
# Run the launch helper for the current directory
. ../launch ${PWD##*/}
```

### macOS

```
brew install go
go run bad_example.go ## WILL FAIL
go run example.go
```


# `:=`

[Short variable declarations, golang.org](https://golang.org/ref/spec#Short_variable_declarations)

# `-128/-1=-128`

[Fun golang facts, pasiphae_goals, twitter](https://twitter.com/pasiphae_goals/status/923821863222079488)
> Fact #2: -128/-1=-128 in #golang, but only sometimes.

[Link to working example, rozaliev, twitter](https://twitter.com/rozaliev/status/923919964720988166)

[Operators, golang](https://golang.org/ref/spec#Operators)

> The one exception to this rule is that if the dividend x is the most negative
value for the int type of x, the quotient q = x / -1 is equal to x (and r = 0)
due to two's-complement integer overflow

[Integer overflow, golang.org](https://golang.org/ref/spec#Integer_overflow)
