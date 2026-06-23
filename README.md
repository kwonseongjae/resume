# 권성재 (Seongjae Kwon)
**AI Engineer · AI 연구원**

📧 kwonseongjae0314@gmail.com · 📱 [연락처 입력]
🔗 GitHub: github.com/kwonseongjae · 🌐 Tech Blog: jack-0314.tistory.com

> **타겟 직무: AI 엔지니어 (ML/LLM Engineer)**

---

## 한 줄 소개 (Summary)

**연구에서 멈추지 않고 프로덕션까지 만드는 3년차 AI 엔지니어.**
컴퓨터비전(SAM2 실시간 세그멘테이션)부터 LLM 기반 자동화 시스템까지, **AI 모델을 실제 제품·서비스에 통합하고 안정적으로 운영**한 경험이 있습니다. "동작하는 데모"가 아니라 **장애에 견디는 시스템**을 만드는 데 강점이 있습니다.

---

## 핵심 역량 (Skills)

- **Languages:** Python, C, SQL
- **AI / ML:** PyTorch, TensorFlow, scikit-learn · **Computer Vision** (SAM2, 실시간 추론) · **LLM 통합** (Google Gemini, OpenAI GPT·Vision), 프롬프트 엔지니어링
- **Backend / Web:** FastAPI, SQLAlchemy(ORM), MySQL, SQLite, Jinja2, Selenium, APScheduler, asyncio
- **Engineering:** TDD(Pytest), Git, Linux/WSL, REST API, MQTT, 내구성 큐·자가복구 설계
- **Data:** 데이터 분석(ADsP), 데이터 파이프라인

---

## 경력 (Work Experience)

### 베이직테크 — AI 연구원
**2024.06 ~ 재직 중 (만 2년, 3년차)**

#### 실시간 크로마키 시스템 (SAM2 기반 Real-Time Segmentation)
> Meta SAM2를 활용한 실시간 객체 분할로 **크로마키 배경판 없이도 크로마키 합성**을 구현
- Segment Anything Model 2(SAM2)를 실시간 추론 파이프라인에 적용, 실시간 통신으로 객체를 인식하고 크로마키 컬러(RGB 0,175,57)를 합성
- **GPU·모델별 추론 속도를 벤치마크**하여 실시간 처리 가능한 구성 도출
- PyTorch 기반 CV 모델을 실서비스 시나리오(라이브 영상)에 통합
- `Python · PyTorch · SAM2 · Real-Time Inference · GPU`

#### 디지털 사이니지 광고 통합 관리 플랫폼 (Advertise Platform)
> 광고주가 퍼블리셔(디스플레이 기기)를 선택해 광고 캠페인을 예약·관리하는 **CMS 웹 서비스**를 단독 풀스택 구현
- **프론트엔드 전체** — 8개 페이지 UI/UX 설계·구현 (Jinja2 + Vanilla JS)
- **백엔드** — 인증/세션(자동 만료), 퍼블리셔·스크린·디바이스 CRUD, 광고 예약·슬롯 관리, 소재 업로드(Google Drive 연동), 관리자 심사 기능, 네이버 주소 검색 API 연동
- **데이터베이스** — SQLAlchemy ORM + MySQL, 9개 테이블 설계·연동
- `Python · FastAPI · SQLAlchemy · MySQL · Jinja2 · MQTT(연동)`

---

## 개인 프로젝트 (Side Projects)

### 🤖 AI 블로그 자동화 시스템 — 무인 콘텐츠 생성·발행 플랫폼
**개인 프로젝트 · 2026 · 단독 개발·운영**
🔗 github.com/kwonseongjae/ai-blog-automation · 🟢 jack-0314.tistory.com (라이브 운영 중)

API가 종료된 플랫폼(Tistory)에 **사람 개입 없이 매일 콘텐츠를 생성·발행하는 시스템**을 단독 설계·구현·운영.

- **LLM 콘텐츠 파이프라인** — Gemini로 검색 의도 기반 글 자동 생성(검색어 타겟팅·SEO 최적화), 품질 게이트로 미달 콘텐츠 자동 필터·재생성
- **브라우저 자동화 발행 + Vision LLM** — undetected-chromedriver로 웹 에디터 제어, 봇 탐지(이미지 캡차)를 **Gemini/GPT Vision으로 자동 해결**
- **신뢰성 엔지니어링** — 워치독 땜빵 대신 **버그 클래스 제거 설계**: 1회용 임시 프로필(공유 상태 충돌 제거), 하드 타임아웃·자가복구, **내구성 발행 큐**(enqueue/worker·지수 백오프·dead-letter), 멱등 가드(정확히 한 번 발행)
- **품질 관리** — TDD(Pytest)로 핵심 로직·도메인 규칙을 테스트로 기계화
- **성과** — 매일 5건 자동 발행을 **무인으로 라이브 운영**
- `Python · FastAPI · Selenium · Gemini/OpenAI · APScheduler · Pytest`

### 🎬 YouTube Shorts 자동화 파이프라인 + SaaS 플랫폼
**개인 프로젝트 · 단독 개발·운영**
🔗 github.com/kwonseongjae/youtube-shorts-automation

Reddit에서 바이럴 영상을 수집해 **AI로 한국어 Shorts를 자동 생성·업로드**하고 채널 분석까지 자동화한 **풀스택 SaaS 시스템**.

- **AI 영상 생성 파이프라인** — 수집한 클립에 AI가 한국어 스크립트·TTS·BGM·자막을 입혀 Shorts로 자동 편집·업로드
- **분산 작업 처리 아키텍처** — FastAPI(Web UI) + **Celery Worker**(파이프라인) + **Celery Beat**(스케줄러), Nginx(SSL)·Docker Compose로 컨테이너 배포, Alembic DB 마이그레이션
- **완전 자동 스케줄 운영** — 매일 영상 수집 / 매주 Shorts 생성·업로드 / 주간 채널 분석 리포트(조회수·예상수익·증감)를 **텔레그램으로 자동 보고**
- **운영 결과** — Shorts **53개 업로드**, 영상 누적 **69개 생성**, 소스 클립 **119개** 처리
- `Python · FastAPI · Celery · Docker · Nginx · Alembic · YouTube API`

---

## 학력 (Education)

**상명대학교 — 컴퓨터과학 전공**  ·  2023년 졸업

- **캡스톤디자인 — Coin ATS (코인 자동매매 시스템)** 🏆 *캡스톤디자인 경진대회 수상*
  Python + Upbit API 기반 암호화폐 자동매매 시스템 (팀 프로젝트)
  🔗 github.com/woosook0127/Coin_ATS

---

## 교육 / 부트캠프 (Training)

**포스코 청년 AI·빅데이터 아카데미 21기 수료** 🏆 *수료 프로젝트 우수상*
- AI·빅데이터 실무 교육 과정 이수 (데이터 분석·머신러닝·프로젝트)
- **프로젝트 우수상** 수상 — 팀 프로젝트 *(시연영상·발표자료 보유)*

---

## 수상 (Awards)

- 🏆 **캡스톤디자인 경진대회 수상** — Coin ATS (암호화폐 자동매매 시스템, 상명대)
- 🏆 **프로젝트 우수상** — 포스코 청년 AI·빅데이터 아카데미 21기 수료 프로젝트

---

## 자격증 (Certifications)

- **ADsP** (데이터분석 준전문가)

---

<sub>본 이력서는 사이드 프로젝트·실무 경험을 바탕으로 AI 엔지니어 직무에 맞춰 작성되었습니다.</sub>
