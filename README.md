<p align="center">
  <a href="#-about-me">소개</a> ·
  <a href="#-featured-projects">프로젝트</a> ·
  <a href="#-tech-stack">기술 스택</a> ·
  <a href="#-education--awards">수상 및 교육</a>
</p>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:4facfe,100:00f2fe&height=220&section=header&text=Hello,%20I'm%20JuHyeong&fontSize=70&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Security-Based%20AI%20Engineer%20%7C%20Data%20Analyst&descAlignY=55&descAlign=50" />
</div>

<div align="center">
  
### 👋 Welcome to My GitHub

**"보안(Security)을 이해하는 엔지니어, 데이터 흐름을 설계하여 비즈니스 문제를 해결합니다."** 네트워크/보안 실무 경험을 바탕으로, **안정적이고 효용성 높은 AI 파이프라인**을 구축합니다.

![Visitor Badge](https://visitor-badge.laobi.icu/badge?page_id=your_github_id.visitor_badge)

</div>

---

## 🙋‍♂️ About Me

- 🛡️ **Security Base**: 네트워크 패킷 분석 및 모의해킹(MITM) 경험을 보유하여, **보안과 안정성**을 최우선으로 고려합니다.
- 🎯 **AI & Data**: 도메인 특화 **sLLM Fine-tuning** 및 **RAG 파이프라인 최적화**에 강점이 있습니다.
- 💡 **Strength**: 
  - **Full-Cycle Dev**: 기획부터 데이터 수집, 모델링, 백엔드 API, 웹 배포까지 **E2E 개발**을 주도합니다.
  - **Communication**: 복잡한 기술 개념을 시각화하고, PM으로서 팀을 리딩하는 협업 역량을 갖췄습니다.
- 🚀 **Goal**: 단순 기능 구현을 넘어, **비용 효율(Cost-Efficiency)과 신뢰성(Reliability)**을 갖춘 서비스를 만듭니다.

---

## 💼 Featured Projects

### 1) ⚖️ Veraclaim: 특허 거절 사유 예측 및 자동 대응 AI
> **🏆 Awards**: SK네트웍스 Family AI 캠프 **우수상** / 한국컴퓨터정보학회(KSCI) **우수논문상** > **Repository**: [Veraclaim-Patent-Response-AI](https://github.com/your-id/Veraclaim-Patent-Response-AI)

특허 심사 비용과 시간을 줄이기 위해, **거절 가능성을 사전 진단하고 대응 논리를 자동 생성**하는 도메인 특화 sLLM 솔루션입니다.

- **Role**: PM, AI 모델링(sLLM), RAG 파이프라인 설계, 백엔드 개발
- **Key Tech**:
  - **sLLM Optimization**: `Qwen-2.5-14B`에 QLoRA를 적용하여 한국어 특허 데이터 6,000건 학습 (**Accuracy 0.87** 달성)
  - **Reliable RAG**: GPT Score & Spearman 상관계수를 도입한 **Multi-Metric 평가**로 생성 결과의 논리적 타당성 검증
  - **Secure Arch**: Django & Next.js 기반의 **관리자 권한 분리(RBAC)** 및 OpenSearch 검색 엔진 구축

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

### 2) 📝 Django RAG Study Assistant: 학습 보조 & Anki 생성 웹 서비스
> **Repository**: [Django-RAG-Study-Assistant-Web](https://github.com/your-id/Django-RAG-Study-Assistant-Web)

강의 자료를 업로드하면 **RAG 기반으로 질의응답**을 제공하고, 중요 개념을 **암기장(Anki) 파일로 자동 변환**해주는 학습 플랫폼입니다.

- **Key Features**:
  - **Multi-Agent System**: 질문 의도에 따라 단순 검색/심층 분석 에이전트로 자동 분기 처리
  - **Auto-Anki Pipeline**: 강의 내용에서 핵심 키워드를 추출하여 `.apkg` 파일 자동 생성 및 다운로드
  - **Real-time**: Django Channels와 Redis를 활용한 **실시간 스트리밍 답변** 및 채팅 인터페이스 구현
- **Tech Stack**: `Django`, `LangChain`, `ChromaDB`, `Redis`, `Celery`

---

### 3) 📡 Telecom Churn Prediction: 통신사 고객 이탈 예측 대시보드
> **Repository**: [Telecom-Customer-Churn-Dashboard](https://github.com/your-id/Telecom-Customer-Churn-Dashboard)

Cell2Cell 데이터셋을 활용하여 **이탈 위험 고객을 조기에 식별**하고, 마케팅 전략 수립을 돕는 분석 대시보드입니다.

- **Insight**: 단순 예측을 넘어, **'서비스 품질'과 '이탈률'의 상관관계**를 히트맵으로 시각화하여 비즈니스 액션 도출
- **Modeling**: LightGBM, CatBoost 앙상블 모델을 적용하여 이탈 예측 정확도 최적화
- **Viz**: Streamlit을 활용하여 이탈 확률 분포 및 **주요 변수 중요도(Feature Importance)** 대시보드 개발

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

---

### 4) 🔓 MITM Simulation: 웹 취약점 분석 및 모의해킹
> **Repository**: [MITM-Attack-Simulation](https://github.com/your-id/MITM-Attack-Simulation)

사용자 계정 탈취 위험성을 분석하기 위해 **피싱 사이트 구축부터 패킷 스니핑까지 공격 전 과정**을 시뮬레이션했습니다. (졸업논문 프로젝트)

- **Scenario**: 네이버 로그인 페이지 클론 코딩(Phishing) 및 데이터 탈취 로직 구현
- **Analysis**: 로그인 시 발생하는 평문 패킷 흐름을 분석하여 **HTTPS 암호화 및 시큐어 코딩의 중요성** 실증
- **Tech Stack**: `PHP`, `JavaScript`, `HTML/CSS`, `Wireshark`

---

## 🛠 Tech Stack

### 🧠 AI & Data
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

### 💻 Backend & Infra
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## 🏆 Education & Awards

- **한국컴퓨터정보학회(KSCI) 하계/동계 학술대회** | 우수논문상 (2026.01)
  - 논문: *sLLM을 활용한 특허 거절사유 자동 생성 및 의미 기반 평가*
- **SK네트웍스 Family AI Camp 최종 프로젝트** | 우수상 (2025.11)
  - 주제: 기업 실무 연계형 특허 AI 에이전트 개발
- **SK Networks Family AI Camp (15기)** | AI/SW 개발자 과정 수료 (2025.05 - 2025.11)
- **LG Aimers** | AI 전문가 양성 과정 Phase 1 수료
- **오산대학교** | 컴퓨터소프트웨어과 졸업 (학점 3.76/4.5)
- **자격증** | 데이터분석 준전문가(ADsP)

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:4facfe,100:00f2fe&height=100&section=footer" />
</div>
