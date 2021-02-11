# Description!
- 맥 또는 맥북에서 도구를 설정 또는 설치하는 정보를 다룸
---
#### 다운로드 받은 파일을 전역적으로 사용하는 방법
  - ln - s {실행할 파일 경로} {실행 될 이름}

---
#### Netdiscover 설치
```
# MAC 에서 netdiscover 설치
[+] libnet-dev : http://www.noktec.be/pentesting-with-os-x/netdiscover
1. cd libnet
2. sudo ./configure
3. sudo make
4. sudo make install

# netdiscover : https://github.com/alexxy/netdiscover
1. chmod +x update-oui-database.sh
2. cmake .
3. make
4. make install 
```

---
#### How to install exiftool
```
1. brew install exiftool
```

---
#### How to install wpscan
```
1. brew install wpscan 
```

---
#### How to install smbmap
```
1. https://github.com/ShawnDEvans/smbmap
```

---
#### How to install debugfs
```
1. brew install e2fsprogs
2. find / -name "debugfs" 2>/dev/null
-/opt/homebrew/Cellar/e2fsprogs/1.46.0/sbin
3. append System-Enviorment
```

---
#### How to install binwalk
```
1. Passvie Install : https://github.com/ReFirmLabs/binwalk/blob/master/INSTALL.md
```


### How to install mysql using with docker on M1 Mac
```
1. docker pull 
docker pull mysql:5.7 --platform linux/x86_64
```
