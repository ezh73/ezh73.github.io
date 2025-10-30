[# ezh73.github.io](https://ezh73.github.io/)

# 이력서

# AI 기술로 실제 가치를 만들어내는 서비스 빌더, 이지훈입니다.
# 비전공자로서 10개월 만에 5개의 프로젝트를 완성하며, 문제 정의부터 End-to-End 구현까지의 역량을 길렀습니다. 
# Python 백엔드에 전문성을 두고, AI를 활용하여 생산성을 극대화하는 문제 해결형 개발자입니다.

## 인적사항
- 이름: 이지훈  
- 연락처: 010-4236-2619  
- 이메일: ezh737@gmail.com  
- GitHub: [https://github.com/ezh73](https://github.com/ezh73)  

---

## 학력
- 경북대학교 지질학과 졸업 (2011.03 ~ 2018.08)

---

## 교육
- 융합 메디컬 AI with 스마트 웰니스 과정 수료 (2025.01 ~ 07)  
- 대경ICT산업협회 주관 데이터 분석·AI 부트캠프 (2025.07 ~ 2025.10.)  
  - 머신러닝/딥러닝, 데이터 전처리, 시각화, 웹서비스 구현 등 프로젝트 기반 학습  
  - 팀 프로젝트 및 개인 프로젝트 다수 수행  

---

## 프로젝트 경험

### 개인 프로젝트
- **Laions: 팬 참여형 AI 야구 예측 플랫폼 (2025.10.15. ~ 2025.10.30.)**  
  - **역할:** 기획 및 End-to-End 개발
  - **성과:**
    - 초기 기획의 문제점을 분석하고, **AI 예측과 팬 참여 중심으로 프로젝트 방향을 성공적으로 전환(Pivot)**하여 서비스 차별성 확보.
    - Gemini API의 실시간 호출 속도 문제를 해결하기 위해 DB 캐싱 구조를 직접 설계 및 구현하여 사용자 경험과 비용 효율성 개선.
    - 정규/포스트/비시즌에 따라 기능이 달라지는 복잡성을 해결하기 위해, '관리자 모드'를 직접 설계하여 테스트 용이성과 서비스 안정성 확보.
  - **기술:** FastAPI, React, LightGBM, Gemini API, PostgreSQL, Firebase, GitHub Actions


### 팀 프로젝트
- **CT 기반 폐 결절 악성 예측 모델 구현 (2025.04 ~ 05)**  
  - **역할:** AI 모델 성능 분석 및 기술 타당성 검증
  - **프로젝트 전체 기술 스택 :** Python, Pytorch, Transform, Convnext-tiny, CBAM, Grad-CAM
  - **나의 역할 및 기여:**
    - AI 모델 성능 분석 및 기술 타당성 검증
    - 프루닝, 양자화 등 다양한 모델 경량화 기법의 실현 가능성과 예상 효과를 직접 테스트하고 분석하여, 팀의 기술적 의사결정에 기여함.
  - **내가 사용한 기술:** Python, Pytorch, CBAM, Grad-CAM
    
- **음성 AI 기반 ADHD 조기 진단 지원 시스템 (2025.05 ~ 06)**  
  - **역할:** 백엔드 API 구축 및 프론트엔드 구조 개선
  - **프로젝트 전체 기술 스택 :** Python, FastAPI, SvelteKit, Whisper, gTTS, RapidFuzz, Zonos
  - **나의 역할 및 기여:**
    - 기존 Svelte의 페이지 처리 방식이 가진 구조적 한계를 분석하고, 폴더 기반 라우팅이 가능한 SvelteKit으로의 전환을 직접 제안하고 구현하여 서비스 확장성을 확보함.
    - FastAPI를 활용하여 음성 데이터를 처리하고 설문 결과를 저장하는 백엔드 API를 구축하여, 안정적인 실시간 음성 기반 설문 시스템의 기반을 마련함.
  - **내가 사용한 기술:** Python, FastAPI, SvelteKit, gTTS

- **뇌수막종 MRI 세그먼트 및 시각화 웹 시스템 (2025.06 ~ 07)**  
  - **역할:** 백엔드 전처리 구조 및 프론트엔드 구현
  - **프로젝트 전체 기술 스택 :** Python, FastAPI, SvelteKit, Pytorch, HD-BET, Transform
  - **나의 역할 및 기여:**
    - 사용자가 3D MRI 원본 영상을 그대로 업로드하면, 서버에서 자동으로 2D 이미지로 전처리되는 시스템 아키텍처를 제안하고 구현하여 사용자의 불편함을 획기적으로 개선.
    - FastAPI와 SvelteKit을 연동하여, AI 모델의 예측 결과를 사용자에게 시각적으로 전달하는 전체 파이프라인 구축.
  - **내가 사용한 기술:** Python, FastAPI, SvelteKit, HD-BET

- **제주 안전 관광 웹서비스 미리제주 (2025.09 ~ 2025.10.15.)**
  - **역할:** 예측 모델 설계 및 데이터 처리
  - **프로젝트 전체 기술 스택 :** Python, prophet, Langchain, Wordcloud, Figma, Oracle
  - **나의 역할 및 기여:**
    - 1억 건의 대규모 교통 데이터 처리를 위해 Pandas 대신 Polars와 LazyFrame을 도입하여 메모리 효율성 및 처리 속도 개선 시도.
    - 팀의 베이스라인 모델(Prophet) 외에, 더 복잡한 시계열 예측을 위해 NeuralProphet과 LightGBM을 활용한 모델링을 시도하며 성능 한계를 테스트함.
    - 데이터 수집의 법적/기술적 제약을 분석하고, 현실적인 대안(시뮬레이션)을 설계하며 데이터 품질의 중요성을 체득함.
  - **내가 사용한 기술:** Python, Polars, LightGBM, Neuralprophet



---

## 기술 스택
- **주력 기술 (Proficient):**
  - Backend: Python, FastAPI
  - AI / ML: Scikit-Learn, LightGBM, Pytorch
  - Database: PostgreSQL
  - Data Engineering: Pandas, Polars, Web Crawling

- **사용 경험 (Familiar with):**
  - Frontend: React, MUI, SvelteKit  
  - Infra & Auth: Firebase Authentication, GitHub Actions
  - AI API: Gemini API, OpenAI API
  - Database : Oracle
