
- [Bash - For Loop in 1 line](#bash-for-loop-in-1-line)
- [Command du](#command-du)

### Bash for loop in 1 line

```bash
for file in $(ls); do echo ${file}; done
```
Example:

```bash
Applications
Desktop
Documents
Downloads
Library
Movies
Music
Pictures
Public
```

---

### Command **du**

#### Give a summary (total size of directory) - this is the most used option

```bash
du -s .
```

#### Give a summary of each directory within a directory - second most used option

```bash
du -s ./*
```

#### Limit **du** to a certain number of subdirectories

For example to show a max of 1 sub level (subdirectory):

```bash
du -d 1 /your-dir/
```

---

