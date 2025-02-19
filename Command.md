## Useful Commands
### System and User Management
- `/usr/bin/*session`
- `sudo chage -l ltuan-mi`
- `hostnamectl`
- `sudo hostnamectl set-hostname new_hostname`
- `sudo reboot`
- `uname -v`
- `getent group sudo`
- `getent group user42`
- `sudo adduser name_user`
- `sudo addgroup evaluating`
- `sudo adduser name_user evaluating`
- `getent group evaluating`

### Firewall (UFW)
- `sudo ufw status`
- `sudo ufw status numbered`
- `sudo ufw allow 8080`
- `sudo ufw delete 4`

### SSH (Secure Shell)
- `sudo service ssh status`
- `ssh new_user@127.0.0.1 -p 4242`

### Sudo Configuration
- `dpkg -l | grep sudo` (Check if sudo is installed)
- `nano /etc/sudoers.d/sudo_config`
- `cd /var/log/sudo`
- `cat sudo_config`
- `sudo nano abc`
- `sudo sudo_config`

### Disk Management
- `lsblk`

### Cron Jobs
- `sudo crontab -u root -e`
- `sudo /etc/init.d/cron stop`
- `sudo /etc/init.d/cron start`
- `sudo service cron status`
- `sudo systemctl disable cron`
- `sudo systemctl enable cron`
- `sudo systemctl start cron`
