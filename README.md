# Menu-Based-System-Health-Check-Script

# Menu-Based System Health Check Script

This bash script provides a menu-driven interface for checking the health of a Linux system.  It allows users to select various checks and receive a comprehensive report via email.

## Features

* **Menu-driven interface:** Easy navigation and selection of health checks.
* **Disk usage check:** Displays disk space usage with `df -h`.
* **Running services monitor:** Lists currently running services using `systemctl`.
* **Memory usage assessment:** Shows memory usage statistics with `free -h`.
* **CPU usage evaluation:** Provides a snapshot of CPU usage with `top`.
* **Email reporting:** Sends a comprehensive report of all checks to a specified email address.  The report is formatted for readability.

## Requirements

* A Linux system (tested on Debian/Ubuntu).
* `mailutils` package installed (`sudo apt-get install mailutils` or equivalent for your distribution).
* A properly configured mail transfer agent (MTA) to send emails.  This usually involves setting up an SMTP server and configuring authentication.  Test your email configuration before using the script.

## Installation

1.  **Save the script:** Copy the script below and save it to a file (e.g., `system_health_check.sh`).
2.  **Make it executable:** `chmod +x system_health_check.sh`
3.  **Configure:** Edit the script and replace `"your_email@example.com"` with your email address.

## Usage

1.  Run the script: `./system_health_check.sh`
2.  Select options from the menu to perform health checks.
3.  Option 5 ("Send Comprehensive Report via Email") will send a report to the specified email address.

## Script

```bash
#!/bin/bash

# ... (Paste the improved script from the previous response here) ...
