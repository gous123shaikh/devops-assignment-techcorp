# 🚀 DevOps Assignment - TechCorp

![Linux](https://img.shields.io/badge/Linux-Ubuntu-orange?logo=linux)
![Shell](https://img.shields.io/badge/Shell-Scripting-green)
![DevOps](https://img.shields.io/badge/DevOps-Learning-blue)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📌 Project Overview

This project demonstrates core **DevOps practices** including system monitoring, user management, and automated backup solutions using Linux.

---

## ⚙️ Technologies Used

* 🐧 Linux (Ubuntu - WSL)
* 💻 Shell Scripting
* ⏰ Cron Jobs
* 📊 System Monitoring Tools (htop, nmon)
* 📁 GitHub (Version Control)

---

## 📊 Task 1: System Monitoring

* Installed `htop` and `nmon`
* Monitored CPU, memory, and disk usage
* Identified high resource processes
* Logged system metrics

---

## 👤 Task 2: User Management

* Created users: **Sarah & Mike**
* Created isolated workspaces
* Applied secure permissions (`700`)
* Implemented password expiry policy (30 days)

---

## 💾 Task 3: Backup Automation

* Created backup scripts for:

  * Apache
  * Nginx
* Automated using cron jobs (Tuesday 12 AM)
* Stored backups in `/backups`
* Verified backup integrity using `tar`

---

## 📂 Project Structure

```
scripts/
logs/
screenshots/
report/
```

---

## ⏰ Cron Jobs

```
0 0 * * 2 /home/shaikh/apache_backup.sh
0 0 * * 2 /home/shaikh/nginx_backup.sh
```

---

## 📸 Screenshots

All execution screenshots are available in the **screenshots/** folder.

---

## 🔗 GitHub Repository

https://github.com/gous123shaikh/devops-assignment-techcorp

---

## 👨‍💻 Author

DevOps Fresher | Learning & Building Real-World Projects 🚀
