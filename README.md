# Description!
~~~
이 저장소는 맥 또는 맥북에서 도구를 설정 또는 설치하는 방법에 대해 메모
1. 데비안 패키지를 설치하는 경우
2. 침투 테스팅 또는 그에 관련한 도구를 설치하는 방법
~~~

# 다운로드 받은 파일 환경변수 실행방법
```
1. /usr/local/bin 밑에 심볼릭 링크 생성
2. /usr/local/bin 경로로 이동한 뒤 지정
3. ln - s {실행할 파일 경로} {실행 될 이름}

```

# Mac Tool INSTALL NOTE
```
# MAC 에서 netdiscover 설치
[+] libnet-dev : http://www.noktec.be/pentesting-with-os-x/netdiscover
1. cd libnet
2. sudo ./configure
3. sudo make
4. sudo make install

[+] netdiscover : https://github.com/alexxy/netdiscover
1. chmod +x update-oui-database.sh
2. cmake .
3. make
4. make install 
```
# How to install exiftool
```
1. brew install exiftool
```
# How to install wpscan
```
1. brew install wpscan 
```

# How to install smbmap
```
1. https://github.com/ShawnDEvans/smbmap
```