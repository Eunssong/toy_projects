# AIFFEL Campus Online 7th Code Peer Review Templete

- 코더 : 방은송
- 리뷰어 : 윤빛나

루브릭
아래의 기준을 바탕으로 프로젝트를 평가합니다.
평가문항	상세기준
1. SentencePiece를 이용하여 모델을 만들기까지의 과정이 정상적으로 진행되었는가?	코퍼스 분석, 전처리, SentencePiece 적용, 토크나이저 구현 및 동작이 빠짐없이 진행되었는가?
2. SentencePiece를 통해 만든 Tokenizer가 자연어처리 모델과 결합하여 동작하는가?	SentencePiece 토크나이저가 적용된 Text Classifier 모델이 정상적으로 수렴하여 80% 이상의 test accuracy가 확인되었다.
3. SentencePiece의 성능을 다각도로 비교분석하였는가?	SentencePiece 토크나이저를 활용했을 때의 성능을 다른 토크나이저 혹은 SentencePiece의 다른 옵션의 경우와 비교하여 분석을 체계적으로 진행하였다.



🔑 **PRT(Peer Review Template)**

- [x] **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
- 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
- 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개,
퀘스트 문제 요구조건 등을 지칭
- 해당 조건을 만족하는 부분의 코드 및 결과물을 근거로 첨부

SentencePiece를 이용하여  분석, 전처리, 적용 및 토크나이저 구현이 빠짐없이 진행되고 정상적으로 모델 학습을 하여 80%이상의 accuracy를 확인할 수 있었으며 성능을 다각도로 비교하여 체계적으로 분석하였습니다.

<img width="793" alt="스크린샷 2023-12-27 17 37 42" src="https://github.com/Eunssong/AIFFEL/assets/100587126/cb27b2e9-5b78-4541-964a-d532ea4dcc1a">

<img width="512" alt="스크린샷 2023-12-27 17 38 05" src="https://github.com/Eunssong/AIFFEL/assets/100587126/f7145309-0fe3-4452-a9b5-5bdbe317dfc3">

<img width="793" alt="스크린샷 2023-12-27 17 37 42" src="https://github.com/Eunssong/AIFFEL/assets/100587126/e171c837-ea3e-4220-be5d-b0e73f5ebc17">

<img width="793" alt="스크린샷 2023-12-27 17 37 42" src="https://github.com/Eunssong/AIFFEL/assets/100587126/adc75f8b-f554-4208-a26b-c5a28b0cac23">



- [x] **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**


  코드에 자세한 주석을 남겨 어떻게 진행되고 있는지와 스텝별로 잘 구분하여 보기 좋았습니다.

<img width="533" alt="스크린샷 2023-12-27 17 39 25" src="https://github.com/Eunssong/AIFFEL/assets/100587126/1c4a0461-96c3-40dc-a350-57c877339279">



- [x] **3. 에러가 난 부분을 디버깅하여 문제를 “해결한 기록을 남겼거나”
”새로운 시도 또는 추가 실험을 수행”해봤나요?**

중간중간 파일들을 확인하고 결과를 확인해보며 코드가 잘 실행되고 있는지에 대한 과정을 잘 담았습니다.

<img width="347" alt="스크린샷 2023-12-27 17 43 17" src="https://github.com/Eunssong/AIFFEL/assets/100587126/553ed9fe-8204-461b-a084-0bb8fda6529e">

<img width="516" alt="스크린샷 2023-12-27 17 43 08" src="https://github.com/Eunssong/AIFFEL/assets/100587126/92c3a117-c754-4caa-9efc-e4f59123533b">

<img width="481" alt="스크린샷 2023-12-27 17 45 25" src="https://github.com/Eunssong/AIFFEL/assets/100587126/e94561c1-789e-471b-a21a-5b45e72ede4a">


- [x] **4. 회고를 잘 작성했나요?**

어떤 값을 조정했을 때 결과가 달라졌는지가 잘 설명되어 있었습니다.

<img width="906" alt="스크린샷 2023-12-27 17 45 28" src="https://github.com/Eunssong/AIFFEL/assets/100587126/a4e152c4-29b1-4c09-a064-85dafa4c664e">



- [x] **5. 코드가 간결하고 효율적인가요?**

loss와 accuracy에 대한 그래프를 따로 작성하여 간결하고 보기좋게 잘 작성하였습니다.

<img width="484" alt="스크린샷 2023-12-27 17 47 15" src="https://github.com/Eunssong/AIFFEL/assets/100587126/41d192cc-4eb6-4552-bfb5-2e89f8b27970">

<img width="483" alt="스크린샷 2023-12-27 17 47 19" src="https://github.com/Eunssong/AIFFEL/assets/100587126/2c84f60b-e036-482a-b992-feac17889249">


