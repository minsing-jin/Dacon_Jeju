# Dacon_Jeju
https://dacon.io/competitions/official/235985/overview/description

private score: 3.87808(251위)

<br/>

## 시도해봤던것
1. sweetviz를 활용한 auto eda로 insight 얻어보기
2. feature importance와 permutation importance를 통해서 유의미성이 떨어지는 column 제거
3. 다양한 모델 활용(catboost / xgboost / lgbm / randomforestregressor / decisiontree등) / 작게나마 하이퍼 파이미터 시도(대부분 모델 돌리다가 싸지방 이용 제한시간 초과)
4. cv score를 통해서 성능 좋은 모델들을 선정(5-fold) + 각 모델들의 prediciton 값들을 평균값으로 ensemble
5. 모델 선정을 통해서 score을 올리는데에서 한계를 느끼고, 다른 ensemble 방식인 blending 적용(싸지방의 제한된 시간때문에 상대적으로 시간적 소요가 덜 걸리는 blending을 선정함.)


## 아쉬운점
1. 다양한 시도를 하기에는 제한되는 싸지방 이용시간
2. 꺼놓은 상태에서는 colab계속 모델을 돌리기에는 제한이 있음
3. feature engineering을 시도 못한것
4. eda를 다양한것들을 시도해봤지만 insight를 유의미하게 얻지는 못함. 다양한 사례들을 참고할것 
5. colab에서 hyperparameter tune을 하기에는 싸지방 이용시간 초과
6. 코드의 가시성<br/>

높은 점수를 얻은 사람들의 코드들을 보고 insight들을 얻으면서 다양한 시도를 해볼 필요가 있음.
