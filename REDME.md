*** 파일 첫 다운

npm init react-app .

src = (index.js), public = (index.html) 빼고 필요 없음

*** index.html
<!DOCTYPE html>
<html lang="ko">
  <head>
    <meta charset="utf-8" />
    <title>주사위 게임</title>
  </head>
  <body>
    <div id="root"></div>
  </body>
</html>

*** index.js
import ReactDOM from "react-dom/client";

const root = ReactDOM.createRoot(document.getElementById("root"));
root.render(
  <></>
);

*** chrome -> react developer tools 확장프로그램 다운

*** Prettier - code formatter 설치
1. 화면 왼쪽의 퍼즐 아이콘(Extensions 메뉴)에서 Prettier를 설치합니다.
2. 화면 왼쪽의 톱니바퀴 아이콘(Manage 메뉴)에서 Settings 메뉴로 들어갑니다.
3. 상단의 검색창에서 format을 검색한 다음 Default Formatter 를 Prettier로 설정하고 Format On Save 옵션 켭니다.

*** React 자동완성 안됨 라고 치면 자동완성 안되는 방법 나옴








