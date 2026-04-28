# **🤖 AX Control Tower: Master Prototype Prompt (v2.1)**

당신은 중견기업용 'AX Control Tower'를 개발하는 시니어 풀스택 개발자입니다.

기존 기능에 **'베스트 과제 DB(Hall of Fame)'** 메뉴를 추가하여 단일 파일의 React 프로토타입을 작성하세요.

### **1\. 기술 스택 & 환경**

* React 18+, Tailwind CSS, Lucide React, Recharts  
* Firebase SDK 연동 (Auth, Firestore 실시간 리스너 필수)  
* 환경변수(\_\_firebase\_config, \_\_app\_id) 기반 초기화

### **2\. 핵심 추가 기능: 베스트 과제 DB**

* **명예의 전당 배너:** 분기별 최고의 ROI를 기록한 과제 강조 노출.  
* **아카이브 리스트:** 소스코드(Zip), MD 문서, 개발 가이드가 포함된 카드 UI.  
* **검색 및 필터:** 부서별, 태그별(Python, 자동화, RAG 등) 필터링 기능.  
* **업로드 연동 UI:** PC 업로드 및 Drive(Google/MS) 선택 모달 시뮬레이션.  
* **소셜 인터랙션:** '좋아요' 및 '댓글 수' 표시로 사내 공유 문화 활성화.

### **3\. 기존 기능 유지 (Phase 2\)**

* 보안 서약 모달 및 실시간 프롬프트 자가 진단 엔진.  
* 수준별 교육 센터(초/중/상) 및 4단계 과제 칸반(아이디어\~배포).  
* 모델, 인력, 인프라 통합 리소스 대시보드.

### **4\. 보안 및 안정성 (CRITICAL)**

* ReferenceError: Settings is not defined가 발생하지 않도록 모든 아이콘을 명시적으로 임포트하세요.  
* 데이터 렌더링 시 객체({$$typeof...})가 직접 출력되지 않도록 String() 처리나 속성 접근을 철저히 하세요.  
* Firebase 경로: /artifacts/{appId}/public/data/best\_tasks 사용.

### **5\. 출력 형식**

* 모든 로직과 스타일을 포함한 단일 App.jsx 파일로 작성하세요.  
* 주석은 한글로 작성하고, '베스트 과제 DB'의 자산화 로직을 상세히 설명하세요.