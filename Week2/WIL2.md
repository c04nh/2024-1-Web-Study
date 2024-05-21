## 1주차 과제 제출

### Q. JavaScript가 DOM에 어떻게 접근하고 적용될까?
JavaScript가 DOM에 어떻게 접근하고 적용될까?
다양한 방법으로 DOM에 접근할 수 있는데, 기본적으로 document 객체를 사용하여 접근한다. 
- document.getElementById("id명")
- document.querySelector("선택자")
- document.getElementsByClassName("class명")[순서]
- document.getElementsByTagName("태그명")[순서]
- document.querySelectorAll("선택자명")[순서]

같은 메서드를 사용해 특정 태그에 접근한다.


### Q. 브라우저를 이루는 컴포넌트 중, JavaScript Engine은 무엇이고 어떤 일을 할까?
JavaScript Engine은 JavaScript 코드를 실행하는 프로그램이다. 웹브라우저에서 JavaScript 코드를 해석하고 실행하는 일을 한다.


### Q. inline CSS가 항상 좋은 것일까? 아니라면 그 이유는 무엇일까?
좋지 않다.
inline CSS는 요소마다 개별적으로 작성하기 때문에 스타일을 재사용하기 어렵고, HTML 코드가 복잡해져서 가독성이 떨어진다.