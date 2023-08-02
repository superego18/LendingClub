# LendingClub
### 소속
SNU 핀테크데이터사이언스 전문가 과정 중 통계, 데이터사이언스 과목의 팀프로젝트

### 활동기간
2023.02

### 데이터셋
Lending Club dataset
- tabular data
- 설명변수: depvar(부도 여부)
- 종속변수: loan_amount(총 대출금액), ...
- 종속변수 총 333개 (?)
- 관측치 수: 896,887
- 특징: 이진 분류, 불균형 데이터(부도 16.2%)

### 활동내용
목적: 부도 여부 예측

목적함수 설정

데이터셋 이원화
- processed: 단순 전처리
- autoencoded: 단순 전처리 후 AutoEncoding

모델링 
- 사용 모듈: sklearn
- 사용 모델: DecisionTree, ...
- hyperparameter tuning: GridSearchCV (안 한 것은 default)

### 역할
Base 코드 파이프라인 구축
- 적절한 dataset과 model 선택
- hyperparameter tuning
- validation and test
- 결과 저장 및 시각화

모델 테스팅
- Logistic, Lasso, Ridge, ElasticNet

### 결과
- 성능지표: 목적함수의 Loss
- 최종 모델: DecisionTree (Loss: 0.3096)
