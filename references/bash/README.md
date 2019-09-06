# Bash

[gnu.org/software/bash](https://www.gnu.org/software/bash/)

## Run these examples yourself

### docker

```
# Run the launch helper for the current directory
. ../launch ${PWD##*/}
```

### macOS

```
bash
```

# Bash Arithmetic

[How bash handles arithmetic](https://ryanstutorials.net/bash-scripting-tutorial/bash-arithmetic.php)

# and just for fun...


```bash
$ if [ 36 < 42 ]; then "true"; else "false" ; fi;
-bash: 42: No such file or directory
$ if [ 36 > 42 ]; then "true"; else "false" ; fi;
$
$ cat 42
$ 
```

Because everything is a file. - RKM 2019
