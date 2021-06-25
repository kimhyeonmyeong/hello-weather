## ReactNative

크로스 플랫폼앱에 관해서, 그 중에서도 ReactNative에 대해서 공부하고 강의를 수강한 뒤 간단한 날씨 알림 App을 구현한 코드들입니다.

https://kimsmartblog.tistory.com/

블로그 ReactNative 파트에 기능별로 정리되어있습니다.


## 강의 제목 및 출처

https://nomadcoders.co/react-native-fundamentals
Web front, backend Full stack Nomad 선생님

## 진행 기간
2020-07-27 ~ 2020-07-31


## 목차

![image](https://user-images.githubusercontent.com/44837403/114274864-5002e300-9a5b-11eb-9452-f132693fe5d6.png)
![image](https://user-images.githubusercontent.com/44837403/114274871-55602d80-9a5b-11eb-8a83-6d4d56fd7bda.png)


## 프로그램 기능

#### Loading Screen

![image](https://user-images.githubusercontent.com/44837403/123379898-b793ed80-d5c9-11eb-95e3-5cd2a12c9f40.png)

Loading Component를 만들고 App.js의 render 부분에서 실행해줍니다.

#### Expo library를 활용해서 위치 정보를 받아오고 권한을 요청하는 기능

expo-location을 이용해보기. expo 공식문서를 참조해서 requestpermission을 받고 사용자의 지역정보를 가져옵니다.
try-catch문을 사용하고 getLocation은 await - async의 형태입니다.

#### Weather API받아와서 사용

axios를 이용한 async - await형식으로 데이터를 API로 받아와서 사용해줍니다.

#### 받아온 날씨 데이터를 PropTypes를 지정해서 사용

날씨 데이터를 Clear, Clouds 등등 condition에 맞게 Proptypes를 지정해서 사용합니다.

#### 날씨 상태에 따라서 icon 적용해서 App에 나타내기

https://docs.expo.io/guides/icons/
expo icon 에서 expo init에서 기본적으로 깔리는 package를 사용하였습니다. 위 참고링크를 참고해서 보면 됩니다. 배치할때에는 flex로 공간할당을 생각하면서 하였고, 이 때 container를 두개의 halfcontainer로 나누어서 사용을 하였습니다.


#### 프로그램 동작

![image](https://user-images.githubusercontent.com/44837403/123379856-a9de6800-d5c9-11eb-9b50-1ff952a047d6.png)


## 느낀점

 React Native앱을 만들고자 그동안 공부했던 VanliaJS, ReactJS들이 기초가 되면서 어느 정도 수월하게 진행되었던 것 같습니다. 본격적인
 ReactNative앱을 만들기 전에 환경 setting을 하고 어떤식으로 앱이 만들어지는지에 대해서 알 수 있었습니다. 확실히 모바일 어플로 확인을 하니
보람이 느껴지는 순간이였습니다.







