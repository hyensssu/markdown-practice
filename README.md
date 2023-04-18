# 제목(Header)

# 제목 1

## 제목 2

### 제목 3

#### 제목 4

##### 제목 5

###### 제목 6

<br><br>

# 문장(paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

<br><br>

# 줄바꿈(Line Breaks)

동해물과 백두산이 마르고 닳도록(space 두번)  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산<br/>
대한 사람 대한으로 길이 보전하세

<br><br>

# 강조(Emphasis)

_이탤릭_  
**두껍게**  
**_이탤릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>

<br><br>

# 목록(List)

1. 순서가 필요한 목록
2. 순서가 필요한 목록
   1. 순서가 필요한 목록 - 1 (Tab 두번 후 입력)
   2. 순서가 필요한 목록 - 2

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록 sub
  - 순서가 필요하지 않은 목록 sub

* 순서가 필요하지 않은 목록
* 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록 sub
  - 순서가 필요하지 않은 목록 sub
* 순서가 필요하지 않은 목록

<br><br>

# 링크(Link)

[]()

<a href="http://google.com" >GOOGLE</a>

[GOOGLE](http://google.com)

<a href="http://naver.com" title="NAVER로 이동!">NAVER</a>

[NAVER](http://naver.com 'NAVER로 이동!')

<br><br>

# 이미지(Image)

![]()

![HEROPY](https://heropy.blog/css/images/logo.png)

[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/ 'HEROPY BLOG')

<br><br>

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장  
> (네이버 국어 사전)

> 인용문을 작성 하세요!
>
> > 중첩된 인용문
> >
> > > 중중첩된 인용문 1
> > > 중중첩된 인용문 2
> > > 중중첩된 인용문 3

<br><br>

# 인라인(inline) 코드 강조

CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

<br><br>

# 블럭(block) 코드 강조

```html
<a href="http://www.google.co.kr/" target="_blank">GOOGLE</a>
```

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

```javascript
function func() {
  const a = 'AAA';
  return a;
}
```

```powershell
$ git commit -m 'Study Markdown'
```

```plaintext
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
```

<br><br>

# 표

position 속성

| 값       |       의미        | 기본값 |
| :------- | :---------------: | -----: |
| static   |     기준 없음     |      O |
| relative |     자기 자신     |      X |
| absolute | 위치 상 부모 요소 |      X |
| fixed    |      뷰포트       |      X |

<br><br>

# 원시 HTML(Raw HTML)

동해물과 <u>백두산</u>이 마르고 닳도록<br>
하느님이 보우하사 우리나라 만세

동해물과 <span style = 'text-decoration: underline'>백두산</span>이 마르고 닳도록<br>
하느님이 보우하사 우리나라 만세

<a href = "http://naver.com" title ="NAVER로 이동!" target = "_blank">NAVER</a>

<img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEROPY" />

<br><br>

# 수평선

---

---

---
