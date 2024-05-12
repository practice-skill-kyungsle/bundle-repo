# skill 을 연구하고 연습하는 공간 🙌

<!-- 
||||
|----|----|----|
||||
||||
||||
-->

## 🧪🧪🧪 2024

| ⭐react dom server 공부| 무한 슬라이드 구현    | 번개장터 코딩테스트 공부   | 
|--------------|--------------|--------------|
|| ![ezgif com-video-to-gif-converter](https://github.com/keinn51/practice_skill/assets/79993356/f14bed25-1bff-4843-ac89-055b2f5c8dbf) |    ![image](https://github.com/keinn51/practice_skill/assets/79993356/c2d8f935-4a57-4751-9b10-a2c50cf27db1)|
|#react #ssr #react-server #express|#react|#react|
| React DOM Server라는 것에 대해서 부끄럽게도 전혀 모르고 있었다. React와 express를 이용해서 SSR을 구성해보고, NextJS가 과연 어떻게 생겨먹은 애일까 생각해본다. |  Qshop 제품에 무한슬라이드를 구현해야 해서 연구   | 라이브러리 사용 이유, 폴더 구조, 데이터 불러오기, 코드 주석 등에 대해서 사전 준비. 사용한 라이브러리를 왜 사용했는지 충분히 고민해보기.  |

## 🧪🧪🧪 2023

|이벤트 버스 연구|웹워커 연구|child component로 jsx tag를 내려줄 때, property를 새로 붙이는 방법 연구|
|--------------|--------------|--------------|
|![image](https://github.com/keinn51/practice_skill/assets/79993356/043d2cde-5c59-453e-91d5-41776802d07a)|![image](https://github.com/keinn51/practice_skill/assets/79993356/9f913f68-82a5-4694-8875-94ef2e679e19)||
|#event_bus #reactjs|#web_worker #vanilla_js|#reactjs|
|현업 제품에서 전역 상태 라이브러리를 이미 사용하고 있던 상태. 전체 리팩토링을 하기 어려워, 일부 컴포넌트만 이벤트 버스를 활용하여 성능을 개선하기 위해 사용. |현업 제품에서 이미지 렌더링, 이벤트 등으로 인한 메인 스레드 과부화를 방지하기 위해 연구. 서브 스레드를 활용하여 메인 스레드의 작업량 줄이기.|elem에 중괄호를 붙여 바로 렌더링할 수 있지만, 이 방식을 사용하면 property를 동적으로 붙이지 못한다. property를 붙이려면 함수형 컴포넌트를 동적으로 만들어야 한다는 생각으로 이어졌다.|

|Nomad Coder React Native 101|리액트 테스트 라이브러리 연구|webpack 으로 MPA를 SPA로 바꾸어보자|
|--------------|--------------|--------------|
|![image](https://github.com/keinn51/practice_skill/assets/79993356/a5e2343c-0030-488d-b731-9d59ad32d35c)|![image](https://github.com/keinn51/practice_skill/assets/79993356/f26443d3-7d70-4d1b-898d-536fcf1a420e)||
|#react_native|#testing_library #jest_dom|#webpack #vanillajs|
|프론트엔드 개발자는 화면단에 보이는 모든 것을 개발할 수 있어야 하지 않을까? 앱이든 웹이든? 서버 개발자와 디자이너가 주는 것들을 쳐낼 수 있어야 한다. 마침 자바스크립트를 사용해서 앱을 개발할 수 있는 방법이 있다고 해서 공부해본다.|리액트에서 제공하는 Testing Library와 Jest-Dom을 사용하여 테스트 환경 연습해보기!|VanillaJS 에서 사용하는 Multi Page Application 형식에서, webpack을 이용한 Single Page Application으로 전환해본다.|

|JSON 스키마 연구|웹 쿠키 주고받기 해보기|react color picker 연구|
|--------------|--------------|--------------|
|||![image](https://github.com/keinn51/practice_skill/assets/79993356/5289ae21-b143-4df8-9f17-d167df304fa3)|
|#json|#cookie|#color_picker #reactjs|
|현업에서 JSON을 다룰 일이 많아서, JSON 테스트를 할 수 있다는 스키마에 대해서 공부.| 도메인이 달라서 쿠키가 안 보내지는 상황 목격. server에서 쿠키를 보내고 받아보는 연습을 통해 쿠키와 친해지기.|현업에서 컬러피커를 구현해야 하는데.. 어떻게 해야 하는지 몰라 하나하나 써봅니다.|

## 🧪🧪🧪 2022

|scroll indicator 연구|jquery scroll 연습|redux 101 노마드 코더 강의 수강|nextjs 노마드 코더 강의 수강|
|----|----|----|----|
|![image](https://github.com/keinn51/practice_skill/assets/79993356/2298be8e-34bd-465c-b088-c8581db86714)|![image](https://github.com/keinn51/practice_skill/assets/79993356/08797cef-ee3c-46dc-9734-c900f975f6c5)|||
|#vanillajs #scroll|#jquery #scroll|#reactjs #redux|#nextjs|
|Qshop 메인 페이지에서 스크롤 인디케이터를 넣어야 하는데 어떻게 넣어야 하는지 몰라서 공부.|Quv라는 Qshop 이전 버전 제품의 메인 페이지에서 스크롤 애니메이션 구현을 맡아 공부. 어떤 식으로 구현해야 할지를 연습했으며, 스크롤 시 특정 범위를 넘어가면 애니메이션이 작동하도록 구현함. |redux의 사용법을 공부하여, Qshop에서 사용하는 react 자체의 context hook 에 대한 이해를 하려고 함.|Qshop 제품에서 nextjs를 도입하려고 하는데 이에 대한 숙련도가 낮은 것 같아 공부.|

## 🧪🧪🧪 2021
|html css 생활코딩 강의 듣기|display flex 속성 공부|구글 페이지 클론|
|----|----|----|
||![image](https://github.com/keinn51/practice_skill/assets/79993356/6cc200d1-1f98-4c9a-8598-3e4173d8a04f)|![image](https://github.com/keinn51/practice_skill/assets/79993356/36117eaf-e458-4ea8-9b1e-5b71c9a1f0e1)|
|#vanillajs|#vanillajs #display-flex|#vanillajs|
|vanillajs 기본기를 더욱 익히기 위하여 강의 수강|flex 속성이 무엇인지 몰라 공부|거의 맨 처음 진행했던 프로젝트. 구글 페이지를 클론해보며 기본기를 익힘.|
