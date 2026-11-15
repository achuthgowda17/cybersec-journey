Week 02 – Linux Fundamentals
A record of my Week 2 cybersecurity learning: Linux terminal fundamentals, filesystem navigation, file operations, users, permissions, and guided command-line practice.
Environment
Kali Linux running in Oracle VirtualBox
TryHackMe – Linux Fundamentals (Part 1)
OverTheWire – Bandit
Learning focus
Linux terminal basics and shell navigation
Listing files and directories, including hidden files
Creating, reading, copying, moving, and deleting files
Understanding user identity and groups
Linux permissions: owner, group, others; read, write, execute
Using command-line search and text utilities
Practice evidence
TryHackMe: The supplied screenshot records Linux Fundamentals (Part 1) at 100% completion.
OverTheWire Bandit: The supplied screenshot records work on the Level 12 → Level 13 challenge in Kali Linux.
Cheat sheet: A one-page Linux (Bash) command and permissions reference was created.
Key commands
Area	Commands
Navigation	`pwd`, `ls`, `ls -la`, `cd`
Files and folders	`mkdir`, `touch`, `cat`, `cp`, `mv`, `rm`
Search and text	`find`, `grep`, `sort`, `uniq`, `strings`, `file`
Users and shell	`whoami`, `su`, `sudo`, `clear`, `nano`
Permissions	`chmod`
Permission basics
`r` = read (4)
`w` = write (2)
`x` = execute (1)
Permissions apply to owner, group, and others.
Follow least privilege: grant only the permissions required.
Repository structure
```text
week-02-linux-fundamentals/
├── README.md
├── report/
│   └── Week_2_Linux_Fundamentals_Report.pdf
├── cheat-sheet/
│   └── Linux_Cheat_Sheet_One_Page_Darker.pdf
└── screenshots/
    ├── tryhackme-linux-fundamentals-pt1.png
    └── bandit-level-12-to-13.png
```
Learning reflection
Week 2 helped me build confidence using the Linux terminal inside my Kali Linux virtual machine. I practised navigating the filesystem, inspecting files, and learning how permissions work. Guided labs reinforced that understanding command output is just as important as memorising commands.
Learning resources
TryHackMe – Linux Fundamentals
OverTheWire – Bandit
Security note
Do not publish passwords, challenge credentials, tokens, private IP information, or other sensitive details. Review and redact screenshots before uploading them to a public repository.
