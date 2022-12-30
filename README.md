# linux-commands
Linux commands

Connecting root user
```
su <password>
su - <otherUser>
```

update system ubuntu / 
```
sudo apt-get update -y
sudo yum update -y
```

Machine name
```
hostname
```

Current directory
```
pwd
```

Copy / move files
```
cp <file> <destination>
mv <file> <destination>
```

Delete file / directory
```
rm <file>
rmdir <directory> # empty directory
```

Remove recursively all files current directory
```
rm -rf * 
```

List process
```
ps aux
```

List files and directories hidden
```
ls -la
```

Ip configuration
```
# net-tools package
ifconfig
```

nmap
```
sudo nmap -sn <ip>
```

List files and directories tree
```
tree -L 1 # 1 = level
```

Change permissions
n = 7 (full access)
n = 4 (r)
n = 2 (w)
n = 1 (x)
n = 0 (-)
```
chmod nnn <file>
```

Change file owner
```
chown <user>:<user> <file>
```

Download
```
wget <link>
```

Install program
```
dpkg -i package_file.deb
bash <file.sh>
```

Zip files
```
zip <file.zip> *
```

Unzip file tar.gz
```
tar -xzf file.tar.gz
```

Unzip file .zip
```
unzip file.zip -d destination directory
```

See file content
```
cat <file>
```

Save content file in another file
```
cat <file> > <otherFile>
```

Run program file
```
./<file program>
```

Create user
```
adduser <userName>
```

Create group
```
addgroup <groupName>
```

Change primary user group
```
usermod -g <newGroupName> <userName>
```

Change secondary user group
```
usermod -a -G <newGroupName> <userName>
```

User access
```
id
```

Create file
```
touch <fileName>
```

File validate
```
source <file>
```

Compile C with gcc
```
gcc <file.c> -o <file.out>
```

Compile C++ with g++
```
g++ <file.c> -o <file.out>
```

Execute program
```
./file.out
```

Generate SSH Key
```
ssh-keygen -t rsa
```

Access an instance with SSH
```
ssh -i <key.pem> <instance>
```

Secure copy SSH
```
scp -i <key.pem> <origin> <destination>
```

Restart Linux service
```
sudo systemctl restart <service>
```

Create and save content in file
```
echo "conntent" > <file>
```

Free up disk space
```
sudo apt-get autoremove
sudo apt-get autoclean
sudo apt-get clean
```

Disk space
```
df -h
```

Disk usage
```
du -h
```

Archive system 
```
df -Th
```

Install CLI heroku
```
sudo curl https://cli-assets.heroku.com/install.sh | sh
```

Restart system
```
sudo reboot
```

Schedule
```
crontab -e
crontab -l
```

Stress-ng
```
sudo apt-get install stress-ng
# stress-ng -c 1 -l 90 -t 5m (example)
```

Show url ip
```
dig <site>
```

Environment Variables
```
# List
env
printenv

# Print all variables and functions
set

# Delete environment variables
unset <variable>

# Create environment variable
export <KEY>=<value>

# Access environment variable directory
cd $<VARIABLE_NAME>
```

Enviroment variables
```
gedit .bashrc
```

Loop for
```
for i in {1..n};
do <action>;
done;
```

Stop/Disable firewall
```
systemctl stop firewalld
systemctl disable firewalld
```

