# ⚡ 전력 수요량 예측 시스템 (Power Demand Forecast)

Azure Machine Learning과 LSTM 모델을 활용해 전력 수요량을 예측한 프로젝트입니다.  
날씨 요인(CDD/HDD), 고객 수, 시간대 데이터를 기반으로 단기 수요량을 정밀 예측했습니다.

---

## 🎯 Overview
- **목표:** 시간·기온·지역 요인에 따른 전력 수요량 예측 정확도 향상  
- **문제:** 기존 모델은 특정 변수(예: 고객 수)에 편향 → Feature Importance 왜곡  
- **해결:** 이상치 제거, 파생변수 재구성, LSTM 기반 시계열 학습 적용  

---

## 👩‍💻 My Role
- Azure ML Designer에서 LSTM 모델 설계 및 하이퍼파라미터 최적화  
- 데이터 정제 및 이상치 처리 (IQR, Z-score)  
- Feature Importance 편향 완화 (CDD/HDD 변수 보정)  
- Python 기반 예측 모델 시각화 및 성능 비교  

---

## ⚙️ Tech Stack
- **Language:** Python (Pandas, Numpy, Matplotlib)  
- **Platform:** Azure Machine Learning Studio  
- **Model:** LSTM, Linear Regression, TCN  
- **Metrics:** RMSE, MAPE, R² Score  

---

## 📈 Result
- MAPE 기준 **7.2% → 4.9%**로 예측 정확도 개선  
- LSTM 모델이 시계열 패턴 학습에 가장 효과적  
- Feature 중요도 균형 확보 → 모델 신뢰도 상승  

---

## 🧭 Learnings
> 단순한 정확도 향상이 아니라, 데이터 편향을 해소하는 설계가  
> 실제 AI 모델 신뢰도를 높인다는 점을 체감했습니다.
