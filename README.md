DeepTask Backup Disk Document
===========================================================


## SocialRobot

![내부 구조도](./assets/images/deeptask_network_structure.png)
<a href="#"><img src="https://github.com/hyeonukbhin/deeptask_backup/blob/master/assets/images/socialrobot.png" width="400px" alt="sample image"></a>

### PC1(Main)

![badge](https://img.shields.io/badge/OS_ver.-ubuntu--mate--16.04-blue.svg)
![badge](https://img.shields.io/badge/Disk_Type.-ssd_m.2-blue.svg)

로보케어 Base Package가 구동되는 PC [socialrobot_ros](https://github.com/deep-task/socialrobot_ros "깃허브")
실제 로봇 동작에 필요한 6가지 요소 관장
* LED(Ear-L,R,Base Wheel)
* Neck, Waist Joint
* Arm
* Speech
* Base Driving(Tele-Operating)
* ~~Navigation~~

Disk Label | 날짜 | OS |비고 | 동작 상태
------------ | ------------- | ------------- | ------------- | ------------- 
SocialRobot-PC1-1 | 2021.04.02 | Ubuntu Mate, 16.04 | 4차년도 통합 시나리오 동작 버전 | ![badge](https://img.shields.io/badge/test-passing-brightgreen.svg)
SocialRobot-PC1-2 | 2021.04.14 | Ubuntu Mate, 18.04 | 16.04->18.04 업그레이드 테스트 | ![badge](https://img.shields.io/badge/test-failed-red.svg)
SocialRobot-PC1-3 | 2021.04.28 | Ubuntu Mate, 16.04 | Moveit 설치 및 테스트 | ![badge](https://img.shields.io/badge/test-passing-brightgreen.svg)

### PC2

![badge](https://img.shields.io/badge/OS_ver.-ubuntu--18.04-blue.svg)
![badge](https://img.shields.io/badge/Disk_Type.-sata-blue.svg)


2세부 통합 프레임워크 구동 PC
* KIST-성격인식기
* HY-의도 추정기
* HY-발화 생성기
* DHCP Server
* ROS Multimaster
* ~~DeepTask GUI~~

Disk Label | 날짜 | OS |비고 | 동작 상태
------------ | ------------- | ------------- | ------------- | ------------- 
SocialRobot-PC2-1 | 2021.04.28 | Ubuntu, 16.04 | 4차년도 통합 시나리오 동작 버전 | ![badge](https://img.shields.io/badge/test-passing-brightgreen.svg)


### Jetson

![badge](https://img.shields.io/badge/OS_ver.-ubuntu--nvidia--18.04-blue.svg)
![badge](https://img.shields.io/badge/Disk_Type.-microSD-blue.svg)


ETRI 단기적 사회성 인식기

Disk Label | 날짜 | OS |비고 | 동작 상태
------------ | ------------- | ------------- | ------------- | ------------- 
SocialRobot-Jetson-1 | 2021.05.14 | Ubuntu(Nvidia kernel), 18.04 | 4차년도 통합 시나리오 동작 버전, microSD | ![badge](https://img.shields.io/badge/test-passing-brightgreen.svg)





## Integration Server Rack



2세부 통합 프레임워크 구동 PC(Only Interface)
* ~~KIST-성격인식기~~
* ~~HY-의도 추정기~~
* ~~HY-발화 생성기~~
* DHCP Server
* ROS Multimaster
* DeepTask GUI


### Integration PC

![badge](https://img.shields.io/badge/OS_ver.-ubuntu--18.04-blue.svg)
![badge](https://img.shields.io/badge/Disk_Type.-sata-blue.svg)

Disk Label | 날짜 | OS |비고 | 동작 상태
------------ | ------------- | ------------- | ------------- | ------------- 
Integration-1 | 2021.04.30 | Ubuntu, 16.04 | 4차년도 통합 시나리오 동작 버전 | ![badge](https://img.shields.io/badge/test-passing-brightgreen.svg)


### Simonpic

![badge](https://img.shields.io/badge/OS_ver.-ubuntu--16.04-blue.svg)
![badge](https://img.shields.io/badge/Disk_Type.-sata-blue.svg)

Disk Label | 날짜 | OS |비고 | 동작 상태
------------ | ------------- | ------------- | ------------- | ------------- 
Simonpic1-1 | 2021.04.28 | Ubuntu, 16.04 | 4차년도 통합 시나리오 동작 버전 | ![badge](https://img.shields.io/badge/test-passing-brightgreen.svg)
Simonpic2-1 | 2021.04.28 | Ubuntu, 16.04 | 4차년도 통합 시나리오 동작 버전 | ![badge](https://img.shields.io/badge/test-passing-brightgreen.svg)
PSN1-1 | 2021.05.14 | Ubuntu, 16.04 | 4차년도 통합 시나리오 동작 버전 | ![badge](https://img.shields.io/badge/test-passing-brightgreen.svg)
PSN2-1 | 2021.05.14 | Ubuntu, 16.04 | 4차년도 통합 시나리오 동작 버전 | ![badge](https://img.shields.io/badge/test-passing-brightgreen.svg)
PSN3-1 | 2021.05.14 | Ubuntu, 16.04 | 4차년도 통합 시나리오 동작 버전 | ![badge](https://img.shields.io/badge/test-passing-brightgreen.svg)
PSN4-1 | 2021.05.14 | Ubuntu, 16.04 | 4차년도 통합 시나리오 동작 버전 | ![badge](https://img.shields.io/badge/test-passing-brightgreen.svg)


