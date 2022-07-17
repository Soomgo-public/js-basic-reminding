## 📚 읽은 내용

### 스코프 역할을 하는 함수
- 익명 힘수 표현식은 빠르고 쉽게 입력할 수 있어서 많은 라이브러리와 도구가 이 자바스크립트 특유의 표현법을 권장하지만
- 익명 힘수 표현식 단점 -> 힘수 표현식을 사용할 때 이름을 항상 쓰자!
    - 스택 추적시 표시할 이름이 없어서 디버깅이 더 어려울 수 있다.
    - 폐기 예정인 arguments.callee 침조가 필요하다.
    - 쉽게 이해하고 읽을 수 있는 코드 작성에 도움이 되는 이름이 없다.
- ( )로 함수를 감싸면 즉시 호출 함수 표현식 (IIFE) 이 됨.
    - 함수를 둘러싼 첫번째 ()는 함수를 표현식으로 바꾸고, 두번째 ( )는 함수를 실행시킨다.

### 스코프 역할을 하는 블록
- 블록 스코프: 블록 {}이 생성될 때마다 새로운 스코프가 형성되는 것을 의미
- 블록 스코프의 목적: 변수를 최대한 사용처 가까이에서 최대한 직은 유효 범위를 갖도록 선언하는 것
- 블록 스코프는 '최소 권한 노출의 원칙'을 확장하여 정보를 함수 안에 숨기고, 나아가 정보를 코드 블록 안에 숨기기 위한 도구다.
- try/catch 문 중 catch 부분에서 선 언된 변수는 catch 블록 스코프에 속한다.


## 📚 느낀점


## 📚 공유하고 싶은 부분(사이트)