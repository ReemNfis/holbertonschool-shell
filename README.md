# Shell, init files, variables and expansions

Bash scripts covering aliases, variables, expansions and shell arithmetic.

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
| `1-hello_you` | `echo "hello $USER"` | Prints hello followed by the current user |
