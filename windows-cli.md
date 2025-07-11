# 🪟 Windows CMD Commands 
| Command                 | Description                             | Example                            |
| ----------------------- | --------------------------------------- | ---------------------------------- |
| `whoami`                | Show current user                       | `whoami`                           |
| `hostname`              | Display machine name                    | `hostname`                         |
| `ipconfig`              | Show network interfaces and IPs         | `ipconfig /all`                    |
| `net user`              | List local users                        | `net user`                         |
| `net user [username]`   | View info about a specific user         | `net user Administrator`           |
| `net localgroup`        | Show local groups                       | `net localgroup`                   |
| `net localgroup admins` | Show group members                      | `net localgroup administrators`    |
| `systeminfo`            | OS version, architecture, patch info    | `systeminfo`                       |
| `tasklist`              | List running processes                  | `tasklist`                         |
| `taskkill /PID`         | Kill a process by ID                    | `taskkill /PID 1234 /F`            |
| `dir`                   | List files in directory                 | `dir /a`                           |
| `cd`                    | Change directory                        | `cd C:\Users`                      |
| `copy` / `move`         | Copy/move files                         | `copy a.txt D:\`                   |
| `del` / `rmdir`         | Delete files or directories             | `del file.txt` / `rmdir folder /s` |
| `type`                  | Show file contents                      | `type notes.txt`                   |
| `attrib`                | View/change file attributes             | `attrib -h -s secret.txt`          |
| `findstr`               | Search for strings in files (like grep) | `findstr "admin" users.txt`        |
| `cls`                   | Clear the terminal                      | `cls`                              |
