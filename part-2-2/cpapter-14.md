# 역순 주소 결정과 TCP/IP 역순 주소 결정 프로토콜

## 역순 주소 결정 프로토콜

부트스트래핑이란 아무것도 없는 상태에서 어떤 것을 시작하는 것을 가리킨다.  
TCP/IP 통신에 필요한 IP 주소를 얻기 위해 TCP/IP를 사용하는 것은 모순이다. 하지만 대상 주소를 모르는 경우에도 로컬 통신이 일어나도록 하는 브로드캐스트를 이용하면 이 작업을 수행할 수 있다.  

> 역순 주소 결정 프로토콜 (RARP, Revers Address Resolution Protocol)은 장비가 TCP/IP 네으퉈크에서 사용할 수 있는 IP 주소를 얻도록 하는 초창기에 나온 간단한 프로토콜이다. RARP는 ARP에 근거를 두고 있으며 기본적으로 ARP와 동일하게 동작한다. 다만 그 방향이 반대다. 장비는 하드웨어 주소를 담은 요청을 보내고, RARP 서버로 설정된 장비는 요청을 보낸 장비에게 할당된 IP 주소 정보를 담은 응답을 보낸다.

![Operation of the Reverse Address Resolution Protocol!](http://www.tcpipguide.com/free/diagrams/rarptrans.png)

![Reverse Address Resolution Protocol (RARP) Operation!](http://www.tcpipguide.com/free/diagrams/rarpoperation.png)  