# HTML

## HTML Introduction

https://www.w3schools.com/html/html_intro.asp

> HTML : Hyper Text Markup Language

> -
> - 웹페이지의 컨텐츠 표시
> - 웹페이지의 구조 표시

## HTML Element
https://www.w3schools.com/html/html_elements.asp

- 콘텐츠를 표시하는 언어 : 태그
- 시작태그 + 콘텐츠 + 종료태그 : Element (요소)

```
문법
<tagname>contents</tagname>

콘텐츠, 종료 태그 없는 요소 : 빈요소(Empty Element)
<br>
```

> Nested Element (중첩, 포함 관계)

```
<section>
  <div>
    <p>텍스트</p>
  </div>
</section>

1. p 태그 기준
  - 포함하는 요소
    - div : 부모요소(parent)
    - section : 조상요소(ancestor)

2. div 태그 기준
  - 포함하는 요소 : section - 부모요소
  - 포함되는 요소 : p - 자식요소(children)

3. section 태그 기준
  - 포함되는 요소
    - div : 자식요소
    - p : 자손요소(descendant)
```

## HTML 기본 구조

```
<!DOCTYPE html> : 웹 문서 종류 표시
<html> : HTML 문서 영역 표시
  <head> : Web page 관련 정보, 파일 정보 등의 내용이 표시되는 영역

  </head>
  <body> : Web page 콘텐츠, 구조가 표시되는 영역

  </body>
</html>
```

## HTML Attribute (속성)
https://www.w3schools.com/html/html_attributes.asp

- HTML Element에 추가 정보를 제공
- 시작태그에 작성
- name="value" 형식으로 구성

## HTML Contents 표시 Element

> - Text contents
>   - 제목, 단락, 목록, 링크, 테이블(표)
> - Multimedia contents
>   - 이미지, 비디오, 오디오

### HTML Heading

- h : (h)eading : 제목 표시 태그
- h1 ~ h6 : h1 - 가장 큰 제목

### HTML Paragraph

- p : (p)aragraph : 단락 표시 태그

