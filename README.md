# Dacon_koreanNLP

# Dacon 참가
- hugging face 처음으로 사용해봄
- nlp 관심이 없었지만, transfer learning 부분은 신박한 아이디어 인 것 같다.
- 아무래도 수치형 데이터가 아니다 보니까 EDA 에 대한 중요도는 낮아지는 것 같고, 진짜 모델의 정확도만으로 겨루는 대회!
- 하지만,, 우리는 서버도 없고,, GPU를 제공하는 코랩이 유일한 희망이었다...
- 무료 코랩은 모델 베이스라인도 돌아가지 않아서(:() 코랩 프로를 결제했다. + 구글 드라이브도 200GB로 늘림ㅠㅠ
- 코랩 프로에서는 베이스 라인은 돌아갔지만 진짜로 성능을 올려주는 모델 (xlm-RoBERT같은것들)은 터져버렸다. GPU,TPU 다 써봐도 해결 불가능. 고용량 RAM도 시도해봄. (다른 팀들은 어떻게 하고 있는건지 모르겠다...!)
- 코랩 프로 플러스 결제는 넘 비싸서 하지 못했지만 시도하고 싶은 모델은 진짜 진짜 많았다. (리눅스 기반의 HanBERT도 궁금했고 여러 BERT 모델을 stacking 해보고도 싶었다.)
- 베이스 모델 training 만 5시간이 걸렸던 대회
- 그러고 보면 NSML 대회는 GPU 3대씩 빌려주고 참 좋았던 대회였다. 내가 그 기회를 잘 못살려서 아쉬운 마음,,,(좀만 더 도전적인 모델들을 사용해볼껄!)
- 첫번째 리더보드 대회가 너무 인프라가 좋았던 것 같다. 앞으로는 가볍지만 학습력 좋은 다양한 모델들이 연구되었으면 좋겠다~~ (like Efficient Net, MobileNet in computer vision)
- 아무나 연구해주라~~

# 배웠던 점, 아쉬운 점
- 딥러닝 모델도 예측력이 중요한 경우, 앙상블이 가능하구나! -> 그럼 stacking 은 어떨까?? (GPU가 허락해줬을 때 해봐야지!)
- transfer learning based on BERT model -> koBERT,alBERT, roBERT,xlmBERT ...등등
- 기계탓을 하고 싶진 않지만, 어쩔 수 없이 GPU탓이다. 코드 자체가 돌아가지 않아 결과 제출도 5번밖에 하지 못했다. 

