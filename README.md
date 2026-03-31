# open-source-audit-python
Open Source Audit Project on Python for OSS course
# Python: Open Source Audit Project

This repository contains five shell scripts and a project report for the **Open Source Audit** course project based on the open-source software **Python**.

## Developer Information

* **Student Name:** Tarang Gupta
* **Registration Number:** 24BSA10352
* **Chosen Software:** Python

## Project Structure

```
open-source-audit-python/
│
├── README.md
├── scripts/
│   ├── sys_identity.sh
│   ├── package_inspector.sh
│   ├── disk_audit.sh
│   ├── log_audit.sh
│   ├── manifesto.sh
```

## Project Shell Scripts

All scripts are located inside the `scripts/` directory and are designed to run on a standard Linux environment.

1. **sys_identity.sh**
   Displays system information such as kernel version, OS distribution, logged-in user, uptime, and current date/time.

2. **package_inspector.sh**
   Checks whether Python (`python3`) is installed using system package managers and displays package details.

3. **disk_audit.sh**
   Audits important system directories to show their size, permissions, and ownership details.

4. **log_audit.sh**
   Analyzes a given log file to count keyword occurrences (default: "error") and displays recent matching entries.

5. **manifesto.sh**
   Generates a personalized open-source manifesto based on user input and saves it to a text file.

## Instructions to Run

1. Clone the repository or open the project folder in a Linux terminal.

2. Grant execution permissions to all scripts:

```bash
chmod +x scripts/*.sh
```

3. Run any script using:

```bash
./scripts/script_name.sh
```

### Example:

```bash
./scripts/sys_identity.sh
```

### Log Script Example:

```bash
./scripts/log_audit.sh /var/log/syslog error
```

## Dependencies

* Bash shell (`/bin/bash`)
* Common Linux utilities: `awk`, `grep`, `tail`, `du`, `dpkg` or `rpm`

No additional installations are required on most Linux distributions.

## Notes

* All scripts are command-line executable.
* The project follows open-source principles and standard Linux practices.
* Ensure scripts are executed in a Linux environment for correct output.

  
## Personal Reflection
This project helped me understand how open-source software like Python works in real-world environments. I learned how to interact with Linux systems using shell scripting and gained practical knowledge about system auditing and automation.
