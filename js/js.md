# Front End Develop Class

codesandbox 원본 주소: https://codesandbox.io/s/class06-vg1ugv

# Javascript

- 문법

  - Javascript 언어에 대한 문법 (HTML 과 CSS 를 배제한 Javascript 만)
  - 문법의 내용
    - 변수, 데이터, 연산자
    - 명령문
    - 함수
    - 배열, 객체, Class
    - 추가문법 (위의 4 가지에 걸쳐서 있는 문법 요소)

- 활용
  - HTML, CSS, JS 를 종합한 문법의 활용
  - HTML DOM
  - Open API: 객체 개념과 연결

# Javascript basic

- Version

  - ES5 와 ES6 는 문법이 약간 다름

- 작성방식

  - Javascript 와 CSS 는 HTML 안에서 합쳐져서 작동함
  - External 방식
    - HTML 파일과 js 파일을 각각 만들어서 HTML 파일에서 js 파일을 불러와서 작동시킴
  - Internal 방식
    - 파일을 HTML 안에 만드는 방식
    - HTML 문서 안에 Javascript 코드를 넣어주는 경우
    - js 코드 블럭을 따로 구분해서 작성
    - 우리 예제는 이 방식으로 진행
  - Inline 방식
    - HTML 코드 안에 js 코드를 넣는 방식
    - 쓰지 않는 것이 좋음

- 작성위치
  - js 가 실행되는 시점에 해당 js 가 적용될 HTML 코드가 로딩 (렌더링) 되어 있어야 한다.
  - js 실행방식: 최초 한번만 실행됨.

  ## JS 문법
  ### 데이터/변수/연산자
  - 데이터
   - 숫자
   - 문자
   ```
   숫자: 0,1,2,3,4,5......
   문자: 가, 나, 다...., a,b,c...
   ```
  - 데이타 타입
    - 숫자 : 정수, 실수
    - 문자
      - 코드상에서 문자는 따옴표로 묶임
      - 낱개 글자, 묶은 글자...
    ```
    1 + 1 = 2
    'a' + 1 = 'a1'
    '1' + 1 = '11'
    ```
    ** Javascript는 데이터 타입을 엄격하게 구분하지 않음
   - 변수(variable)
      - 데이터를 저장하는 공간
      - 변수는 선언(declaration), 정의(definition)를 한 이후에 사용해야 함
      - 변수 선언 예약어(키워드)
         - var (ES5) : 타입 구분 안함, 데이터 변경 자유로움
         - let (ES6) : 타입 구분 안함, 데이터 변경 자유로움
         - const (ES6) : 타입 구분 안함, 데이터 변경 불가능
      ```
      JAVA
      정수 변수 선언 : int number1;
      실수 변수 선언 : float number2;
      문자 변수 선언 : char text;

      ES5/ES6
      정수 변수 선언 : var number1; | let number1; | const number1;
      실수 변수 선언 : var number2; | let number2; | const number2;
      문자 변수 선언 : var text;    | let text;    | const text;
      ```
   - 연산자(Operators)
      _ 산술 연산자: Arithmetic Operators
         - +, *, -, /
         - % : 나머지 연산
      - 할당(대입) 연산자: Assignment Operators
         - = : 값을 변수에 저장
         ```
         const PI = 3.141592;
         ```
         - 산술 + 대입연산자 (재귀)
         ```
         let a=10;
         a=a+5
         a += 5 축약
         ```
         ** 산술 + 대입 연산이 반복 실행되면 일정 값을 지속적으로 연산
         - 카운터
         ```
         a += 1 => a++
         a -= 1 => a--
         ```
      - 비교 연산자: Comparision Operators
        ```
        같음 '1' == 1 : yes | '1' === 1 : no
        다름 != not equal   | !== not equal value and type
        ```
        - 비교 연산자를 사용한 식의 결과는 True/False

  ### 명령문
  ### 함수
  ### 배열/객체/Class
  ### 추가문법: 변수

  ## JS 활용
