## execution context
__실행 가능한 코드를 형상화하고 구분하는 추상적인 개념__  
__실행 가능한 코드가 실행되기 위해 필요한 환경__  
__실행 가능한 코드를 보면 그 코드를 실행 문맥으로 만들어 실행한다.__

실행 가능한 코드
- 전역코드: 전역 영역에 존재하는 코드
- Eval 코드: eval 함수로 실행되는 코드
- 함수 코드: 함수 내에 존재하는 코드

실행에 필요한 여러가지 정보
- 변쉬 전역/지역/매개 변수, 프로퍼티
- 함수 선언
- 스코프
- this, 등...

__실행에 필요한 정보를 형상화하고 구분하기 위해 자바스크립트 엔진은 실행 컨텍스트를 물리적 객체의 형태로 관리함(execution context stack)__