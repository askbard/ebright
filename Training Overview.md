# Ebright Linux Crash Course: Training Overview

This document defines the two core pillars of the 1-day Linux Server Maintenance course, designed to equip the Ebright IT and Administration team with the practical skills required for independent cloud server management.

## Pillar 1: System Identity, Access & Administration

**Focus:** Establishing Infrastructure Foundations and Organizational Hierarchy.

The Pillar 1 session is designed to break the reliance on graphical interfaces and establish a professional "Server Mindset" through the Command Line Interface (CLI). The team will explore the Linux ecosystem-from the Kernel to the Cloud-learning to manage Virtual Private Servers (VPS) and secure them via SSH. The goal is to ensure the team can confidently navigate the filesystem, monitor system vitals, and implement a robust departmental user/group structure that secures Ebright's internal data.

### Included Modules

#### Module 1: Introduction, Fundamentals & Remote Access

The Linux Ecosystem: Transitioning to "Headless" operation, the power of the CLI over GUI, and the long-term stability of Ubuntu Server LTS.

Cloud Computing & VPS: Moving from managed hosting to IaaS, understanding the Shared Responsibility Model, and leveraging Root Access on isolated virtual servers.

System Fundamentals: Exploring the architecture of the Linux Kernel, the Bash Shell interpreter, and the hierarchy of operation between the user and hardware.

The Sandbox: Comparing Docker Containers vs. Virtual Machines (VM) for high-performance, non-destructive practice.

Remote Access Theory: Securing connections via SSH using Asymmetric Encryption (Keys) and the technical handshake process.

The Server Mindset: Essential operational rules-Case Sensitivity, Sudo (administrative) usage, and the "no feedback is success" principle.

#### Module 2: Mastering the Filesystem, Users & Permissions

The Filesystem Hierarchy (FHS): Understanding the Linux tree structure and the specific roles of core system and data directories.

Help, Documentation & Information: Mastering self-documentation tools and system/identity identification (`uname`, `hostname`, `whoami`).

Filesystem Operations: Mastering navigation, file/directory creation, and advanced manipulation (copying, moving, and safe deletion).

Content Exploration & Text Editing: Viewing file data, utilizing terminal-based text editors (`nano`/`vi`), and managing archiving/compression.

Security Logic (Users & Permissions): Provisioning accounts, managing departmental groups, octal permission logic, and granting `sudo` privileges.

Terminal Productivity & Task Scheduling: Using command history, efficiency shortcuts, I/O redirection/piping, and automation via `crontab`.

Storage, Time & Software Management: Monitoring disk health, managing system time/timezones, and installing software via `apt`.

Process & Network Operations: Real-time process monitoring, connectivity troubleshooting, remote transfers, and safe power operations (`reboot`/`shutdown`).

## Pillar 2: Deployment, Security & Continuity

**Focus:** Application Delivery, Monitoring, and System Stability.

The 2d session transitions from system-level administration to application-level management. We focus on the procedures required to deploy website updates, monitor system health, and implement security hardening to ensure the continuity of Ebright's parent portal and student databases.

### Included Modules

#### Module 3: Deployment, Security & Continuity

System Snapshots: Performing server-wide snapshots as a primary restore point before configuration changes.

System Diagnostics: Monitoring system vital signs using `df -h` (Disk), `free -m` (Memory), and `top` (Processes).

Log Management: Troubleshooting application errors via real-time log analysis using `tail -f`.

Software Stack: Managing application packages; installing Nginx and PostgreSQL via the `apt` package manager.

Version Control: Utilizing Git for deployment; cloning repositories and updating production code with `git pull`.

Network Identity: Managing DNS records (A, CNAME, MX) to facilitate proper domain routing.

Perimeter Hardening: Configuring the UFW Firewall to restrict network access to essential web traffic.

Data Protection: Establishing automated backup protocols and distinguishing between snapshots and off-site storage.

Operational Readiness: Implementing emergency recovery procedures, system power operations (`reboot`, `shutdown`), and internal escalation workflows.

## Learning Outcome

By the end of the day, the Ebright IT team will have moved from being passive observers of a managed host to active administrators of their own cloud infrastructure. They will possess the technical "Survival Skills" needed to keep Ebright's digital services stable, secure, and accessible.
