<p align="center">
  <a href="#-about-me">소개</a> ·
  <a href="#-featured-projects">프로젝트</a> ·
  <a href="#-tech-stack">기술 스택</a> ·
  <a href="#-education--awards">수상 및 교육</a>
</p>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:4facfe,100:00f2fe&height=220&section=header&text=Hello,%20I'm%20JuHyeong&fontSize=70&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%20Engineer%20%7C%20Data%20Driven%20Solution&descAlignY=55&descAlign=50" />
</div>

<div align="center">
  
### 👋 Welcome to My GitHub

**"데이터 흐름을 설계하고, AI로 실무의 비효율을 해결합니다."** 문제의 본질을 파악하여 **최적의 모델을 선정(Model Selection)**하고,  
사용자가 실제로 활용 가능한 **안정적인 서비스(Full-Stack AI)**를 구축합니다.

</div>

---

## 🙋‍♂️ About Me

- 🎯 **Focus**: Domain-Specific **sLLM Fine-tuning**, **RAG Optimization**, **Agentic Workflow**
- 💡 **Strength**: 
  - **Full-Cycle Dev**: 기획부터 데이터 수집, 전처리, 모델링, 웹 서비스 배포까지 **E2E 개발**을 주도합니다.
  - **Communication**: 복잡한 기술 개념을 명확히 문서화하고, PM으로서 팀의 목표를 조율하는 협업 역량을 갖췄습니다.
- 🚀 **Goal**: 단순한 기능 구현을 넘어, **비즈니스 임팩트(ROI, 효율화)**를 창출하는 실용적인 AI 서비스를 만듭니다.

---

## 💼 Featured Projects

### 1) ⚖️ Veraclaim: 특허 거절 사유 예측 및 자동 대응 AI
> **🏆 Awards**: SK네트웍스 Family AI 캠프 **우수상** / 한국컴퓨터정보학회(KSCI) **우수논문상** > **Repository**: [Veraclaim-Patent-Response-AI](https://github.com/your-id/Veraclaim-Patent-Response-AI)

특허 심사 비용과 시간을 줄이기 위해, **거절 가능성을 사전 진단하고 대응 논리를 자동 생성**하는 도메인 특화 sLLM 솔루션입니다.

- **Role**: PM, AI 모델링(sLLM), RAG 파이프라인 설계, 백엔드 개발
- **Key Tech**:
  - **sLLM Optimization**: `Qwen-2.5-14B`에 QLoRA를 적용하여 한국어 특허 데이터 6,000건 학습 (**Accuracy 0.87** 달성)
  - **Reliable RAG**: GPT Score & Spearman 상관계수를 도입한 **Multi-Metric 평가**로 생성 결과의 논리적 타당성 검증
  - **Architecture**: Django & Next.js 기반의 **관리자 권한 분리(RBAC)** 및 OpenSearch 검색 엔진 구축

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

### 2) 📝 Django RAG Study Assistant: 학습 보조 & Anki 생성 웹 서비스
> **Repository**: [Django-RAG-Study-Assistant-Web](https://github.com/your-id/Django-RAG-Study-Assistant-Web)

강의 자료를 업로드하면 **RAG 기반으로 질의응답**을 제공하고, 중요 개념을 **암기장(Anki) 파일로 자동 변환**해주는 학습 플랫폼입니다.

- **Role**: Full-Stack Developer (Django, LangChain)
- **Key Tech**:
  - **Multi-Agent System**: 질문 의도에 따라 단순 검색/심층 분석 에이전트로 자동 분기 처리하여 답변 품질 향상
  - **Auto-Anki Pipeline**: 강의 내용에서 핵심 키워드를 추출하여 `.apkg` 파일 자동 생성 및 다운로드 제공
  - **Real-time Architecture**: Django Channels와 Redis를 활용한 **실시간 스트리밍 답변** 및 비동기 작업 처리

![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=chainlink&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)

---

### 3) 📡 Telecom Churn Prediction: 통신사 고객 이탈 예측 대시보드
> **Repository**: [Telecom-Customer-Churn-Dashboard](https://github.com/your-id/Telecom-Customer-Churn-Dashboard)

Cell2Cell 데이터셋을 활용하여 **이탈 위험 고객을 조기에 식별**하고, 마케팅 전략 수립을 돕는 분석 대시보드입니다.

- **Role**: Data Analyst & ML Engineer
- **Key Tech**:
  - **Insight Analysis**: 단순 예측을 넘어, **'서비스 품질'과 '이탈률'의 상관관계**를 히트맵으로 시각화하여 비즈니스 액션 도출
  - **Ensemble Modeling**: LightGBM, CatBoost 앙상블 모델을 적용하여 이탈 예측 정확도 최적화
  - **Interactive Viz**: Streamlit을 활용하여 이탈 확률 분포 및 **주요 변수 중요도(Feature Importance)** 대시보드 개발

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

---

### 4) ⚖️ Legal RAG Chatbot: 법률 정보 검색 어시스턴트
> **Repository**: [Legal-RAG-Assistant](https://github.com/your-id/Legal-RAG-Assistant)

복잡한 법률 용어와 판례를 일반인이 쉽게 이해할 수 있도록 돕는 **법률 특화 RAG 챗봇**입니다.

- **Role**: AI Application Developer
- **Key Tech**:
  - **Legal RAG Engine**: 판례 데이터 임베딩 및 벡터 DB(FAISS) 기반의 **의미 기반 검색(Semantic Search)**
  - **Context Awareness**: 대화 맥락을 유지하며 사용자의 질문에 관련된 법률 조항을 정확히 인용하여 답변
  - **Containerization**: Docker 컨테이너 기반의 배포 환경 구축으로 이식성 및 배포 편의성 확보

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=chainlink&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

### 5) 🚗 Korean Used Car Market Analysis: 중고차 시세 분석 시각화
> **Repository**: [Korean-Used-Car-Analysis-Dashboard](https://github.com/your-id/Korean-Used-Car-Analysis-Dashboard)

보배드림, 엔카 등 국내 주요 중고차 플랫폼 데이터를 수집하여 **차종별 시세 트렌드와 선호도**를 분석했습니다.

- **Role**: Data Engineer & Pipeline Builder
- **Key Tech**:
  - **Automated Pipeline**: `Selenium`과 `BeautifulSoup`을 활용한 동적 크롤링 및 데이터 전처리 자동화
  - **Market Analysis**: 브랜드별 감가율 분석 및 가격대별 추천 차종 FAQ 시스템 구현
  - **Dashboarding**: Plotly와 Streamlit을 연동한 인터랙티브 시세 시각화

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

---

### 6) 🧑‍🍳 AI Store Manager Agent: 매장 매출 분석 & 운영 자동화 (In Progress)
> **Repository**: [AI-Store-Manager-Agent](https://github.com/your-id/AI-Store-Manager-Agent)

POS/매출 데이터와 외부 변수(날씨, 트렌드)를 통합 분석하여 **매출 하락 원인을 설명**하고, 마케팅 실행을 자동화하는 **AI 점장 에이전트**입니다.

- **Role**: AI Engineer (Agentic Workflow Design)
- **Key Tech**:
  - **ReAct Workflow**: [현황 분석 → 계획 → 실행 → 검토 → 제안]의 루프를 통해 능동적으로 문제 해결
  - **Marketing Automation**: 라이징 인플루언서 발굴/스코어링 및 **컨택 메일 초안 자동 생성**
  - **Operations Logic**: 직원 스케줄 추천, **손익계산서(P&L) 자동화**, 네이버 플레이스 순위 추적

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=chainlink&logoColor=white)
![BigQuery](https://img.shields.io/badge/Google%20BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
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

### 🏅 Awards
- **한국컴퓨터정보학회(KSCI) 하계/동계 학술대회** | 우수논문상 (2026.01)
  - 논문: *sLLM을 활용한 특허 거절사유 자동 생성 및 의미 기반 평가*
- **SK네트웍스 Family AI Camp 최종 프로젝트** | 우수상 (2025.11)
  - 주제: 기업 실무 연계형 특허 AI 에이전트 개발

### 🎓 Education
- **SK Networks Family AI Camp (15기)** | AI/SW 개발자 과정 수료 (2025.05 - 2025.11)
- **LG Aimers** | AI 전문가 양성 과정 Phase 1 수료 
- **오산대학교** | 컴퓨터소프트웨어과 졸업 (학점 3.76/4.5)

### 📜 Certificates
- **데이터분석 준전문가 (ADsP)** | 한국데이터산업진흥원
- **SQL 개발자 (SQLD)** | 한국데이터산업진흥원
- **정보처리산업기사** | 한국산업인력공단
- **리눅스마스터 2급** | 한국정보통신진흥협회
---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:4facfe,100:00f2fe&height=100&section=footer" />
</div>
