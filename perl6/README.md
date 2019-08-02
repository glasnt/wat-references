# Perl 6

[perl6.org](https://perl6.org/)

## Run these examples yourself

### docker

```
# Run the launch helper for the current directory
. ../launch ${PWD##*/}
```

### macOS

```
brew install perl6
perl6 --repl-mode=interactive
```

# Numeric values

[Unicode versus ASCII symbols, perl6.org](https://docs.perl6.org/language/unicode_ascii)

Perl6 can handle numbers if the codepoint in unicode has one of the following types: 

* `Nd` (Number, decimal digit), e.g. １\uFF11
* `No` (Number, other) e.g. ⅒o \u2152
* `Nl` (Number, letter) e.g. Ⅳ \u2163

