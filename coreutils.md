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
