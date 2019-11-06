# ubuntu
## 가상머신 설치
1. vm tool 설치 ( virtualbox, hyper-v ... )
2. ubuntu iso 파일 다운로드
3. vm linux 설치 - ssh 
4. vi /etc/ssh/sshd_config
- PermitRootLogin yes 로 수정
- service sshd start or service ssh start
- ps -ef | grep ssh
5. root password 설정
6. vi /etc/netplan/*.yaml 에서 고정 ip 설정
7. xshell or putty 사용하여 접속
- 접속 ip : vm #ifconfig -> end33 ip 입력
