# 모던 자바스크립트 STUDY

+ 자바스크립트 요약
    + 변수,자료형
    + 연산자
    + 조건문
    + 함수

+ ### 리액트
    
+ mini 프로젝트



## What is ES6 ?

 + ECMAScript6 를 의미하며, 자바스크립트의 버전을 의미
   ES6는 2015년에 도입되어 ES2015라고도 한다.
   
 + 이후에 계속해서 나오고 있다.
   ES7(ES2016) ES8(ES2017) ES9(ES2018) ES10(ES2019).. 새로운 버전이 나올때마다 새로운 문법이 소개된다.

 + 현재 ES6 웹브라우저 지원현황
     + https://kangax.github.io/compat-table/es6/


 + Babel 이라는 도구를 사용하여 최신 버전의 자바스크립트가   구버전의 브라우저에서도 실행되도록 할 수 있다.
 (정확히는, 최신버전 자바스크립트를 구버전 형태로 변환하는 작업.)

 + babel 설치
    + babel 설치를 위해서는 npm이라는 패키지 매니저가 있어야 하는데, 이건 node.js를 깔면 자동으로 딸려온다. 없으면 노드를 먼저 깔아주자. cmd창 열고 아래 커맨드
    
        ```
        npm install -g babel
        
        npm install --save-dev -g babel-cli

        npm install --save-dev babel-preset-env
        ```
        + 사용법
        ```
        babel index.js

        babel index.js --preset=env --out-file foo.js
        ```

    + 다른방법
        + https://github.com/babel/babel-standalone

## CodeSandbox 

 + 코드를 작성하고 바로 결과물을 확인 할 수 있는 서비스

 + Create Sandbox 를 누르고 Vanilla 선택 
 
 + ( Vanilla 는, 다른 라이브러리 없이 자바스크립트만 사용하겠다는 의미)



## 참고 사이트

+ Webpack과 Babel로 최신 JavaScript 웹프론트 개발환경 만들기 
    https://beomi.github.io/2017/10/18/Setup-Babel-with-webpack/

+ https://ux.stories.pe.kr/134
