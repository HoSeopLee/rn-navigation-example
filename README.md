# RN Navigation Example

## 1.React Navigation tab 소개

모바일 앱은 기본적으로 탭을 기반으로 한 네비게이션 스타일을 흔히 볼 수 있습니다. 탭은 주로 하단이나 헤더를 대신하여 상단에 주로 위치해있고, 이 탭을 이용하여 우리는 이벤트를 발생시켜 다른 라우트로 쉽게 전환할 수 있게 됩니다.
</br>

## 2. React Navigation tab 설치

react-navigation에서 탭을 구현하기 위해서는 필요한 라이브러리들을 아래의 명령어를 통해 설치해야합니다.

- react-navigation-tabs 설치
  - npm install react-navigation-tabs --save or yarn add react-navigation-tabs
- react-native-reanimated 설치
  - npm install react-native-reanimated --save or yarn add react-native-reanimated
    </br>

## 3.Stack Navigation

- 스택 네비게이션의 개념은 자료구조의 스택처럼 하나씩 쌓아가는 개념입니다. 만약 모바일 앱에서 어떤 다른 페이지로 이동을 한다고 했을 때 그 페이지로 완전히 전환 되는 것이 아닌 그 페이지가 위에 쌓인다고 할 수 있습니다. 또 다른 페이지로 이동이 되면 쌓이고 뒤로가기 버튼을 통해 쌓인 스택을 하나 벗겨낼 수 있습니다.

</br>

## 4. Stack Navigation 설치

일단 스택 네비게이션의 사용을 위해 몇가지 라이브러리를 설치합니다.

- @react-navigation/stack @react-navigation/native 설치
  - npm install @react-navigation/stack @react-navigation/native --save or yarn add @react-navigation/stack @react-navigation/native
- 의존성 모듈 설치
  - npm install react-native-gesture-handler react-native-reanimated react-native-screens react-native-safe-area-context --save or yarn add react-native-gesture-handler react-native-reanimated react-native-screens react-native-safe-area-context
