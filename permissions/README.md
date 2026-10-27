# Shell, permissions

| File | Command | Description |
|---|---|---|
| `0-iam_betty` | `su betty` | Switches the current user to the user `betty`. |
| `1-who_am_i` | `whoami` | Prints the effective username of the current user. |
| `2-groups` | `groups` | Prints all the groups the current user is part of. |
| `3-new_owner` | `chown betty hello` | Changes the owner of the file `hello` to the user `betty`. |
| `4-empty` | `touch hello` | Creates an empty file called `hello`. |
| `5-execute` | `chmod u+x hello` | Adds execute permission to the owner of the file `hello`. |
| `6-multiple_permissions` | `chmod ug+x,o+r hello` | Adds execute permission to the owner and the group owner, and read permission to other users, to the file `hello`. |
| `7-everybody` | `chmod ugo+x hello` | Adds execute permission to the owner, the group owner and other users, to the file `hello`. |
| `8-James_Bond` | `chmod 007 hello` | Sets no permissions for the owner and group, and all permissions for other users, on the file `hello`. |
| `9-John_Doe` | `chmod 753 hello` | Sets the mode of the file `hello` to `-rwxr-x-wx`. |
| `10-mirror_permissions` | `chmod --reference=olleh hello` | Sets the mode of the file `hello` the same as `olleh`’s mode. |
| `11-directories_permissions` | `chmod a+X *` | Adds execute permission to all subdirectories of the current directory for everyone; regular files are not changed. |
| `12-directory_permissions` | `mkdir -m 751 my_dir` | Creates a directory called `my_dir` with permissions `751` in the working directory. |
| `13-change_group` | `chgrp school hello` | Changes the group owner of the file `hello` to `school`. |
