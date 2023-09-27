# 월간 데이콘 쇼츠 - 뉴스 기사 레이블 복구 해커톤

## Competition

[대회 개요](https://dacon.io/competitions/official/236159/overview/description)

[데이터](https://dacon.io/competitions/official/236159/data) ) 6개의 카테고리로 분류되어야 하는 6만 행의 csv 파일이 데이터셋으로 제공됨

대회 기간) 23.09.22 10:00 금요일 ~ 23.09.25 10:00 월요일

대회 주제) 긴급 레이블 복구: 뉴스 데이터 6개 카테고리 분류

평가 산식) Macro F1 Score

## Result

Public 6th, Private 6th (308명 참여)


## Description
[데이콘 코드 공유](https://dacon.io/competitions/official/236159/codeshare/8871?page=1&dtype=recent)

HuggingFace 에 있는 Sentence-transformers 모델을 위주로 인퍼런스하였고,

sklearn 에서 제공하는 여러 클러스터링 알고리즘을 사용하여 라벨별로 분류한 뒤 앙상블하였습니다.(하드 보팅)

제출 시 여러 모델을 사용한 결과를 앙상블하기보다, 여러 클러스터링 알고리즘을 사용한 결과를 앙상블한 것이 결과가 좋았습니다.



## License

데이콘 대회 참가 시 동의하는 라이선스에 따릅니다.
