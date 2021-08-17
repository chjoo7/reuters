# Reuters database: multiclass classification¶

## 보도자료 분류 : 46개 서로 다른 토픽으로 분류되는 로이터 보도자료 데이터베이스
- 만약 각각의 데이터들이 하나의 카테고리에 해당하면 single-label, multiclass classification
- 만약 각각의 데이터들이 복수의 카테고리에 해당 (이 경우, topic)하면, multilabel, multiclass classification

## Reuters dataset 로드
*** Reuters 데이터세트 로드 ***
- Reuters 데이터세트는 Keras 에 패키지 되어 같이 제공됨
- 46개 토픽당 최소 10개 이상의 example 이 제공됨
- num_words=10000 은 10,000개의 제일 많이 발생하는 단어로 제한을 둠