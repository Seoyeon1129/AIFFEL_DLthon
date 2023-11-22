# AIFFEL_DLthon
2023년 11월 19일부터 22일까지 진행된 모두의 연구소 아이펠 리서치 과정 6기 디엘톤(딥러닝 해커톤) 프로젝트 저장소입니다.
이 프로젝트는 4개 범주로 분류된 괴롭힘 대화 코퍼스로부터 모델을 학습하고, 학습된 모델로 테스트 대화를 추론하여 성능을 평가하는 과정으로 진행되었습니다.

- aiffel_DLthon.ipynb : 초기화된 임베딩 레이어 / word2vec으로 학습한 레이어 + bidirectional LSTM 모델과 Transformer encoder 모델
- EDA_w2vembedding_PTH.ipynb : 데이터 전처리 코드, 사전학습된 word2vec 이용 + bidirectional LSTM 모델과 Transformer encoder 모델
- aiffel_DLthon_KoBERT.ipynb : SKT(2021)의 한국어용 양방향 인코더(KoBERT) 모델 및 해당 모델 라이브러리의 자체 임베딩 활용
