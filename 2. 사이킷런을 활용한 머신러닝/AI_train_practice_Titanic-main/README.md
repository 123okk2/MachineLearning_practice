# AI_train_practice
SKLEARN PRACTICE



# Deceision Tree (결정 트리)

-분류, 회귀 모두 가능한 지도 학습

-스무 고개를 하듯이 예/아니오 질문을 이어가며 학습하며 트리 형태로 진행된다.

-단, 지나치게 많은 질문을 하면 오버 피팅이 발생할 수 있다.

-가지치기 : 결정 트리에서 오버피팅을 막기 위한 기법. 최대 깊이나 터미널 노드의 최대 개수 등을 제한하여 분기와 최대 깊이를 제한하여 오버피팅을 방지한다.



# Random Forest (랜덤 포레스트)

-현명한 한 명의 결정보다 평범한 여러 명이 머리를 모으는 것이 낫다.

-데이터의 특징들을 랜덤으로 선별하여 여러 개의 결정 트리들을 만들어 숲을 이룬다.

-그리고 결정 트리들이 내린 예측값 중 다수결의 원칙에 따라 많은 예측값을 최종 예측값으로 결정한다.



# Logistic Regression (로지스틱 회귀)

-선형 또는 바이러니 분류 문제를 위한 단순하면서 강력한 분류 알고리즘

-순입력 함수의 리턴값을 시그모이드 함수에 대입하여 가중치 업데이트를 결정

-입력되는 훈련 데이터의 특정 클래스에 포함될 예측 확률에 따라 머신러닝 수행



# 교차검증

-하나의 테스트 셋 사용해 테스트를 할 경우 해당 테스트 셋에만 너무 잘 맞는 모델이 될 가능성이 있다.

-이를 방지하기 위해 테스트 셋을 랜덤한 여러 묶음으로 나누어 테스트 함으로써 테스트 데이터에 과적합 되지 않도록 한다.

-이를 통해 하나의 테스트 케이스로 여러 테스트 케이스를 얻는 이점도 존재한다.



# GridSearchCV

-파라미터를 순차적으로 입력하며 최적의 파라미터를 도출할 수 있는 편리한 방법

-데이터 세트를 학습/테스트용으로 자동 분할한 뒤 모든 파라미터를 순차적으로 적용해 최적의 파라미터를 찾는다.

-편리하게 최적의 파라미터를 찾을 수 있지만 시간이 오래 걸린다.


# References

Data From https://www.kaggle.com/c/titanic/data

Code From https://book.naver.com/bookdb/book_detail.nhn?bid=16238302

