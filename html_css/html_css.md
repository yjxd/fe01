# HTML

## HTML Introduction

- HTML : Hyper Text Markup Language

  - Hyper Text : 하이퍼링크로 연결된 웹 문서 => 웹 문서(페이지)
  - Markup Language : 표시 언어

- HTML 표시 내용
  - Web Page의 Contents
    - Text Contents
    - Meltimedia Contents : image, video, audio
      - Embed(ed) Contents : 끼워넣은(넣어진) 컨텐츠- 이미 만들어진 컨텐츠를 가져다가 사용하는 것을 말함
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

### HTML List

- 순서없는 목록 : ul \_ li
- 순서있는 목록 : ol \_ li
- 설명 목록 : dl _ dt _ dd

※ 포함관계 / 중첩관계( Nested Element )

- 포함하는 요소 : 부모요소(Parent), 조상요소(ancestor)
- 포함되는 요소 : 자식요소(Child), 자손요소(descendant)
- 이웃하는 요소 : 형제요소(sibling)

### HTML Link

- 하이퍼링크 연결
- a(anchor)
  - href(hypertext reference) attribute : 연결되는 페이지의 주소 정보
  - target attribute : 새탭 열기 설정
    - target="\_blank" : 새탭 열기
- Bookmark 기능
  - 목적지에 id attribute를 사용해서 이름 지정
  - a 태그의 href 속성에 "#이름" 으로 위치 표시

### HTML Table

- 표를 표시
- table : 표의 영역 표시
- tr(table row) : 행(가로 줄)
- th(table heading) : 열 제목(칸)
- td(table date) : 열(칸)
- table generator
https://www.tablesgenerator.com/html_tables

## Multimedia Contents

### HTML image
- img(image) : 
- attribute
  - src(source) : 이미지의 파일 경로, 이름
  - alt(altanative) : 대체 텍스트

### HTML Video
- video tag
- attribute(name만 사용하는 형태)
  - controls : 동영상 컨트롤 버튼 표시 여부
  - autoplay : 자동 재생
  - muted : 음소거
  - loop : 반복 재생
  - poster : 영상 포스터(시작 전 화면) 대체 이미지

## Semantic Element
- 영역을 구분하는 Element를 의미있게 사용하는 것
- header : 로고, 로그인/회원가입, 사이트맵, 언어변경
- nav(navigation) : 메뉴 
  - gnb(global navigation bar), lnb(local navigation bar)
- section : 웹 페이지의 본문 / 영역 구분
- article : 웹 페이지의 본문 / 독립된 글/내용
- aside : 부수적인 내용 / 광고 배너
- footer : 웹 사이트의 위치 정보 / 관련 링크
- figure : 다이어그램 / 이미지 같은 시각 요소를 감싸주는 역할
- main : 웹 페이지 본문 전체