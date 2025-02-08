<div align="center">    
  <h1>Tech Interview Questions</h1>
  
  <img src="https://img.shields.io/badge/Software-Basic-yellow" alt="Basic"/>
  <img src="https://img.shields.io/badge/Position-Frontend-orange" alt="Frontend"/>
  <img src="https://img.shields.io/badge/Position-Backend-blue" alt="Backend"/>
  <img src="https://img.shields.io/badge/Position-Data-green" alt="Data"/>
  <img src="https://img.shields.io/badge/Position-AI/Machine Learning-teal" alt="AI/Machine Learning"/>

  <h4> 기본부터, Front/Back/Data/AI,ML 까지 많이 다뤄지는 기술 면접 질문 리스트 </h4>
</div>

## Table of Contents  

- [Basic](#basic)  
- [Frontend](#frontend)
- [Backend](#backend)
- [Data](#data)
- [AI/Machine Learning](#aimachine-learning)

## Basic

### Authentication
- 인증에서 Session과 Token 방식 각각의 장, 단점은 무엇이 있나요? 또 어디에 활용하면 좋은가요?

### Computer Architecture
- Float은 보통 소수를 표현하기 위해 사용됩니다. 컴퓨터 내부적으로는 어떻게 표현이 될까요?

### Data Structure
- 웹 브라우저를 기준으로 Stack/Queue가 어디에 사용되고 있는지 설명해주세요.
- Array 와 List은 여러개의 데이터를 처리할 때 보통 사용됩니다. 어떤 경우에 Array를 혹은 List를 사용하시겠나요?
- List, Set에서 ‘A’ 라는 아이템이 들어있는지 확인하는데, 걸리는 시간 복잡도는?

### Database
- RDB 와 NoSQL 의 각각의 장단점 그리고 어디에 사용하면 좋은지 대표적인 사용처를 설명해주세요.

### Encoding
- Base64이 어떻게 동작하는지 그리고 어디에 쓰이는지 설명해주세요
- UTF-8이란 무엇일까요? 그리고 여기서 한글은 몇 바이트로 표현되는지 아시나요?

### Network
- HTTP 프로토콜에서 keep-alive 옵션은 무엇을 의미하고, 어떤 상황에서 유용할까요?
- DNS 프로토콜이 TCP 대신 UDP를 사용하는 이유는 무엇일까요?
- HTTP 프로토콜의 버전 별로 가장 큰 특징을 설명해주세요. (1.1, 2.0, 3.0)
- 흔히 TCP는 신뢰성을 보장한다고 하는데, 어떤 식으로 보장하나요?

### OS
- 프로세스와 스레드 각각의 관점에서 Context Switching을 설명해주세요.
- 운영체제에서 System Call이 무엇인가요? 알고 계신 예시들을 함께 설명해주세요.
- 가상메모리는 무엇이고, 또 어떻게 동작하나요?

### System Design
- 보통 서비스를 Stateless 하게 만들어야 한다고 말을 합니다. Stateless의 장점과 Stateful 이 문제가 되는 상황을 함께 설명해주세요.

---

## Frontend

### CSS
- CSS 는 Cascading Style Sheets의 약자입니다. Cascading 이 의미하는 바와 장점을 설명해주세요.
- CSS에서 알고 있는 display 속성을 모두 말씀해주세요. 그리고 개발할 때는 주로 어떤 속성을 왜 사용하셨나요?
- CSS 속성 중 z-index 는 어떻게 동작하나요?
- 두개의 엘리맨트가 있고 각각 margin-top, margin-bottom 이 정의 되어있을떄, 위 아래로 인접해있다면 어떻게 표시될까요?

### HTML
- HTML 태그 중 <script async>, <script defer> 간의 차이점을 설명해주세요.

### JavaScript
- JavaScript에서 event.target와 event.currentTarget 이 각각 다른 요소를 가리키는 경우는 어떤 상황인가요?
- 개발을 하다보면 CORS 에러를 마주치곤 합니다. CORS가 무엇인지? 그리고 이 문제를 해결하는 방법을 알려주세요.
- 자바스크립트의 이벤트 루프의 동작 방식을 아시는 것을 모두 설명해주세요.
- 브라우저 저장소들의 각각 장단점과 대표적인 사용처를 알려주세요.
- JavaScript 호이스팅이란 무엇인가요? 그리고 var 와 let, const 각각 호이스팅 시 다르게 동작하는데 왜 그런가요?
- JavaScript에서 undefined 와 null 은 각각 무엇을 의미하나요?
- JavaScript에서 async/await, Promise 문법 각각의 장단점과 적합한 사용처를 함께 설명해주세요.

### Next.js
- Next.js의 ISR(Incremental Static Regeneration)은 어떤 기능인가요? 또 어디에 사용하면 좋을까요?
- Next.js의 next/image 컴포넌트가 일반적인 <img> 태그와 다른 점은 무엇이며, 어떻게 활용하면 성능을 최적화할 수 있나요?
- Next.js는 흔히 SEO에 최적화가 되어있다고 하는데, 어떤 장점들이 있나요?
- Next.js의 getServerSideProps, getStaticProps 각각을 언제 사용하는 것이 적합한지 사례와 함께 설명해주세요.
- Next.js를 사용하면 얻을 수 있는 이점들은 무엇이 있을까요?
- Next.js를 사용하면서 프로젝트에서 코드 스플리팅이나 번들 크기 최적화를 위해 했던 작업을 공유해주세요.

### React
- React에서 strict 모드는 랜더링을 두번 합니다. 왜 그럴까요?
- React에서 useEffect와 useLayoutEffect hook의 차이점은 무엇인가요?
- React Fragment란 무엇인가요? 그리고 장점은 무엇이 있나요?
- React의 Reconciliation 프로세스에 대해서 key를 포함해서 설명해주세요.
- React 컴포넌트에서 ‘key’ prop 은 어떤 역할을 하나요? 값을 부여할때 주의할 점이 있다면 무엇이 있을까요?
- React의 state와 props에 대해서 설명해주세요.
- 리엑트에서 클래스형으로 컴포넌트를 만든다면, 어떤 상황에서 적합할까요?
- React에서 Prop Drilling 문제를 들어보신 적이 있으신가요? 이 문제를 해결하기 위한 방법은 무엇이 있을까요?
- 리엑트에서 사용자의 인증 정보를 다양한 컴포넌트에서 접근해서 사용하게 만드려면 어떤 방식으로 해결하시겠나요?
- 리엑트에서 고차컴포넌트(Higher-Order Component)를 구성한다면 어떤 상황에 적용하시겠나요?
- React에는 많은 상태관리 라이브러리들이 있습니다. 왜 상태관리가 이렇게나 필요할까요?

### TypeScript
- TypeScript에서 any, unknown 의 차이점과 어디에 사용하면 좋을지 설명해주세요
- TypeScript 에서 지원하는 Type, Interface의 차이점은 무엇인가요? 각각 어디에 사용하시겠어요?

### Web
- 랜더링 방식 들 중 CSR, SSR, SSG 각각 방식의 장단점과 차이를 설명해주세요.
- Web Vitals(웹 성능 지표)를 모니터링하고 최적화한 경험이 있으신가요? 있다면 각 지표와 어떻게 최적화했는지 설명해주세요.

---

## Backend

### Cache
- 읽기 성능을 높이기 위해서 캐시 레이어를 추가하려고 합니다. 캐싱 전략(읽기/쓰기 관점)을 어떻게 설계하시겠나요?

### Database
- 데이터베이스의 파티셔닝(Partitioning)이란 무엇이며, 언제 그리고 어떻게 사용해야 하나요?
- MySQL 에서 SlowQuery 의 성능을 개선한다면 어떻게 접근하시겠나요?
- DB의 트랜잭션 격리수준에 대해서 알고 계신 것을 모두 설명해주세요.
- MySQL의 Covering Index, Secondary Index 각각 무엇을 위한 용도인가요? 그리고 커버링 인덱스가 동작하는 상황도 함께 설명해주세요.
- MySQL 에서 제공하는 인덱스에 대해서 알고 있는 것들을 편하게 말씀해주세요.
- 샤딩이란 무엇이며, 분산 데이터베이스에서 샤딩을 설계할 때 고려해야 할 주요 요소는 무엇인가요? 실제로 설계하거나 운영해본 경험이 있다면 설명해주세요.
- 데이터베이스 인덱스 중 LSM, B-Tree 각각의 장점과 사용처를 설명해주세요.
- 분산락을 사용해보신 적이 있으신가요? 어떤 경우에서 많이 사용을 하나요?
- 팬덤리드란 무엇인가요? 그리고 MySQL 에서 팬덤리드가 발생하지 않는 이유는 무엇인가요?
- MySQL에서 UUID를 PK로 했을 때 생기는 성능 이슈는 무엇이 있나요?

### Distributed
- 분산 시스템에서 이야기 되는 최종적 일관성(Eventual Consistency)은 무엇인가요?
- Paxos나 Raft와 같은 합의 알고리즘(consensus algorithm)을 설명하고, 각각의 장단점을 비교하세요.
- 안정 해시(Consistent Hashing)는 무엇이고, 어디에 주로 사용이 되나요?
- Strong Consistency, Eventual Consistency, 그리고 Causal Consistency의 차이를 설명하고, 어떤 상황에서 각각을 선택하는 것이 적절한지 설명해주세요.

### Elasticsearch
- Elasticsearch 는 분산시스템으로 대용량 트래픽을 안정적으로 처리하기 용이하게 설계되어 있습니다. 내부가 어떤 식으로 구성되어 있나요?

### Java
- Java 언어의 메모리 모델과 GC 동작방식을 설명해주세요.
- Thread-Safe란 무엇인가요? Java에서 어떤 방식으로 달성할 수 있을까요?
- Java의 에러 처리 전략에 대해서 Checked/Unchecked Exception을 포함해서 설명해주세요.

### JPA
- JPA를 이용하여 상속을 구현한다면, 어떤 방식을 사용하시겠나요? 각각의 장단점을 함께 서술해주세요.
- JPA 에서 제공하는 영속성 컨텍스트(Persistence Context)은 무엇이며, 어떤 장점이 있나요?
- JPA를 사용할 때 발생할 수 있는 N+1 문제에 대해서 설명해주세요
- JPA에서 Dirty Checking 은 내부적으로 어떻게 동작하나요? 그리고 성능에 미치는 영향을 설명해주세요

### Kafka
- Kafka의 각각의 구성요소들은 무엇이 있는지, 그리고 역할은 무엇인지 설명해주세요.
- Kafka에서 Consumer Group 이 하는 역할을 설명해주세요.
- Kafka에서 브로커가 다운되면 전체 시스템에 어떤 영향을 주나요? 그리고 이 문제를 해결하려면 어떻게 하시겠나요?
- Kafka에서 파티션 개수가 6개인 토픽을 구독하는 컨슈머를 만든다면, 몇개의 인스턴스로 구성하시겠나요?
- Kafka는 분산 시스템으로 빠르고, 처리량 또한 높은 것으로 알려져 있습니다. 내부 구조를 기반으로 왜 그런지 설명해주세요.

### Kotlin
- Kotlin의 inline 키워드는 어떤 상황에서 사용하며, 이를 사용함으로써 얻을 수 있는 장점과 주의할 점은 무엇인가요?
- Kotlin 에서 제공하는 확장 함수란 무엇인가요? 사용한다면 어디에 적용해보시겠나요?
- Kotlin의 Sealed 클래스와 Enum의 차이를 설명하고, Sealed 클래스를 사용하여 복잡한 상태를 관리한 경험이 있다면 공유해주세요.
- Kotlin에서 지원하는 코루틴이 무엇인가요? 그리고 내부적으로 어떻게 구현이 되어있나요?

### Messaging
- 메시지 브로커(Message Broker)의 역할은 무엇인가요?
- 메시지 처리 실패 시 재시도 전략을 설계하거나 적용한 경험이 있으신가요?
- 메시징 시스템에서 메시지 중복 전송이 발생했을 때 이를 감지하고 처리하는 방법은 무엇인가요?
- 메시지의 순서를 보장해야 하는 요구사항이 들어왔다면, 어떻게 구현하시겠나요?
- 메시징 시스템에서 ‘Back Pressure’란 무엇이고, 이를 어떻게 처리하나요?
- 메시지큐에서 발생할 수 있는 성능 병목 현상은 어떤 것들이 있고, 또 어떻게 해결할 수 있을까요?
- Dead Letter Queue(DLQ)란 무엇이고, 이를 사용하여 실패한 메시지를 처리한 경험을 공유해주세요.
- 메시지의 정확한 전달(Exactly Once)을 보장해야 한다면, 어떤 방식으로 처리하시겠나요?

### MSA
- Circuit Breaker Pattern은 어떤 상황에서 필요한가요?
- 흔히 팀/비즈니스가 확장되면 모놀리식에서 MSA로 전환하곤 합니다. 구체적으로는 어떤 점들을 고려해야 할까요?

### Python
- Python 언어에서 GC는 어떤 식으로 동작하나요?

### Redis
- Redis가 단일 스레드로 동작하는 이유와 좋은 성능을 내는 이유를 설명해주세요.
- Redis는 어떤 데이터 구조를 지원하나요? 각 데이터 구조의 사용 사례를 설명해주세요.
- Redis의 라이브러리 중, Lettuce 와 Redisson는 동작방식이 어떻게 다른가요? 또 각각 어떤 상황에서 유용한가요?

### Spring
- WebFlux의 스레드 모델은 Spring MVC와 어떻게 다른가요?
- Spring WebFlux는 무엇이며, Spring MVC와의 주요 차이점은 무엇인가요? 어떤 상황에서 WebFlux를 선택해야 하나요?
- 스프링에서 @Component와 @Bean은 무슨 차이가 있나요? 또 각각 어디에 사용하나요?
- 스프링은 여러가지 디자인패턴으로 이루어져있는 프레임워크 입니다. 어떤 디자인패턴이 어디에 사용이 되고 있나요?
- 스프링에서 보통 읽기에는 @Transactional(readOnly=true)를 사용하는데, 어떤 이점이 있을까요?
- 스프링에서 비관적/낙관적 락을 사용하는 경우를 각각 예시를 들어주세요.
- 스프링에서 제공하는 @Transactional 은 어떻게 동작하나요? 그리고 이런 동작을 가능하게 만드는 내부 구조도 함께 설명해주세요.
- Spring의 @Async 어노테이션을 ThreadPool 관점에서 동작방식을 설명해주세요.
- Spring의 @Autowired 는 내부적으로 어떻게 동작하나요? 그리고 어떤 장/단점이 있나요?
- Spring Security의 기본 개념과 인증(Authentication) 및 인가(Authorization)의 작동 방식(Filter 포함)을 설명해주세요. 실제로 Spring Security를 활용한 경험이 있다면 사례를 공유해주세요.

### System Design
- 수직적 확장과 수평적 확장의 차이점은 무엇이며, 각각 언제 사용하는 것이 적합한가요?
- 어뷰징을 방지하기 위해서 API Rate Limit 직접 구현하려고 합니다. 어떻게 구현하실지 고민해보시고 공유해주세요.
- CQRS 패턴의 장단점을 서술하고, 어떤 상황에 유용한지 설명해주세요.

---

## Data

### Data Engineering
- 분산 파일 시스템(HDFS)의 주요 특징은 무엇인가요?
- Data Warehouse와 Lake 간의 차이점 그리고 각각 어떻게 사용하실지 말씀해주세요.
- 데이터 엔지니어링의 가장 기본이 되는 ETL에 대해서 설명해주세요.
- CDC(Change Data Capture) 기법이란 무엇이며, 어떻게 구현할 수 있을까요? 또 어디에 적용하면 좋을까요?

### Data Lake
- Data Lake란 무엇인가요? 주요 사용 사례도 함께 설명해주세요.

### Data Warehouse
- Star 스키마에 대해서 들어보신 적이 있으신가요? 있다면 어떤 것인지 설명해주세요.

### Flink
- Flink에서 Bounded Stream과 Unbounded Stream의 차이를 설명해주세요.
- Flink의 기본 아키텍처(JobManager, TaskManager 등)를 설명해주세요.
- Flink를 사용해서 특정 시간 간격 동안 발생한 이벤트 수를 계산하려면 어떤 접근 방식을 사용할 수 있나요?
- Flink 애플리케이션에서 성능 병목 현상을 디버깅하고 개선한다면 어떻게 하시겠어요?

### Spark
- Spark는 분산 데이터 처리 엔진으로 알려져 있습니다. 어떤 구조로 되어있는지 설명해주세요.
- 일련의 장애로 Spark RDD에서 데이터 유실이 발생했을 때, 이를 복구하는 방법은?
- Spark의 RDD는 분산 환경에서 병렬처리를 지원하는 가장 핵심적인 데이터 구조입니다. 내부적으로는 어떻게 이를 지원하고 있나요?
- Spark 작업에서 발생할 수 있는 OOM(Out of Memory) 문제를 해결하는 방법은?

---

## AI/Machine Learning

### LLM
- 프롬프트는 어떻게 작성하느냐에 따라 성능의 차이가 많이 나곤 합니다. 어떻게 작성하시는 편인가요? 관련해서 알고 계신 논문도 함께 설명해주세요.

### Machine Learning
- 편향-분산 트레이드오프(bias-variance tradeoff)를 설명하고 이를 최적화하는 방법에 대해서 알고 계신 것을 모두 설명해주세요
- 실무에서 직접 데이터를 전처리 하다 보면, 빠져있는 값들을 발견하곤 합니다. 이때 어떤 식으로 처리를 하면 좋을까요?
- 성능 평가에 사용되는 매트릭에 대해서 알고 계신 것들을 모두 말씀해주세요.
- 앙상블 기법 중 Bagging 과 Boosting 이 무엇인지 데이터, 모델 관점에서 설명해주세요. 또한 각각의 장점과 대표적인 알고리즘도 함께 소개해주세요.
- Binary Classification 문제에서 데이터가 불균형할때 어떤 방식으로 해결하시겠나요?
- 모델 드리프트(Model Drift)의 개념과 이를 방지하기 위한 전략은 무엇이 있을까요?

### MLOps
- 모델은 꾸준히 재학습이 필요할 수 있습니다. 재학습 및 배포과정을 자동화한다면 어떻게 시스템을 구성하시겠나요?

### Serving
- 모델을 배포할때, 크게 배치(batch)과 실시간 처리(online)로 나눌 수 있습니다. 각각 어떤 식으로 동작하고 어디에 적합한지 설명해주세요.
- REST API와 gRPC를 비교하고, 모델 서빙에는 어떤 통신방식이 더 적합할지 설명해주세요.
- 모델 서빙성능을 최적화하기 위해서, 많은 프레임워크에서 Adaptive Batching, Dynamic Batching 와 같은 기능들이 제공하고 있습니다. 해당 기능은 내부적으로 어떻게 동작하나요?
- 새로운 모델을 만들어서 배포를 하려고 합니다. 성능과 안정성에 중요하다면, 어떤 배포전략을 가지고 가면 좋을지 말씀해주세요.
