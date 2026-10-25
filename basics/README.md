# Shell, basics

| File | Command | Description |
|------|---------|-------------|
| `0-current_working_directory` | `pwd` | Prints the absolute path of the current working directory. |
| `1-listit` | `ls` | Displays the contents list of the current directory. |
| `2-bring_me_home` | `cd` | Changes the working directory to the user's home directory. |
| `3-listfiles` | `ls -l` | Displays the current directory contents in long format. |
| `4-listmorefiles` | `ls -la` | Displays the current directory contents, including hidden files, in long format. |
| `5-listfilesdigitonly` | `ls -lan` | Displays the current directory contents, including hidden files, in long format with numeric user and group IDs. |
| `6-firstdirectory` | `mkdir /tmp/my_first_directory` | Creates a directory named `my_first_directory` in the `/tmp/` directory. |
| `7-movethatfile` | `mv /tmp/betty /tmp/my_first_directory` | Moves the file `betty` from `/tmp/` to `/tmp/my_first_directory`. |
| `8-firstdelete` | `rm /tmp/my_first_directory/betty` | Deletes the file `betty` from `/tmp/my_first_directory`. |
| `9-firstdirdeletion` | `rmdir /tmp/my_first_directory` | Deletes the empty directory `my_first_directory` from `/tmp`. |
| `10-back` | `cd -` | Changes the working directory to the previous one. |
| `11-lists` | `ls -la . .. /boot` | Lists all files, including hidden ones, in the current directory, the parent directory and `/boot`, in long format. |
| `12-file_type` | `file /tmp/iamafile` | Prints the type of the file `iamafile` located in `/tmp`. |
| `13-symbolic_link` | `ln -s /bin/ls __ls__` | Creates a symbolic link named `__ls__` to `/bin/ls` in the current working directory. |
| `14-copy_html` | `cp -u *.html ..` | Copies HTML files from the current directory to the parent directory, only if they are new or newer. |
| `15-lets_move` | `mv [A-Z]* /tmp/u`  `mv [[:upper:]]* /tmp/u` | Moves all files beginning with an uppercase letter to `/tmp/u`. |
| `16-clean_emacs` | `rm *~` | Deletes all files in the current working directory that end with `~`. |
| `17-tree` | `mkdir -p welcome/to/school` | Creates the directories `welcome/`, `welcome/to/` and `welcome/to/school` in the current directory. |

