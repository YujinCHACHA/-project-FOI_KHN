# 국민영양조사 데이터분석

## 분석 주제
"고혈압 여부 예측 모델의 정확도를 높이기 위한 가족력 데이터 보간용 결측치 예측 모델"
### 1. 필요성
- 건강정보 설문조사 데이터 수집의 어려움(비용이 많이 듦)
- 가족력이 주요 요인인 질병들(고혈압, 당뇨병, 심혈관질환, 아토피피부염)을 예측하는 모델을 만들기 위함
### 2. 2. 질병 예측 모델의 필요성
- 100개 이상이므로 사람보다 효율적인 처리 가능
- 데이터 활용도를 높이기 위함(질병 데이터도 결측치가 많음. 연쇄적인 효과 기대)
## 분석 결과
- ![image](https://user-images.githubusercontent.com/106477624/219936461-4d6f44b7-5055-46fd-a933-7735e6b0d20e.png)

## 분석 과정
### 1. 데이터 전처리
- 결측치 처리
  - 기준: 
- ![image](https://user-images.githubusercontent.com/106477624/219936744-dabc3a99-217f-4839-b096-41dba408ce58.png)
- 필요한 열만 추출
- one-hot encoding
- 정규화
  - 숫자형 데이터 정규화: 
 - ![image](https://user-images.githubusercontent.com/106477624/219936751-56459fa3-7b41-42f7-b449-16083d7837c6.png)
  - 범주형 데이터 정규화: 
 - ![image](https://user-images.githubusercontent.com/106477624/219936764-43c29020-9530-4f68-93af-9a26c1807d04.png)
### 2. EDA
- 상관계수 분석
- class imbalance 확인
  - 결과: 
- ![image](https://user-images.githubusercontent.com/106477624/219936778-7b324238-d070-4ac8-bbd4-845362d447c9.png)

### 3. 모델링
- accuracy
- mae

