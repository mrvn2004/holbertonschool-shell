# I/O Redirections and Filters

## 0. Hello World
Prints "Hello, World" followed by a new line to standard output.
- **1-confused_smiley**: Displays a confused smiley `"(Ôo)'`
.
- **2-hellofile**: Displays the contents of the `/etc/passwd` file.
- **3-twofiles**: Displays the contents of `/etc/passwd` and `/etc/hosts`.
- **4-lastlines**: Displays the last 10 lines of `/etc/passwd`.
- **5-firstlines**: Displays the first 10 lines of `/etc/passwd`.
- **6-third_line**: Displays the third line of the file `iacta`.
- **7-file**: Creates a file with a special name containing `Best School` followed by a new line.
8-cwd_state: Writes the output of ls -la to ls_cwd_content, overwriting the file if it already exists.
9-duplicate_last_line: Duplicates the last line of iacta and appends it to the file.
10-no_more_js: Deletes all regular .js files in the current directory and its subdirectories.
11-directories: Counts all directories and subdirectories, including hidden ones, excluding the current and parent directories.
12-newest_files: Displays the 10 newest entries in the current directory, sorted from newest to oldest.
13-unique: Displays words that appear exactly once, sorted alphabetically.
14-findthatword: Displays lines containing the pattern root from /etc/passwd.
15-countthatword: Counts the lines containing the pattern bin in /etc/passwd.
16-whatsnext: Displays lines containing root and the three lines that follow in /etc/passwd.
17-hidethisword: Displays all lines in /etc/passwd that do not contain the pattern "bin".                               18-letteronly: Displays lines in /etc/ssh/sshd_config that start with a letter.
19-AZ: Replaces all occurrences of A with Z and c with e in standard input.
20-hiago: Removes all occurrences of the characters c and C from standard input.
21-reverse: Reverses each line of standard input.
22-users_and_homes: Displays usernames and home directories from /etc/passwd, sorted by username.
