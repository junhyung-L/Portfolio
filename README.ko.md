# 이준형 | 데이터 사이언스 · AI 포트폴리오

[English](README.md)

고객·정책·공간 데이터로 예측 모델과 의사결정 시뮬레이션을 만듭니다. 각 저장소에 데이터, 평가 조건, 결과가 보여 주는 것과 보여 주지 않는 것을 함께 적었습니다.

현재 하나금융융합기술원 BigData&AI Cell 인턴(2026.07–)입니다. 인천대학교 DIVE Lab 학부연구생(2025.02–2026.02)으로 아래 CRM 논문을 제1저자로 썼고, 마케팅 피로도에 대한 인과추론 후속 연구를 진행 중입니다.

## 대표 작업

### 동태적 마케팅 지식 기반 구매 전환 예측

제1저자 논문, 『마케팅연구』(한국마케팅학회) 2026년 11월 게재 예정. [crm-conversion-prediction](https://github.com/junhyung-L/crm-conversion-prediction)

전환율 0.1234%인 REES46 CRM 메시지 1억 7,200만 건에서 마케팅 이론을 4대 동태적 피처군(구매 주기, 시계열적 반응, 피로도, 채널 효과성)으로 만들고 9종 모형을 비교했습니다. 이 피처를 더한 XGBoost가 원분포 holdout에서 F1(0.3806)과 PR-AUC(0.3620)가 가장 높았습니다. 상위 0.78% 메시지만 발송하면 전환의 95.83%를 정밀도 15.26%(lift 123.7배)로 포착합니다.

### 산림 작물 적합지·생산량 분석

2024 임업통계 스마트활용 경진대회 · 대상(산림청장상) · 2024.12.13. [forestry-crop-suitability](https://github.com/junhyung-L/forestry-crop-suitability)

GIS 토양 레이어, 기후, 생산 데이터를 7개 산림 작물에 연결하고, 통계 검정으로 변수를 고른 뒤 작물마다 모델을 골랐습니다. 결과물은 신규 임업인을 위한 재배 적합지 분석과 지도 서비스 구상입니다.

### 인천 e음 캐시백 정책 시뮬레이션

2025 인천대학교 산학 캡스톤디자인 경진대회 · 금상 · 2025.07.01. 4인 팀 팀장. [incheon-eeum-policy-simulation](https://github.com/junhyung-L/incheon-eeum-policy-simulation)

캐시백 5%·10% 조건별로 LightGBM으로 군·구 소비를 예측하고, 예산 2,000억 원 안에서 두 달짜리 캐시백 일정 66개를 소비 창출과 잔여 예산 기준으로 순위를 매겼습니다. 시나리오 비교이며 정책의 인과 효과 추정은 아닙니다.

### 동인천 원도심 상권 마케팅 파일럿

2025 PBL 프로그램 · 대상(인천광역시장상) · 2026.02.27. [dongincheon-marketing-pilot](https://github.com/junhyung-L/dongincheon-marketing-pilot)

Marketing & Data Analysis 역할로 공실 데이터와 상인 인터뷰를 원도심 매장 마담티의 실행 과제로 정리하고, 30일 파일럿 동안 네이버 플레이스·인스타그램·숏폼을 운영했습니다.

## 전체 프로젝트

| 분야 | 프로젝트 | 요약 |
|---|---|---|
| CRM 연구 | [동태적 마케팅 지식 기반 구매 전환 예측](https://github.com/junhyung-L/crm-conversion-prediction) | 제1저자 논문: 이론 기반 피처를 9종 모형으로 검증 |
| 추천·광고 | [DCN-V2와 행동 시퀀스 인코더를 활용한 CTR 예측](https://github.com/junhyung-L/ctr-sequence-modeling) | DCN-V2와 DIN·DIEN·BST 시퀀스 인코더 |
| 고객 분석 | [신용카드 고객 세그먼트 분류](https://github.com/junhyung-L/credit-card-customer-segmentation) | 857개 컬럼의 결측을 고려한 분류 |
| 가격 | [중고 전기차 가격 예측](https://github.com/junhyung-L/used-ev-price-forecasting) | 배터리 용량 대체와 XGBoost 가격 회귀 |
| 정책 시뮬레이션 | [인천 e음 캐시백 정책 시뮬레이션](https://github.com/junhyung-L/incheon-eeum-policy-simulation) | 예산 제약 아래 캐시백 일정 66개 비교 |
| 수요 시뮬레이션 | [신제품 콜드스타트 수요 시뮬레이션](https://github.com/junhyung-L/cold-start-demand-simulation) | 신제품 식품 15종의 페르소나 기반 몬테카를로 |
| GIS·산림 | [산림 작물 적합지·생산량 분석](https://github.com/junhyung-L/forestry-crop-suitability) | 작물별 적합지·생산량 모델 |
| 공간 안전 | [Fallin: 고령 보행자 낙상 위험 GIS 지도](https://github.com/junhyung-L/fallin-gis-risk-mapping) | 규칙 기반 보행 낙상 위험 지도 프로토타입 |
| 현장 마케팅 | [동인천 원도심 상권 마케팅 파일럿](https://github.com/junhyung-L/dongincheon-marketing-pilot) | 현장 조사와 30일 매장 파일럿 |
| LLM 앱 | [Job Simulator AI](https://github.com/junhyung-L/ai-interview-simulator) | 구조화된 피드백을 주는 Next.js 역할극 연습 |
| 수업 과제 | [학생 우울 설문 분석](https://github.com/junhyung-L/student-depression-risk-analysis) | 설문 데이터의 해석 가능한 로지스틱 회귀 |

각 저장소에는 README(방법과 결과)와 사례 연구(`PORTFOLIO.ko.md`: 주요 결정, 대가, 한계)가 있습니다. 수치마다 측정 조건(holdout, 검증, 리더보드, 시뮬레이션, 현장 파일럿)이 다르며, 각 README에 조건을 적었습니다.

상장 사본은 요청 시 제공합니다.

---

[이력서](https://github.com/junhyung-L/Resume) · [GitHub](https://github.com/junhyung-L) · [LinkedIn](https://www.linkedin.com/in/junhyung-lee-data) · [Email](mailto:jun010914@inu.ac.kr)
