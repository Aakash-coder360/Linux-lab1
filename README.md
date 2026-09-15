# Linux-lab1

Vagrant multi-VM lab setup using VirtualBox provider.

## VMs Created
- **Ubuntu** (bento/ubuntu-22.04)
- **Rocky Linux** (bento/rockylinux-9)
- **AlmaLinux** (bento/almalinux-9)

## Files
- `Vagrantfile` – Vagrant configuration defining the three VMs (ubuntu, rocky, alma)
- `lab1.txt` – Full PowerShell command and output log for the lab session

## Commands Used
- mkdir Infraguardian
- cd Infraguardian
- vagrant --version
- vagrant init
- notepad Vagrantfile
- vagrant validate
- vagrant up
- vagrant ssh ubuntu
- vagrant ssh rocky
- vagrant ssh alma
- vagrant halt
-vagrant status
