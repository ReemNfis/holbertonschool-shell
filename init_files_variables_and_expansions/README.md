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
