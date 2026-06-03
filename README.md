# Corporate Finance Failure Prediction Model

상장기업의 재무비율 데이터를 활용하여 기업 부실 여부를 예측하는 머신러닝 프로젝트입니다.
- 연구 제목 : "로지스틱회귀 모형과 머신러닝 알고리즘을 이용한 코스피,코스닥 상장기업 부실 예측 모델 성능 비교 연구"
- 데이터: KOSPI·KOSDAQ 상장기업 (2014~2024)
- 목표변수: 상장폐지 여부
- 모델: Logistic Regression, Random Forest, XGBoost
- 변수구성: 원비율 변수 및 파생변수
- 평가척도: Accuracy, Precision, Recall, F1-score, AUC
- 연구 결과
  ① 원재무비율과 파생변수를 결합한 확장된 Dataset3의 XGBoost 모델이 AUC가 가장 높았다.
  ② 시계열 외 검증에서는 모든 모형의 예측 성능이 감소하였으나, Random Forest는 상대적으로 성능 저하 폭이 작아 과적합에 대한 견고성이 높은 것으로 나타났다.
  ③ 부실기업(상장폐지)에 영향을 주는 주요 변수로 F36(자기자본구성비율)과 F40(재고자산대순운전자본비율)이 선정되었다.
  ④ 원재무비율만 활용한 데이터셋보다 파생변수를 결합한 데이터셋에서 더 높은 예측 성능이 나타난 것은, 파생변수가 기업의 재무상태 변화와 산업 내 상대적 특성을 효과적으로 반영하여 부실 예측에 유의한 정보를 제공함을 시사한다.

## Research Framework

![](ppt/1.png)
![](ppt/1.png)
![](ppt/2.png)
![](ppt/3.png)
![](ppt/4.png)
![](ppt/5.png)
![](ppt/6.png)
![](ppt/7.png)
![](ppt/8.png)
![](ppt/9.png)
![](ppt/10.png)
![](ppt/11.png)
![](ppt/12.png)
![](ppt/13.png)
![](ppt/14.png)
![](ppt/15.png)
![](ppt/16.png)
![](ppt/17.png)
![](ppt/18.png)
![](ppt/19.png)
![](ppt/20.png)
![](ppt/21.png)
![](ppt/22.png)
![](ppt/23.png)
![](ppt/24.png)
![](ppt/25.png)
![](ppt/26.png)
![](ppt/27.png)
