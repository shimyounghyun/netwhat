
 > 컴퓨터 네트워크에서 장치들이 서로를 인식하고 통신을 하기 위해서 사용하는 특수한 번호

## 구조 
`32bit(8byte)로 구성된 논리적인 주소 체계`이며 형태는 ex)172.168.10.1로 표기된다.
`.`으로 구분된 Octet(8bit / 1byte)로 조합된다. 알기 쉽게 10진수 형태로 쓰인다.
| 10101100 (8bit) | 10101000 (8bit) | 00001010 (8bit) | 0000001 (8bit) |
| 172 | 168 | 10 | 1 |
| Octet1 | Octet2 | Octet3 | Octet4 |



## 관련 단어
 
- ### protocol
  > 컴퓨터, 통신 장비 사이에 정보를 주고 받는 양식, 규칙 체계
  
 - ### router
  > 네트워크 상에서 출발지에서 특정 목적지로 가는 길을 라우트(route)라고 하며, 이러한 길을 찾아내는 역할을 하는 장비를 '라우터'라고 한다.

 - ### 전송 제어 프로토콜 (TCP : Transmission Control Protocol)
 > 인터넷에 연결된 컴퓨터간 정보 전달 시 순서 대로, 에러없이 교환할 수 있게하는 프로토콜.

 - ### TCP/IP
 > 패킷 통신을 위한 인터넷 규약. IP는 데이터 패킷을 최대한 빨리 목적지로 보내는 역할을 하며 조각의 순서, 누락을 신경쓰지 않는다. TCP는 IP보다 느리지만 순서를 정렬하고, 누락된 정보를 다시 요청 하는 역할을한다. 두 방식을 조합하여 인터넷 데이터 통신을 하는것을 TCP/IP라고 한다.

## 참조
[http://korean-daeddo.blogspot.com/2015/12/ip.html](http://korean-daeddo.blogspot.com/2015/12/ip.html)  
[https://ehym.tistory.com/entry/IP-%EC%A3%BC%EC%86%8C?category=361468](https://ehym.tistory.com/entry/IP-%EC%A3%BC%EC%86%8C?category=361468)  
[https://websecurity.tistory.com/94](https://websecurity.tistory.com/94)  
