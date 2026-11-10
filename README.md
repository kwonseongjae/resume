<div align="center">

# 권성재 · Seongjae Kwon

### AI Engineer · AI 연구원

**모델을 제품까지 연결하고 수치로 검증하는 AI 엔지니어**

*LLM 응용 프로그램 · 컴퓨터비전 · 서비스 백엔드*

<a href="mailto:kwonseongjae0314@gmail.com"><img src="https://img.shields.io/badge/Email-kwonseongjae0314@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
<a href="https://github.com/kwonseongjae"><img src="https://img.shields.io/badge/GitHub-kwonseongjae-181717?style=flat-square&logo=github&logoColor=white"/></a>
<a href="https://jack-0314.tistory.com"><img src="https://img.shields.io/badge/Tech_Blog-jack--0314-FF5722?style=flat-square&logo=tistory&logoColor=white"/></a>

</div>

---

## 🧭 About

- **모델의 제품 적용** — 인물 분리·합성 30fps, LLM 도구 호출 챗봇, 콘텐츠 자동 발행 파이프라인을 구현했습니다.
- **수치 기반 검증** — 문항별 정답 평가, 검색 조건 5,002건 대조, 질문당 비용 실측으로 결과를 확인합니다.
- **기획부터 운영까지** — 2~3명 팀에서 데이터·백엔드·프론트엔드와 모델 적용을 연결합니다.

| | |
|---|---|
| 🎯 **목표 직무** | AI Engineer / LLM·CV Engineer |
| 🏢 **현재** | 베이직테크 AI 연구원 (2024.06~재직 중, 경력 2년 5개월) |
| 🎓 **학력** | 상명대학교 컴퓨터과학 (2023 졸업) |
| 🌱 **관심** | LLM 응용·Tool Calling 평가, 실시간 비전 추론, 서비스 백엔드 |

---

## 🛠 Tech Stack

**Languages**
<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**AI / ML**
<br>
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![SAM2](https://img.shields.io/badge/SAM2-0467DF?style=flat-square&logo=meta&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-111F68?style=flat-square&logo=ultralytics&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Google_Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)

**Backend / Web**
<br>
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)

**Infra / Quality**
<br>
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white)

---

## 💼 Work Experience

### 🏢 베이직테크 — AI 연구원
`2024.06 ~ 재직 중` · `경력 2년 5개월`

#### 💡 LED 부품 검색·견적 플랫폼 및 전문상담 챗봇
**2026.05 ~ 현재 · 2명 팀**  
**역할:** 기획, DB·백엔드·프론트엔드, 챗봇 개발, 데이터 정비, 검증·보고

- **118개 제조사** 제품의 사양 검색과 수신카드·캐비닛 조립 구성 검증을 구현했습니다.
- 사양 **52개 컬럼**을 군집 분석해 환경·설치·특수형 3개 축의 분류 규칙을 설계했습니다. 기존 **104,832행**의 판정을 유지하며 축 정보를 추가하고, 미분류 646개 중 후보 **545개**를 도출하고, 현행 규칙과 다른 **143개**를 검토·승인해 미분류를 **646 → 503**으로 줄였습니다.
- 지식을 3층으로 나누고 모델명 검색·용도별 통계 도구를 연결해 사양·통계 질문의 정답 수를 개선했습니다.
- DB SQL·SQLite·챗봇 도구의 검색 결과를 **AND 조건 5,002건·자연어 질문 150건**으로 대조했습니다. AND 조건은 경로별 결과가 모두 일치했고, 자연어는 결과 건수 150/150·필터 변환 149/150이 일치했습니다.
- 질문당 **1.3원**을 실측하고, DB 기록과 연계한 시간당·일일 사용 한도 및 일일 예산 상한을 구현했습니다.
- 제조사명 중복 **10쌍·919행**을 통합하고, 변경 전 백업과 변경 이력을 남겼습니다.

**상담 지식 3층 구조**

```text
사용자 질문 → 도구 호출 → 질문에 맞는 근거 조회
                          ├─ 1층: 용도 기준 JSON
                          ├─ 2층: 검토 승인 지식 DB
                          └─ 3층: 제품 수치 테이블
                       → 조회 근거에 따른 답변 → 답변 숫자·DB 계산값 대조
```

| 평가 항목 | 결과 |
|---|---|
| 사양 질문 | 정답 **23 → 97 / 100문항** |
| 통계 질문 | 정답 **38 → 110 / 110문항** |
| 숫자 근거 | **39 / 39건** |
| 범위 밖 질문 거절 | **60 / 60건** |
| 질문당 비용 | **1.3원 실측** |

`Next.js 16` `TypeScript` `MySQL` `OpenAI API` `Function Calling` `Jest` `Python`

<br>

#### 🎥 실시간 인물 분리·합성 시스템
**2024.06 ~ 2025.12 · 3명 팀**  
**역할:** 학습 서버 구축, 모델 학습·평가·선정, 실시간 추론 파이프라인·데스크톱 앱 개발  
[SAM2 단계 공개 구현](https://github.com/kwonseongjae/Segment-anything-model2-SAM2_Real-Time-Inference-without-Chromakey)

- SAM2 앞단에 YOLO 사람 검출을 연결하고, **10 → 15 FPS·지연 100 → 60ms·mIoU 0.987**을 측정했습니다.
- A6000 학습 서버를 구축하고 MobileNetV3 기반 인물 분리 모델을 **4단계**로 학습했습니다. SD·HD 비교 후 **4단계 HD 27 epoch** 가중치를 최종 제품에 적용했습니다.
- 미세조정한 YOLOv5s·SAM2.1 tiny로 이미지·마스크 **10,037쌍**을 생성하고, 정답 마스크 **2,558장** 대비 평균 정밀도 **0.929**를 확인했습니다.
- USB·스마트폰 HTTP·TCP·RTMP·RTSP **5가지 입력**과 투명 전체화면 오버레이를 연결했습니다. **HD USB·FHD 모바일/TCP 입력에서 30fps**를 실측하고, QHD 8fps·UHD 4fps의 한계를 확인했습니다.
- 학습 가중치를 FP16 TorchScript로 변환해 모델 파일을 **15.2MB → 8.0MB**로 줄였습니다.

`Python` `PyTorch` `SAM2` `MobileNetV3` `YOLOv5` `TorchScript FP16` `PyQt5` `OpenCV` `RTMP/RTSP`

<br>

#### 📺 디지털 사이니지 광고 통합 관리 플랫폼 CMS
**2025.09 ~ 2026.05 · 3명 팀**  
**역할:** 화면·DB·API 설계, 인증·광고 예약·소재 심사 기능의 풀스택 개발

- 광고 예약·관리용 **8개 화면**을 설계·구현했습니다.
- 회원·예약·소재 등을 관리하는 **9개 DB 테이블·약 70개 API 엔드포인트**를 구성했습니다.
- 인증·세션 자동 만료, 퍼블리셔·스크린·디바이스 CRUD, 광고 예약·슬롯 관리를 구현했습니다.
- Google Drive 소재 업로드, 관리자 승인·거절, 네이버 주소 검색을 연동해 소재 접수부터 심사·예약까지 연결했습니다.

`FastAPI` `SQLAlchemy` `MySQL` `Jinja2` `Vanilla JS` `Google Drive API`

<br>

#### 👥 유동 인원 측정 모듈
**2025.09 ~ 2026.05 · 2명 팀 · CMS 프로젝트 기간**  
**역할:** 실시간 인원 집계, 시간대별 통계 저장, 환경별 실행 버전 제작

- **1920×1080** 카메라 영상에 YOLO11n을 적용해 사람 수를 실시간으로 집계했습니다.
- 시간대별 최대 인원을 산출하고 통계 파일로 저장했습니다.
- Windows 화면 표시 버전과 라즈베리파이 무화면 실행 버전의 **2개 환경용 버전**을 제작했습니다.

`YOLO11n` `Windows` `Raspberry Pi`

<br>

#### 🖼 얼굴 인식 기반 체험형 인물 사진 생성
**2025.05 ~ 2025.06 · 2명 팀**  
**역할:** 모델 선정, 생성 파이프라인, 사진 접수·합성·이메일 발송 자동화

- InsightFace 얼굴 임베딩과 IP-Adapter FaceID를 연결해 입력 얼굴 특징을 반영한 한복·역사 인물 사진 생성 흐름을 구현했습니다.
- 여성 입력이 남성형으로 생성되는 문제에 성별 인식과 성별별 프롬프트·스타일 세트 분리를 적용했습니다.
- 배경 제거·소품 합성과 새 사진 감지를 연결하고, **사진 업로드 → 인물·배경 합성 → 결과 이메일 발송**의 전 과정을 자동화했습니다.

`Stable Diffusion img2img` `IP-Adapter FaceID` `InsightFace` `rembg` `diffusers`

---

## 🚀 Personal Projects

### 🤖 블로그 콘텐츠 생성·자동 발행 시스템
**2026.03 ~ 현재 · 개인 프로젝트**  
[공개 저장소](https://github.com/kwonseongjae/ai-blog-automation) · 🟢 [라이브 블로그](https://jack-0314.tistory.com) · 📘 [엔지니어링 전자책](https://kwonseongjae.github.io/ebook-landing/)

공식 API가 없는 블로그 플랫폼에서 글 생성·품질 검사·브라우저 발행·검색 통계 수집을 연결했습니다.

```text
콘텐츠 생성(LLM) → 품질 검사·미달 글 재생성 → 발행 큐 → 브라우저 발행
                                                    ↓
                                      검색 통계 수집·진단 → 생성 함수 개선
```

| 멈춤 지점 | 대응 |
|---|---|
| 이미지 캡차 | Vision 모델 기반 캡차 처리 |
| 브라우저 프로필 충돌 | 1회용 브라우저 프로필로 공유 상태 충돌 제거 |
| 발행 실패 | 지수 백오프·dead-letter 발행 큐 |
| 중복 발행 | 멱등 가드 |

- 발행 이력 **449건**(2026.06.15~11.02)을 쌓았습니다. 일일 자동 발행 잡은 현재 설정상 중단 상태입니다.
- Search Console로 **검색 유입 83% 감소**, 신규 글 노출의 **6월 218 → 9월 2.4 하락**을 진단했습니다. 그라운딩이 꺼진 생성 함수를 수정해 검색 근거 기반 생성으로 전환했습니다.
- 자정 직후 수집으로 **40일간 통계가 0으로 기록된 계측 결함**과 신규 카테고리 정렬 오류를 수정했습니다.

`Python` `FastAPI` `APScheduler` `Selenium` `Gemini API` `OpenAI API Vision` `Google Search Console API` `Pytest`

<br>

### 🎬 YouTube Shorts 자동화 SaaS
**2026.03 ~ 2026.10 · 개인 프로젝트**  
[공개 저장소](https://github.com/kwonseongjae/youtube-shorts-automation)

영상 수집부터 한국어 스크립트·음성·자막 편집, 업로드와 주간 분석 리포트까지 연결했습니다.

```text
                 Nginx (SSL/HTTPS)
                       │
        ┌──────────────┼──────────────┐
   FastAPI         Celery Worker    Celery Beat
   (Web UI)        (영상 파이프라인)   (스케줄러)
```

**영상 생성 파이프라인** — 영상 수집 → 한국어 스크립트 → TTS·BGM·자막 합성 → Shorts 편집 → 업로드

- Celery Worker/Beat로 제작·업로드 일정을 자동화했습니다.
- 주간 채널 분석 리포트의 텔레그램 발송을 자동화했습니다.

<div align="center">

| 📤 Shorts 업로드 | 🎞 영상 생성 | 📦 소스 클립 |
|:---:|:---:|:---:|
| **53개** | **69개** | **119개** |

</div>

`FastAPI` `Celery Worker/Beat` `Docker Compose` `Nginx SSL` `Alembic` `YouTube API` `TTS`

<br>

### 🎞 썰툰 영상 자동 생성기
**2026.10 · 개인 프로젝트 · 비공개 저장소**

- 커뮤니티 글 수집 → 장면 분할 → 캐릭터 일관성을 유지한 이미지 생성 → TTS·자막 합성으로 **1분 영상**을 자동 제작했습니다.
- **테스트 106개**와 실제 영상 렌더링으로 동작을 검증했습니다.

`이미지 생성` `TTS` `영상 렌더링`

<br>

### ✍️ 네이버 블로그 글 작성기 + 크롬 확장
**2026.10 · 개인 프로젝트 · 비공개 저장소**

- 사진에서 제목·본문·태그를 생성하고, 확장 프로그램으로 블로그 에디터에 직접 입력하도록 구현했습니다.
- 에디터의 숨은 입력 iframe 구조를 실험으로 확인해 붙여넣기 제약을 우회했습니다.
- 글 상태판·중복 감지·발행 계획·시리즈 링크 관리를 자동화했습니다.

`Next.js` `TypeScript` `OpenAI API` `IndexedDB` `Chrome Extension`

<br>

### 💰 부부 가계부 + 증권사 Open API
**2026.10 · 개인 프로젝트**  
[공개 저장소](https://github.com/kwonseongjae/budget-book)

- 가계부 시트 자동 생성·공유, 반복 지출·예산·자산 기록 기능을 구현했습니다.
- 증권 계좌 **2개**를 실연동해 평가액·손익을 자동 갱신했습니다.
- **Pytest 108개·Apps Script 테스트**로 기능을 검증하고, 인증 키를 코드·저장소 밖에서 관리했습니다.

`Python` `Google Sheets API` `Google Apps Script` `메리츠증권 Open API` `Pytest`

<br>

### 📈 미국 주식 퀀트 시스템
**2026.03 ~ 2026.05 · 개인 프로젝트 · 비공개 저장소**

- Purged Walk-Forward CV·CPCV 기반 백테스트 엔진에 몬테카를로·HMM 국면 탐지·Deflated Sharpe Ratio·Fama-French 5팩터 분석을 적용했습니다.
- 증권사 **2곳·모의 브로커** 연동 계층과 **유닛 테스트 162개**를 구성했습니다.

<br>

### 🧳 Travel OS
**2026.07 ~ 2026.08 · 개인 프로젝트 · 비공개 저장소**

- 개인용 여행 일정 앱의 하드코딩을 제거하고, 시트를 복사하면 연결된 앱을 사용할 수 있는 판매용 템플릿으로 전환했습니다.
- 템플릿·개인본 **배포 2곳**을 기존 URL로 동시에 갱신하는 스크립트를 작성했습니다.

`Google Apps Script` `Google Sheets API` `Apps Script API`

---

## 🎓 Education & Training

| 기간 | 내용 | 프로젝트·성과 |
|---|---|---|
| 2023 졸업 | **상명대학교 컴퓨터과학** | [Coin ATS](https://github.com/kwonseongjae/Coin_ATS): Upbit API 기반 암호화폐 자동매매 팀 프로젝트 · 캡스톤디자인 경진대회 **최우수상(2022.08.11)** |
| 2023.02.13 ~ 2023.04.21 | **포스코 청년 AI·BigData 아카데미 21기 수료** | **5명 팀 대표** · [밀집 인파 위험 탐지 드론](https://github.com/kwonseongjae/AIBigData): RTMP·YOLOv8s 기반 **제곱미터당 6명 이상 경고** · 수료 프로젝트 **우수상(2023.04.21)** |

---

## 🏆 Awards & Certifications

| 구분 | 내용 | 일자 |
|---|---|---|
| 🏆 수상 | **상명대학교 캡스톤디자인 경진대회 최우수상** — Coin ATS | 2022.08.11 |
| 🏆 수상 | **포스코 청년 AI·BigData 아카데미 21기 수료 프로젝트 우수상** — 밀집 인파 위험 탐지 드론 | 2023.04.21 |
| 📜 자격증 | **ADsP** (데이터분석 준전문가) | 2023.09 |

---

## 🧩 How I Work

- 설계서 → 구현 계획 → 테스트 작성 → 구현 → 수치 검증 순서로 진행하고 결과를 문서로 남깁니다.
- 데이터를 수정하기 전에 백업과 변경 이력을 먼저 남깁니다.
- AI 코딩 도구를 개발 과정에 적극 활용해, 2~3명 팀에서도 많은 분량의 기능을 짧은 기간에 검증된 상태로 내놓습니다.

---

## 📊 GitHub

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=kwonseongjae&show_icons=true&theme=radical&hide_border=true&count_private=true" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kwonseongjae&layout=compact&theme=radical&hide_border=true&langs_count=8" height="165"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=kwonseongjae&theme=radical&hide_border=true" height="165"/>

</div>

---

<div align="center">
<sub>이 이력서는 GitHub README로 작성되었습니다 · 공개 저장소 링크가 있는 프로젝트는 코드로 확인할 수 있습니다.</sub>
</div>
