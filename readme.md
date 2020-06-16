## dacon funda 신용카드 매출 예측
[대회 링크](https://dacon.io/competitions/official/140472/overview/)

### 문제
 핀테크 기업인 ‘FUNDA(펀다)’는 상환 기간의 매출을 예측하여 신용 점수가 낮거나 담보를 가지지 못하는 우수 상점들에 금융 기회를 제공하려 합니다.

 이번 대회에서는 2년 전 부터 2019년 2월 28일까지의 카드 거래 데이터를 이용해 2019-03-01부터 2019-05-31까지의 각 상점별 3개월 총 매출을 예측하는 것입니다.

### 측정방식
MAE(mean absolute error) 평균절대오차 
* RMSE는 에러에 따른 손실이 기하급수적으로 오르기 때문에 적절치 않음
* MAE는 에어레 따른 소실이 선형적으로 올가가기 때문에 적절

[참고: DACON MAE인지 설명](https://dacon.io/competitions/official/140472/talkboard/146525?page=4&dtype=recent&ptype=pub)  
[참고2: MAE and RMSE which metric is better](https://medium.com/human-in-a-machine-world/mae-and-rmse-which-metric-is-better-e60ac3bde13d)