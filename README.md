# 제주 특산물 가격 예측 AI 경진대회

## 1. Introduction

**[주제]** 제주도 특산물의 가격을 예측하는 AI 모델 개발 및 인사이트 발굴

**[링크]** https://dacon.io/competitions/official/236176/overview/description

## 2. Data
```
data
├─  train.csv
|    ├─  item : 품목 코드
|    ├─  corporation : 유통 법인 코드
|    ├─  location : 지역 코드
|    └─  supply(kg) : 유통된 물량, kg 단위
|    └─  price(원/kg) : 유통된 품목들의 kg 마다의 가격, 원 단위
├─  international_trade.csv
|    ├─  ID : 질문 ID
|    ├─  image_id : 이미지 ID
|    └─  question : 이미지 관련 질문
└─  sample_submission.csv
     ├─  ID : 품목, 유통 법인, 지역 코드로 구성된 식별자
     └─  answer : 해당 ID에 대한 price(원/kg)
```
