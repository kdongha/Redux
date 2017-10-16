# <a href='http://redux.js.org'><img src='https://camo.githubusercontent.com/f28b5bc7822f1b7bb28a96d8d09e7d79169248fc/687474703a2f2f692e696d6775722e636f6d2f4a65567164514d2e706e67' height='60'></a>
Redux는 자바스크립트 앱을 위한 예측 가능한 상태 컨테이너입니다.
Redux는 여러분이 일관적으로 동작하고, 서로 다른 환경(서버, 클라이언트, 네이티브)에서 작동하고, 테스트하기 쉬운 앱을 작성하도록 도와줍니다. 여기에 더해서 시간여행형 디버거와 결합된 실시간 코드 수정과 같은 훌륭한 개발자 경험을 제공합니다.



##Redux의 세가지 원칙

하나, Single Source of Truth
어플리케이션의 state 를 위해 단 한개의 store 를 사용합니다.
Flux 와의 주요 차이입니다; 
Flux 에서는 여러개의 store 를 사용합니다

둘, State is Read-only
어플리케이션에서 store 의 state 를 직접 변경할 수 없습니다
state 를 변경하기 위해선 무조건 action 이 dispatch 되어야 합니다

셋, Changes are made with pure Functions
action 객체를 처리하는 함수를 reducer 라고 부릅니다
reducer 는 정보를 받아서 상태를 어떻게 업데이트 할 지 정의합니다

reducer 는 '순수 함수' 로 작성되어야 합니다.
    즉, 네트워크 및 데이터베이스 접근 X, 인수 변경 X
    같은 인수로 실행된 함수는 언제나 같은 결과를 반환
'   순수하지 않은' API 사용 불가 (Date.now(), Math.random() 등)




Redux 홈페이지 : https://deminoth.github.io/redux/