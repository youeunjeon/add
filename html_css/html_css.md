# HTML

- Contents

  - Text
  - Media
    - Image, Video, Audio

- Structure
  - Semantic : 의미있는 구조
  - Layout

## HTML basic

- HTML : Hyper Text Markup Lanaguage

  - Hyper Text : 하이퍼링크로 연결된 문서 => 웹페이지(콘텐츠, 구조)
  - Markup : 표시
  - Language : 언어

- HTML 문법
  - 명칭 : Tag/ Element
  - 구성 : 시작태그 ~ 종료태그
  - 종료태그가 없는 태그 : 빈태그(Empty Element)

```
<tag> content </tag> : Element

<tag ...> : Empty Element
```

- HTML 속성

  - HTML Element를 표시할때 필요한 추가정보 입력
  - name="value"

  ```
    <a href="https://www.naver.com">네이버</a>
    <img src="photo.jpg">
  ```

## HTML Basic Structure

```
<!DOCTYPE html>
<html>
  <head>
    <title></title>
  </head>
  <body></body>
</html>
```

### DOCTYPE

- HTML 문서타입
  - HTML 버전
  - HTML5 표준

### Head

- meta : 웹사이트 관련 정보(검색 엔진)
- title tag :

### Body

- web design template free psd
  https://freebiesbug.com/psd-freebies/website-template/
- ui design tool: figma, Adobe XD

## HTML Contents

### Text

#### heading(제목)

#### paragraph(단락)

- p(paragraph):단락태그
- 강제줄바꿈, 강제 공백은 인식되지 않고 공백 한 칸으로만 인식
  - line break : br(강제줄바꿈 태그)
  - space : &nbsp; (강제공백 entity)
- hr(horizontal rule) : 수평선 긋기
  - 단락을 선의 형태로 구분

#### list(목록)
- ul(Unordered list)
- ol(Ordered list)
- li(list item)

** 포함관계(Nested Structure)
- 태그안에 다른 태그들이 포함되는 것
- 포함하는 요소
  - 조상요소(Ancestor)
  - 부모요소(Parant)
- 포함되는 요소
  - 자식요소(Child)
  - 자손요소(Descendant)
- 동급 요소
  - 형제요소(sibling)
  ```
  (1) <html>
  (2)   <body>
  (3)     <h1></h1>
  (4)     <p>
  (5)         단락내용<br>
          </p>
        </body>
      </html>
  ```
  (1) 조상요소 | 기준요소 | 조상요소
  (2) 조상요소 | 자식요소 | 부모요소
  (3)         | 자손요소 | 형제요소
  (4) 부모요소 | 자손요소 | 기준요소
  (5) 기준요소 | 자손요소 | 자식요소
#### table(표)

#### hyper link(하이퍼링크)

### Media

#### image(이미지)

#### video(영상)

## HTML Structure

### Semantic

### Layout

#CSS
