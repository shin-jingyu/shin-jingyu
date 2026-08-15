# 신진규 | Backend Developer

Java와 Spring을 기반으로 서버 애플리케이션을 개발하고 있습니다.

망 분리 환경에서 **Android–DMZ–Core 간 API 연동**, **출입 시스템과 MDM 간 상태 동기화**, **PostgreSQL Replication 환경 구축 및 운영**을 경험했습니다.

기능 요청을 바로 구현하기보다 기준이 되는 데이터와 시스템별 역할을 먼저 확인합니다. 연동에 제약이 있는 경우에는 필요한 조건과 지원 사항을 정리해 관련 담당자와 구현 범위를 조율합니다.

---

## Experience Highlights

* Android–DMZ–Core 간 API 연동 구조 설계 및 개발
* 출입 이벤트 기반 사용자 상태 판별과 MDM 보안 정책 제어
* PostgreSQL Replication 환경 구축 및 운영

---

## Work Experience

### 모피어스 시큐리티

**Backend Developer**
2024.03 ~ 2026.07

`Java` `Spring` `PostgreSQL` `JavaScript` `Android`

### 출입 게이트 연동형 MDM 제어 시스템

출입 게이트에서 발생한 이벤트를 기반으로 사용자의 출입 상태를 판별하고, 모바일 기기의 보안 정책을 자동으로 적용하거나 해제하는 시스템을 개발했습니다.

망 분리 환경에서 출입 시스템의 이벤트가 내부 MDM 시스템까지 전달될 수 있도록 Android 애플리케이션, DMZ 중계 서버, Core 내부 서버의 역할과 통신 흐름을 정의했습니다.

#### 주요 업무

* Android–DMZ–Core 간 API 통신 구조 설계 및 개발
* 각 서버의 역할과 요청·응답 데이터 흐름 정리
* 출입 게이트 통과 이벤트 수신 및 사용자 출입 상태 판별
* 출입 상태에 따른 모바일 기기 보안 정책 적용·해제 로직 개발
* 출입 시스템과 MDM 간 사용자 및 단말 정보 연동
* PostgreSQL 데이터베이스 및 Replication 환경 구축
* 운영 환경의 API 연동 및 데이터베이스 이슈 대응

#### 요구사항 및 연동 조율

출입 시스템과 MDM은 관리하는 데이터와 운영 환경이 달랐기 때문에 API만 추가해서는 전체 기능을 완성하기 어려웠습니다.

출입 상태를 판별하는 데 필요한 이벤트 규격과 사용자 식별값을 확인하고, 각 시스템에서 처리할 데이터와 통신 방향을 정리했습니다. 서버 또는 네트워크 영역의 지원이 필요한 경우에는 구현에 필요한 조건을 구체화해 관련 담당자와 협의했습니다.

이를 바탕으로 출입 이벤트 수신부터 사용자 상태 판별, MDM 정책 변경까지 이어지는 연동 흐름을 구현했습니다.

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
* 서비스 아이디어를 바탕으로 MVP 기능 범위 정의
* JWT 기반 사용자 인증 기능 구현
* OAuth 2.0 기반 소셜 로그인 적용
* Redis를 활용한 데이터 캐싱 구조 설계
* GitHub Issue와 Pull Request 기반 개발 및 코드 리뷰
* Figma와 Notion을 활용한 요구사항과 역할 분담 관리

아이디어 단계의 서비스를 실제 개발 가능한 기능으로 나누고, 팀원들과 도메인 모델과 MVP 범위를 구체화했습니다.

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

기능 구현 결과뿐 아니라 구현 배경과 변경 범위를 Pull Request에 기록해, 팀원이 코드의 맥락과 변경 의도를 함께 이해할 수 있도록 개발하고 있습니다.

---

## Study

### Spring · Backend Study

* **기간:** 2025.02.17 ~ 현재
* **방식:** 학습, 구현, 발표, 기술 토론

Spring과 JPA를 기반으로 백엔드 기술을 직접 구현하고, 기존 방식과의 차이와 실제 적용 방법을 토론하는 스터디입니다.

#### 주요 활동

* Spring Framework와 JPA 핵심 개념 학습
* gRPC 기반 서비스 간 통신 구현
* GraphQL API 구현
* RabbitMQ 기반 비동기 메시지 처리
* 멀티모듈 구조에서 인증 서버 분리
* 인증 서버와 API Gateway 연계
* 관심 기술 발표 및 코드 기반 검증

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

