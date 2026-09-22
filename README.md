# Linux-lab1

Vagrant multi-VM lab setup using VirtualBox provider.

## VMs Created
- **Ubuntu** (bento/ubuntu-22.04)
- **Rocky Linux** (bento/rockylinux-9)
- **AlmaLinux** (bento/almalinux-9)

## Files
- `Vagrantfile` – Vagrant configuration defining the three VMs (ubuntu, rocky, alma)
- `lab1.txt` – Full PowerShell command and output log for the lab session

## Commands Used For Lab1
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
- vagrant status
- vagrant ssh ubuntu
     - vi lab2.sh
     - sh lab2.sh
     - vi s2.sh
     - sh s2.sh
     - exit

## Commands Used For Lab3
- vagrant ssh ubuntu
- sudo apt update
- sudo apt install rsync -y
- rsync --version
- mkdir -p ~/backup_lab/source
- echo "Student Information" > ~/backup_lab/source/student.txt
- echo "Linux Lab Report" > ~/backup_lab/source/report.txt
- echo "Sample Data" > ~/backup_lab/source/data.txt
- ls -l ~/backup_lab/source
- vi backup.sh
- ls
- cd ..
- bash backup.sh
- ls
- cd backup_lab
- ls
- cd backups
- ls
- cd daily
- ls
- cd ..
- cd ..
- cd source
- ls
- cat data.txt
- cat report.txt
- cat student.txt
