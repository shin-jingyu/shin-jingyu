# 신진규 | Backend Developer

Java와 Spring을 기반으로 서버 애플리케이션을 개발해 왔습니다.

망 분리 환경에서 **Android–DMZ–Core 간 API 연동**, **출입 이벤트 기반 MDM 보안 정책 제어**, **트래픽 분산을 위한 다중 서버 및 PostgreSQL Replication 환경 구축·운영**을 경험했습니다.

기능을 바로 구현하기보다 기준이 되는 데이터와 각 시스템의 역할을 먼저 확인합니다. 운영 환경에서는 정상적인 흐름뿐 아니라 데이터 불일치와 누락, 장애 상황에서 어떻게 검증하고 복구할 것인지까지 함께 고려하며 개발합니다.

---

## Experience Highlights

* 망 분리 환경의 Android–DMZ–Core 간 API 연동 구조 설계 및 개발
* 출입 이벤트 기반 사용자 상태 판별 및 MDM 보안 정책 자동화
* 트래픽 분산을 위한 다중 서버·PostgreSQL Replication 환경 구축 및 데이터 정합성 처리
* 운영 장애 원인 분석 및 PostgreSQL 설정 개선

---

## Work Experience

### 모피어스 시큐리티

**Backend Developer**
2024.03 ~ 2026.07

`Java` `Spring` `PostgreSQL` `MyBatis` `JavaScript` `Android`

### 주요 경험

* 망 분리 환경에서 **Android–DMZ–Core 간 역할과 통신 흐름을 정의**하고 API 연동 구조 설계 및 개발
* 출입 게이트 이벤트와 사용자 상태값을 기반으로 **MDM 보안 정책 자동 적용·해제 기능 구현**
* 전화번호와 고유 식별값을 활용한 **출입 시스템–MDM 간 사용자·단말 정보 연동**
* 출퇴근 시간대 집중 트래픽 분산을 위한 **다중 서버 및 PostgreSQL Replication 환경 구축·운영**
* 동일 사용자 다중 접속 제한과 DB 데이터 비교를 통해 **데이터 정합성을 검증하고, 불일치 시 최신 값을 기준으로 재동기화하는 로직 구현**
* 특정 시간대 반복 장애를 사용자 수, 로직 실행 시간, DB 설정 순으로 분석해 **PostgreSQL `work_mem` 설정 문제를 찾아 개선**
* 외부 데이터 누락·생성 지연에 대비한 **검증 및 대체 조회 로직과 운영자 복구 기능 구현**

### 개발 방식

시스템 간 연동에서는 기능 구현에 앞서 **어떤 데이터가 기준인지, 각 시스템이 어디까지 책임지는지, 데이터가 어떤 방향으로 전달되는지**를 먼저 확인합니다.

운영 환경에서는 정상적인 흐름만 전제로 하지 않고 데이터 불일치나 누락, 외부 시스템의 상태 변화까지 고려해 **검증하고 복구할 수 있는 흐름**을 함께 구현해 왔습니다.


---

## Projects

### 4GATHER

지역과 일정에 따라 반려동물 박람회 정보를 조회할 수 있는 웹 플랫폼입니다.

* **기간:** 2025.06 ~ 2025.12
* **역할:** Backend Developer
* **형태:** 팀 사이드 프로젝트

`Spring Boot` `JPA` `Redis` `JWT` `OAuth 2.0` `Docker`

#### 주요 작업

* 지역과 일자를 기준으로 펫페어 정보 검색 및 정렬 기능 개발
* 팀원들과 도메인 모델 및 데이터 관계 설계
* 서비스 아이디어를 실제 개발 가능한 기능으로 구체화하고 MVP 범위 정의
* JWT 기반 사용자 인증 기능 구현
* OAuth 2.0 기반 소셜 로그인 적용
* Redis를 활용한 데이터 캐싱 구조 설계
* GitHub Issue와 Pull Request 기반 개발 및 코드 리뷰
* Figma와 Notion을 활용한 요구사항 및 역할 분담 관리

아이디어 단계의 서비스를 실제 구현 가능한 기능으로 나누고, 팀원들과 도메인 모델과 MVP 범위를 정의하며 개발했습니다.

---

### Nettee Backend Project

네트워크 스터디 구성원들과 개발하고 있는 채팅형 블로그 플랫폼입니다.

* **기간:** 2024.10.15 ~ 현재
* **역할:** Backend Developer

`Spring Boot` `JPA` `QueryDSL` `MapStruct` `Kotest` `Docker`

#### 주요 작업

* 멀티모듈 구조를 적용해 도메인과 의존 관계 분리
* JPA와 QueryDSL을 활용한 데이터 저장 및 조회 기능 구현
* MapStruct를 활용한 DTO와 Entity 변환
* Kotest 기반 테스트 코드 작성
* 외부 도메인 요청을 고려한 CORS 정책 설정
* GitHub Pull Request와 Code Review 기반 협업
* Pull Request에 구현 배경과 변경 범위 기록
* 리뷰 의견을 반영한 코드 구조 개선

기능을 구현한 결과뿐 아니라 해당 구조를 선택한 이유와 변경 범위를 Pull Request에 기록하고 있습니다. 리뷰 과정에서는 서로 다른 구현 방식을 비교하고, 각 방식의 장단점과 변경 의도를 함께 논의하며 개발하고 있습니다.

---

## Study

### Spring · Backend Study

* **기간:** 2025.02.17 ~ 현재
* **방식:** 학습, 구현, 발표, 기술 토론

관심이 생긴 백엔드 기술을 직접 구현하고, 함께 공부하는 구성원과 서로 다른 접근 방식을 비교하며 기술의 적용 이유와 장단점을 학습하고 있습니다.

#### 주요 활동

* Spring Framework와 JPA 핵심 개념 학습
* gRPC 기반 서비스 간 통신 구현
* GraphQL API 구현
* RabbitMQ 기반 비동기 메시지 처리
* 멀티모듈 구조에서 인증 서버 분리
* 인증 서버와 API Gateway 연계
* 관심 기술 직접 구현 및 접근 방식 비교·토론

`Spring Boot` `JPA` `gRPC` `GraphQL` `RabbitMQ` `API Gateway`

---

### Nettee Network Study

* **기간:** 2024.08.20 ~ 2024.10.27
* **방식:** 주 2회 학습, 발표, 피드백

TCP/IP, DNS, HTTP를 중심으로 클라이언트의 요청이 서버에 전달되고 응답이 돌아오는 과정을 학습하고 발표했습니다.

`TCP/IP` `DNS` `HTTP` `Client-Server`

---

## Tech Stack

### Main Experience

`Java` `Spring` `Spring Boot` `PostgreSQL` `MyBatis` `REST API`

### Project Experience

`JPA` `QueryDSL` `Redis` `JWT` `OAuth 2.0` `MapStruct` `Kotest` `Docker`

### Studied & Implemented

`gRPC` `GraphQL` `RabbitMQ` `API Gateway` `Multi Module`

### Additional Experience

`JavaScript` `Android` `MySQL` `Git` `GitHub`

---

## Education

* **한국방송통신대학교** 컴퓨터과학과
  2024.03 ~ 2026.08 · 졸업

* **메가스터디 아카데미** 백엔드 웹 개발 전문가 과정
  2023.01 ~ 2023.09 · 수료

* **영진전문대학교** 전자정보통신계열 IT소재 전공
  2016.03 ~ 2022.02 · 졸업

---

## Contact

* **Email:** [wlsrb97@naver.com](mailto:wlsrb97@naver.com)
* **GitHub:** [github.com/shin-jingyu](https://github.com/shin-jingyu)

---

<a href="https://github.com/devxb/gitanimals">
  <img src="https://render.gitanimals.org/farms/{shin-jingyu}"/>
</a>
