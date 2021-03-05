# Study_OPC_UA
OPC UA란?
-------------------------------
OPC UA(OPC Unified Architecture)는 산업 자동화를 위한 Machine 사이의 통신을 위한 프로토콜
* client-server communication
* cross-platfrom : 윈도우에서만 돌아가는 OPC DA와 달리 OS나 언어의 선택에 자유롭다.

PROTOCOLS
-------------------------------
OPC UA는 두가지 프로토콜을 지원한다.
### BINARY PROTOCOL - opc.tcp://Server
* 성능이 좋고, overhead가 적으며 자원이 적게 든다.
* tunneling이나 방화벽을 통한 활성화를 쉽게하기위해, 임의로 선택가능한 하나의 tcp 포트를 사용한다.

### Web Service (SOAP) PROTOCOL - http://Server
* 확장성이 좋다.
* HTTP(S) 포트 사용


