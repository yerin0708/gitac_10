# Javascript

- 알고리듬(algorithm)

https://www.youtube.com/watch?v=SESuctdE9vM
https://www.youtube.com/watch?v=OoRrKmmlEeY

- 문법
- 활용 => 알고리듬
  - 자바스크립트 활용 범위
    - Front end 개발
    - Node js => Back end 개발
  - 활용 방향
    - Library, Framework
    - API, Component 개념

## Javascript 문법

- javascript : 웹 브라우저에서 효과를 실행하기위해 사용된 언어
- version

  - ES5
  - ES6

- JS 작성방식

  - External, Internal, Inline
  - JS가 실행되는 시점에서 필요한 HTML Element가 로딩(렌더링)되어 있어야 함.
    - JS의 실행 순서를 HTML 렌더링 시점 이후로 배치
  - JS가 실행되는 시점에 상관없이 HTML Element가 로딩(렌더링)이 완료될 때 까지 기다림.
    - script 시작태그에 defer attribute를 사용함
    - External 방식에서만 사용 가능

- ES6에서 추가된 내용
  - 변수 개념 확장
  - class 개념 추가
  - 함수 사용 방식 확장
  - 프레임워크/라이브러리(node.js / react / vue.js) 사용됨

### 문법 내용

- 변수 / 데이터 / 연산자
- 명령문(구문)
- 함수
- 배열 / 객체 / class
- 추가 문법

### js variable(변수)

https://www.w3schools.com/js/js_variables.asp

- 변하는 수
- 수(값:데이터/value)가 저장되는 공간
- 변수를 사용하기 위해서 선언(declaration)해야 함

```
변수선언키워드 변수이름 [= 초기값];

** 키워드 : 예약어
** [] : 생략 가능

var a = 0;

** var(variable) : 변수 선언 키워드, ES5
```

```
Naming 표기법
- 가독성 : 여러 단어를 사용해서 Naming을 할 때 단어와 단어사이를 구분

car-person-name : kebab case
car_person_name : snake case
carPersonName : camel case
CarPersonName : Pascal case

Ex)
HTML/CSS id, class : kebab case
file, folder : snake case
javascript : camel case, pascal case
```

### js let, const

https://www.w3schools.com/js/js_let.asp
https://www.w3schools.com/js/js_const.asp

- ES6에서 추가된 변수 선언 키워드

```
let a = 0;
const b = 'abc';
```

- let

  - 변수 적용 범위의 변화
  - 변수 값을 변경 가능

- const
  - 변수 적용 범위의 변화
  - 변수 값을 변경 불가능

* 객체(object)

  - 데이터 집합

* javascript 데이터의 타입을 구분하지 않음
  - 변수 선언시에 데이터 타입을 구분하지 않음
  - 데이터 상세 타입을 구분하지 않음

```
java

int a = 0; // 정수 형태의 데이터, 1byte 크기
short b = 1; // 정수 형태의 데이터, 2byte 크기
float c = 1.5; // 실수 형태의 데이터
String d = "Hello"; // 문자열 데이터

** 변수가 데이터 타입을 구분
- int 변수에 문자데이터를 저장할 수 없음

javascript

var a = 1;
var b = "Hello";
let c = 1;
let d = "Hello";

** 변수가 데이터 타입을 구분하지 않음
** typescript 언어 - javascript + 데이터 type을 구분
```

### 연산자(operator)

https://www.w3schools.com/js/js_operators.asp

- 할당(assignment) 연산자

```
=
```

- 산술(arithmetic) 연산자

  - +, -, \*, / (사칙연산자)
  - % : 나머지 연산자

- 할당 연산자 + 산술연산자 축약표현
