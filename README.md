# BlockChain-in-js

### 용어 정리
#### 블록체인
* **블록<sup>*block*</sup>**: 데이터를 저장하는 단위
* **체인<sup>*chain*</sup>**: 블록은 계속 엮어놓는 것
* **Blockchain**: 변경불가(immutable)한 분산 원장
---
* **원장<sup>*ledger*</sup>**: 단순히 금융 계정이나 사용자들이 일으킨 <u>트랜잭션의 묶음</u>
* **노드<sup>*node*</sup>**: 블록체인 네트워크에 기여하는 각 <u>참여자</u>
  각 node는 정확히 동일한 ledger 사본을 가지고 있음
  즉, ledger 데이터는 전체 네트워크에서 호스팅되고 동기화됨
---
* 비가역성: 이미 일어난 일을 되돌리기 어려움

* 블록체인의 변경 불가(immutable) 특성 - 기록이 결코 바뀔 수 없다는 것
블록체인의 변경 불가 특성에 의해 트랜잭션이 일단 기록되면 보낸 금액이나 트랜잭션에 참여한 사람을 포함하여 그 트랜잭션의 어떤 측면도 바꿀 수 없음

블록체인은 분산 네트워크로 어떠한 단일 세력에 의해 제어되지 않으며, 정상적인 보통 사람들에 의해 운영됨
비트코인과 같은 블록체인은 전세계 수천명의 사람들이 지원하고 호스팅함
블록체인 기술은 데이터를 독점한 한 회사를 신뢰할 필요가 없으므로 큰 이점을 가짐
데이터는 모두 독립적으로 움직이는 수천명의 사람들이 참여하는 전체 네트워크에 의해 유지됨

블록체인은 변경불가한 분산 원장으로 트랜잭션이 절대 변경될 수 없고, 
블록체인 그 자체가 네트워크 전체에 분산되어 
수천 명의 독립적인 노드들에 의해 운영된다는 것을 의미함

---
#### 블록체인은 무엇일까?
* **블록**은 데이터를 저장하는 단위이자 공간임
* **체인**은 블록을 계속 엮어놓는 것을 의미함
* 즉, 블록체인은 데이터를 저장하는 단위이자 공간인 블록을 계속 엮어놓는 것
블록을 계속 엮어놓는 것이 왜 의미가 있을까?
'왜 엮어놓는가?' 그리고 '어떻게 엮어놓는가?'가 블록체인을 특별하게 만들어줌
##### 1. 왜 엮어놓는가?

