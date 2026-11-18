# CEIS 106 — Introduction to Operating Systems

### Course & Lab Overview
During **CEIS 106 (Introduction to Operating Systems)** at **DeVry University**, I completed hands-on labs across **Microsoft Windows** and **Fedora Linux** (via uCertify), earning full credit on all 15 graded hands-on activities. My coursework focused on operating system administration, command-line navigation, file system permissions, user and group management, Bash shell scripting, and network connectivity diagnostics.

---

### Operating Systems, Tools & Commands Practiced
- **Operating Systems & Environments:** Microsoft Windows, Fedora Linux, Linux Bash Shell, and uCertify Lab Environment
- **File & Directory Operations:** `pwd`, `ls`, `cat`, `cp`, `rm`, `touch`, `mkdir`, and output redirection operators
- **Permissions & Ownership:** `chmod`, `chown`, `chgrp`, `umask`
- **User & Group Administration:** `useradd`, `usermod`, `userdel`, `groupadd`, `groupdel`, `id`, `who`, `su`, `sudo`
- **Hardware & Process Monitoring:** `ps`, `top`, `free`, `df`, `lscpu`, `uname`
- **Text Editing & Shell Scripting:** `vi`, `nano`, Bash scripts (`#!/bin/bash`, `read`, `echo`, `while`, `case`, `exit`)
- **Network & DNS Troubleshooting:** `ping`, `ping6`, `host`, `dig`, `ifconfig`, `netstat`, `route`
- **Core Linux System Directories & Files Studied:** `/etc/passwd`, `/etc/shadow`, `/etc/group`, `/etc/skel`, `/proc/cpuinfo`, `/var/log`, and `/tmp`

---

### Completed Hands-On Lab Modules
1. **Module 1 — Windows Administration:** Configured user account settings and performed baseline Windows security checks.
2. **Module 2 — Linux Fundamentals:** Navigated the Fedora Linux graphical desktop, used built-in command-line help documentation, and reviewed terminal command history.
3. **Module 3 — Linux System Management:** Inspected system CPU specifications, checked storage and disk usage, and monitored or controlled running processes.
4. **Module 4 — Linux File Systems:** Explored Linux directory structures, practiced input/output redirection operators, and queried active process information.
5. **Module 5 — Linux Scripting & Security:** Created and edited text files using `vi`, built conditional Bash shell scripts, and managed local user accounts and security groups.
6. **Module 6 — Linux Administration & Networking:** Configured file access permissions, queried DNS records to locate a domain's mail server, and tested network connectivity.

---

### Reference Command & Scripting Syntax Practiced
*Note: The snippets below represent documented command and scripting syntax practiced during course study sessions rather than exported lab files.*

```bash
# User, Group & Permission Administration Examples
useradd -M nemo
groupadd --gid 1027 groupname
chmod o+x filename
chown carol:students text.txt

# Network & DNS Diagnostic Examples
ping -c 11 tranquility.luna.edu
host google.com
dig google.com
```

```bash
#!/bin/bash
# Interactive Bash Input & Conditional Branching Example
echo "Enter your name:"
read name
echo "Hello $name"

case $choice in
    yes) echo "Yes selected" ;;
    no)  echo "No selected" ;;
esac
```

---

### Key Takeaways & IT Support Relevance
- **Least-Privilege Access Control:** Learned how Linux user accounts, groups, ownership (`chown`), and permission strings (`chmod`) protect sensitive system files from unauthorized changes.
- **Command-Line Diagnostics:** Built confidence inspecting CPU load, disk capacity, memory usage, and background processes directly from the terminal.
- **Foundational Automation:** Practiced structuring Bash scripts with user prompts, conditional `case` logic, and exit codes to automate repetitive administrative tasks.
- **Network & DNS Troubleshooting:** Connected operating system configuration to network health by testing reachability (`ping`) and verifying DNS/mail server records (`host`, `dig`).
