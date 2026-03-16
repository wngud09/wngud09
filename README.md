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

**"데이터 흐름을 설계하고, AI로 실무의 비효율을 해결합니다."** 문제의 본질을 파악하여 **최적의 모델을 선정(Model Selection)** 하고,  
사용자가 실제로 활용 가능한 **안정적인 서비스(Full-Stack AI)** 를 구축합니다.

</div>

---

## 🙋‍♂️ About Me

- 🎯 **Focus**: Domain-Specific **sLLM Fine-tuning**, **RAG Optimization**, **Agentic Workflow**
- 💡 **Strength**: 
  - **Full-Cycle Dev**: 기획부터 데이터 수집, 전처리, 모델링, 웹 서비스 배포까지 **E2E 개발** 을 주도합니다.
  - **Communication**: 복잡한 기술 개념을 명확히 문서화하고, PM으로서 팀의 목표를 조율하는 협업 역량을 갖췄습니다.
- 🚀 **Goal**: 단순한 기능 구현을 넘어, **비즈니스 임팩트(ROI, 효율화)** 를 창출하는 실용적인 AI 서비스를 만듭니다.

---

## 💼 Featured Projects

### 1) ⚖️ Veraclaim: 특허 거절 사유 예측 및 자동 대응 AI
> **Repository**: [Veraclaim-Patent-Response-AI](https://github.com/wngud09/Patent-Rejection-Response-AI) > **🏆 Awards**: SK네트웍스 Family AI 캠프 **우수상** / 한국컴퓨터정보학회(KSCI) **우수논문상** 

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
> **Repository**: [Django-RAG-Study-Assistant-Web](https://github.com/wngud09/Django-RAG-Study-Platform)

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

### 3) ⚖️ Legal RAG Chatbot: 법률 정보 검색 어시스턴트
> **Repository**: [Legal-RAG-Assistant](https://github.com/wngud09/Legal-RAG-Chatbot)

약 5.5만 건의 판례 데이터를 활용하여 사용자의 질문과 관련된 법률 근거를 검색하고, 이를 바탕으로 자연스러운 상담 답변을 생성하는 RAG 기반 챗봇 서비스입니다.

**My Role:** AI/LLM Engineer · DevOps / MLOps

**My Contributions**
- LangChain 기반으로 벡터 검색과 LLM 응답 생성을 결합한 RAG 파이프라인 설계 및 구현
- FAISS 인덱스를 활용해 수만 건의 판례 데이터에 대한 고속 유사도 검색 시스템 구축
- Upstage Embeddings와 OpenAI GPT-4o를 연동하여 법률 문맥 이해와 답변 품질 최적화
- 프롬프트 엔지니어링을 통해 검색된 판례 근거 중심으로 답변하도록 설계하여 환각 현상 완화
- Docker / Docker-Compose를 도입해 개발 환경을 표준화하고 실행 환경 재현성 확보
- entrypoint.sh 기반 초기화 자동화 및 환경 설정 구조 정비로 운영 효율 개선

**Project Features**
- 사용자 질문 기반 지능형 법률 상담
- 사건명 / 사건번호 기반 정밀 판례 검색
- 검색된 판례를 근거로 한 RAG 기반 답변 생성
- 컨테이너 기반 실행 환경 표준화

**Tech Stack**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Upstage](https://img.shields.io/badge/Upstage-000000?style=flat-square)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)

---

### 4) 📡 Telecom Churn Prediction: 통신사 고객 이탈 예측 대시보드
> **Repository**: [Telecom-Customer-Churn-Dashboard](https://github.com/wngud09/Telecom-Customer-Churn-Prediction)

**My Role:** Streamlit Web Dashboard Development

**My Contributions**
- Streamlit 기반의 웹 서비스 화면 구성 및 사용자 인터페이스 구현
- 프로젝트 개요, EDA, 모델링 결과, 인사이트 요약 등 주요 페이지를 대시보드 형태로 정리
- 사용자가 CSV 파일을 업로드해 실시간으로 이탈 확률과 예측 결과를 확인할 수 있는 시뮬레이션 기능 구현
- 데이터 탐색(EDA) 및 모델 성능 비교 결과를 시각적으로 전달할 수 있도록 화면 흐름 구성
- 웹 구현뿐 아니라 EDA와 모델 평가 과정에도 참여하며 전체 분석 파이프라인을 이해하고 협업 수행

**Project Features**
- 고객 이탈 분포 및 주요 변수별 이탈률 시각화
- XGBoost 및 Soft Voting 모델 성능 비교
- CSV 업로드 기반 이탈 예측 시뮬레이션
- 주요 이탈 요인 분석 및 비즈니스 인사이트 제공

**Results**
- **XGBoost:** Accuracy 0.7162 / Recall 0.5644
- **Soft Voting Ensemble:** Accuracy 0.6388 / Recall 0.6386
- 가입 후 1년 미만 고객, 기기 사용일수가 오래된 고객, 낮은 요금제 사용 고객에서 높은 이탈률을 확인하고 맞춤형 리텐션 전략을 제안

**Tech Stack**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-8B4513?style=flat-square)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
---

### 5) 🚗 Korean Used Car Market Analysis: 중고차 시세 분석 시각화
> **Repository**: [Korean-Used-Car-Analysis-Dashboard](https://github.com/wngud09/Korean-Used-Car-Market-Analysis)

보배드림, 엔카, 차차차 등 국내 주요 중고차 플랫폼 데이터를 통합하여, 차량 시세 검색·비교와 시장 트렌드 시각화를 제공하는 프로젝트입니다.

**My Role:** Web Crawling / Data Collection

**My Contributions**
- 중고차 플랫폼의 차량 데이터를 수집하기 위한 크롤링 작업 수행
- 사이트별 페이지 구조를 분석하여 차량명, 가격, 연식, 주행거리 등 주요 정보 추출
- 수집 데이터를 후속 DB 저장 및 시각화에 활용할 수 있도록 정리
- 데이터 수집 단계에 참여하며 전체 데이터 파이프라인 흐름 이해 및 협업 수행

**Project Features**
- 차량 조건별 통합 검색 및 가격 비교
- 브랜드/모델/색상/가격 분포 시각화
- 중고차 구매 관련 FAQ 제공

**Tech Stack**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-8B4513?style=flat-square)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)

---

### 6) 🧑‍🍳 AI Store Manager Agent: 매장 매출 분석 & 운영 자동화 (In Progress)
> **Repository**: [AI-Store-Manager-Agent](https://github.com/o2fms/fms-platform)

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
