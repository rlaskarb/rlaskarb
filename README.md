# 안녕하세요.

Java 풀스택과 UI/UX 퍼블리싱을 함께 익히며, 매일 실력을 키워가는 사용자 중심 개발자입니다.

<hr/><br/>

# 🛠 기술 스택

| 분류         | 사용 기술 및 프레임워크                                           | 활용 목적 및 역할                        |
|--------------|--------------------------------------------------------------------|------------------------------------------|
| **프로그래밍 언어** | Java, JavaScript                                                  | 주요 개발 언어로 백엔드 및 프론트 구현  |
| **프론트엔드**     | React.js(Redux, Router), Bootstrap, JQuery, HTML5, CSS3, Thymeleaf | SPA 및 SSR UI 구성, 반응형 인터페이스 구현  |
| **백엔드**         | Spring Boot, Spring Framework, Spring Security(JWT), Servlet, JSP, Node.js, Rest API | 비즈니스 로직 구현, 인증/인가, REST API 설계 |
| **데이터베이스**   | MySQL, Oracle, MyBatis, JDBC, JPA, Spring Data JPA              | 데이터 모델링 및 CRUD 기능 구현    |
| **형상 관리**      | Git, GitHub                                                      | 소스 버전 관리 및 팀 협업    |
| **협업/설계 도구** | Figma, Notion, Miro, Postman                                     | UI 설계, API 문서화 및 테스트, 협업 문서 관리 |
| **배포/운영**      | Railway                                                         | 백엔드/프론트엔드 애플리케이션 배포 및 호스팅 |





<br/><hr/><br/>

# 📂  프로젝트

<br/>

# ⛱️ 보험사 그룹웨어 시스템 (2024.11 ~ 2025.01)


## 📌 개요

보험사의 내부 업무 효율화를 위한 그룹웨어 시스템으로,  
인사관리, 전자결재, 계약관리 등 핵심 기능을 구현하였습니다.

## 🛠 사용 기술

- 백엔드: Java, Spring Boot
- 프론트엔드: Thymeleaf, Bootstrap
- 데이터베이스: MySQL

## ⚙️ 직접 구현한 핵심 기능

- 고객/상품/계약 등록
- 실적 분석 대시보드
- 만기 고객 자동 조회 및 알림
  
[👉 GitHub 바로 가기](https://github.com/rlaskarb/LYNK_LIFE)





##
<br/>

# 🍺 맥주 생산 ERP 시스템 (2025.02 ~ 2025.03)

## 📌 개요

맥주 제조 공정의 생산부터 출하까지 전 과정을 직관적으로 관리할 수 있도록 설계한 ERP 시스템입니다.  
생산계획 → 작업지시 → 공정 실행 → 실적 관리로 이어지는 흐름을 구현했으며,  
현장 중심의 생산 관리 UX에 중점을 두었습니다.


## 🛠 사용 기술

- 백엔드: Java, Spring Boot, Spring Data JPA
- 프론트엔드: React.js, Redux, React Router
- 데이터베이스: Oracle
- API: REST API

## ⚙️ 직접 구현한 핵심 기능

- 작업지시 기반 공정 흐름 자동화  
- 공정별 원재료·수율 자동 연산 및 조건별 전환 처리  
- LOT 단위 생산 기록 및 PDF 작업지시 연동

[👉 GitHub 바로 가기 ](https://github.com/rlaskarb/QualityCore)  

<hr/> <br/>

# 📸 프로젝트 대표 이미지


#### LYNK_LIFE | 보험회사 그룹웨어 | 계약등록 ![계약등록](https://github.com/user-attachments/assets/c66060b3-a93c-47b9-8061-1d6b2e305aa6)
<details>
<summary>보험 계약을 등록 및 실적현황판 기능입니다</summary>

  <br/>
  
📄 보험 계약을 등록하는 기능입니다.  
사전에 등록된 **상품 정보, 고객 정보, 설계사 정보**를 불러와  
작업자가 직접 입력하는 실수를 최소화하고,  
등록된 계약은 **홈 화면 실적 현황판에 실시간으로 반영**되어  
**계약 금액과 계약 건수**를 바로 확인할 수 있습니다.

</details>

[👉 GitHub 바로 가기](https://github.com/rlaskarb/LYNK_LIFE)

<br/><hr/>

#### QualityCore | 맥주생산 ERP | 끓임 공정 ![끓임공정gif](https://github.com/user-attachments/assets/cb385815-b42e-4291-8ce5-40462a2a9556)
<details>
<summary>홉 투입 타이밍 및 온도 변화 시각화를 위한 타이머 기반 공정 흐름 입니다.</summary>

  <br/> 

🔥 끓임공정은 여과된 맥즙에 홉을 투입한 후, 고온에서 끓이는 단계입니다.

공정은 설정된 온도에 도달하면 모달창이 표시되며, 사용자가 확인하면 끓임공정이 시작됩니다.<br/>
온도 변화는 타이머 기반 구조로 설계되어, 끓임 설비의 온도 변화를 실시간으로 시각화할 수 있도록 구성했습니다.<br/>

초기 워트량은 **여과공정에서 최종 회수된 워트량을 기준** 으로 자동 설정되며,<br/>
홉 투입 정보는 **작업지시서에 등록된 자재 정보를 기반** 으로 자동 불러옵니다.<br/>
첫 번째와 두 번째 홉의 투입량이 자동으로 입력되어, 작업자는 이를  확인할 수 있습니다.<br/>

끓임 종료 시, **끓임 손실량(초기 워트량의 5%)이 자동 계산되어 표시되며** ,<br/>
최종 끓임 후 워트량은 초기 워트량 - 끓임 손실량으로 실시간 산출되어 업데이트됩니다.<br/>

이 과정을 통해 작업자는 홉 투입 시점과 수율 변화 상황을 직관적으로 파악할 수 있습니다.

</details>

[👉 GitHub 바로 가기 ](https://github.com/rlaskarb/QualityCore)  

<br/>


