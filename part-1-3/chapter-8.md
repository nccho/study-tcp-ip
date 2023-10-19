# TCP/IP 프로토콜 슈트와 구조

## TCP/IP 개요  

TCP와 IP 이 두 프로토콜은 매우 중요해서 이들의 이름 약자가 전체 프로토콜 슈트의 이름(TCP/IP)이 됐다.  
TCP/IP는 구성 프로토콜 체계를 갖추기 위해 고유의 4계층 구조를 사용한다.  

### TCP/IP 성공 요인  

- 통합 주소 지정 체계
- 라우팅을 위한 설계
- 하부 네트워크와의 독립성
- 확장성
- 표준과 개발 절차 공개
- 보편성

### TCP/IP 서비스 개념적 구분

- 다른 프로토콜에 제공하는 서비스
    - 네트워크 계증: IP 주소 지정
    - 전송 계층: TCP/UDP 사용자 데이터 캡슐화 장비간 연결 관리
- 최종 사용자 서비스
    - TCP/IP 네트워크를 이용하기 위한 어클리케이션으 동작을 돕는다.

### TCP/IP 구조와 모델

- 애플리케이션 계층: 최종 사용자 서비스를 제공하는 역활
- 호스트 간 전송 계층: 네트워크 상에서 종단간 통신을 수행
- 인터넷 계층: 논리적 장비 주소 지정, 데이터 패키징, 라우팅 작업 수행
- 네트워크 인터페이스 계층: 로컬 네트워크에 접근하기 위한 인터페이스 역활

![TCP IP Protocol!](http://www.tcpipguide.com/free/diagrams/tcpipprotocols.png "TCP/IP Protocol")


> suite: 집합  
> IP: Internet protocol  
> TCP: Transmission Control Protocol  