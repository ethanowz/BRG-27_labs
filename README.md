# BRG-27 Labs

**Student:** Ethan Ow
**Student ID:** CT0386857

---

## BRG-ISEA Lab Activities

---

## Session 1a: Setting Up Linux

### GitHub Setup

* Create a GitHub account and start documenting progress.

  * Go to https://github.com and sign up for a new account.
  * Create a new repository (e.g., `BRG-27-labs`).
  * Clone the repository to your local machine using Git.
  * Add a `README.md` and start documenting each lab you complete.
<img width="953" height="736" alt="image" src="https://github.com/user-attachments/assets/0d74716f-732b-4e9e-ac12-1856199cba59" />

---

### Lab: Obtaining Linux on your PC

**Install Ubuntu using VirtualBox**

* Download Ubuntu ISO from the official website.
* Install VirtualBox and create a new virtual machine.
* Configure VM settings (e.g., 4GB RAM, 20GB disk).
* Mount ISO and install Ubuntu through guided installer.

---

### Lab: Familiarity with Ubuntu Linux

**Basic command line navigation and utilities**

* Practice using:

  * `pwd`
  * `ls`
  * `cd`
  * `mkdir`
  * `touch`
* Understand directory structure:

  * `/etc`
  * `/var`
  * `/home`
* Use `man` to explore Linux manual pages.

---

## Session 1b: Exploring Linux

### Lab: Linux Services

**Understanding and managing background services**

* List services:

  ```bash
  systemctl list-units --type=service
  ```
* Start/stop services:

  ```bash
  sudo systemctl start [service]
  sudo systemctl stop [service]
  ```
* Check service status:

  ```bash
  sudo systemctl status [service]
  ```

---

### Lab: Linux Permissions

* View permissions:

  ```bash
  ls -l
  ```
* Change permissions:

  ```bash
  chmod 755 file.sh
  ```
* Change ownership:

  ```bash
  chown user:group file.txt
  ```

---

### Lab: Searching Filesystems

* Find files:

  ```bash
  find /path -name 'filename'
  ```
* Search content:

  ```bash
  grep -r 'search-term' /path/
  ```

---

## Session 2a: Total Cost of Ownership

### Lab: Total Cost of Ownership (TCO)

* Compare cloud vs on-prem cost:

  * Hardware
  * Software
  * Licensing
* Use Excel or Google Sheets:

  * Monthly and yearly costs
  * Break-even point
  * ROI
  * 3-year projections
* Compare TCO across cloud providers.

---

## Session 2b: Cloud Services

### Lab: Cloud Computing

* Create free tier account (AWS or Azure).
* Launch Ubuntu instance (`t2.micro` or `B1s`).
* Configure:

  * SSH keypair
  * Security groups / firewall
* SSH into VM and update OS packages.

---

### Lab: Bash Scripting

* Create `.sh` file:

  ```bash
  #!/bin/bash
  ```
* Use:

  * `echo`
  * `if`
  * `for`
  * `while`
  * `cron`
* Run scripts:

  ```bash
  bash script.sh
  chmod +x script.sh
  ```

---

## Session 3a: DNS & Certificates

### Lab: DNS

* Register a domain (or use Freenom).
* Configure A record → server public IP.
* Verify DNS:

  ```bash
  dig yourdomain
  nslookup yourdomain
  ```

---

### Lab: Digital Certificates

* Install Certbot:

  ```bash
  sudo apt install certbot python3-certbot-nginx
  ```
* Run:

  ```bash
  sudo certbot --nginx
  ```
* Verify:

  * Open `https://yourdomain` in browser.

---

## Session 3b: Server Automation

### Lab: Scripting Linux Server Functions

* Automate update/backup tasks.
* Schedule using cron:

  ```bash
  crontab -e
  ```
* Log output:

  ```bash
  >> /var/log/task.log
  ```

---

## Session 4a: Lab Consultation & Additional Server Services

* Participated in Q&A session with teaching staff.
* Listed issues encountered.
* Tested all configurations before final presentation.

### Cloud First and Server Architecture Design

* Considerations & approaches discussed.

---

### Additional Service Installation

* Installed, configured, and tested an additional service:

  * Options: MySQL, Jenkins, Samba, FTP, Docker, etc.
* Steps:

  * Download source
  * Install using `apt` or `curl`
  * Configure service
  * Test functionality
  * Document steps in GitHub

---

## Session 4b: Lab Documentation & Reflection Journal

### Documentation & Peer Feedback

* Prepared GitHub README with clear documentation.
* Included screenshots of servers and commands.
* Explained what was done and what was learnt.
* Listed unresolved issues and doubts.
* Received final feedback and clarifications.
* Practised articulating technical concepts as a consultant would.

---

### Reflection

* Key improvements made
* Obstacles faced and how they were resolved
* Tools used
* Insights gained
* Lessons learned
* Related experience to future IT roles:

  * System Administrator
  * DevOps Engineer
