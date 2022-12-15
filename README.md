# Credit_Risk_Prediction
금융 거래 고객 신용 위험 예측

## 프로젝트 목표
- 금융 거래 데이터 분석을 통하여 고객 신용 위험을 예측하는 분류 모델 수행
- 고객 신용 위험에 영향을 미치는 특성 데이터들에 대한 데이터 분석 수행


## 프로젝트 목차
1. **데이터 읽기:** 금융 데이터를 불러오고 Dataframe 구조를 확인
    

2. **데이터 정제:** 비어 있는 데이터 또는 쓸모 없는 데이터를 삭제


3. **데이터 시각화:** 변수 시각화를 통하여 분포 파악<br>
    3.1. Age 시각화<br>
    3.2. Sex 시각화<br>
    3.3. Job 시각화<br>
    3.4. Housing 시각화<br>
    3.5. Saving accounts 시각화<br>
    3.6. Checking account 시각화<br>
    3.7. Credit amount 시각화<br>
    3.8. Duration 시각화<br>
    3.9. Purpose 시각화<br>
    3.10. Risk 시각화<br>
    

4. **데이터 전 처리:** 머신러닝 모델에 필요한 입력값 형식으로 데이터 처리<br>
    4.1. Object 자료형 -> 수치 자료형 변환 - Dummy<br>
    4.2. 학습, 테스트 데이터 분리<br>
    

5. **머신러닝 모델 학습:** 분류 모델을 사용하여 학습 수행<br>
    5.1. 기본 분류 모델 학습 - 의사결정나무<br>
    5.2. 다양한 분류 모델 학습<br>
    5.3. 모델 튜닝 및 K-fold 교차 검증<br>


6. **평가 및 예측:** 학습된 모델을 바탕으로 평가 및 예측 수행<br>
    6.1. Confusion Matrix<br>
    6.2. Precision & Recall<br>
    6.3. 테스트 데이터의 예측값 출력<br>




## 데이터 출처
-  https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data)


## 프로젝트 개요

금융 거래 데이터는 해당 데이터에 속한 사람들의 소비 패턴을 판단할 수 있고 나아가 생활 패턴까지 유추할 수 있게 합니다. 이러한 정보는 마케터나 금융기관에서 상품을 적절하게 추천할 수 있도록 도움을 줄 수 있습니다. 특히나 고객의 신용 위험 정도는 금융 상품을 추천하거나, 금융 활동을 제한하는데 있어서 중요한 정보로 사용될 수 있을 것입니다.

이번 프로젝트에서는 독일 금융 거래 고객 데이터를 바탕으로 금융 고객의 신용 위험을 예측해보는 분류 모델을 구현합니다. 데이터 분석 및 분류 모델을 바탕으로 새로운 고객의 데이터를 받았을 때, 신용 위험 여부를 예측할 수 있으며, 어떠한 특성 데이터가 위험 여부를 예측하는데 큰 영향을 미쳤는지 또한 알 수 있습니다.



