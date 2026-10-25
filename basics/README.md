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
