## Hi, I'm Park — Backend Developer

Spring 기반으로 안정적인 서버와 데이터 중심 시스템을 설계하는 백엔드 개발자입니다.  
기능 구현에 앞서 데이터 흐름, 트랜잭션 경계, 유지보수 비용을 먼저 고려하며 설계합니다.

-   트랜잭션 경계 설정과 데이터 정합성을 중심으로 서버 로직 설계 경험
    
-   ORM의 장단점을 구분해 사용하며, 성능·가독성이 중요한 영역은 구조적으로 분리
    
-   운영 환경을 가정한 예외 처리, 로그 설계, 성능 저하 원인 분석에 관심
    

Contact: qseft5231@gmail.com


## What I Focus On

-   Spring Boot 기반 REST API 설계 및 계층 분리
    
-   JPA/Hibernate 사용 시 발생하는 성능 이슈 분석 및 개선
    
-   RDB(MySQL) 기반 데이터 모델링과 조회 구조 최적화
    
-   OS, 네트워크 개념을 서버 동작 흐름과 연결해 이해하는 학습 방식
    


## Tech Stack

### Core

-   Java 17
    
-   Spring Boot
    
-   Spring Data JPA
    
-   MySQL
    

### Experience

-   Node.js, Express.js (Raw SQL, Custom Mapper)
    
-   Kotlin
    
-   React / Vue.js (클라이언트 협업 경험)
    
-   PostgreSQL, Oracle
    

### Tools

-   Git / GitHub
    
-   Docker
    
-   IntelliJ IDEA
    
-   Postman
    


## Featured Projects

### 애드벌룬 (Spring Boot 기반, JPA 성능 이슈 개선 경험)

Spring Boot 기반 게시판 서비스 백엔드 개발

-   게시글 목록 조회 시 발생하던 N+1 문제 분석
    
-   Fetch Join을 적용해 연관 엔티티를 단일 쿼리로 조회하도록 개선
    

**결과**

-   리스트 조회 기준 쿼리 11회 → 1회로 감소
    
-   DB I/O 감소를 통한 응답 속도 및 안정성 개선

----------

### 장애인 활동 지원 매칭 플랫폼 (Node.js 기반, 복잡한 검색 조건 처리 경험)

Node.js 기반 매칭 서비스 백엔드 개발

-   다중 조건(지역, 장애 유형, 활동 시간 등)이 조합되는 복잡한 검색 기능 구현
    
-   ORM으로 관리하기 어려운 영역을 Raw SQL 기반 구조로 분리
    
-   도메인별 SQL 파일 관리 + Custom Mapper 유틸리티 직접 구현
    

**결과**

-   SQL 수정 시 비즈니스 로직 변경 없이 대응 가능한 구조 확보
    
-   ORM 오버헤드 제거로 조회 성능과 유지보수성 동시 개선
    

## Currently Learning

-   Operating System
    
    -   프로세스 / 스레드
        
    -   동기화, 컨텍스트 스위칭을 서버 동작 관점에서 이해
        
-   Advanced Spring
    
    -   트랜잭션 전파
        
    -   AOP 활용
        
    -   테스트 코드 설계
        

## GitHub Activity

![GitHub Activity](https://github-readme-activity-graph.vercel.app/graph?username=kimbab2066&theme=github-dark)


## Development Philosophy

-   빠르게 구현하는 코드보다, **문제를 반복하지 않는 구조**
    
-   기술 선택은 유행이 아니라 **요구사항과 유지보수 비용 기준**
    
-   백엔드 개발자는 기능 구현과 함께 **시스템 안정성에 책임을 져야 한다고 생각**
