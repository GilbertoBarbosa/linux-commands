# linux-commands
Linux commands

Install program
```
dpkg -i package_file.deb
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
