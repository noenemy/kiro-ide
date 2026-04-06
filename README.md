## Introduction to ESEP Kiro IDE Workshop

ESEP는 Enterprise Support Experts Program의 약자로서, AWS Enterprise Support 고객사들의 워크로드 운영에서 얻은 경험과 베스트 프랙티스 사례를 다른 Enterprise Support 고객사분들께 전파하고 도움을 드리기 위한 컨설팅 프로그램입니다.

ESEP 프로그램 중에 하나로서 이 실습에서는 Kiro IDE를 이용해서 바이브 코딩 및 스펙기반 코딩을 하는 방법을 알아보도록 하겠습니다.

다른 ESEP 및 Gen AI 워크샵을 원하실 경우 담당 Technical Account Manager에게 문의주시기 바랍니다.

본 실습은 다음과 같은 내용을 포함합니다. 

<li>Lab 1 - Kiro IDE 실습</li>
<li>Lab 2 - Kiro IDE 실습</li>
<li>Lab 3 - Kiro IDE 실습</li>

<img src="https://kiro.dev/images/home/cli.png" width="600">

## Kiro IDE 소개
Kiro는 AI 기반의 개발 환경(IDE)으로, 개발자가 코드를 작성하고 설계하는 전 과정을 지원합니다.

### 핵심 기능

### 1. Spec (스펙 기반 개발)

기능 개발을 요구사항 → 설계 → 구현 태스크의 3단계로 구조화합니다.
에이전트와 반복적으로 협업하며 점진적으로 기능을 완성해 나갑니다.
복잡한 기능도 체계적으로 관리할 수 있어 팀 단위 개발에 적합합니다.

### 2. Steering (스티어링)

프로젝트의 코딩 표준, 빌드/테스트 방법, 팀 규칙 등을 마크다운 파일로 정의합니다.
AI가 코드를 생성하거나 수정할 때 이 규칙을 자동으로 참고합니다.
항상 적용 / 특정 파일 매칭 시 적용 / 수동 적용의 세 가지 모드를 지원합니다.

### 3. Hooks (에이전트 훅)

IDE 이벤트에 반응하여 자동으로 에이전트 액션을 실행합니다.
예시: TypeScript 파일 저장 시 자동 린트 실행, 태스크 완료 후 테스트 실행
파일 변경, 프롬프트 제출, 도구 사용 전/후 등 다양한 이벤트를 지원합니다.

### 4. MCP (Model Context Protocol) 연동

외부 MCP 서버를 연결하여 AI의 기능을 확장할 수 있습니다.
설정 파일 하나로 다양한 도구와 데이터 소스를 통합합니다.

### 5. 자율성 모드

모드	설명
- Autopilot	AI가 파일을 자율적으로 수정
- Supervised	변경 사항 적용 후 되돌릴 기회 제공

## 주요 활용 시나리오
- 코드 작성, 수정, 리팩토링
- 버그 분석 및 디버깅
- 프로젝트 구조 탐색 및 이해
- 셸 명령어 실행 및 자동화
- 웹 검색을 통한 최신 기술 정보 조회
- 이미지, PDF 등 문서 첨부를 통한 컨텍스트 공유
