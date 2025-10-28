# 🐧 Linux Command Guide

A beginner-friendly collection of essential **Linux commands**, organized by category with examples.  
Perfect for quick reference and learning the Linux terminal.

---

## 📂 File and Directory Commands

| Command | Description | Example |
|----------|--------------|----------|
| `ls` | Lists files and directories | `ls -l` |
| `cd` | Changes the current directory | `cd /home/user/Documents` |
| `pwd` | Prints the current working directory | `pwd` |
| `mkdir` | Creates a new directory | `mkdir my_folder` |
| `rmdir` | Removes an empty directory | `rmdir old_folder` |
| `rm` | Removes files or directories | `rm file.txt` / `rm -r folder/` |
| `cp` | Copies files or directories | `cp file.txt /home/user/` |
| `mv` | Moves or renames files or directories | `mv file.txt newfile.txt` |
| `touch` | Creates an empty file or updates a file timestamp | `touch newfile.txt` |
| `cat` | Displays file contents | `cat file.txt` |
| `more` / `less` | Views file contents one page at a time | `less file.txt` |
| `head` | Shows the first lines of a file | `head -n 10 file.txt` |
| `tail` | Shows the last lines of a file | `tail -n 10 file.txt` |
| `find` | Searches for files or directories | `find /home -name "*.txt"` |
| `locate` | Quickly finds files using a database | `locate file.txt` |

---

## ⚙️ File Permissions and Ownership

| Command | Description | Example |
|----------|--------------|----------|
| `chmod` | Changes file permissions | `chmod 755 script.sh` |
| `chown` | Changes file owner and group | `chown user:group file.txt` |
| `chgrp` | Changes group ownership | `chgrp developers file.txt` |
| `umask` | Sets default file permissions | `umask 022` |

---

## 🧠 System Information

| Command | Description | Example |
|----------|--------------|----------|
| `uname` | Displays system information | `uname -a` |
| `hostname` | Shows or sets the system’s hostname | `hostname` |
| `uptime` | Shows how long the system has been running | `uptime` |
| `date` | Displays or sets the date and time | `date` |
| `cal` | Displays a calendar | `cal 2025` |
| `df` | Shows disk space usage | `df -h` |
| `du` | Shows file/directory space usage | `du -sh /home/user` |
| `free` | Displays memory usage | `free -h` |
| `top` | Displays running processes | `top` |
| `htop` | Interactive process viewer (if installed) | `htop` |

---

## 💻 User Management

| Command | Description | Example |
|----------|--------------|----------|
| `whoami` | Displays the current user | `whoami` |
| `id` | Displays user ID and group info | `id` |
| `adduser` | Adds a new user | `sudo adduser newuser` |
| `passwd` | Changes a user’s password | `passwd` |
| `su` | Switches user | `su root` |
| `sudo` | Runs a command as superuser | `sudo apt update` |
| `who` | Shows who is logged in | `who` |
| `last` | Shows login history | `last` |

---

## 🌐 Networking Commands

| Command | Description | Example |
|----------|--------------|----------|
| `ping` | Checks network connectivity | `ping google.com` |
| `ifconfig` / `ip addr` | Displays network configuration | `ip addr` |
| `netstat` | Shows network connections | `netstat -tuln` |
| `curl` | Transfers data from or to a server | `curl https://example.com` |
| `wget` | Downloads files from the web | `wget https://example.com/file.zip` |
| `ssh` | Connects to a remote system | `ssh user@192.168.1.10` |
| `scp` | Copies files over SSH | `scp file.txt user@server:/path/` |
| `traceroute` | Traces the route packets take to a host | `traceroute google.com` |

---

## 📦 Package Management (Ubuntu/Debian)

| Command | Description | Example |
|----------|--------------|----------|
| `apt update` | Updates package lists | `sudo apt update` |
| `apt upgrade` | Upgrades installed packages | `sudo apt upgrade` |
| `apt install` | Installs a package | `sudo apt install vim` |
| `apt remove` | Removes a package | `sudo apt remove vim` |
| `apt autoremove` | Removes unused packages | `sudo apt autoremove` |

---

## 🧾 Text Processing Commands

| Command | Description | Example |
|----------|--------------|----------|
| `grep` | Searches for text in files | `grep "error" logfile.txt` |
| `sort` | Sorts lines of text | `sort names.txt` |
| `uniq` | Filters duplicate lines | `uniq list.txt` |
| `cut` | Extracts fields from text | `cut -d',' -f1 data.csv` |
| `awk` | Pattern scanning and text processing | `awk '{print $1}' data.txt` |
| `sed` | Stream editor for modifying text | `sed 's/apple/orange/g' file.txt` |

---

## 🔁 Process Management

| Command | Description | Example |
|----------|--------------|----------|
| `ps` | Displays running processes | `ps aux` |
| `kill` | Terminates a process by PID | `kill 1234` |
| `killall` | Kills processes by name | `killall firefox` |
| `bg` | Sends a process to the background | `bg` |
| `fg` | Brings a background process to the foreground | `fg` |
| `jobs` | Lists background jobs | `jobs` |
| `nice` / `renice` | Changes process priority | `nice -n 10 command` |

---

## 📜 Compression and Archiving

| Command | Description | Example |
|----------|--------------|----------|
| `tar` | Archives files | `tar -cvf archive.tar folder/` |
| `gzip` / `gunzip` | Compresses/decompresses files | `gzip file.txt` / `gunzip file.txt.gz` |
| `zip` / `unzip` | Creates/extracts ZIP files | `zip archive.zip file.txt` / `unzip archive.zip` |

---

## 🧩 Other Useful Commands

| Command | Description | Example |
|----------|--------------|----------|
| `history` | Shows command history | `history` |
| `alias` | Creates a shortcut for commands | `alias ll='ls -la'` |
| `man` | Shows manual pages | `man ls` |
| `clear` | Clears the terminal screen | `clear` |
| `exit` | Logs out of terminal | `exit` |

---

## 💡 Tips

- Use `man <command>` to learn details about any command.  
  Example: `man grep`
- Combine commands with `|` (pipe) for powerful workflows.  
  Example: `ls -l | grep ".txt"`

---

## 📘 Author
**Your Name**  
📂 GitHub: [0xSafkat20 Repositoy](https://github.com/0xSafkat20/bash_book)

---

✅ *Feel free to fork and contribute — add new commands or examples!*
