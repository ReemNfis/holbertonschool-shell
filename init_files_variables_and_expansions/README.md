# Shell, init files, variables and expansions

Bash scripts covering init files, variables, expansions, shell arithmetic, and aliases.

## Requirements

- Tested on Ubuntu 20.04 LTS with Bash
- Each script is exactly two lines, starting with `#!/bin/bash`
- `&&`, `||`, `;`, `bc`, `sed` and `awk` are not allowed

## Usage

Scripts that change the current shell (aliases, variables) must be sourced:

```bash
source ./0-alias
```

## Tasks

| File | Command | Description |
|------|---------|-------------|
| `0-alias` | `alias ls='rm -f *'` | Creates an alias `ls` that runs `rm -f *` |
| `1-hello_you` | `echo "hello $USER"` | Prints `hello` followed by the current Linux user |
| `2-path` | `PATH=$PATH:/action` | Adds `/action` as the last directory in `PATH` |
| `3-paths` | `echo "$PATH" \| tr ":" "\n" \| grep -c '.'` | Counts the number of directories in `PATH` |
| `4-global_variables` | `printenv` | Lists all environment (global) variables |
| `5-local_variables` | `set` | Lists all local variables, environment variables and functions |
| `6-create_local_variable` | `BEST="School"` | Creates a local variable `BEST` with the value `School` |
| `7-create_global_variable` | `export BEST="School"` | Creates a global (environment) variable `BEST` with the value `School` |
| `8-true_knowledge` | `echo $((128 + TRUEKNOWLEDGE))` | Prints the sum of 128 and the value of `TRUEKNOWLEDGE` |
| `9-divide_and_rule` | `echo $((POWER / DIVIDE))` | Prints the result of `POWER` divided by `DIVIDE` |
| `10-love_exponent_breath` | `echo $((BREATH ** LOVE))` | Prints `BREATH` raised to the power of `LOVE` |
| `11-binary_to_decimal` | `echo $((2#$BINARY))` | Converts the base 2 number in `BINARY` to base 10 |
| `12-combinations` | `printf "%s\n" {a..z}{a..z} \| grep -v oo` | Prints all two-letter combinations from `aa` to `zz`, except `oo` |
| `13-print_float` | `printf "%.2f\n" "$NUM"` | Prints the value of `NUM` with two decimal places |
| `14-decimal_to_hexadecimal` | `printf "%x\n" "$DECIMAL"` | Converts the base 10 number in `DECIMAL` to base 16 |
