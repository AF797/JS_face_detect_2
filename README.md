# JavaScript를 이용한 얼굴 인식

---

## 코드 구현

이번 실험은 지난번 실험에서 학습 시키는 사람을 6명으로 늘려서 실험하여 보았다.

아래 링크는 지난번 실험 링크이다.

[https://github.com/AF797/JS_face_detect](https://github.com/AF797/JS_face_detect)

JavaScript를 이용한 얼굴 인식을 구현하여보았다.

작업 환경은 VS code에서 구현하였다.

확장으로 Live Server를 사용하였다.

[https://www.youtube.com/watch?v=AZ4PdALMqx0](https://www.youtube.com/watch?v=AZ4PdALMqx0)

위 영상을 참고하여 JavaScript를 이용하여 얼굴 인식을 구현해보았다.

쉽게 설명하여 주어서 매우 도움이 된다.

코드는 다음 GitHub 주소에서 가져왔다.

[https://github.com/WebDevSimplified/Face-Recognition-JavaScript](https://github.com/WebDevSimplified/Face-Recognition-JavaScript)

---

## 구현 과정

![js2js](https://user-images.githubusercontent.com/86837707/203839760-c7db0eab-2dfb-4340-86a8-cd0ab0d90de4.jpg)

위에서 첨부한 GitHub 주소에서 파일을 다운 받은 후 위 사진처럼 6명의 폴더를 생성하여 주고, 각 폴더에 1.jpg, 2.jpg로 2장의 사진을 넣어준다.

사진을 2장을 넣는 이유는 아래 사진의 코드에 for문이 1~2인데 const labels의 요소들의 이름의 폴더에 1.jpg와 2.jpg로 학습 시킨 후 detect를 하여서 그러하다.

![js3js](https://user-images.githubusercontent.com/86837707/203839763-a5573cf0-479e-4800-9f91-4be3cb5053cb.jpg)

위 사진에 코드

const labels = []에 만든 폴더들과 이름을 같게 추가하여 준다.

그 후  index.html 파일을 오른쪽 클릭한 후 Open with Live Server를 클릭하면 동작하게 된다.

---

## 구현 결과

다음 사진들은 원본과 얼굴을 detect 한 후의 사진이다.

![jsjsjs](https://user-images.githubusercontent.com/86837707/203839752-485713eb-ea86-4752-9297-8c73a4cabafb.png)

![js1js](https://user-images.githubusercontent.com/86837707/203839758-e98551c1-4d13-4144-aab7-bf2079f857de.jpg)

정상적으로 구현이 잘 되는 것을 확인할 수 있다.
