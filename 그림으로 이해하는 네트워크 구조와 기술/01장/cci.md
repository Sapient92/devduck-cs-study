네트워크란?
-----------

네트워크란 하나의 노드가 하나 이상의 다른 노드와 연결되어 있는 상태를 뜻한다.

기술적 관점에서 네트워크 연결대상은 전자기기나 시스템을 뜻한다.

## 네트워크 토폴로지

1. 라인형 : 직렬로 연결
2. 링형 : 둥글게 링으로 연결
3. 스타형 : 가운데 허브(기점 노드)를 두고 허브와 모든 노드가 연결
4. 버스형 : 선 (동축케이블) 하나에 노드들이 달라붙은 형태
5. 트리형 : 루트 노드와 리브노드를 제외하고 각 노드는 부모노드와 자식노드를 가지고 있음.
6. 메시형 : 각 노드가 하나 이상의 노드와 연결된 상태.

**결론 : 대부분 이 유형들을 섞은 복합형 토폴로지를 사용한다.**

## 네트워크 구성요소

1. LAN 케이블 : 컴퓨터와 네트워크를 연결하는 물리적인 선
2. 스위치 허브 : 여러 LAN 케이블 연결 가능. 지정된 노드에만 신호를 보낸다.
3. 리피터 : 여러 LAN 케이블 연결 가능. 수신한 신호를 그대로 전송한다.
4. 브리지 : 전송 원리가 다른 네트워크 사이에서 변환
5. 네트워크 인터페이스 카드 : 신호를 변환
6. 라우터 : LAN과 LAN을 연결할 때 쓰이는 기기
7. 게이트웨이 : 네트워크 접속점. 네트워크나 세그먼트의 경계에 설치되어 패킷 출입을 제어한다. 특정 장치 기술 x. 라우터나 서버등 네트워크 장치라면 정의할 수 있다. (나중에)

## 데이터 전송 원리

1. **직렬 & 병렬** 

|  | 신호선 | 비트 | 신호유형 | 장거리통신 | 사용빈도 | 사용방식 |
| --- | --- | --- | --- | --- | --- | --- |
| 직렬 | 1개 | 1비트 | 펄스형 | 유리 | 대부분 | 송신,수신 따로 |
| 병렬 | 8개, 16개 | 8개, 16개 | 펄스형 | 불리 | 잘 안쓰임 |  |

1. **비동기 & 동기**
   
|  | 방식 |
| --- | --- |
| 비동기 | 시작비트,종료비트 |
| 동기 | 클럭 신호에 맞춰 일정하게 |
