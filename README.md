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

---

### Lab: Obtaining Linux on your PC

**Install Ubuntu using VirtualBox**

* Download Ubuntu ISO from the official website.
* Install VirtualBox and create a new virtual machine.
* Configure VM settings (e.g., 4GB RAM, 20GB disk).
* Mount ISO and install Ubuntu through guided installer.
<img width="953" height="736" alt="image" src="https://github.com/user-attachments/assets/0d74716f-732b-4e9e-ac12-1856199cba59" />
<img width="1282" height="800" alt="image" src="https://github.com/user-attachments/assets/0b3513a2-e0fb-4b75-9c2f-08680800f255" />

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
<img width="1280" height="800" alt="pic 1 real" src="https://github.com/user-attachments/assets/c17f71f6-b0fe-4d70-91ef-79889cf8dc09" />
<img width="1280" height="800" alt="pic 2" src="https://github.com/user-attachments/assets/d3c16bdc-367e-4246-b978-7979ab344a4e" />
<img width="1280" height="800" alt="pic 3" src="https://github.com/user-attachments/assets/83b90629-f065-4bb9-af3d-2d4fd1548f09" />

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
<img width="1280" height="800" alt="pic 4" src="https://github.com/user-attachments/assets/2a2a5b79-cde7-4cd2-85b9-25019a7eec60" />
<img width="1280" height="800" alt="pic 5" src="https://github.com/user-attachments/assets/f33fe6ec-ac9a-4b5e-a49b-facc2d27c40a" />

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
<img width="1280" height="800" alt="pic 6" src="https://github.com/user-attachments/assets/70bee44d-3b45-4d67-8bdb-d76bd73aa7bc" />

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
<img width="1280" height="800" alt="pic7" src="https://github.com/user-attachments/assets/d33a3961-3e2c-46ba-88bc-405cff997608" />

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
<img width="758" height="463" alt="image" src="https://github.com/user-attachments/assets/d1f9779f-b548-449d-adb5-001777248bfb" />

---

## Session 2b: Cloud Services

### Lab: Cloud Computing

* Create free tier account (AWS or Azure).
* Launch Ubuntu instance (`t2.micro` or `B1s`).
* Configure:

  * SSH keypair
  * Security groups / firewall
* SSH into VM and update OS packages.
<img width="1280" height="800" alt="pic 10" src="https://github.com/user-attachments/assets/b21ac93d-de84-4295-a05e-35a5b1060ad0" />
<img width="1280" height="800" alt="pic 9" src="https://github.com/user-attachments/assets/99fb9cb1-cd69-49bf-9ad7-057709b95582" />
<img width="1280" height="800" alt="pic 11" src="https://github.com/user-attachments/assets/9551574a-3a40-453f-86bd-bbc3383ef5aa" />

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
<img width="1280" height="800" alt="pic 8" src="https://github.com/user-attachments/assets/209ce911-fabf-4a82-9c10-bb15de96e758" />

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
<img width="847" height="546" alt="image" src="https://github.com/user-attachments/assets/5efdeca4-92df-4e38-8c80-ed5829cdf1d9" />
<img width="1280" height="800" alt="pic 14" src="https://github.com/user-attachments/assets/290611f7-d182-48b2-b905-1f53a5da484c" />
<img width="1280" height="800" alt="pic 13" src="https://github.com/user-attachments/assets/59f57eae-3a45-44c5-83a7-42581861ba2c" />

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
<img width="1280" height="800" alt="pic 15" src="https://github.com/user-attachments/assets/9df786b2-cd2b-4634-af20-d30227baf4da" />
<img width="1280" height="800" alt="pic 16" src="https://github.com/user-attachments/assets/c16ce053-1a72-413b-9f47-1df95827a57c" />

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
<img width="1280" height="800" alt="pic 17" src="https://github.com/user-attachments/assets/0b61334b-e2e7-4965-b075-ba4f4f128795" />
<img width="1280" height="800" alt="pic 18" src="https://github.com/user-attachments/assets/9da84ae8-a86a-4661-aef3-d3aa051b7b69" />
<img width="1280" height="800" alt="pic 19" src="https://github.com/user-attachments/assets/097f3582-abdb-44fb-92bd-628c41c17e37" />

---

## Session 4a: Lab Consultation & Additional Server Services

* Participated in Q&A session with teaching staff.
* Listed issues encountered.
* Tested all configurations before final presentation.

---

### Additional Service Installation

* Installed, configured, and tested an additional service:
* Steps:

  * Download source
  * Install using `apt` or `curl`
  * Configure service
  * Test functionality
  * Document steps in GitHub
<img width="1280" height="800" alt="pic 20" src="https://github.com/user-attachments/assets/1ce3cf10-9f6f-43c7-97ca-4c1b484ebe18" />
<img width="1280" height="800" alt="pic 21" src="https://github.com/user-attachments/assets/abb12cac-b960-4a0f-b3e8-d90a8efa9765" />
<img width="1280" height="800" alt="pic 22" src="https://github.com/user-attachments/assets/269f5d8e-55c0-4eae-ae6e-d7e92421136c" />
<img width="1280" height="800" alt="pic 23" src="https://github.com/user-attachments/assets/9a85c1cc-cecc-4170-9f30-53df89f32e64" />
<img width="1280" height="800" alt="pic 24" src="https://github.com/user-attachments/assets/e3aaa300-3a39-49c9-9836-162d73bd2edf" />
<img width="1280" height="800" alt="pic 25" src="https://github.com/user-attachments/assets/f771a97e-765f-42da-898a-f0377b045627" />

---

### Reflection

* Overall, this project provided a comprehensive and practical introduction to server environments, significantly enhancing both my technical skills and problem solving abilities. At the beginning of the lab sessions, I had limited experience with Linux systems and cloud infrastructure. However, through hands on practice, I developed confidence in navigating command line environments, managing system configurations and troubleshooting technical issues independently. 
