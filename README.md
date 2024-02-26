# kor_semantic_search
문서 임베딩 기반 문서 유사도 모델 비교
- 토크나이징 방법에 따른 성능 차이
    - NER -> 텍스트만 가지고 mecab 다시 돌리기
    - NER만 돌리기 https://github.com/eagle705/pytorch-bert-crf-ner <- 이 NER 사용
    - word piece 돌리기
    - '바른': https://docs.bareun.ai/intro/
    - fast text 돌리기
- 문서 유사도 결과 비교
    - TopicRank
    - 코사인 유사도 / 유클리디안 / 자카드
