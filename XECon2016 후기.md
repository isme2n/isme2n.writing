# XECon 2016
2017-01-23-XECon2016

XECon 2016에 다녀와서 메모한 것들을 정리해 본다.

 # webpack 실무

 레진 개발자.

 웹팩 - 여러리소스 번들링

 로더 - 파일을 핸들링 -리소스파일 변환 - babel loader, css loader
 플러그인 - 청크를 핸들링

 ## 웹팩을 선택한 이유

 * ES2015(ES6)를 사용하기 위해

 ## 후보
 * 브라우저리파이
 * 시스템 JS
 * 웹팩
 * 롤업

## 적용법

* yarn
* babel 
* multiple
* common module
* html plugin
* webpack dev server

# 프론트엔드 스택변화 : JQuery, Backbone, ReactJS
텀블벅 개발자.

JQuery - 복잡한 클라에 대응

SPA - 모든걸 넘길테니 조립하세요.

여태껏 대세 - BackboneJS + JQuery

BackboneJS 
* Model - data 
* Collection - model의 집합
* Event - user가 만드는
* View
* Router


ReactJS
* View만 담당 - 백본은 위와 같이 많은 반면.
* 상태에 따른 View 관리만 신경쓰면 됩.
* 모든걸 컴포넌트로
* 단방향 데이터
* 서버사이드 렌더링 - 확장가능

## 결론

* 편리하면 씁니다.
* 커지는 사용자 요구

## 이후는?
* 프로그레시브 웹 앱
    * 네이티브앱 유사
    * 홈스크린 설치
    * 오프라인 기능구현
    * 푸쉬알림가능
* 함수형 프로그래밍 인기
    * 상속보단 조립
    * 불변성 (부작용 없앰)
* 웹 컴포넌트
    * 커스텀 엘리멘트
    * HTML imports
    * Templates
    * Shadow DOM
