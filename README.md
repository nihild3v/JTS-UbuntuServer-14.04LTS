JTS_UbuntuServer_14.04LTS
=========================

JackTheStripper Deployer for Ubuntu Server 14.04LTS

JackTheStripper is an Open Source tool developed to help SysAdmin and developers secure there Linux Servers in which they will be deploying any web application. This tool automates the process of installing all the necessary packages to host a web application and Hardening a Linux server with little interaction from the user.

This tool is a Bash Script with a little python script that hardens the Linux Server security automatically and the steps followed are:

* Configures a Hostname
* Reconfigures the Timezone
* Updates the entire System
* Creates a New Admin user so you can manage your server safely without the need of doing remote connections with root.
* Generates Secure RSA Keys, so that remote access to your server is done exclusive from you local pc and no Conventional password
* Configures, Optimize and secures the SSH Server
* Configures IPTABLES Rules to protect the server from common attacks
* Protects the server against Brute Force attacks by installing a configuring fail2ban
* Stop Portscans by blocking intrusive IP via IPTABLES using portsentry
* Install, configure, and optimize MySQL
* Install the Apache Web Server
* Install, configure and secure PHP
* Secure Apache via configuration file and with installation of the Modules ModSecurity, ModEvasive, Qos and SpamHaus
* Installs RootKit Hunter
* Secures Root Home and Grub Configuration Files
* Installs Unhide to help Detect Malicious Hidden Processes
* Installs Tiger, A Security Auditing and Intrusion Prevention system
* Restrict Access to Apache Config Files
* Disable Compilers
* Creates Daily Cron job for System Updates
* Kernel Hardening via sysctl configuration File

To Run the tool

./dms.sh

As the Root user

# ChangeLog
==============================
v2.0 - Script more easy to Follow, More Hardening Steps
