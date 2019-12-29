# stock_predict_SKhynix

# 프로그램 설명
* 딥러닝(LSTM)을 활용한 SK hynix 주가 예측 그래프 그리기
# 개발 환경
* Window10
* python 3.7.5

# 개발 내용

## Load Dataset
* Yahoo finance에서 다운 받은 SK hynix 주가 엑셀 데이터를 불러온다. 
* 2014년 12월 29일 ~ 2019년 12월 29일 데이터
![image](https://user-images.githubusercontent.com/55618626/71556235-14682380-2a79-11ea-8a87-b6a3c1dda0be.png)
## Compute Mid Price
* 중간 가격 계산
![image](https://user-images.githubusercontent.com/55618626/71556230-09ad8e80-2a79-11ea-82f8-c6f4b8c1b2e5.png)
## Create Windows
* LSTM을 위해 Window 사이즈 설정(현재 설정 50)
![image](https://user-images.githubusercontent.com/55618626/71556228-03b7ad80-2a79-11ea-9369-a355bea1ab88.png)
## Normalize Data
* 데이터 정규화, Train 데이터와 Test 데이터 나누기
![image](https://user-images.githubusercontent.com/55618626/71556218-e387ee80-2a78-11ea-8dcc-d46db1774119.png)
## Build a Model
* LSTM 모델 설정
![image](https://user-images.githubusercontent.com/55618626/71556217-d9fe8680-2a78-11ea-8170-434ed66c5afa.png)
## Training
* 모델 학습
![image](https://user-images.githubusercontent.com/55618626/71556214-d0751e80-2a78-11ea-9462-7aab2b59a292.png)
## Prediction
* 실제 데이터와 예측 데이터를 그래프로 비교.
![image](https://user-images.githubusercontent.com/55618626/71556208-be937b80-2a78-11ea-97f5-439fa5343f5d.png)
