> **AI Developer |**
> 실무 데이터를 분석하여 문제를 해결하고, 효율적인 AI 서비스를 구현하는 데 집중합니다.

---

<p align="center">
  <a href="#-about-me">소개</a> ·
  <a href="#-featured-projects">프로젝트</a> ·
  <a href="#-tech-stack">기술 스택</a> ·
  <a href="#-education--awards">수상 및 교육</a>
</p>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:4facfe,100:00f2fe&height=220&section=header&text=Hello,%20I'm%20Developer&fontSize=70&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%20Engineer%20%7C%20Data%20Driven%20Solution&descAlignY=55&descAlign=50" />
</div>

<div align="center">
  
### 👋 Welcome to My GitHub

**"데이터 흐름을 설계하고, AI로 실무의 비효율을 해결합니다."** 보안(Security) 엔지니어링 베이스 위에 sLLM, RAG 등 최신 AI 기술을 결합하여, **비즈니스 임팩트가 있는 안정적인 서비스**를 구축합니다.

![Visitor Badge](https://visitor-badge.laobi.icu/badge?page_id=your_github_id.visitor_badge)

</div>

---

## 🙋‍♂️ About Me

- 🎯 **Focus**: Domain-Specific sLLM, RAG Optimization, Multi-Agent System
- 🛡️ **Background**: 네트워크 보안 기업 인턴 & MITM 모의해킹 경험 → **System Security & Stability** 중시
- 💡 **Strength**: 
  - **Full-Cycle Dev**: 데이터 수집부터 모델 튜닝(Fine-tuning), 백엔드 API, 웹 배포까지 **E2E 개발 주도**
  - **Communication**: 복잡한 기술 개념을 시각화/문서화하고, PM으로서 팀을 리딩하는 협업 역량
- 🚀 **Goal**: 단순 기능 구현을 넘어, **비용 효율(Cost-Efficiency)과 신뢰성(Reliability)**을 갖춘 AI 파이프라인 설계

---

## 💼 Featured Projects

### 1) ⚖️ Veraclaim: 특허 거절 사유 예측 및 자동 대응 AI
> **🏆 Awards**: SK네트웍스 Family AI 캠프 **우수상** / 한국컴퓨터정보학회(KSCI) **우수논문상** > **Repository**: [Veraclaim-Patent-Response-AI](https://github.com/your-id/Veraclaim-Patent-Response-AI)

특허 출원 비용과 심사 대기 시간을 줄이기 위해, **거절 가능성을 사전 진단하고 대응 논리를 자동 생성**하는 도메인 특화 sLLM 솔루션입니다.

- **Role**: PM, AI 모델링(Qwen-14B Fine-tuning), RAG 파이프라인 설계, 백엔드 개발
- **Key Tech**:
  - **sLLM Optimization**: `Qwen-2.5-14B`에 QLoRA를 적용하여 한국어 특허 데이터 6,000건 학습 (Accuracy 0.87 달성)
  - **Reliable RAG**: GPT Score & Spearman 상관계수를 도입한 **Multi-Metric 평가**로 생성 신뢰도 검증
  - **Architecture**: Django & Next.js 기반의 **관리자 권한 분리(RBAC)** 및 OpenSearch 검색 엔진 구축

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![OpenSearch](https://img.shields.io/badge/OpenSearch-005E7C?style=flat-square&logo=opensearch&logoColor=white)

---

### 2) 📝 Django RAG Study Assistant: 학습 보조 & Anki 생성 웹 서비스
> **Repository**: [Django-RAG-Study-Assistant-Web](https://github.com/your-id/Django-RAG-Study-Assistant-Web)

강의 자료를 업로드하면 **RAG 기반으로 질의응답**을 제공하고, **암기 카드(Anki)를 자동 생성**해주는 학습 보조 웹 플랫폼입니다.

- **Key Features**:
  - **Multi-Agent RAG**: 질문의 의도를 파악하여 단순 검색/심층 분석 에이전트로 분기 처리
  - **Auto-Anki**: 중요 개념을 추출하여 Anki(apkg) 파일로 자동 변환 및 다운로드 제공
  - **Real-time Chat**: Django Channels를 활용한 실시간 스트리밍 답변 및 채팅 인터페이스
- **Tech Stack**: `Django`, `LangChain`, `ChromaDB`, `Redis`, `Celery`

---

### 3) 📡 Telecom Churn Prediction: 통신사 고객 이탈 예측 대시보드
> **Repository**: [Telecom-Customer-Churn-Dashboard](https://github.com/your-id/Telecom-Customer-Churn-Dashboard)

Cell2Cell 데이터셋을 활용하여 **이탈 위험 고객을 조기에 식별**하고, 마케팅 전략 수립을 돕는 분석 대시보드입니다.

- **Insight**: 단순 예측을 넘어, **'서비스 품질'과 '이탈률'의 상관관계**를 히트맵으로 시각화하여 비즈니스 액션 도출
- **Modeling**: LightGBM, CatBoost 앙상블 모델을 적용하여 예측 정확도 최적화
- **Viz**: Streamlit을 활용하여 이탈 확률 분포 및 주요 변수 중요도(Feature Importance) 대시보드 구현

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

---

### 4) 🚗 Korean Used Car Market Analysis: 중고차 시세 분석 시각화
> **Repository**: [Korean-Used-Car-Analysis-Dashboard](https://github.com/your-id/Korean-Used-Car-Analysis-Dashboard)

보배드림, 엔카, KB차차차 등 국내 주요 중고차 플랫폼 데이터를 크롤링하여 **차종별 시세 트렌드와 선호도**를 분석했습니다.

- **Process**: `Selenium`/`BeautifulSoup` 기반 동적 크롤링 → 데이터 전처리 → 시각화 파이프라인 구축
- **Output**: 브랜드별 감가율 분석 및 가격대별 추천 차종 FAQ 시스템 구현

---

### 5) ⚖️ Legal RAG Chatbot: 법률 정보 검색 어시스턴트
> **Repository**: [Legal-RAG-Assistant](https://github.com/your-id/Legal-RAG-Assistant)

복잡한 법률 용어와 판례를 일반인이 쉽게 이해할 수 있도록 돕는 **법률 특화 RAG 챗봇**입니다.

- **Tech**: 판례 데이터 임베딩(Vector DB) 및 LLM 기반의 자연어 답변 생성
- **Deploy**: Docker 컨테이너 기반의 배포 환경 구축으로 이식성 확보

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
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## 🏆 Education & Awards

- **한국컴퓨터정보학회(KSCI) 하계/동계 학술대회** | 우수논문상 (2026)
  - 논문: *sLLM을 활용한 특허 거절사유 자동 생성 및 의미 기반 평가*
- **SK네트웍스 Family AI Camp 최종 프로젝트** | 우수상 (2025)
  - 주제: 기업 실무 연계형 특허 AI 에이전트 개발
- **SK Networks Family AI Camp (15기)** | AI/SW 개발자 과정 수료
- **LG Aimers** | AI 전문가 양성 과정 (Phase 1 수료)
- **네트워크 보안 기업 인턴** | 기술지원 및 인프라 진단 (TCP/IP, 방화벽)

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:4facfe,100:00f2fe&height=100&section=footer" />
</div>
---

### 📊 GitHub Stats
![GitHub activity](https://github-readme-stats.vercel.app/api?username=wngud09&show_icons=true&theme=radical)

![contribution graph](https://github-readme-streak-stats.herokuapp.com/?user=wngud09&theme=radical)

