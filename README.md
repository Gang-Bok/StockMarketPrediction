# StockMarketPredict
2020-2학기 기계학습 수업에서 진행한 프로젝트 입니다. 논문을 읽고 리뷰 및 논문의 내용을 코드로 구현한 프로젝트 입니다. 주제는 주식시장 예측 입니다.

## Contents

### 1. GetData
S&P 500 dataset을 Load하고 Load한 데이터중 Change Value(주식 가격의 변화량)를 이용해 데이터 표준화 및 Sequence형태로 데이터를 만들어 학습 준비를 한다.

### 2. Training
얻은 데이터셋을 바탕으로 LSTM 모델을 이용하여 train을 진행한다.

### 3. Trading
Test Data를 이용하여 주식이 상승할지 하락할지 예측하여 확률값이 높은 k개의 주식을 사는 것을 규칙으로 모의 Trading을 진행한다.

## Review Video
논문 리뷰 영상 : https://youtu.be/32hwHjMfcrg

## References
참고한 논문 : Deep Learning with long short-term memory networks for financial market predictions - Thomas Fischer , Christopher Krauss

