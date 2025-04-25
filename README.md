## 웰니스 데이터셋을 이용한 실시간 응답 챗봇 구현 프로젝트

[AI-Hub의 웰니스 대화 스크립트 데이터셋](https://aihub.or.kr/aihubdata/data/view.do?currMenu=120&topMenu=100&aihubDataSe=extrldata&dataSetSn=267)을 기반으로,  
[nawnoes님의 Korean Language Model for Wellness Conversation](https://github.com/nawnoes/WellnessConversation-LanguageModel) 코드를 활용해 파인튜닝한 언어 모델을 구축하였고,  
해당 모델을 [omrawal님 UpbeatBuddy-Chatbot](https://github.com/omrawal/UpbeatBuddy-Chatbot) 웹 페이지 코드와 연동하여 실시간 응답 챗봇을 구현한 프로젝트.

## 파일 설명
- `check_model structure, configuration.ipynb` : 모델 구조 살펴보기
- `eda_data.ipynb` : 데이터 탐색
- `evaluate_electra.ipynb` : koelectra모델 평가 과정
- `evaluate_kogpt2.ipynb` : 평가 과정
- `evaluate,text-generation_kogpt2_small.ipynb` : 평가, 텍스트 생성 예시(n_ctx 축소 모델에 대한)
- `preprocess_gpt.ipynb` : 전처리 과정
- `text-generation_kogpt2.ipynb` : 최종 텍스트 생성 예시
- `train_kogpt2_wellness_1_hyper.ipynb` : 학습 과정(기존 조건, 로스, 체크포인트 저장) 
- `train_kogpt2_wellness_2_turning.ipynb` : 학습 과정(lr, generate, GPU 변경 )
- `train_kogpt2_wellness_3_small.ipynb` : 학습 과정(n_ctx 변경)
