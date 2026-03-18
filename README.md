# Linux Command Journal

A personal journal documenting Linux commands I'm learning on my DevOps journey. Updated regularly.

---

## Table of Contents

- [Navigation](#navigation)
- [File Management](#file-management)
- [Permissions](#permissions)
- [Text Processing](#text-processing)
- [Networking](#networking)
- [Bash Scripting](#bash-scripting)

---

## Navigation

| Command | Description | Example |
|---|---|---|
| `pwd` | Print current working directory | `pwd` |
| `ls` | List files in a directory | `ls -la` |
| `cd` | Change directory | `cd /var/log` |
| `tree` | Display directory structure as a tree | `tree -L 2` |

---

## File Management

| Command | Description | Example |
|---|---|---|
| `touch` | Create a new empty file | `touch file.txt` |
| `mkdir` | Create a new directory | `mkdir -p folder/subfolder` |
| `cp` | Copy a file or directory | `cp file1.txt file2.txt` |
| `mv` | Move or rename a file | `mv oldname.txt newname.txt` |
| `rm` | Remove a file or directory | `rm -rf foldername` |
| `find` | Search for files | `find / -name "file.txt"` |

---

## Permissions

| Command | Description | Example |
|---|---|---|
| `chmod` | Change file permissions | `chmod 755 script.sh` |
| `chown` | Change file owner | `chown user:group file.txt` |
| `ls -l` | View file permissions | `ls -l` |

---

## Text Processing

| Command | Description | Example |
|---|---|---|
| `cat` | Display file content | `cat file.txt` |
| `grep` | Search for a pattern in a file | `grep "error" file.txt` |
| `awk` | Pattern scanning and processing | `awk '{print $1}' file.txt` |
| `sed` | Stream editor for filtering text | `sed 's/old/new/g' file.txt` |
| `wc` | Count lines, words, characters | `wc -l file.txt` |

---

## Networking

| Command | Description | Example |
|---|---|---|
| `ping` | Test network connectivity | `ping google.com` |
| `curl` | Transfer data from a URL | `curl https://example.com` |
| `wget` | Download files from the web | `wget https://example.com/file` |
| `netstat` | Display network connections | `netstat -tuln` |
| `ssh` | Connect to a remote server | `ssh user@192.168.1.1` |

---

## Bash Scripting

| Command | Description | Example |
|---|---|---|
| `chmod +x` | Make a script executable | `chmod +x script.sh` |
| `./script.sh` | Run a script | `./script.sh` |
| `echo` | Print text to terminal | `echo "Hello World"` |
| `$()` | Command substitution | `date=$(date +%F)` |

---

*This journal grows as I learn. Last updated: March 2026*