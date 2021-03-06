# BlockchainStudy

## Terminology

### 1. Blockchain
- 사용자의 DID 관련 정보가 저장되는 탈중앙화된 저장소.

### 2. DID(Decentralized Identifier)
- 사용자의 분산 식별자(Decentralized Identifier). 
- 생태계의 모든 주체(entity)들은 자신의 DID를 하나 이상 가진다.

### 3. DID Document
- 블록체인에 등록되어 있는 사용자 DID 관련 정보를 담고 있는 문서.

### 4. Entity
- 생태계에서 하나 이상의 역할을 수행 하는 사람, 조직 혹은 장치를 일컫는 말로 여기서는 Issuer, Verifier, Holder 등의 구성 요소를 표현하는데 쓰인다.

### 5. Issuer
- 사용자 요청에 의해 사용자 정보를 인증하고 Credential을 발급하는 발급기관

### 6. Verifier
- 서비스의 이용을 위해서 사용자로부터 전달 받은 Presentation을 검증하고 서비스를 제공하는 서비스 제공자

### 7. Holder
- 플랫폼에서 서비스를 이용하는 사용자. 이슈어로부터 Credential을 발급 받고 Verifier의 서비스를 이용하기 위해 Presentation을 만들어서 제출하는 사용자

### 8. Credential
- Issuer로부터 인증받고 발급받은 증명내역. 
- 실제 증명받은 Claim Data와 이 Claim Data를 증명해 줄 수 있는 Verifiable Credential로 구성된다. 
- 보통 Credential과 Verifiable Credential은 동일한 경우가 많다.

### 9. Verifiable Credential
- Issuer로부터 발급받은 증명서로 위변조를 검증할 수 있다. 
- 단, Credential 내에 Claim Data가 실제로 존재하지 않고, Claim Data를 검증할 수 있는 정보만 포함되어 있다.

### 10. VC
- Verifiable Credential을 줄여서 VC로 표현하기도 한다.


### 11. Claim
- Issuer로부터 인증받고 Credential로 발급 받은 사용자 정보.

### 12. Verifiable Presentation (Presentation)
- 서비스 이용을 위해, Verifier가 요구한 사용자 정보에 대하여 사용자(Holder)가 Credential을 포함한 후 사용자가 서명한 제출 데이터. 
- 위변조 검증이 가능하다는 점에서 Verifiable Presentation이라고 불리며, 이는 Presentation과 기술적으로 동일하다. 
- Credential과 Verifiable Credential은 다르지만, Verifiable Presentation과 Presentation은 동일하다.

### 13. VP
- Verifiable Presentation을 줄여서 VP로 표현하기도 한다.

### 14. VCP (Message)
- Verifiable Credential, Verifiable Presentation의 약자로 VC를 발급하고 VP를 제출할 때 사용하는 메세지 프로토콜.

### 15. JWT (JSON Web Token)
- Credential, Presentation 등의 발급에 사용되는 기본 포맷.

### 16. JWS (JSON Web Signature)
- JWT는 header, payload, signature로 구성되는데, JWT 내에 포함되는 서명(signature).

### 17. JWE (JSON Web Encryption)
- Credential, Presentation의 데이터를 보호하기 위해 서버와 클라이언트간 암호화한 데이터 포맷.


### 18. 블록체인의 핵심 요소
- 분산 원장 기술
  - 모든 네트워크 참여자는 분산 원장과 트랜잭션의 불변 레코드에 액세스할 수 있다. 이 공유 원장에서 트랜잭션은 한 번만 기록되며,
  - 기존 비즈니스 네트워크에서는 흔한 중복 업무가 사라진다.
- 불변 레코드
  - 일단 공유 원장에 기록되면 어떤 참가자도 트랜잭션을 변경하거나 이를 위조할 수 없다.
  - 트랜잭션 레코드에 오류가 포함되면 해당 오류를 되돌리기 위해 새 트랜잭션을 추가해야 하며, 두 트랜잭션을 모두 볼 수 있다.
- 스마트 계약
  - 트랜잭션 속도를 높일 수 있도록, 스마트 계약이라고 부르는 일련의 규칙들이 블록체인에 저장되어 자동으로 실행된다.
  - 스마트 계약은 기업 채권양도증명서의 조건을 정의할 수 있으며 지급할 여행보험의 조항 등을 포함할 수 있다.



