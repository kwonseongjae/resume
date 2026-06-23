<div align="center">

# 권성재 · Seongjae Kwon

### AI Engineer · AI 연구원

데모가 아니라 **장애에 견디는 시스템**을 만드는 3년차 AI 엔지니어
*Computer Vision · LLM · 프로덕션 자동화*

<a href="mailto:kwonseongjae0314@gmail.com"><img src="https://img.shields.io/badge/Email-kwonseongjae0314@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
<a href="https://github.com/kwonseongjae"><img src="https://img.shields.io/badge/GitHub-kwonseongjae-181717?style=flat-square&logo=github&logoColor=white"/></a>
<a href="https://jack-0314.tistory.com"><img src="https://img.shields.io/badge/Tech_Blog-jack--0314-FF5722?style=flat-square&logo=tistory&logoColor=white"/></a>

</div>

---

## 🧭 About

> **"AI 모델을 실제 제품으로 만들고, 사람 없이 안 죽게 운영한다."**

컴퓨터비전(SAM2 실시간 세그멘테이션)부터 LLM 기반 자동화 SaaS까지, 연구에서 멈추지 않고 **설계 → 구현 → 배포 → 24/7 운영**까지 직접 책임진 경험이 있습니다. 워치독 같은 땜빵이 아니라 **버그 클래스 자체를 제거하는 설계**로 신뢰성을 만듭니다.

| | |
|---|---|
| 🎯 **목표 직무** | AI Engineer / ML·LLM Engineer |
| 🏢 **현재** | 베이직테크 AI 연구원 (2024.06~, 만 2년차) |
| 🎓 **학력** | 상명대학교 컴퓨터과학 (2023 졸업) |
| 🌱 **관심** | LLM 애플리케이션, CV 실시간 추론, 프로덕션 신뢰성 |

---

## 🛠 Tech Stack

**Languages**
<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)

**AI / ML**
<br>
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![SAM2](https://img.shields.io/badge/SAM2-0467DF?style=flat-square&logo=meta&logoColor=white)
![Gemini](https://img.shields.io/badge/Google_Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)

**Backend / Infra**
<br>
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)

**Tools**
<br>
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

---

## 💼 Work Experience

### 🏢 베이직테크 — AI 연구원
`2024.06 ~ 재직 중` · `만 2년, 3년차`

<table>
<tr><td width="50%" valign="top">

#### 🎥 실시간 크로마키 (SAM2)
**Meta SAM2 기반 실시간 객체 분할로 크로마키 배경판 없이 합성**

- SAM2의 streaming memory 구조를 실시간 추론 파이프라인에 적용, points/bbox 프롬프트로 객체 인식
- 인식 영역 외부를 크로마키 컬러 **RGB(0,175,57)** 로 실시간 합성
- **GPU·모델별 추론 속도(FPS) 벤치마크**로 실시간 처리 가능 구성 도출

`PyTorch` `SAM2` `Real-Time Inference` `CV`

</td><td width="50%" valign="top">

#### 📺 디지털 사이니지 광고 CMS
**광고주가 디스플레이를 골라 캠페인을 예약·관리하는 웹 서비스 풀스택 단독 구현**

- **프론트** 8개 페이지 UI/UX (Jinja2 + Vanilla JS)
- **백엔드** 인증·세션, 퍼블리셔/디바이스 CRUD, 광고 예약·슬롯, 소재 업로드(Google Drive), 관리자 심사, 네이버 주소 API
- **DB** SQLAlchemy ORM + MySQL 9개 테이블

`FastAPI` `SQLAlchemy` `MySQL` `MQTT`

</td></tr>
</table>

---

## 🚀 Featured Projects

### 🤖 AI 블로그 자동화 시스템
> API가 사라진 Tistory에 **사람 개입 없이 매일 콘텐츠를 생성·발행하는 무인 시스템**
> [`github.com/kwonseongjae/ai-blog-automation`](https://github.com/kwonseongjae/ai-blog-automation) · 🟢 [라이브 블로그](https://jack-0314.tistory.com) · 📘 [엔지니어링 전자책](https://kwonseongjae.github.io/ebook-landing/)

```
수집/생성(LLM) → SEO → 브라우저 발행 → 색인 신청 → 운영·모니터링
   Gemini          스니펫    Selenium+Vision      구글/네이버    스케줄·큐·알림
```

**핵심 — 자동 블로그가 멈추는 지점을 "구조적으로" 제거**

| 멈춤 지점 | 구조적 해결 |
|---|---|
| 세션 만료 → 2FA 루프 | 암호화 쿠키 저장소 + 세션 keepalive로 **재로그인 회피** |
| 봇 탐지(이미지 캡차) | **Vision LLM(Gemini/GPT)으로 자동 해결** |
| 프로필 락 충돌 | **1회용 임시 프로필**로 공유 상태 버그 클래스 제거 |
| 발행 중 무한 멈춤 | 하드 타임아웃 + 워치독 **자가복구** |
| 중복 발행 | **멱등 가드** (정확히 한 번 발행) |
| 발행 유실 | **내구성 큐** (enqueue/worker·지수 백오프·dead-letter) |

- **성과** — 매일 5건 자동 발행을 **무인으로 라이브 운영**, TDD(Pytest)로 핵심 로직·도메인 규칙 회귀 방지

`Python` `FastAPI` `Selenium` `Gemini/OpenAI` `APScheduler` `Pytest`

<br>

### 🎬 YouTube Shorts 자동화 + SaaS 플랫폼
> Reddit 바이럴 영상을 수집해 **AI로 한국어 Shorts를 자동 생성·업로드**하고 채널 분석까지 자동화한 풀스택 SaaS
> [`github.com/kwonseongjae/youtube-shorts-automation`](https://github.com/kwonseongjae/youtube-shorts-automation)

```
                 Nginx (SSL/HTTPS)
                       │
        ┌──────────────┼──────────────┐
   FastAPI         Celery Worker    Celery Beat
   (Web UI)        (영상 파이프라인)   (스케줄러)
```

**영상 생성 파이프라인** — 클립 수집 → AI 한국어 스크립트 → **TTS·BGM·자막** 합성 → Shorts 자동 편집 → 업로드

**자동 스케줄 운영**
- 📥 매일 — Reddit 바이럴 영상 수집
- 🎞 매주 — Shorts 생성·업로드
- 📊 주간 — 채널 분석 리포트(조회수·예상수익·증감)를 **텔레그램 자동 보고**

<div align="center">

| 📤 Shorts 업로드 | 🎞 영상 생성 | 📦 소스 클립 |
|:---:|:---:|:---:|
| **53개** | **69개** | **119개** |

</div>

`Python` `FastAPI` `Celery` `Docker` `Nginx` `Alembic` `YouTube API`

---

## 🎓 Education & Training

| 기간 | 내용 | 비고 |
|---|---|---|
| ~2023 | **상명대학교** 컴퓨터과학 전공 (졸업) | 캡스톤 *Coin ATS* 🏆 |
| — | **포스코 청년 AI·빅데이터 아카데미** 21기 수료 | 프로젝트 우수상 🏆 |

---

## 🏆 Awards & Certifications

| 구분 | 내용 |
|---|---|
| 🏆 수상 | **캡스톤디자인 경진대회 수상** — *Coin ATS* (Python + Upbit 암호화폐 자동매매, 상명대) |
| 🏆 수상 | **프로젝트 우수상** — 포스코 청년 AI·빅데이터 아카데미 21기 수료 프로젝트 |
| 📜 자격증 | **ADsP** (데이터분석 준전문가) |

---

<div align="center">
<sub>이 이력서는 GitHub README로 작성되었습니다 · 모든 프로젝트는 공개 저장소에서 코드로 확인할 수 있습니다.</sub>
</div>
