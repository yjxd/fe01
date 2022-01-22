# HTML

## HTML Introduction

- HTML : Hyper Text Markup Language

  - Hyper Text : 하이퍼링크로 연결된 웹 문서 => 웹 문서(페이지)
  - Markup Language : 표시 언어

- HTML 표시 내용
  - Web Page의 Contents
    - Text Contents
    - Meltimedia Contents : image, video, audio
  - Wdb Page의 Structure

## HTML Basic

- 기본구조

※ ` : backtick

```
<!Doctype html>
<html>
  <head>
    웹 문서의 부가정보
  </head>
  <body>
    웹 문서의 내용
  </body>
</html>
```

## HTML Element

- Tag와 Contents로 구성
- Tag는 시작태그와 종료태그로 구성
  - contents와 종료태그 없이 시작태그만 있는 요소 : 빈요소(Empty Element)

```
  <h1>제목</h1>

  <br> => 빈 요소(Empty Element)
```

## HTML Attribute

- HTML Tag의 추가정보
- syntax : name="value"

```
  <img src= "photo.jpg" alt="사진">
```

## Text Contents Element

### Heading
- 제목 : h(heading)
- h1 ~ h6

### Paragraph
- p(paragraph) : 단락
- hr(Horizontal Rules) : 수평선(단란을 구분하는 의미)
- br(Line Break) : 강제 줄바꿈
  ( ※ 강제 공백(Entity Code): &nbsp; - Non-breaking space )
  ( ※ & : ampersand )
  - HTML Text 줄바꿈, 공백 인식
    - 공백 1칸으로 인식

