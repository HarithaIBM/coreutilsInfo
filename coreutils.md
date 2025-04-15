# 🧰 GNU Core Utilities (coreutils)

GNU Core Utilities (coreutils) is a package of essential command-line tools used on Unix-like operating systems. These are the basic file, shell, and text manipulation utilities that form the backbone of most Linux distributions.

---

## 📦 What's Included?

Coreutils brings together three sets of tools:

### 📁 File Utilities
Used for file operations.

| Command | Description |
|---------|-------------|
| `ls`    | List directory contents |
| `cp`    | Copy files and directories |
| `mv`    | Move/rename files and directories |
| `rm`    | Remove files or directories |
| `mkdir` | Create directories |
| `rmdir` | Remove empty directories |
| `touch` | Change file timestamps or create empty files |
| `stat`  | Display file/directory status |
| `readlink` | Print resolved symbolic links |

---

### 🧮 Text Utilities
Used to manipulate text data.

| Command | Description |
|---------|-------------|
| `cat`   | Concatenate and display files |
| `tac`   | Reverse version of `cat` |
| `cut`   | Remove sections from lines of text |
| `paste` | Merge lines of files |
| `sort`  | Sort lines of text |
| `uniq`  | Filter out repeated lines |
| `wc`    | Word, line, character, byte count |
| `head`  | Output the first lines of a file |
| `tail`  | Output the last lines of a file |
| `split` | Split a file into pieces |

---

The `ls` command in Unix is used to list the contents of directories. Common options include:</br>
`-l` for long listing format</br>
`-a` to include hidden files</br>
`-h` to make file sizes human-readable</br>

 The `cp` command is used to copy files and directories. The `-r` option enables recursive copying of directories. </br>
 
 The `grep` command is used to search for patterns in text. Useful options include:</br>
`-i` for case-insensitive matching</br>
`-r` for recursive directory search</br>
`-n` to show line numbers in output</br>

The `wc` command counts lines, words, and characters in files. Example:</br>
`wc -l file.txt` → count lines</br>
`wc -w file.txt` → count words</br>
`wc -c file.txt` → count characters</br>

The `sort` command arranges lines of text alphabetically or numerically. Use:</br>
`-n` for numeric sort</br>
`-r` to reverse order</br>
`-u` to remove duplicates</br>

### ⚙️ Shell Utilities
General-purpose shell tools.

| Command | Description |
|---------|-------------|
| `echo`     | Display a line of text |
| `printf`   | Format and print data |
| `test`     | Evaluate conditional expressions |
| `true`     | Return a true (zero) value |
| `false`    | Return a false (non-zero) value |
| `yes`      | Output a string repeatedly |
| `sleep`    | Delay for a specified amount of time |
| `date`     | Display or set the system date and time |
| `whoami`   | Show the current user ID |
| `id`       | Print user and group information |
| `env`      | Show environment or run a command in a modified environment |
| `basename` | Strip directory and suffix from filenames |
| `dirname`  | Extract directory portion of a path |

---

## 🧪 Example Usage

```bash
# List files with details
ls -l

# Count lines, words, and characters
wc filename.txt

# Display only the first 5 lines
head -n 5 filename.txt

# Sort a list and remove duplicates
sort data.txt | uniq

# Sleep for 2 seconds
sleep 2
