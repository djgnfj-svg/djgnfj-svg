# **Summary**

안녕하세요. 실무에서 테스트와 성능측정을 자동화하여 비즈니스 가치를 창출한 백엔드 개발자 송영재 입니다.

Chips&Media에서 Python script로 제품 테스트에 들어가는 수작업 시간을 제거하고 성능 측정 속도를 60% 향상시킨 경험이 있습니다.

FastAPI를 활용해 실시간 서비스를 만들었고, Django를 활용한 AI 웹 애플리케이션을 설계하고 AWS에 배포 및 운영하고 있습니다.

### **기술 스택 (Tech Stack)**

- **Language**: Python
- **Frameworks**: Django, Django REST Framework, FastAPI
- **Database**: PostgreSQL, Redis
- **DevOps**: AWS(EC2, RDS, S3), Docker, GitHub Actions, Jenkins
- **Others**: WebSocket, asyncio, aiohttp, Streamlit, Claude API

# Experiences

**Chips&Media** VS(QA) Team

기간 2024.07.15 ~ 2025.07.14

**주요 역할**: Python을 활용한 테스트 및 측정 프로세스 자동화 시스템 설계&개발 그외 레거시코드 최적화

- **수작업 제거를 위한 Power 측정 파이프라인 자동화**
    - **수행**: 수동으로 진행되던 로그 기록, PC 대여, 파일 수정 등 전체 과정을 Python 스크립트로 자동화하고 Jenkins CI 파이프라인에 연동
    - **성과**: 엔지니어의 반복적인 2시간 이상의 수작업 공수를 완전히 제거하여, 핵심적인 분석 및 개발 업무에 집중할 수 있는 환경을 조성
- **라이선스 병목 현상 해결 및 분석 효율 증가를 위한 시각화 대시보드 개발**
    - **수행**: Streamlit을 활용해 측정 결과(txt, csv)를 실시간으로 분석하는 웹 대시보드를 개발하여 고가의 상용 GUI 툴 의존도를 제거
    - **성과**: 라이선스 점유로 인한 작업 대기 시간을 없애고, 여러 측정 결과를 동시에 비교 분석할 수 있는 환경을 구축하여 테스트 사이클 단축에 기여
- **처리 속도 60% 향상을 달성한 대용량 데이터 스크립트 최적화**
    - **수행**: 1시간 이상 소요되던 10만 줄 이상의 데이터 처리 로직에 멀티스레딩을 적용하고 알고리즘을 개선.
    - **성과**: 기존 대비 **측정 속도 60% 향상**, **코드 라인 40% 감소**를 달성했으며, 데이터 오류를 조기에 발견할 수 있도록 함.

# Projects

### **Resee | AI 기반 스마트 복습 플랫폼** (1인 개발)

AI로 최적의 복습 시점을 추천하는 지능형 학습 관리 플랫폼 백엔드 개발

- **Link** : [Resee](http://reseeall.com/) 운영중 (25.09 ~)
- **Tech**: Django DRF, PostgreSQL, Redis, Claude API, Docker, AWS, GitHub Actions

### 주요 기능 및 성과
- **지능형 복습 스케줄링 엔진 설계**: Django Signals를 활용, 유저의 학습 패턴과 구독 등급에 따라 복습 주기를 실시간으로 재계산하는 핵심 도메인 로직 구현
- **대규모 트래픽 처리 및 성능 개선**: Redis 캐싱 시스템 구축, ORM 최적화(select_related, prefetch_related) 및 복합 인덱싱으로 N+1 쿼리 문제 해결
- **인증·보안 아키텍처 구축**: JWT와 Google OAuth 2.0을 연동한 Multi-Provider 인증 시스템 및 API Throttling(요청 제한)을 적용하여 보안 강화
- **Claude API 기반 AI 학습 시스템**: 구독 등급별 차별화된 AI 기능(주간 테스트, 콘텐츠 품질 검사, 서술형 평가) 및 사용량 제한 시스템 구현
- **실시간 헬스체크 모니터링 시스템**: 데이터베이스, 캐시, AI 서비스 상태를 실시간으로 감시하고 장애 발생 시 자동 알림을 통한 안정적인 운영 환경 구축

### **KKUA | 실시간 멀티플레이어 끝말잇기 게임** (3인 개발)

WebSocket 기반 실시간 멀티플레이어 웹 게임 서버 개발 및 배포

- **GitHub**: https://github.com/djgnfj-svg/kkua
- **Status**: 개발 완료 (로컬 환경 실행 가능)
- **Tech**: FastAPI, WebSocket, PostgreSQL, Redis, Docker, AWS (EC2/RDS)

### 주요 기능 및 성과

- **실시간 서버 엔진 개발:** WebSocket, asyncio 기반 서버 구축, 동시 접속 100명 환경에서 **응답 속도 50ms 미만** 달성
- **DB·API 성능 최적화:** Redis 캐싱 도입으로 DB 쿼리 **85% 감소** 및 API 응답 속도 **80% 향상**
- **CI/CD 파이프라인 구축:** Docker, GitHub Actions 기반 배포 자동화, 배포 시간 **70% 단축** (10분→3분)
- **인프라 확장 및 안정화:** Load Balancer를 이용한 트래픽 분산 및 서버 부하 최소화로 안정성 확보
- **선제적 장애 대응 시스템 설계:** 임계치(동시 접속자 수) 기반 Slack 자동 알림 시스템 구축

### **웹 크롤링 프리랜서 프로젝트**

**기간**: 2024.01 ~ 2024.07

**Tech**: Python, aiohttp, asyncio, Telegram API

### 주요 기능 및 성과

- **aiohttp, asyncio 기반의 비동기 웹 크롤러 개발**로 대규모 데이터 수집 성능 최적화
- **데이터 변경 감지 및 Telegram API를 연동한 자동 알림 봇 구현**
- **변화에 유연한 크롤링 아키텍처 설계**를 통해 유지보수 비용 최소화

---

## **Activities**

**#42 Seoul** | Common Core (2021.01 - 2022.01)

- C언어 기반의 심층 학습 및 알고리즘 학습
- 동료 학습 및 코드 리뷰를 통해 협업 및 커뮤니케이션 역량 강화

## **Education**
**이리 공업 고등학교** | 디지털전자정보학과 (2013.03 - 2016.02 졸업)
