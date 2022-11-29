![header](https://capsule-render.vercel.app/api?type=Rect&color=auto&height=300&section=header&text=Hello%20Wonpyo&fontSize=90&fontColor=000000)
# 😉PYTHON DATA ANALYSIS PROJECT (Use : Riot API)
RIOT API를 활용한 라인별 챔피언 승률 예측

## 진행기간
2022-11-10 ~ 2022-11-17
 <br>

## ⚙ 순서
- 데이터 준비
- 데이터 전처리
- 데이터 분석
- 결과 도출
<br>

### 1.데이터 준비
- Riot API를 활용하여 MySQL에 데이터 적재
- Jupyter를 활용하여 MySQL 내 데이터를 DataFrame으로 변환

### 2.데이터 전처리
- 데이터 라벨링
- 타입 변환(object -> int64)
- 결측치 제거 (dropna())
- 이상치 제거 (values_count())
- 인덱스 재설정

### 3.데이터 분석
- 분석 기법 선정(logistic regression)
- 모델학습 (train_test_split)

### 4.결과 도출
- Accuracy, Precision, Recall 측정 (sklearn_metrics)
