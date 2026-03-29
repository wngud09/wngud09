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

🎯 **Focus**  
도메인 특화 sLLM 파인튜닝, RAG 최적화, 그리고 AI 워크플로우 설계에 관심을 갖고 있습니다.

💡 **Strength**  
**Full-Cycle Development**  
기획부터 데이터 수집·전처리, 모델 적용, 웹 서비스 구현·배포까지 전 과정을 연결하며 실제로 동작하는 서비스를 만드는 데 강점이 있습니다.  
**Communication**  
복잡한 기술 개념을 구조화해 문서화하고, PM 경험을 바탕으로 팀의 목표와 실행 방향을 조율하며 협업할 수 있습니다.

🚀 **Goal**  
단순한 기능 구현을 넘어, 효율화와 실질적인 비즈니스 임팩트로 이어지는 실용적인 AI 서비스를 만드는 것을 목표로 합니다.

---

## 💼 Featured Projects

### 1) ⚖️ Patent Rejection Reason Generation System: 로컬 LLM 기반 특허 거절 사유 생성 시스템
> **Repository**: [Veraclaim-Patent-Response-AI](https://github.com/wngud09/Patent-Rejection-Response-AI) > **🏆 Awards**: SK네트웍스 Family AI 캠프 **우수상** / 한국컴퓨터정보학회(KSCI) **우수논문상** 

민감한 특허 데이터를 보호하기 위해 외부 서버 전송이 없는 로컬 환경에서 Qwen2.5 모델을 운용하며, QLoRA 미세조정과 RAG를 결합해 심사관 관점의 논리적인 거절 사유를 생성하는 시스템입니다.  
정량 지표와 루브릭 기반 LLM 평가(LLM-as-a-Judge)를 결합한 하이브리드 검증 방식을 통해 생성 품질의 실무적 신뢰성을 확보했습니다.

**My Role:** PM · AI Integration Engineer · Chatbot API Manager

**My Contributions**
- 타깃 청구항과 상위 3개의 유사 청구항 컨텍스트를 결합한 chat-style 입력 구조 설계 및 대규모 특허 데이터 전처리 파이프라인 구축
- Qwen2.5 기반 4-bit QLoRA 경량 미세조정 및 Rank Sweep 실험을 통한 도메인 적응 성능 최적화
- GPT-4o-mini 기반 5단계 루브릭 평가 시스템 구축 및 다단계 점수 안정화(Strict Parsing, Fallback) 로직 구현
- FAISS 기반 Vector DB와 임베딩 모델을 활용하여 유사 청구항 및 거절 사례를 탐색하는 RAG 모듈 통합
- Django REST Framework와 Next.js 간 인터페이스를 관리하고, 관리자 승인 기반의 보안 회원가입(Pending status) 프로세스 구현
- 특허법 조문, 심사기준, 관련 논문 데이터를 통합하여 생성 답변의 법적 근거와 배경지식을 강화하는 다중 소스 컨텍스트 구성

**Project Features**
- 온프레미스(On-premise) LLM 환경 구축을 통한 기업 기밀 정보 및 특허 아이디어 유출 방지
- ROUGE, BLEU, BERTScore, chrF를 결합한 다각적 정량 품질 평가
- 인간 평가 라벨과 Judge 점수 간 상관관계(Pearson 0.611) 검증을 통한 평가 체계의 객관성 확보
- 등록/거절 예측 분류 모델과 근거 생성 모델의 역할 분리를 통한 시스템 처리 효율 최적화

**Tech Stack**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL(PGVector)-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square)
![Qwen2.5](https://img.shields.io/badge/Qwen2.5(QLoRA)-7A3EFF?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=flat-square&logo=amazon-ec2&logoColor=white)
![AWS RDS](https://img.shields.io/badge/AWS_RDS-527FFF?style=flat-square&logo=amazonrds&logoColor=white)

---

### 2) 📝 Django RAG Study Assistant: 학습 보조 & Anki 생성 웹 서비스
> **Repository**: [Django-RAG-Study-Assistant-Web](https://github.com/wngud09/Django-RAG-Study-Platform)

사용자와 챗봇의 학습 대화를 Anki와 연동하여 복습 가능한 학습 카드로 전환하고, 장기 기억 형성을 지원하는 지능형 지식 관리 시스템입니다.  
다중 소스 RAG와 LangGraph 기반 라우팅을 통해 정확한 학습 정보를 제공하고, Django 기반 웹 서비스로 확장해 실제 사용성을 높였습니다.

**My Role:** AI Integration Engineer · Chatbot API Manager

**My Contributions**
- 질문·답변 데이터를 4지선다형 문제와 해설 형태로 변환하는 복습 카드 파싱 로직 설계
- AnkiConnect API를 활용해 생성된 카드를 Anki 덱에 자동 저장하는 연동 모듈 구현
- LangGraph 기반 AI 엔진을 API 형태로 추상화하고 Django 백엔드와의 인터페이스 관리
- AI 기능과 웹 서비스 간 연결 구조를 정리하여 서비스 환경에서 안정적으로 동작하도록 통합
- Git 브랜치 전략 및 충돌 해결 과정에 참여하며 협업 효율 개선

**Project Features**
- PGVector, PDF, 웹 검색을 결합한 Multi-source RAG
- LangGraph 기반 질문 의도 분석 및 라우팅
- 자동 복습 카드 생성 및 Anki 연동
- Django 기반 사용자 계정 및 대화 이력 관리

**Tech Stack**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square)
![LangGraph](https://img.shields.io/badge/LangGraph-0E7C86?style=flat-square)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=flat-square&logo=amazon-ec2&logoColor=white)

---

### 3) 🧑‍🍳 아리계곡 AI 점주용 데이터 분석 & 마케팅 에이전트
> **Repository**: [AI-Store-Manager-Agent](https://github.com/o2fms/fms-platform)

**My Role:** APM(Assistant Product Manager) · AI Integration Engineer

**My Contributions**
- LangChain SQL Agent를 활용해 점주의 자연어 질의를 SQL로 변환하고, POS 매출 DB를 실시간 조회하여 핵심 지표를 산출하는 NL2SQL 기반 매장 진단 엔진 설계
- 내부 매출 데이터에 날씨 API, 네이버 플레이스 순위 등 외부 소스를 결합해 매출 변동 원인을 다각도로 분석하는 Multi-Source 컨텍스트 기반 의사결정 로직 구현
- 분석 결과를 바탕으로 ‘라이징 인플루언서’ 탐색 및 맞춤형 제안 문구를 자동 생성하는 Marketing-as-a-Service 워크플로우를 기획하고, Human-in-the-loop 승인 프로세스를 통해 운영 안정성 확보
- 비정형 매출 엑셀 데이터를 정규화된 PostgreSQL 데이터베이스로 자동 적재하는 수집·전처리 파이프라인(`scripts/pipeline`) 구축 및 자동화
- `few_shot_examples.json` 기반 프롬프트 엔지니어링을 통해 매장 도메인 특화 용어와 복잡한 매출 구조에 대한 모델 이해도를 높여 SQL 생성 정확도 향상
- FastAPI 기반 도메인 라우터를 설계하여 사용자 질문의 의도(매출 분석 / 리뷰 감성 분석)를 판별하고 적절한 서비스 모듈로 자동 분기되는 백엔드 구조 구현

**Project Features**
- 채팅 기반 ChatBI 인터페이스를 통해 “어제 매출 하락 원인 분석해줘”와 같은 자연어 질의에 대해 데이터 기반 Insight와 Action Plan 제공
- AI의 분석 단계를 실시간으로 시각화하는 Live Thinking 기능을 통해 추론 과정의 투명성을 확보하고 사용자 신뢰도 및 UX 향상
- 단순 매출 및 데이터 조회 테스트셋 50개 기준 SQL 쿼리 생성 정확도 90% 달성
- 기존 수 시간이 걸리던 데이터 수집, 분석, 마케팅 전략 수립, 인플루언서 섭외 프로세스를 5분 이내로 단축하여 운영 효율화 실현

**Tech Stack**  
![Python](https://img.shields.io/badge/Python(FastAPI)-009688?style=flat-square&logo=python&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js(React)-000000?style=flat-square&logo=next.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL(Prisma)-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square)
![OpenAI API](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=flat-square&logo=amazon-ec2&logoColor=white)

---

### 4) ⚖️ Legal RAG Chatbot: 법률 정보 검색 어시스턴트
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
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

### 5) 📡 Telecom Churn Prediction: 통신사 고객 이탈 예측 대시보드
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
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-EC6B23?style=flat-square)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=flat-square)
![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?style=flat-square)
---

### 6) 🚗 Korean Used Car Market Analysis: 중고차 시세 분석 시각화
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
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)

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
- **SK네트웍스 Family AI캠프(15기) 기업 참여 프로젝트** | 우수상 (2025.11)
  - 주제: 로컬 LLM 기반 특허 거절 사유 생성 시스템

### 🎓 Education
- **SK네트웍스 Family AI캠프 (15기)** | AI/SW 개발자 과정 수료 (2025.05 - 2025.11)
- **LG Aimers** | AI 전문가 양성 과정 8기 수료 (2026.01 - 2026.03)
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
