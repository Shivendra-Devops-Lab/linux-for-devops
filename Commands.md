# Linux Commands for DevOps 🚀

## Navigation Commands
pwd
ls
ls -la
cd
cd ..
clear
history

## File & Directory Management
mkdir project
mkdir -p devops/linux
rmdir foldername
touch file.txt
cp file.txt backup.txt
cp -r folder1 folder2
mv old.txt new.txt
mv file.txt /home/user/
rm file.txt
rm -r foldername

## File Viewing
cat file.txt
less file.txt
more file.txt
head file.txt
tail file.txt
tail -f logfile.log
nl file.txt

## Search Commands
find / -name file.txt
find . -type f
locate nginx
which python3
whereis ssh

## Users & Groups
whoami
id
who
users
adduser devops
passwd username
usermod -aG sudo username
deluser username
groupadd developers
groups username

## Permissions
ls -l
chmod 755 script.sh
chmod +x script.sh
chown user:user file.txt
chgrp developers file.txt
umask

## Process Management
ps
ps aux
top
htop
pgrep nginx
kill PID
kill -9 PID
pkill nginx
nice -n 10 process
uptime

## Services
systemctl status nginx
systemctl start nginx
systemctl stop nginx
systemctl restart nginx
systemctl enable nginx
systemctl disable nginx

## Package Management (Ubuntu/Debian)
apt update
apt upgrade
apt install nginx
apt remove nginx
apt autoremove

## Package Management (RHEL/CentOS)
yum install httpd
yum update
dnf install docker

## Disk & Storage
df -h
du -sh *
du -sh foldername
lsblk
blkid
mount
fdisk -l

## Memory & CPU
free -m
lscpu
vmstat
iostat

## Logs
journalctl
journalctl -xe
journalctl -u nginx
dmesg
last
last reboot

## Archives
tar -cvf backup.tar folder/
tar -xvf backup.tar
tar -czvf backup.tar.gz folder/
unzip file.zip
zip -r files.zip folder/

## SSH Basics
ssh user@server-ip
scp file.txt user@server:/home/user/
ssh-keygen

## Networking Basics
ping google.com
ip a
ip route
ss -tulnp
netstat -tulnp

## Useful DevOps Commands
hostname
hostnamectl
date
timedatectl
env
export NAME=value
echo $PATH
alias ll='ls -la'
