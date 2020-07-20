# Description!
~~~
이 저장소는 맥 또는 맥북에서 특정 도구를 설정하는 방법에 대해 경험한 것들을 메모함
여기서 말하는 특정 도구는 다음과 같은 것에 해당
1. 데비안 패키지를 설치하는 경우
2. 모의 해킹 또는 그에 관련한 도구를 설치하는 방법
~~~


# MAC 에서 netdiscover 설치
~~~
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
~~~

# Mac 에서 exiftool 설치
~~~
brew install exiftool
~~~