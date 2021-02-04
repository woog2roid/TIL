## var, let, const
__var 키워드의 단점들을 해결하기 위해 ES6에서 도입__  

var 키워드의 문제점/특징
- 함수 레벨 스코프
  - 전역변수 남발, 블록 레벨 스코프에서 되던 것들이 안됨...
- var 키워드 생략 허용
  - 암묵적 전역 변수 양산...
- 변수 중복 선언 허용
  - 변수값의 의도치 않은 변경 가능
- 변수 호이스팅
  - 변수를 선언하기 이전에 참조가 가능해짐(선언은 맨 위로 올라갈테니)
---
__let의 특징__
- 블록 레벨 스코프
- 변수 중복 선언 금지
- 선언 이전에 참조 불가

_이제는 closure 없이도 편하게 코딩가능_

---
__const의 특징__
- let은 재할당이 가능하지만 const는 불가능
  - 선언과 동시에 초기화 필요
- 블록 레벨 스코프
- 객체 타입 변수 선언에는 const가 좋다
  - 참조는 바꾸지 못하지만 property는 바꿀 수 있다.

---
__var,  let, const ??__
1. ES6를 사용한다면 var은 사용하지 않을 것
2. 재할당이 필요할 경우 let사용, 변수의 스코프는 좁게
3. 변경이 발생하지 않는 원시 값과 객체에는 const 이용   