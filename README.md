# linux-commands
Linux commands

Machine name
```
hostname
```

Current directory
```
pwd
```

List process
```
ps aux
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

User access
```
id
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

