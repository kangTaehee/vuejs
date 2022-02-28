# vue.js

## 대용량 성능 최적화

* 전역 변수의 사용
* 타이머와 콜백
* 외부에서의 참조
* Closures의 사용
* [출처:  [웹아틀리에 - Web atelier]](https://web-atelier.tistory.com/49)

* 그래서 가장 중요한 것은 대용량의 데이를 가지고 있는 모델은 Vue의 반응형 관리대상에서 제외를 시키는 것이다.

* 모델에 대한 가공은 최소화
* 모델에 대한 반응형 제거

1. Object.freeze() - 사용
