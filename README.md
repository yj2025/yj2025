<div align="center">

# Hi, I'm CYJ 👋

**데이터와 AI를 연결해 서비스를 구현하는 백엔드 개발자**

LLM 파인튜닝부터 API 서빙까지, 모델이 실제 서비스에서 동작하도록 만드는 일에 관심이 있습니다.

</div>

<br>

## 🔭 Now

- 🏦 **AICA Financial (7th)**: 금융 도메인 AI 과정 수강 중
- 🧪 은행 약관을 LLM으로 **실행 가능한 조건식**으로 바꾸는 프로젝트 진행 중
- 📚 관심 주제: **RAG · LLM Fine-tuning · LLM Evaluation**

<br>

## 🚀 Featured Projects

### 📑 [Clause-to-Rule](https://github.com/yj2025/clause-to-rule): 약관 조문 → 실행 가능한 조건식

> 은행 상품설명서 조문을 **조건식 JSON**으로 변환하고, 고객별 최종 적용금리를 계산하는 파이프라인

```
약관 조문 ──▶ 조건식 JSON ──▶ 개별 판별 ──▶ 최종 적용금리
           (LLM)           (결정론적 코드)  (결정론적 코드)
```

- **LLM은 변환 단계에만** 쓰고, 조문 분할과 판별(3치 논리 실행기)은 결정론적 코드로 구현
- **Qwen3-8B QLoRA** 파인튜닝, 사람이 검토한 정답셋 기반 평가 체계 구축
- 코퍼스 43개 조문 정확도 **67.4% (기준선) → 79.7%**
- 테스트 **1,072개**, 라운드별 실험 기록과 노이즈 분석

`Python` `PyTorch` `Transformers` `QLoRA` `Prompt Engineering`

### 🔍 [Korean OCR Test](https://github.com/yj2025/korean-ocr-test): CPU 전용 한국어 OCR 환경

> GPU 없이 한글·영문 문서, 사진, PDF에서 텍스트를 추출하는 경량 OCR 환경

- RapidOCR + ONNX Runtime 기반, 비교 실험으로 **Korean PP-OCRv5 mobile** 모델 선정
- 이미지당 **2~4초**, 인쇄체 기준 문자 정확도 **95~100%**
- 저신뢰도 줄 자동 분류("검토 필요"), 정확도 채점 스크립트 포함

`Python` `ONNX Runtime` `RapidOCR`

### 📰 [News Digest](https://github.com/yj2025/yj2025_NewsDigest): AI 뉴스 요약 웹 서비스

> 뉴스 URL을 입력하면 본문을 크롤링하고 핵심 내용을 요약해주는 서비스

- FastAPI 기반 REST API (`/api/summarize`) 설계 및 구현
- HuggingFace **KoBART** 모델로 한국어 뉴스 요약

`FastAPI` `Transformers` `BeautifulSoup`

<br>

## 🛠 Tech Stack

| 분야 | 기술 |
|---|---|
| **AI / ML** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![QLoRA](https://img.shields.io/badge/QLoRA-6E40C9?style=flat-square) ![Prompt Engineering](https://img.shields.io/badge/Prompt%20Engineering-412991?style=flat-square) |
| **Backend** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) |
| **Database** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) |
| **Infra** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![KubeSphere](https://img.shields.io/badge/KubeSphere-3D3E49?style=flat-square) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square) |

<br>

## 🎓 Education

| 과정 | 기수 |
|---|---|
| **명지대학교** (Myongji University) | |
| **AICA Financial** | 7기 · 수강 중 |
| **Global Academy** | 7기 |
| **멋쟁이사자처럼** (LIKELION) | 7기 |

<br>

## 📜 Certifications

| 자격증 | 발급 |
|---|---|
| 정보처리기사 | 한국산업인력공단 |
| ADsP (데이터분석 준전문가) | 한국데이터산업진흥원 |
| AICE Basic | KT |

<br>

<details>
<summary><b>🗂 Other Projects</b></summary>
<br>

- [godot-yeoul-farm](https://github.com/yj2025/godot-yeoul-farm): Godot 4 농장 경영 시뮬레이션 (작물 재배, 생산, 거래, 일꾼 자동화)
- [OneShot](https://github.com/yj2025/OneShot): 웹 기반 FPS 게임 (JavaScript)
- [django-jyj-ecommerce](https://github.com/yj2025/django-jyj-ecommerce) · [django-jyj-boards](https://github.com/yj2025/django-jyj-boards) · [django_vote_service](https://github.com/yj2025/django_vote_service): Django 웹 서비스 실습
- [JSP_BBS](https://github.com/yj2025/JSP_BBS): JSP 게시판

</details>
