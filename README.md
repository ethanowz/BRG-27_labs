# BRG-27_labs

Student: Ethan Ow

Student ID: CT0386857

BRG-ISEA Lab Activities
Session 1a: Setting Up Linux
• Create a GitHub account and start documenting progress.
• → Go to https://github.com and sign up for a new account.
• → Create a new repository (e.g., BRG-27-labs).
• → Clone the repository to your local machine using Git.
• → Add a README.md and start documenting each lab you complete.


• Lab: Obtaining Linux on your PC – Install Ubuntu using VirtualBox.
• → Download Ubuntu ISO from the official website.
• → Install VirtualBox and create a new virtual machine.
• → Configure VM settings (e.g., 4GB RAM, 20GB disk).
• → Mount ISO and install Ubuntu through guided installer.


• Lab: Familiarity with Ubuntu Linux – Basic command line navigation and utilities.
• → Practice using `pwd`, `ls`, `cd`, `mkdir`, and `touch`.
• → Understand directory structure (`/etc`, `/var`, `/home`).
• → Use `man` to explore Linux manual pages.


Session 1b: Exploring Linux
• Lab: Linux Services – Understanding and managing background services.
• → List services using `systemctl list-units --type=service`.
• → Start/stop services with `sudo systemctl start|stop [service]`.
• → Check status of services using `sudo systemctl status`.


• Lab: Linux Permissions – Explore and apply file and directory permissions.
• → Use `ls -l` to view permissions.
• → Change permissions using `chmod` (e.g., `chmod 755 file.sh`).
• → Change ownership using `chown user:group file.txt`.


• Lab: Searching Filesystems – Use commands like `find` and `grep`.
• → Use `find /path -name 'filename'` to locate files.
• → Use `grep -r 'search-term' /path/` to search content.


Session 2a: Total Cost of Ownership
• Lab: Total Cost of Ownership – Apply TCO concepts in practical comparison.
• → Compare cloud vs on-prem cost (hardware, software, licensing).
• → Use Excel or Google Sheets to document monthly and yearly costs.
• → Calculate break-even point, ROI and 3-year projections.
• → Compare TCO across cloud providers


Session 2b: Cloud Services
• Lab: Cloud Computing – Launch and configure EC2 instance or Azure VM.
• → Create free tier account on AWS or Azure.
• → Launch Ubuntu instance (t2.micro or B1s).
• → Configure SSH keypair, security groups/firewall.
• → SSH into VM and update OS packages.


• Lab: Bash Scripting – Write simple shell scripts for server automation.
• → Create a `.sh` file and add `#!/bin/bash` at top.
• → Use `echo`, `if`, `for`, `while`, `cron` examples.
• → Run scripts using `bash script.sh` or `chmod +x script.sh`.


Session 3a: DNS & Certificates
• Lab: DNS – Configure and test DNS using BIND or cloud provider.
• → Register a domain (or use free domain service like Freenom).
• → Configure A record to point to server public IP.
• → Use `dig` or `nslookup` to verify DNS propagation.
• Lab: Digital Certificates – Use Let's Encrypt to secure a server.
• → Install Certbot: `sudo apt install certbot python3-certbot-nginx`.
• → Run `sudo certbot --nginx` or `--apache`.
• → Verify certificate using `https://yourdomain` in browser.


Session 3b: Server Automation
• Lab: Scripting Linux Server Functions – Automate server tasks using scripts.
• → Write script to automate update/backup tasks.
• → Use cron jobs: `crontab -e` to schedule the script.
• → Log output to a file using `>> /var/log/task.log`.


Sessin 4a: Lab Consultation & Additional Server Services
• Participated in Q&A session with teaching staff
• → List issues you've encountered and bring them up.
• → Test all configurations before final presentation.
• → Cloud First and Server Architecture Design – Considerations & Approaches
• Experiment with another server service of interest (in discussion with lecturer)


Installed, configured and tested an additional service of your choice.
• → Choose from: MySQL, Jenkins, Samba, FTP, Docker, etc.
• → Download source for server service to be installed
• → Install service eg. using apt or curl.
• → Configure and test the basic functionality.
• → Documented service configuration and testing steps in GitHub


Session 4b: Lab documentation & Reflection Journal
• Lab activity documentation and peer feedback.
• → Prepare GitHub README with clear documentation.
• → Create screenshots of your servers and commands.
• → Be ready to explain what you did and what you learnt.
• → Prepared a list of unresolved issues or conceptual doubts
• → Received final feedback and clarifications on your server deployment
• → Practised articulating technical concepts as a consultant would
• Reflection on lab consultancy, peer demonstrations and self-assessment
• → Noted key improvements, obstacles faced, and how they were resolved
• → Tools you used, Insights gained, lessons learned
• → Related experience to future IT roles (System Admin, DevOps, etc.)

