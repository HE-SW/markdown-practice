# 제목(Header)

# 제목 1 
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6
```
# 제목 1 
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6
```


# 문장(paragragh)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈(Line Breaks)
띄어쓰기 2번  
동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려강산<br/>
대한 사람 대한으로 길이 보전하세
```
띄어쓰기 2번  
동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려강산<br/>
대한 사람 대한으로 길이 보전하세
```

# 강조(Emphasis)

_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
```
_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
```
<u>밑줄</u>


# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록(서브)
    1. 순서가 필요한 목록(서브)
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
        - 순서가 필요하지 않은 목록
        - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
```
1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록(서브)
    1. 순서가 필요한 목록(서브)
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
        - 순서가 필요하지 않은 목록
        - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
```

# 링크(Links)

<a href = "https://www.google.com/webhp?hl=ko&sa=X&ved=0ahUKEwi5zqiH09H2AhWLDt4KHRrYD5cQPAgI">Google</a>

[Google](https://www.google.com/webhp?hl=ko&sa=X&ved=0ahUKEwi5zqiH09H2AhWLDt4KHRrYD5cQPAgI)

<a href ="http://naver.com" title="Naver로 이동!">NAVER</a>

[NAVER](http://naver.com "네이버로 이동!")

<a href ="http://naver.com" title="Naver로 이동!" targer="_blank">NAVER</a> 이 기능은 없음

# 이미지(Images)

![HEROPY](https://heropy.blog/css/images/logo.png)

```
![HEROPY](https://heropy.blog/css/images/logo.png)
```

[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/)
```
[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/)
```
# 인용문(BlockQuote)

> 남의 말이나 글에서 간접으로 따온 문장.  
>(네이버 국어사전)

>중첩기능
>> 중첩된인용
>>> 중첩된 인용문  
>>> 중첩된 인용문
>>> 중첩된 인용문 
```
>중첩기능
>> 중첩된인용
>>> 중첩된 인용문  
>>> 중첩된 인용문
>>> 중첩된 인용문 
```

# 인라인(inLine) 코드 강조

CSS에서 `background` 혹은 `background-image` 속성으로 이미지 배경 삽입 할수있습니다.
```
CSS에서 `background` 혹은 `background-image` 속성으로 이미지 배경 삽입 할수있습니다.
```

# 블록(block)코드 강조

```html
<a href ="http://naver.com" title="Naver로 이동!" targer="_blank">NAVER</a>
```
```
```html
<a href ="http://naver.com" title="Naver로 이동!" targer="_blank">NAVER</a>
```
```css
.container{
  color : #222;
}
```
```javascript
let arr = [1, 2]
arr.reduce((a,b)=>a+b)
```

```plaintext
동해물과 백두산이 마르고 닳도록
```

# 표 (Table)

position 속성

값 | 의미 | 기본값
--|:--:|--:
static | 기준없음 | O
relative | 요소 자신 | X
absolute | 위시 상 부무 요소 | X
fixed| 뷰포트 |X
```
값 | 의미 | 기본값
--|:--:|--
static | 기준없음 | O
relative | 요소 자신 | X
absolute | 위시 상 부무 요소 | X
fixed| 뷰포트 |X
```

# 원시 HTML(Raw Html)

동해물과 <span style="text-decoration: underline">백두산</span>이 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세

<a href ="http://naver.com" 
title="Naver로 이동!" 
targer="_blank">NAVER</a>
```
<a href ="http://naver.com" 
title="Naver로 이동!" 
targer="_blank">NAVER</a>
```

---

<img width="70" src="https://heropy.blog/css/images/logo.png"
alt="HEROPY">
```
<img width="70" src="https://heropy.blog/css/images/logo.png"
alt="HEROPY">
```
# 수평선(Horizontal Rule)

---

***

___
```
---
***
___
```