# List of Projects

**아래의 제목들을 클릭하시면 자세한 내용을 보실 수 있습니다.** 

English version : [https://github.com/espseongsm/list_of_projects](https://github.com/espseongsm/list_of_projects)

## 데이터 전처리 - Pandas and SQL

- [Pandas를 이용한 LeetCode Database 문제 솔루션](https://github.com/espseongsm/LeetCodeDatabaseQuestions/blob/master/SolutionsForLeetCodeDatabaseSolutions.ipynb)
- [Pandas 및 SQL을 이용한 HackerRank SQL 문제 솔루션](https://github.com/espseongsm/HackerRankSQLSolutions/blob/main/SolutionsForHackerRankSQL.ipynb)

## [세포이미지를 통한 핵 감지 모델 | Nucleus Detection in Cell](https://github.com/espseongsm/Nucleus_Detection_in_Cell) 

- Language: R
  - Library: ggplot2, glmnet, randomForest, reshape, gridExtra, dplyr, MASS, e1071
- Supervised learning: classification
- Models: LASSO, Ridge, Elastic net, Random forest, Logistic regression
- DNA 연구에 도움이 되도록 세포의 셀 보유 유무를 예측할 수 있는 5가지의 image classification 모델을 개발 후 최적의 모델 선정 (98.5% 정확도 | 핵의 모양을 인식) 
- 다양한 방법을 통하여 에측 성능을 높임 (oversampling, 하이퍼파라미터 튜닝, regularization | 15% improvement)
- ggplot library (R)를 통하여 가장 효과적인 모델을 시각적으로 분석
- AB 테스팅을 통하여 예측성능을 보장하면서 데이터 크기를 줄임 (45% reduction in training time)

## [음성정보를 통한 파킨슨 병 진단 모델 | Parkinson’s Disease Diagnosis from Acoustic Features](https://github.com/espseongsm/Parkinson_Disease_Diagnosis)

- Language: R
  - Library: ggplot2, glmnet, randomForest, reshape, gridExtra, dplyr, MASS
- Supervised learning: classification
- Models: LASSO, Ridge, Logistic regression
- 파킨슨 병의 진단이 용이하도록 노인들의 음성정보만으로 진단할 수 있는 3가지의 classification 모델 개발 후 최적의 모델 선정
- 하이퍼파라미터를 최적화하여 모델의 예측성능을 높임 (cross-validation | 7% improvement)
- 모델의 성능과 계산 시간을 시각적으로 분석하여 최적의 classification model을 평가
- 파킨슨 병의 진단에 영향을 미치는 중요 변수를 파악

## [트위터의 이슈 트윗 감지 모델 | Buzz Prediction in Twitter](https://github.com/espseongsm/Buzz_prediction_on_twitter)

- Language: R
  - Library: ggplot2, glmnet, randomForest, reshape, gridExtra, dplyr, MASS
- Supervised learning: regression
- Models: LASSO, Ridge, Elastic net, Random forest
- cross-validation을 통해서 4가지의 머신러닝 모델을 개발하고 최적의 모델을 평가함
- 트윗의 active discussion 횟수를 예측하여 트위터의 중요 이슈를 감지할 수 있는 모델 (99% 정확도)
- 부트스트랩을 이용하여 중요 이슈에 가장 큰 영향을 미치는 Top 2 요인을 분석
- feature selection을 자동화하여 예측정확도를 높임

## [AWS를 통한 주식 정보 분석 | Streaming and Analyzing Yahoo Stock Price in AWS](https://github.com/espseongsm/streaming_stock_prices_and_analyzing_in_AWS)

- Language: Python, Jupyter notebook, SQL
  - Library: pandas, yfinance, boto3, os, subprocess, sys, json, yfinance
- Service: Docker, AWS S3, Kinesis, Athena, Glue, and Lambda function
- 매시간 가장 높은 주식값을 주요 회사별로 분석함
- Yahoo Finance stock price data를 AWS S3로 스트리밍하여 저장하고 AWS Glue &Athena로 분석함 (SQL)

## [비트코인 가격 예측 모델(Time Series) | Bitcoin Price Time Series Analysis (Deep Learning)](https://github.com/espseongsm/Bitcoin_Time_Series_Deep_Learning)

- Language: R
  - Library: keras, tensorflow, ggplot2, dplyr, glmnet, reshape, gridExtra
- Supervised learning: regression
- Models: Deep Learning, LASSO, Ridge, Elastic net
- 선형대수학을 이용하여 데이터의 구조를 time series 분석에 용이하도록 변경하는 프로그램 개발
- 딥러닝을 포함한 4개의 모델을 개발하고 예측성능을 시각적으로 분석하여 비트코인 가격을 예측하는 최적의 모델을 개발 (cross-validation을 통하여 최적화 | 97% 정확도)
  
## [Yelp(식당 리뷰 공유앱)의 식당 및 고객의 비즈니스 패턴 분석 | Analysis on Yelp Business and Customer Patterns](https://github.com/espseongsm/Analysis_on_yelp_business_and_customer_patterns)

- Language: Python Jupyter Notebook
  - Library: Pandas, PySpark, matplotlib
- Service: AWS S3, EMR
- 1GB 이상의 데이터를 AWS S3로부터 로딩하고 AWS EMR을 통하여 분석 (PySpark, Jupyter notebook)
- Yelp 사용자 리뷰의 의미있는 business patterns을 도출 (나쁜 서비스의 기준, 지역별 리뷰 특성)

## [뉴욕시의 5년간 주차 위반 패턴 분석 | Analyzing NYC Parking Violation in past 5 years](https://github.com/espseongsm/STA9760_Big_Data_Project1)

- Language: Python
- Service: AWS EC2, Docker, Elasticsearch, Kibana
- 뉴욕시의 주차 위반 패턴을 시각화 (Top 5 위반, 시간 및 지역별 위반 트렌드, 범칙금 환원 | Docker, AWS EC2, Elasticsearch, Kibana)