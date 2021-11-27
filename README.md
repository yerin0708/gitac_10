# 참고 사이트 주소

https://github.com/

https://codesandbox.io/

https://www.w3schools.com/

# 공유주소

https://github.com/edu-ministori/gitac_10

https://codesandbox.io/s/html-css-2537y?file=/README.md

# 쌤 계정

https://github.com/edu-ministori/gitac_10

# Front End Develop

> 제목
>
> - "# ~ ######"
>   인용문
> - ">"
>   목록
> - "~"
>   블럭영역
> - `(backtick)

## Client - Server Model

> H/W

- Client : 사용자가 사용하는 디바이스(컴퓨터, 모바일)
- Server : 제공자가 사용하는 디바이스(컴퓨터)

> S/W

- Client : 사용자가 사용하는 디바이스에서 실행되고 있는 S/W
  - 웹 개발에서 client : browser
- Server : 서버 컴퓨터에서 실행되고 있는 S/W
- 리눅스 OS - apache
- 윈도우 OS - IIS

> Front End Develop

- Front End : 사용자가 모니터/화면을 통해서 볼 수 있는 영역
- Front End Develop : UI/UX 요소 개발

> Back End Develop

- Back End : 사용자가 확인할 수 없는 영역
- Back End Develop : 데이터 처리, 보안 개발

> 웹 개발 Front End

- browser에서 표시되는 UI/UX 요소 개발
- browser에서 HTML/CSS/Javascript를 랜더링해서 표시
- 소스코드 처리 : 서버에서 HTML/CSS/Javascript 파일을 전송

> 프로그래밍 언어 번역과정

- compile : Ex) 통번역
- interprete : Ex) 동시통역
- 웹 Front End : Render

### HTML table

- HTML table generator

https://www.tablesgenerator.com/html_tables

#CSS

##CSS Syntax

```
h1 {
  color:red;
  font-size:12px;
}
```

###CSS Selector
https://www.w3schools.com/html/html_id.asp
https://www.w3schools.com/html/html_classes.asp

### id

- 같은 HTML 페이지에서 고유한 이름으로 사용되어야 함. (한번만 사용되어야 함) => 논리적 개념
  - id는 프로그래밍 언어에서 변수와 같은 개념
- 한 HTML 요소에 여러개의 id 이름을 지정할 수 없음

### class

- 같은 HTML 페이지에서 같은 class 이름을 여러번 사용 가능함.
- 한 HTML 요소에 여러개의 class 이름을 지정할 수 있음.

```
// HTML
<p id="paragraph">단락</p>
<div class="container">콘텐츠</div>
<div id=>

// CSS
- Element 선택자
p{
  color:red;
}

- id 선택자
#paragraph{
  color:blue;
}

- class 선택자
.container{
  color:green;
}
```

- 선택자 연결 표현
  - 선택자의 자세한 표현

```
<p id="para" class="sentence">단락</p>

p#para{}

p.sentence{}

#para.sentence{}
```

### CSS 작성방식

- External : 외부 파일
- Internal : html 페이지에 CSS를 작성 - head > style 태그를 사용해서 CSS 코드 작성
- Inline : html 요소에 style attribute를 사용해서 직접 적용

##Color 이론

- 색 혼합 방식

  - 가산 혼합 : 빛 혼합

    - 혼합하는 색이 많을수록 밝아짐, 모든 색 혼합 => 흰색
    - 스크린(화면)
    - 컬러모드 : R(ed)G(reen)B(lue)

  - 감산 혼합 : 잉크 혼합
    - 혼합하는 색이 많을수록 어두워짐, 모든 색 혼합 => 검정색
    - 프린터
    - 컬러모드 : C(yan)M(agenta)Y(ello)(blac)K

- RGB 컬러모드에서 색 표현

  - 각각의 색 표현 용량 1byte => Red(8bit), Green(8bit), Blue(8bit)
  - 24bit true color : 약 1700만 개
  - 10진수 표현(0~9)
    - rgb(red 값(0~255), green 값(0~255), blue 값(0~255))
    - Ex) rgb(100, 50, 245)
  - 16진수 표현(0~9, A(10), B(11), C(12), D(13), E(14), F(15))

    - #R(AA)G(0E)B(FF)
    - Ex) #3A79BF

> 컴퓨터에서 사용하는 진법(진수) - 2진수(0,1)
>
> 용량단위
>
> - bit : 데이터 저장 최소 단위
>   > 저장 공간 1칸 : 0, 1 중에 하나를 저장

> - byte : 1byte = 8bit
>   > byte < KB < MB < GB < TB

> 용량 계산
>
> - 1byte = 8bit가 저장할 수 있는 데이터의 개수 : 256개 (0~255)

## CSS 상속

- 조상요소, 부모요소에 적용된 CSS style이 자식요소, 자손요소에 상속되어 적용되는 현상
- 모든 CSS 속성이 상속되는 것은 아님
- 모든 HTML Element가 상속되는 것은 아님

```
<div>
  <p>단락</p>
</div>

div{
  color:red;
}

* div에 적용한 색이 p에도 상속되어 적용됨
```

## CSS Property(속성)

- HTML Contents Styling

  - Text Contents Styling
  - Multi media Contents Styling

- HTML Structure Styling

## Text Contents Styling

### CSS Text

https://www.w3schools.com/css/css_text.asp

- color : text color 지정

```
p{
  color:#34eb74;
}
```

- text-align : 텍스트 정렬

  - left, right, center, justify

- text-decoration : 텍스트 줄

  - overline, lihe-through, underline, none

- text-indent : 들여쓰기

- letter-spacing : 글자 간격

  - 양수, 음수 사용 가능

- line-height : 줄 높이
  - px, 배수 표현

## Box Model

https://www.w3schools.com/css/css_boxmodel.asp

- HTML element는 박스형태로 표현 (디자인)
- Box Model 구성요소
  - content : width (가로길이), height (세로길이)
  - padding (안쪽 여백)
  - border (테두리)
  - Margin (바깥 여백)
  - - background (배경) - 박스모델과 연관
    * background 적용 범위 : content, padding 까지 적용

### height/width

https://www.w3schools.com/css/css_dimension.asp

- 기본 특징 : height/width를 지정하지 않았을 때 특징

  - Block
    - height : 자식요소를 기준으로 맞춰짐
    - width : 부모요소를 기준으로 채워짐
  - Inline

    - height/width : 자식요소를 기준으로 맞춰짐

- px : 수치값으로 고정
- % : 상대적인 크기
  - 부모 요소를 기준으로 상대적 크기 지정
  - 부모의 크기가 변경되면 따라서 변경됨(유동형:fluid)

### padding

https://www.w3schools.com/css/css_padding.asp

> 방향 적용 순서 (top에서 시작 시계방향 순서로 적용)
>
> top -> right -> bottom -> left

- padding-top
- padding-right
- padding-bottomm
- padding-left

- padding 축약 표현(shorthand)

```
padding:10px 20px 30px 40px;
padding:10px 20px 30px;
padding:10px 20px;
padding:10px
```

### border

https://www.w3schools.com/css/css_border.asp

- border 축약표현(shorthand)

```
border:1px solid red;

* 방향 지정
border-top:1px solid red;
border-right:1px solid red;
border-bottom:1px solid red;
border-left:1px solid red;
```

### margin

- padding과 같음

- margin collapse(충돌/상쇄)
  https://www.w3schools.com/css/css_margin_collapse.asp

  - 박스가 위아래 방향으로 놓여있을 때 생기는 현상(좌우 방향에서는 생기지 않음)
  - 위아래 놓여있는 박스에 margin을 적용했을 때, margin이 합쳐지지 않고 큰 margin만 적용
  - 위아래 인접해있는 박스 사이의 margin을 적용할 때 박스 한쪽을 기준으로 적용

### background

https://www.w3schools.com/css/css_background.asp

- 배경 색
  - background-color
- 배경 이미지

  - background-image
  - background-repeat : 배경이미지 반복여부
  - background-position : 배경이미지 위치
  - background-attachment : 배경이미지 고정여부

- 투명도

  - opacity, transparency, alpha

- opacity

```
p{
  opacity:0.5; / * p요소 전체를 0.5만큼 반투명 설정 */
}
```

- transparency

```
h1{
  background-color:transparent; /* 투명 배경 */
}
```

- alpha

```
div{
  background-color:rgba(200, 135, 80, 0.5) /* 배경색에서 투명도 설정 */
}
```

- background-repeat

  - repeat-x, repeat-y, no-repeat

- background-position
  - left, center, right / top center bottom
  - px

```
h1{
  background-position : value1 value2
  /*
    value1 : 가로방향
    value2 : 세로방향
  */
}
```

- background-attachment

  - fixed

- background 축약 표현 (shorthand)

- background-size
  - contain, cover

## multi media contents styling

- image
- video

- 크기 조정, 배치 => Bpx styling

### 박스 모델 적용

- block : 좌우로 나란히 배치가 안됨
- inline : 박스 모델 제대로 적용되지 않음
- inline-block : inline 요소 특징(나란히 배치)과 블럭요소 특징(박스모델이 적용)

- display : 화면에 표시되는 박스 성질을 변경
  - block, inline, inline-block
    - inline, inline-block에서 인라인요소의 단점 : 제어할 수 없는 여백
  - none : 화면에 표시하지 않음
  - flex

### 박스 크기 계산

- width/height, padding, border가 박스 크기 계산에 적용되는 구성요소
- box-sizing:border-box; 적용하면 width/height가 박스 전체길이로 적용됨

## HTML Structure Styling - layout

- 박스 배치

  - 가로
  - 세로

- 규칙
  - 가로, 세로 방향으로 배치될 때 한 가지 연결

### Flexbox

- 부모요소에 적굥하는 css prorperty
  - 레이아웃과 연관되는 property
- 자식요소(배치되는 박스)에 적용하는 css property

- dispaly:flex; 적용
- flexbox 적용했을 때 width/height의 기본 특징이 뒤바뀜

-flex-direction

- column(세로), row(가로)
- column : 축이 90도 회전ㄴ => 가로방향 정렬 : align-items

-flex-wrap

- wrap : 자식요소의 크기를 유지하면서 박스가 줄바꿈되어 표시
