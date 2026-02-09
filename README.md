# Telco Customer Churn Prediction

통신사 고객 데이터를 활용하여 고객 이탈 여부를 예측하는 머신러닝 프로젝트입니다.

## Project Overview
- 고객의 이용 정보와 계약 정보를 기반으로 이탈 여부 예측
- 이진 분류 문제 (Churn: Yes / No)

## Dataset
- Telco Customer Churn Dataset (Kaggle)
- 주요 변수: tenure, MonthlyCharges, Contract, PaymentMethod 등

## Modeling
- Logistic Regression 사용
- 클래스 불균형 문제를 고려하여 class_weight 적용
- 임계값(threshold) 조정을 통해 이탈 고객 recall 개선

## Result
- 기본 모델 이탈 고객 recall: 약 0.52
- 개선 후 이탈 고객 recall: **0.80**
- 이탈 고객을 보다 적극적으로 탐지하는 모델 구축

## Files
- `telco_customer_project.ipynb` : 전체 분석 및 모델링 코드
- `data/churn.csv` : 데이터셋
