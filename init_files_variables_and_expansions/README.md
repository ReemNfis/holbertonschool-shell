# Shell, init files, variables and expansions

Bash scripts covering shell initialization files, variables, expansions, shell arithmetic, and aliases.

## Requirements

- Tested on Ubuntu 20.04 LTS
- Each script is exactly two lines long and starts with `#!/bin/bash`
- No use of `&&`, `||`, `;`, `bc`, `sed`, or `awk`
- All scripts are executable

## Tasks

| File | Description | General syntax |
|------|-------------|----------------|
| `0-alias` | Creates an alias named `ls` with the value `rm -f *`. Run it with `source ./0-alias` so the alias persists in the current shell. | `alias name='command'` |
