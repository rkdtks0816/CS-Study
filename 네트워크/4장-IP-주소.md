영상: [[따라學IT] 04. 실제로 컴퓨터끼리는 IP주소를 사용해 데이터를 주고받는다](https://youtu.be/s5kIGnaNFvM?list=PL0d8NnikouEWcF1jJueLdjRIC4HsUlULi)

## 3계층의 기능
***다른 네트워크 대역까지 어떻게 데이터를 전달할지 "제어"***
### IP 주소
***WAN에서 통신할 때 사용***
### ARP 프로토콜
***IP주소를 이용해 MAC주소 확인***
### IPv4 프로토콜
***WAN에서 통신할 때 사용***


## 일반적인 IP 주소
### Classful IP 주소(사용하지 않음)
***낭비가 심함*** 
<br>![image](https://github.com/rkdtks0816/CS-Study/assets/72867019/2a959062-10d8-4940-95ce-133f02441739)
### Classless IP주소
![image](https://github.com/rkdtks0816/CS-Study/assets/72867019/4ea8cf68-4d9d-4c2c-9218-ba89e25f64f1)
> ### 서브넷 마스크
> ***네트워크 대역을 나눠주는데 사용하는 값***
> 2진수로 표기했을 때 1로 시작, 1과 1사이에는 0이 올 수 없다

> ### 사설 IP와 공인 IP
> ***공인 IP 1개당 2^32개의 사설 IP***
> <br>![image](https://github.com/rkdtks0816/CS-Study/assets/72867019/f44d74d2-e7b0-4f1f-a559-5cc9c591ea1e)

## 특수한 IP 주소
### 0.0.0.0
***Wildcard : 나머지 모든 IP***
### 127.0.0.1
***나 자신을 나타내는 주소***
### 게이트웨이 주소
***어딘가로 가려면 일단 여기로***
<br>![image](https://github.com/rkdtks0816/CS-Study/assets/72867019/0ce418c6-04a3-45df-87f0-883819927599)
