#  안녕하세요! 웹 개발자 지망생 김남규입니다.
꾸준한 학습과 프로젝트 경험을 바탕으로, 사용자 중심의 웹 서비스를 만드는 개발자가 되고자 합니다.
<hr/>

## 🛠 기술 스택

| 분류            | 사용 기술                                 | 활용 목적 및 역할 |
|-----------------|-------------------------------------------|------------------|
| **Frontend**     | HTML, CSS, JavaScript                     | 기본 UI 구성 |
|                 | React                                     | SPA 구조 구현 |
|                 | Thymeleaf                                 | 서버사이드 렌더링 템플릿 |
| **Backend**      | Java, Spring Boot                         | REST API 설계 |
|                 | Node.js                                   | 경량 API 서버 및 실험적 기능 개발 |
| **Database**     | MySQL, Oracle                             | 데이터 저장 및 쿼리 |
| **Dev & Tool**   | Git, GitHub, Notion, Figma                | 협업, 문서화, UI 기획 |
|                 | Postman                                   | API 테스트 |


<br/><hr/>

## 📂 프로젝트
### [QualityCore](https://github.com/rlaskarb/QualityCore)

#### 🍺 맥주생산 ERP 시스템 | 생산계획 -> 작업 지시 -> 생산공정 실행 및 실시간 모니터링 -> 생산실적관리로 이어지는 구조입니다.
#### ✨ 담당 기능: DBA 및 생산 공정 관리 흐름 (10개 공정 구현)

##

### [LYNK_LIFE](https://github.com/rlaskarb/LYNK_LIFE)

#### 보험회사 그룹웨어 | 업무 효율성과 관리 편의성을 높이기 위해 계약 정보의 체계적 관리에 초점을 두었습니다.
#### ✨ 담당 기능: DBA 및 계약등록,고객등록,상품등록,계약조회,만기고객조회, 월별 실적현황

<hr/>

### 📸 프로젝트 대표 이미지

<br/>

#### QualityCore | 맥주생산 ERP | 끓임 공정 ![끓임공정gif](https://github.com/user-attachments/assets/cb385815-b42e-4291-8ce5-40462a2a9556)
<details>
<summary>홉 투입 타이밍 및 온도 변화 시각화를 위한 타이머 기반 공정 흐름 구현</summary>
  
끓임공정은 여과된 맥즙에 홉을 투입한 후, 고온에서 끓이는 단계입니다.

공정은 설정된 온도에 도달하면 모달창이 표시되며, 사용자가 확인하면 끓임공정이 시작됩니다.<br/>
온도 변화는 타이머 기반 구조로 설계되어, 끓임 설비의 온도 변화를 실시간으로 시각화할 수 있도록 구성했습니다.<br/>

초기 워트량은 **여과공정에서 최종 회수된 워트량을 기준** 으로 자동 설정되며,<br/>
홉 투입 정보는 **작업지시서에 등록된 자재 정보를 기반** 으로 자동 불러옵니다.<br/>
첫 번째와 두 번째 홉의 투입량이 자동으로 입력되어, 작업자는 이를  확인할 수 있습니다.<br/>

끓임 종료 시, **끓임 손실량(초기 워트량의 5%)이 자동 계산되어 표시되며** ,<br/>
최종 끓임 후 워트량은 초기 워트량 - 끓임 손실량으로 실시간 산출되어 업데이트됩니다.<br/>

이 과정을 통해 작업자는 홉 투입 시점과 수율 변화 상황을 직관적으로 파악할 수 있습니다.
</details>


<br/>

##

<br/>

#### LYNK_LIFE | 보험회사 그룹웨어 | 계약등록 ![계약등록](https://github.com/user-attachments/assets/c66060b3-a93c-47b9-8061-1d6b2e305aa6)

보험 계약을 등록하는 기능입니다.  
사전에 등록된 **상품 정보, 고객 정보, 설계사 정보**를 불러와  
작업자가 직접 입력하는 실수를 최소화하고,  
등록된 계약은 **홈 화면 실적 현황판에 실시간으로 반영**되어  
**계약 금액과 계약 건수**를 바로 확인할 수 있습니다.

<br/><hr/>

