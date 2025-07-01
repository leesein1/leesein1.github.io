# 경력기술서

## 📌 프로젝트명: 열차운행정보 분석 웹 제작
**기간:** 2024.05 ~ 2025.03  
**성과:** SignalR 기반 실시간 고장 알림 시스템 구축 → 평균 1초 이내 사용자 화면 자동 반영  

### 🔧 주요 업무
- 차량에 부착된 열차운행정보장치로 부터 수집되는 실시간 운행, 고장, 적산 데이터등을 기반으로, 노선도 기반 열차 위치 시각화 및 고장 정보 알림 기능을 갖춘 분석 웹 플랫폼 개발
- 실시간 고장 알림 처리 흐름 설계 및 UI 자동 갱신 기능 구현
- 실시간 해당 열차의 기관사 화면과 같은 화면 관제 기능 구현
- 노선도 위 열차 아이콘 실시간 위치 표시
- 장애 이력 통계 / 검색 필터링 기능 개발  
- 사용자 피드백 반영한 인터페이스 개선 진행  

### 🧑‍💻 역할
1. 고장 발생 데이터 수신 및 통합 관리 부터 UI 알림까지 전 과정 단독 구현  
1-1. SignalR 도입을 제안하고 직접 설계 및 구현  
2. 고장 알림 자동화 및 위치 갱신 기능으로 관제 업무 생산성 향상  
3. 차량 고장 발생 시 조치 내역, 소거 시간 등 정보를 철도공사 ERP에 연계 전송하여 고장 처리 이력 자동 통합 관리
4. 코레일 사용자 피드백을 받아 반복 개선 및 협업 대응  

### 🛠️ 주요 사용 기술
<p>
  <img src="https://img.shields.io/badge/.NET Core 3.1-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/SignalR-5C2D91?style=for-the-badge&logo=signalr&logoColor=white" />
  <img src="https://img.shields.io/badge/Leaflet-199900?style=for-the-badge&logo=leaflet&logoColor=white" />
  <img src="https://img.shields.io/badge/MS SQL-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL%20Dependency-6E4B7E?style=for-the-badge" alt="SQL Dependency">
  <img src="https://img.shields.io/badge/Service%20Broker-6E4B7E?style=for-the-badge" alt="Service Broker">
  <img src="https://img.shields.io/badge/IIS-0078D7?style=for-the-badge&logo=windows&logoColor=white" />
</p>


### 📈 성과
- 평균 알림 반영 시간 1초 이내  
- 노선도 기반 트래킹으로 관제 효율 30% 이상 향상  
- 코레일 사용자 만족도 조사에서 ‘시각화 UI와 알림 기능’ 항목 90% 이상 긍정 평가
- 현장 정비 인력을 위한 모바일 맞춤 UI 및 신규 시스템 기획 완료
- 차기 차량정비 플랫폼 연계 개발안 기획 완료 후 퇴사

### 🧩 문제 해결 사례
- **장기 미사용 시 Chrome에서 SignalR 연결이 끊어지는 문제 해결**  
  → Chrome 브라우저의 장기 유휴 연결 최적화 정책에 따라 SignalR 연결이 끊기는 현상 발생 → 주기적 ping 및 자동 재연결 로직 구현으로 문제 해결

---

## 📌 프로젝트명: 사내전산 알림 시스템 구축
**기간:** 2024.02 ~ 2024.04  
**성과:** 2023년 사내 개선 건의 1위였던 업무 누락 문제를 해소하기 위해, 최초의 실시간 자동 알림 시스템을 구축함  

### 🔧 주요 업무
- 화재 감지기, 물탱크 수위, 수리요청 등 PLC 기반 경보 및 사내 복지(카페 주문/제조 완료 등) 알림 처리 누락 문제 해결
- 카카오톡 공식 딜러사 ‘비즈톡’의 API를 활용하여 메시지 송신 및 결과 수신 구현
- 기존 전산 시스템으로부터 알림용 테이블에 데이터 저장
- 메시지 전송 결과 로그를 남기고 확인 가능한 페이지 제작
- 다양한 내부 이벤트에 대해 자동으로 반응하는 상시 처리 구조 구성

### 🧑‍💻 역할
1. 사내 시스템과 연결된 알림용 테이블 구성 및 트리거 설계  
1-1. 비즈톡 API 연동을 통한 메시지 송신 및 응답 결과 처리  
2. C# 윈도우 폼으로 상시 대기형 프로그램 구현  
3. 전송 로그 저장 및 웹 페이지로 확인 가능한 알림 이력 시스템 개발  
4. 토큰 오류, 중복 발송 방지 등 운영 환경 이슈 직접 해결  

### 🛠️ 주요 사용 기술

<div>
  <img src="https://img.shields.io/badge/C%23-%23239120?style=for-the-badge&logo=c-sharp&logoColor=white" alt="C#">
  <img src="https://img.shields.io/badge/.NET%206.0-512BD4?style=for-the-badge&logo=.net&logoColor=white" alt=".NET 6.0">
  <img src="https://img.shields.io/badge/Windows%20Forms-0078D7?style=for-the-badge&logo=windows&logoColor=white" alt="Windows Forms">
  <img src="https://img.shields.io/badge/MSSQL-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" alt="MSSQL">
  <img src="https://img.shields.io/badge/SQL%20Dependency-6E4B7E?style=for-the-badge" alt="SQL Dependency">
  <img src="https://img.shields.io/badge/Service%20Broker-6E4B7E?style=for-the-badge" alt="Service Broker">
  <img src="https://img.shields.io/badge/Kakao%20BizTalk-FFCD00?style=for-the-badge&logo=kakao&logoColor=black" alt="Kakao BizTalk API">
</div>

### 📈 성과
- 사내 최초 실시간 알림 자동화 시스템 도입
- 개선 건의 1위 항목 실현으로 업무 누락 이슈 해소
- 수동 전달 없이 PLC 알림, 음료 주문, 품질 요청 등 자동 반영

### 🧩 문제 해결 사례
- 토큰 만료 시 자동 재발급 처리 구현
- 단기간 중복 발송 방지 로직 추가
- 실패 응답 로그 기록 및 재전송 정책 마련

---


## 📌 프로젝트명: 사내전산 유지보수 및 소규모 시스템 개선 모음
**기간:** 2023.08 ~ 2025.05  
**성과:** 다양한 사내 업무 효율 향상 요구에 대응하여, 유지보수 외에도 10여 개 이상의 소규모 개선 시스템을 설계 및 구현하여 누락 감소 및 업무 자동화에 기여

### 🔧 주요 업무
- **계측기, 설비공구, 자재 등 사내 물품 관리 시스템 개발**  
  - 각 항목 별 입출고/폐기/점검일 등을 통합 관리하고 상태 이력 기록 기능 제공  
- **PLC 기반 설비 제어 및 실시간 모니터링 시스템 개선**  
  - 설비 상태 변화 감지 시 카카오 알림 자동 발송 기능 연동  
- **사내 음료 카페 주문/제조 관리 시스템 개발**  
  - 주문 접수부터 제조 완료까지 관리하고, 사용자별 주문 로그 통계 제공  
- **전력 시세 수집 자동화 프로그램 제작 (윈도우 기반)**  
  - 일간/월간 SMP(계통한계가격) 정보를 크롤링하여 엑셀 자동 저장  
- **기존 ASP 기반 시스템 내 기능 유지보수 및 페이지 추가 개발**  
  - 클래식 ASP 환경에서 다수 페이지 및 기능 개선, DB 연동 및 배포까지 단독 진행

### 🧑‍💻 역할
1. Classic ASP 기반 사내 시스템 유지보수 및 기능 신규 개발  
2. MSSQL과 연동되는 ASP 페이지 내 쿼리 최적화 및 트랜잭션 처리  
3. PLC 상태 데이터를 기반으로 하는 설비 제어 페이지 신규 구현  
4. 각 부서 담당자와의 협업을 통해 직접 요구사항 수집 및 대응  
5. 단독 운영 중인 윈도우 프로그램을 통해 1주 내 신규 기능 완성  

### 🛠️ 주요 사용 기술
<div>
  <img src="https://img.shields.io/badge/Classic%20ASP-1D4D7D?style=for-the-badge" alt="Classic ASP">
  <img src="https://img.shields.io/badge/MSSQL-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" alt="MSSQL">
  <img src="https://img.shields.io/badge/IIS-0078D7?style=for-the-badge&logo=windows&logoColor=white" alt="IIS">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS">
  <img src="https://img.shields.io/badge/Windows%20Forms-0078D7?style=for-the-badge&logo=windows&logoColor=white" alt="Windows Forms">
</div>

### 📈 성과
- 정기 점검 누락률 0건 유지 (물품 관리 시스템 도입 이후)
- PLC 상태 이상 → 카카오톡 전송 구조로, 설비 이상 발생 시 즉시 알림 및 대응 가능 체계 구축 
- SMP 수집 자동화로 일/월간 데이터 DB 저장 -> 수기 저장 시간 단축
- 수기 작성이던 물품 관리 대장을 시스템화하여, 분실·누락 이슈 예방 및 조회 편의성 향상

### 🧩 문제 해결 사례
- ASP 기반 시스템 내 비정규화된 데이터 구조 정리 및 코드 리팩토링
- PLC 상태 테이블 폴링 방식 → SQL Dependency로 전환하여 DB 부하 감소 및 실시간 반응 속도 확보
- Chrome의 User-Agent 정책 변경으로 크롤링 실패 -> User-Agent 명시적 설정으로 해결