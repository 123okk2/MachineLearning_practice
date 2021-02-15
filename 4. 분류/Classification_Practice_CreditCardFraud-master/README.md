# Classification_Practice_CreditCardFraud

practice deep learning



# 언더 샘플링과 오버 샘플링

레이블의 불균형한 분포를 가진 데이터 세트를 균형적인 데이터 셋으로 바꾼다.

# 언더 샘플링

많은 데이터 셋을 적은 데이터 셋 수준으로 감소시킨다.

너무 많은 정상 레이블 데이터를 감소시켜 정상 레이블의 경우 오히려 학습이 잘 수행되지 않을 수 있다.


# 오버 샘플링

적은 데이터 세트를 증식하여 학습을 위한 충분한 데이터 셋을 확보하는 방법

단순히 증식하는 방법은 과적합이 되기 때문에 원본 데이터 피처 값들을 아주 약간만 변경하여 증식한다.

대표적으로 SMOTE 방법이 있다.

# SMOTE

적은 데이터 세트에 있는 개별 데이터들의 K 최근접 이웃을 찾아 이 데이터와 K개 이웃들의 차이를 일정 값으로 만들어,

기존 데이터와 약간 차이가 나는 새로운 데이터들을 생성한다.

# References

Data From https://www.kaggle.com/mlg-ulb/creditcardfraud

Code From https://book.naver.com/bookdb/book_detail.nhn?bid=16238302

