_**예시 버전입니다.**_
---

# Speech Restaurant Menu for Chef
* Team Name : 메뉴 좀 읽어조
* Developer : 이예은, 이은지, 이지현, 황동준
* Develop Platform : Python, Swift

## Introduction
TTS가 읽기 어려운 텍스트 들을 골라서 읽어 줄 수 있는 모델을 만드는 것이 목적입니다.
<br>
espnet의 open source를 어느 정도 빌려 모델을 만들 것이며, iOS 앱으로 배포함을 목표로 합니다.
<br>

## Method
### espnet
`espnet`에서 `Text to Speech(TTS)` 를 구현하려면 총 7가지의 `method`를 따라야 한다.
_아래는 예시 그림입니다._
![image](https://user-images.githubusercontent.com/51294226/111150517-89b60a80-85d1-11eb-8c4b-88153ee55d41.png)
1. Data Preparation
2. Wav dump or Feature extraction
3. Removal of long / short data
4. Token list generation
5. TTS statistics collection
6. TTS training
7. TTS decoding
8. (optinal) Pack results for upload

8번은 굳이 구현하지 않아도 될 것 같아서, 일단 7번까지의 과정이 필요하다.





Contact: 010-5898-8898, wbsl0427@gmail.com
