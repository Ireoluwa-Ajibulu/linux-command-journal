# Text Processing

Commands for reading, searching and manipulating text in Linux.

| Command | Description | Example |
|---|---|---|
| `cat` | Display file content | `cat file.txt` |
| `grep` | Search for a pattern in a file | `grep "error" file.txt` |
| `grep -r` | Search recursively in all files | `grep -r "error" /var/log` |
| `grep -i` | Search case-insensitively | `grep -i "error" file.txt` |
| `awk` | Pattern scanning and processing | `awk '{print $1}' file.txt` |
| `sed` | Stream editor for filtering text | `sed 's/old/new/g' file.txt` |
| `wc` | Count lines, words, characters | `wc -l file.txt` |
