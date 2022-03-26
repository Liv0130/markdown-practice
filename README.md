# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4

# 문장(Paragraph)
동해물과 백두산이 마르고 닳도록 하느님이 보우하사 우리나라 만세

# 줄바꿈(Line Breaks)
동해물과 백두산이 마르고 닳도록  하느님이 보우하사 우리나라 만세  무궁화 삼천리 화려 강산<br> 대한사람 대한으로 길이 보전하세

<!-- 뛰어쓰기를 두 번 해서 줄바꿈을 만들거나 <br>을 사용해서 가능 -->

# 강조(Emphasis)

_Italic_  
**Bold**  
**_Italic + Bold_**  
~~tilde~~  
<u>Underline</u>

# 목록(List)

1. 순서가 필요한 목록  
1. 순서가 필요한 목록  
1. 순서가 필요한 목록  
    1. 순서가 필요한 목록  
1. 순서가 필요한 목록

<!-- 자동으로 순서를 계산함, 들여쓰기를 두 번 해야 소목록을 만들 수 있음 -->
- 순서가 필요하지 않은 목록   
- 순서가 필요하지 않은 목록  
- 순서가 필요하지 않은 목록  
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
        - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크(Links)

<a href="https://google.com">GOOGLE</a>

[GOOGLE](https://google.com)

<a href="https://naver.com" title="NAVER로 이동!">NAVER</a>

[NAVER](https://naver.com "NAVER로 이동!")

<a href="https://naver.com" title="NAVER로 이동!" target="_blank">NAVER</a>

# 이미지(Images)

![HEROPY](https://heropy.blog/css/images/logo.png)

[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/)

<!-- 이렇게 하면 이미지를 클릭하면 해당하는 링크로 이동 -->

# 인용문 (BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)
>> 중첩된 인용문
>>> 중중첩된 인용문 1
>>> 중중첩된 인용문 2
>>> 중중첩된 인용문 3

# 인라인(inline) 코드 강조

CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

<!-- back tick 사용 -->

# 블록(block) 코드 강조

```html
<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>
```

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

# 표(Table)

position 속성

값 | 의미 | 기본값  |
--|:--:|--:  
static  |  기준없음 |  O  
relative  |  요소 자신  |  X  
absolute  |  위치 상 부모 요소  |  X
fixed  |  뷰포트  |  X  

<!-- 정렬할 때는 콜론기호 사용을 어디에 하냐에 따라 달라짐 -->

# 원시 HTML(Raw HTML)

동해물과 <span style="text-decoration: underline;">백두산</span>이 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세

<a href="https://naver.com" title="NAVER로 이동!" target="_blank">NAVER</a>

---

<img width="70" src= https://heropy.blog/css/images/logo.png alt="HEROPY" />

# 수평선(Horizontal Rule)

---

***
___
