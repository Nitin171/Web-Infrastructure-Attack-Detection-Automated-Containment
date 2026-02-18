# Remediation Steps – Web Server Hardening

## 1. Removed Malicious Web Shell
Deleted uploaded malicious file from web directory:
sudo rm -f /var/www/html/uploads/shell.php

## 2. Restricted Upload Directory Permissions
Updated directory permissions to prevent execution:
sudo chmod -R 755 /var/www/html/uploads

## 3. Secured Apache Configuration
Created upload directory configuration and enabled it:
sudo nano /etc/apache2/conf-available/uploads.conf
sudo a2enconf uploads
sudo systemctl reload apache2

## 4. Applied System Updates
Installed latest security patches:
sudo apt update && sudo apt upgrade -y

## 5. Automated Future Protection
Configured Azure Logic App playbook to automatically block attacker IPs using NSG rules.

## Result
Attack access was blocked and vulnerability removed, preventing future exploitation.

