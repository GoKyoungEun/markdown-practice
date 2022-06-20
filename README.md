# 제목(Header)

# 제목 1

## 제목 2

### 제목 3

#### 제목 4

##### 제목 5

###### 제목 6

<br/>

# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

<br/>

# 줄바꿈(Line Breaks)

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산<br/>
대한 사람 대한으로 길이 보전하세

<br/>

# 강조(Emphasis)

_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>

<br/>

# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
   1. 순서가 필요한 목록
   1. 순서가 필요한 목록
   1. 순서가 필요한 목록
   1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

<br/>

# 링크(Links)

<a href="http://google.com">GOOGLE</a>

[GOOGLE](http://google.com)

<a href="http://naver.com" title="NAVER로 이동">NAVER</a>

[NAVER](http://naver.com "NAVER로 이동")

<a href="http://naver.com" title="NAVER로 이동" target="_blank">NAVER 새창열기</a>

<br/>

# 이미지(Images)

![GitHub](https://velog.velcdn.com/images/seven2649/post/8417a1d3-11aa-4e9f-9fe7-8fab5586cad7/image.png)

### 이미지에 링크넣기

[![GitHub](https://velog.velcdn.com/images/seven2649/post/8417a1d3-11aa-4e9f-9fe7-8fab5586cad7/image.png)
](https://velog.io/@seven2649)

<br/>

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장  
> (네이버 국어 사전)

> 인용문을 작성하세요!
>
> > 중첩된 인용문
> >
> > > 중중첩된 인용문
> > > 중중첩된 인용문
> > > 중중첩된 인용문

<br/>

# 인라인(inline) 코드 강조

CSS에서 `background` 혹은
`background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

<br/>

# 블록(block) 코드 강조

```html
<a href="http://naver.com" title="NAVER로 이동" target="_blank"
  >NAVER 새창열기</a
>
```

```css
#to-top {
  width: 42px;
  height: 42px;
  background-color: #333;
  color: #fff;
  border: 2px solid #fff;
  border-radius: 10px;
  cursor: pointer;
  display: flex;
  justify-content: center;
  align-items: center;
  position: fixed;
  bottom: 30px;
  right: 30px;
  z-index: 9;
}
```

```js
// 클릭하면 최상단으로 자연스럽게 올라가는 기능 구현
toTopEl.addEventListener("click", function () {
  gsap.to(window, 0.7, {
    scrollTo: 0,
  });
});
```

```bash
$ git commit -m 'Study Markdown'
```

```plaintext
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
무궁화 삼천리 화려 강산
대한 사람 대한으로 길이 보전하세
```

<br/>

# 표(Table)

position 속성
값 | 의미 | 기본값
:--|:--:|--:|
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
flxed | 뷰포트 | X

<br/>

# 원시 HTML (Raw HTML)

동해물과 <span style="text-decoration: underline">백두산이</span> 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세

---

<a href="http://naver.com" title="NAVER로 이동" target="_blank">NAVER 새창열기</a>

---

<img width="70" src="https://velog.velcdn.com/images/seven2649/post/8417a1d3-11aa-4e9f-9fe7-8fab5586cad7/image.png" alt="GitHub">

<br/>

# 수평선(Horizontal Rule)

---

---

---
