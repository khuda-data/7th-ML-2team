# 7th-ML-2team
# 대전광역시 생필품 물가 변동 예측 모델 구현 및 시각화

## 폴더 구조
┣ 📂 1_Data_preprocessing

┣ 📂 2_model # 전처리 된 데이터 파일과 EDA 파일

┗ 📜 README.md # 프로젝트 설명 파일

## 📖 배경
지난 3년여간의 소비자 물가 상승, 트럼프 관세 정책에 의한 인플레이션 자극, 고환율등의 여파로 국내 소비자 물가가 상승하고 있습니다. 소비자 물가 상승폭이 지속적으로 증가하는 상황에서 주요 생필품 가격의 미래 변동을 예측하는 모델을 구현하고자 하였습니다.

## 🚀 프로젝트 로드맵
### 1. 데이터 수집
- 대전 광역시 생필품 물가 데이터
- 기간은 2014~2025년
- 주요 생필품 품목별 물가 현황


### 2. 데이터 전처리
- IQR 이상치 제거
- 선형보간을 활용한 결측값 보완


### 3. 모델링 및 평가
- 선형회귀, ARIMA, SARIMA
- AIC/BIC/RMSE/MAPE/LB p-value를 활용한 성능 평가 진행

### 4. 결과 해석
- 주요 생필품 가격을 예측

## 🛠️ 기술 스택
- **데이터 처리**: Pandas, NumPy
- **모델링**: Scikit-learn, ARIMA, SARIMA


