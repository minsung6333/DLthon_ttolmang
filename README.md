# DLthon_ttolmang

### DKTC (Dataset of Korean Threatening Conversations)을 활용하여 담화별 주제를 분류하는 프로젝트

- 각 클래스는 협박, 갈취, 직장 내 괴롭힘, 기타 괴롭힘으로 이루어져있음
```
1. idx = 인덱스
2. class = 0~3
class 0; 협박 대화
class 1; 갈취 대화
class 2; 직장 내 괴롭힘 대화
class 3; 기타 괴롭힘 대화
3. conversation = \n으로 구분된 멀티턴 텍스트 대화
```
- Linear SVC, CNN, LSTM, Bi lstm, Bert의 모델을 사용하여 모델별 성능 비교를 진행하였음

- 평가항목
- ![스크린샷 2023-11-22 오전 1 26 19](https://github.com/minsung6333/DLthon_ttolmang/assets/138687269/8e88c881-48c6-42a4-8cb3-fea3e9cdf0cb)
