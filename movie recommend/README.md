# 영화 추천 모델

[The Movies Dataset](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset)을 활용한 추천 모델을 만들었습니다.

## 영화 추천 모델

영화를 추천하기 위한 matrix factorization 모델을 만듭니다.

the_movies_전처리.ipynb
- 영화 추천 모델 학습을 위한 데이터 전처리 과정입니다.

the_movies_추천_모델.ipynb
- 영화 추천 모델을 학습하고 몇 가지 유사도 추천 예제를 확인합니다.


## 장르 데이터 추가

모델의 예측 정확도를 높이기 위해 장르 데이터를 추가로 활용합니다.

장르-rating_만들기.ipynb
- 장르 임베딩 모델 학습을 위한 데이터 전처리 과정입니다.

장르_임베딩_모델.ipynb
- 영화의 장르를 벡터로 임베딩하는 모델입니다.

장르_추가로_정확도_높이기.ipynb
- 기존 영화 추천 모델에 장르 데이터를 더해 모델의 예측 정확도를 높입니다.
