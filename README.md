## 광고 예산안 최적화 모형 구축

### 프로젝트 개요
- 목적: **광고 예산안 최적화 모형 구축을 통한 업무 효율성 개선**
- 기간: 2021. 1 ~ 2021. 5(5개월)
- 역할: 데이터 전처리, 머신러닝 모형 구축, 대시보드 제작
- Skills: Python(scikit-learn, numpy, pandas, pymysql 등), MySQL

### 추진 배경
대형 광고주의 이탈이 발생하였으나 신규로 유입된 광고주는 대부분 소규모 광고주로, 집행해야하는 광고주 수는 20% 증가했지만 매출은 15% 감소한 상황이었습니다.
이에 따라 업무 효율성을 개선하기 위해 **소규모 광고주 대상 광고 예산안 최적화 모형을 구축**했습니다.

### 진행 과정
광고 목적에 따라 예산안을 구성되는 프로세스에 맞춰 광고 목적별로 KPI(광고 지표)를 선정하여 모델을 세분화했습니다.
또한, 광고 상품 수가 많은 관계로 광고 상품별 개별 모형 구축이 아닌 multi-output regression 을 활용하여 한 번에 광고 상품별 광고비를 예측했습니다.
이를 통해 광고 목적별 KPI 상위 그룹의 집행 패턴을 반영한 **광고 예산안 최적화 모형을 구축**했습니다.
그 결과 **제안 업무 효율성을 50% 개선**할 수 있었고, 관련 외주 프로젝트 2건의 계약이 체결되어 최적화 모형 구축을 진행했습니다.
- 데이터 수집: (API) 광고 플랫폼별 캠페인 집행 데이터
- 변수 설정: (독립) 광고 효과 기반 세그먼트 / (종속) 광고비 비중
- 분석 모형: Multi-output regression

### 파일 링크
[#1. pandas를 활용한 데이터 전처리 및 seaborn를 활용한 데이터 시각화](https://github.com/hyewon0403/media-mix-recommendation/blob/master/media_mix_recommendation_eda.ipynb)\
[#2. sklearn를 활용한 광고 예산안 최적화 모형 구축](https://github.com/hyewon0403/media-mix-recommendation/blob/master/media_mix_recommendation_analysis.ipynb)
