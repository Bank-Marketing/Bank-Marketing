# Bank-Marketing

# 사용된 Data Set
https://www.kaggle.com/datasets/henriqueyamahata/bank-marketing/data

# 1. 서론
## 1.1 배경
최근 금융 산업에서는 고객의 행동 패턴을 예측하여 더 효과적인 마케팅 전략을 수립하는 것이 중요함. 정기 예금과 같은 금융 상품은 고객의 경제적 신뢰와 장기적인 자산 관리 계획을 반영하는 지표로 사용됨. 하지만 모든 고객이 이 상품에 관심을 가지는 것은 아니기 때문에, 고객이 가지는 개인적 특성과 경제적 상황에 따라 가입 가능성을 예측하는 것이 필요함. 


이 프로젝트에서는 고객의 정보(나이, 직업, 학력, 결혼여부 등) 및 경제 지표(금리, 고용시장 상황, 소비 물가 지수 등)를 바탕으로 분석을 통해 정기 예금 가입 여부를 예측하고자 진행함. 이를 통해 더 타겟팅된 마케팅 캠페인을 통해 장기적인 고객 관리에 힘쓰고자 함.


또한 고객 중 정기 예금 가입 비율이 낮은 클래스 불균형 문제를 해결하고, 데이터의 패턴을 파악하기 위해 다양한 머신러닝 기법을 활용하여 예측 모델을 개발함. 이 프로젝트를 통해 고객 데이터를 활용해 데이터 기반의 의사결정에 기여할 수 있을 것임.
  
## 1.2 분석 목표 및 진행 방향
- 고객 정보와 경제 지표를 통해 정기 예금 가입 예측을 위한 데이터 분석
    1. EDA를 통해 고객의 전체 분포 및 해당 시기의 경제 상황 파악
    2. 가설 설정 및 분석을 통한 검정
    3. 발견한 인사이트를 통한 결론 도출
 
    
- 분석 결론을 통해 예측 모델 개발
    1. 분석 결론을 바탕으로 feature enginnering 진행
    2. Catboost, XGBoost, LightGBM, RandomForest모델을 비교 분석
    3. F1-score을 기준으로 모델 선정



## 1.3 사용 된 툴
- 언어 : Python
- 라이브러리 : Pandas, seaborn, scikit-learn, matplotlib

## 2. 팀원 및 역할
- 박연재 : 경제 지표 분석 / 모델 개발 / 보고서 작성
- 김선우 : 보고서 작성 및 취합 / 전체적인 EDA / 모델 개발
- 문선규 : 고객 정보 분석 / 모델 개발 / 보고서 작성
- 홍성연 : 보고서 작성 / 전체적인 EDA

![flowchart](https://github.com/Bank-Marketing/Bank-Marketing/blob/main/Flowchart.png?raw=true)
## 3. 보고서 [링크](https://github.com/Bank-Marketing/Bank-Marketing/blob/main/report.pdf)
