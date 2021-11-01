# PHP

[php.net](https://php.net/)

## Run these examples yourself

### docker

```
# Run the launch helper for the current directory
. ../launch ${PWD##*/}
```

### macOS

```
brew install php
php -a
```

# Ternary comparisons

**Note:** "Nested ternaries now require explicit parentheses." as of PHP 8. See [PHP 8.0 Migration Guide](https://www.php.net/manual/en/migration80.incompatible.php)

# String to Number Comparison

[php.net](https://www.php.net/manual/en/migration80.incompatible.php#migration80.incompatible.core.string-number-comparision)

```php
php> if (0 == "foo") { echo "true"; } else { echo "false";}
false
```
