# JPX Stock Prediction

JPX 주가 데이터를 활용해 미래 수익률을 예측하고,
예측 결과를 기반으로 종목별 순위를 생성하는 머신러닝 프로젝트입니다.

## 프로젝트 목표
- 주가 데이터 탐색 및 전처리
- 주요 Feature 생성
- 선형 회귀 기반 수익률 예측
- 종목별 Ranking 생성
- 모델 성능 평가 및 시각화

## 사용 기술
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Linear Regression
- SGDRegressor
- Jupyter Notebook
- Antigravity AI Agent

## 분석 과정
1. 데이터 탐색
2. 데이터 전처리
3. Feature Engineering
4. Train / Validation 분리
5. 모델 학습
6. 수익률 예측
7. 종목 Ranking
8. 결과 평가

## 주요 Feature
- Return
- MA_5
- MA_20
- Disparity_5
- Disparity_20
- Volatility_20

## 모델
- Linear Regression
- SGDRegressor

## 결과
모델을 이용해 미래 수익률을 예측하고,
예측값을 기준으로 종목별 Rank를 생성했습니다.

MSE, RMSE, R² 및 시각화를 통해 모델 성능을 확인했으며,
현재 Feature와 선형 모델만으로는 실제 주식 수익률을 정확하게
예측하는 데 한계가 있음을 확인했습니다.

## AI 활용
Antigravity의 AI 에이전트를 활용하여
코드 작성, 오류 해결, Feature 설계, 모델 평가 및 시각화를 보조받았습니다.

AI가 생성한 코드를 그대로 사용하기보다,
실행 결과를 직접 확인하고 수정하는 방식으로 활용했습니다.

## 향후 개선
- 거래량 기반 Feature 추가
- 기업 재무정보 활용
- Ridge, Lasso 등 다른 회귀 모델 비교
- Random Forest, XGBoost 적용
- Sharpe Ratio 기반 평가
