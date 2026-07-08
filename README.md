# Phishing Website Detection Model Comparison

## 프로젝트 소개
UCI Machine Learning Repository의 Website Phishing 데이터셋을 활용하여 피싱 웹사이트를 분류하는 머신러닝 모델 비교 프로젝트입니다.

여러 분류 모델을 학습시키고 Accuracy, Recall, F1-Score를 기준으로 성능을 비교한 뒤, SHAP을 활용해 모델 예측에 영향을 미치는 주요 특성을 분석했습니다.

## 사용 데이터
- Dataset: Website Phishing Dataset
- Source: UCI Machine Learning Repository
- 데이터 크기: 1,353개 샘플, 10개 컬럼
- Target: Result

## 사용 기술
- Python
- Pandas
- Scikit-learn
- XGBoost
- TensorFlow/Keras
- SHAP
- Matplotlib, Seaborn

## 주요 기능
- 데이터 로드 및 전처리
- 결측치 확인
- 상관관계 히트맵 시각화
- 학습/테스트 데이터 분리
- 다양한 머신러닝 모델 학습 및 성능 비교
- 최적 모델 선정
- SHAP 기반 XAI 분석

## 비교한 모델
- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- XGBoost
- MLP Classifier
- SVM
- AutoEncoder
