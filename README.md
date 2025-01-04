# Kim Byoung Jun
### Software Developer | Full-Stack Engineer
## Hi there 👋

# About Me
-  I’m currently working on [current project or technology focus]

# Professional Experience

# Projects

### **광고 매핑 시스템 설계 및 구축** | 2022.01 - 2022.05  
- **개요**: 광고 매체 데이터와 캠페인 데이터를 매핑하여 실시간 광고 집행 및 성과 측정을 위한 **광고 매핑 시스템**을 설계 및 구현.
- **역할**:
  - **시스템 설계**: Laravel Blade, Collection, QueryBuilder를 활용하여 광고 매핑 시스템 개발.  
  - **비동기 처리**: Ajax 기반 비동기 ProgressBar 구현으로 사용자 작업 진행 상태를 실시간 시각화.  
  - **Batch 처리**: Laravel Artisan Console과 Linux Crontab을 사용한 대규모 Batch 작업 자동화 및 최적화.  
  - **DB 부하 방지**: PHP usleep을 이용해 대량 데이터 처리 시 DB 부하를 최소화.  
  - **데이터 관리**: MySQL Procedure를 활용한 레거시 데이터 삭제 및 관리 최적화.  
- **성과**:
  - **처리량 확장**: 광고 매핑 처리 성능을 **500만 건/일 → 4억 건/일**로 향상.  
  - **안정성 확보**: 월 평균 **150억 PV** 트래픽 환경에서 안정적으로 실시간 데이터를 저장/삭제 처리하는 시스템 구축.  
  - **운영 효율성**: MySQL Procedure를 통한 데이터 삭제 작업 시간을 **90% 단축**.
- **주요 기술 스택**: Crontab, Procedure, Laravel Artisan Console, QueryBuilder, MySQL, Javscript

### **광고 설정 시스템 고도화** | 2021.01 - 2021.09

- **개요**: 광고 송출 과정에서 발생하는 약 2%의 광고 미송출 현상을 개선하기 위해 광고 설정 시스템을 리엔지니어링했습니다. 주도적으로 다양한 팀과 협업하여 시스템 성능을 최적화하고 안정성을 강화하여 광고 누수를 최소화했습니다.
- **역할**:
  - **시스템 리엔지니어링**:
    - 광고 설정 로직 재구성 및 최적화.
    - 미송출 현상을 추적하고 문제 원인을 분석하여 근본적인 구조 개선.
  - **접근 제어 및 인증 개발**:
    - **Laravel Authentication**을 활용한 사용자 인증 기능 개발.
    - **Laravel Middleware**를 이용해 Router 접근 제어를 구현하여 시스템 보안 강화.
  - **오류 알림 기능 개발**: **Slack Incoming Webhook**과 **Laravel Notifications**를 활용해 실시간 오류 알림 시스템 구축.
  - **쿼리 최적화**: **Laravel Query Builder**를 사용해 성능 향상을 위한 데이터 처리 구현.
  - **UI 및 프론트엔드 개발**: **Laravel Blade**와 **jQuery**를 이용한 광고 설정 시스템의 사용자 인터페이스 개발.
  - **성과**:
    - 광고 미송출 비율을 **2% → 0.5%**로 획기적으로 감소시켜 광고 효율성을 대폭 향상.
    - 시스템 가용성과 안정성 강화로 운영 비용 절감 및 광고주 신뢰도 제고.
  - **주요 기술 스텍**: Middleware, Notifications, Slack Webhook, PHP 7.2(Laravel 5.5), MySQL, JavaScript(jQuery)

### **CDP(Customer Data Platform) 시스템 개발** | 2020.06 - 2020.11

  - **개요**: CDP(Customer Data Platform) 시스템의 일부 모듈을 설계 및 개발하여 사용자 로그인, 캠페인 생성, 문자/SNS 전송 기능과 대시보드 시스템을 구현했습니다.
  - **기여한 역할**:
    - **개발 환경 구축**: **Docker Compose**를 활용하여 개발 환경 구성 및 통합 테스트 환경 구축.
    - **CI/CD 파이프라인 구축**: **GitLab CI/CD**를 통해 운영 서버에 자동화된 배포 환경 설정.
    - **인증 시스템 구현**: **Access Token** 기반의 API 인증 및 외부 서비스 로그인 연동 기능 구현.
    - **캠페인 생성 및 관리**: Laravel Blade와 Query Builder를 사용하여 캠페인 생성 및 문자/SNS 전송 기능 개발.
  - **성과**:
    - CI/CD 및 개발 환경 자동화를 통해 팀 생산성 향상에 기여하여 프로젝트가 초기에 계획된 일정보다 빠르게 서비스가 정상 오픈

### **SSP(Supply Side Platform) 시스템 개발** | 2019.07 - 2019.12

- **개요**: 디지털 광고 RTB(Real-Time Bidding) 기반으로 광고 매체의 수익성을 극대화하고, 퍼블리셔가 효율적으로 광고 지면을 관리할 수 있는 고성능 SSP 시스템 구축.
- **역할**:
  - **관계형 데이터베이스 설계**: 광고 지면 및 사용자 데이터를 효율적으로 관리하기 위한 DB 구조 설계.
  - **회원 및 권한 관리 시스템 개발**: **Laravel Auth**를 이용한 사용자 인증 및 권한 관리 구현.
  - **RTB 데이터 검증 시스템 구축**: 외부 RTB 데이터와 내부 데이터 간의 정합성 검증 및 처리 로직 개발.
  - **광고 매체 지면 생성 및 관리**: **Laravel Blade**, **Javascript** 를 사용하여 사용자 친화적인 관리 인터페이스 개발.
  - **대시보드 설계**: 실시간 데이터 모니터링 및 광고 성과 통계를 제공하는 대시보드 개발.
- **성과**:
  - 월 평균 **30억 건의 입찰 요청**을 처리할 수 있는 안정적인 시스템 구축.
  - **1년간 운영 중 오류 0회**를 달성하여 높은 신뢰성과 안정성을 입증.
- **주요 기술 스택**: RESTfull API, Auth, QueryBuilder, PHP 7.2(Laravel 5.5), MySQL, Javscript(JQuery)


# Skills

# Let's Connect


<!--
**aquaheyday/aquaheyday** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
