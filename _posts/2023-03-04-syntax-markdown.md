---
layout: post
title: How to write blog post?
# subtitle: Each post also has a subtitle
subtitle: Markdown syntax & jekyll theme function
# gh-repo: daattali/beautiful-jekyll
# gh-badge: [star, fork, follow]
thumbnail-img: /assets/img/markdown-thumbnail.png
cover-img: /assets/img/markdown-cover.png
tags: [markdown]
comments: true
---

This is a demo post to show you how to write blog posts with markdown.  I strongly encourage you to [take 5 minutes to learn how to write in markdown](https://markdowntutorial.com/) - it'll teach you how to transform regular text into bold/italics/headings/tables/etc.


---
# `jekyll theme` only function

## Boxes
You can add notification, warning and error boxes like this:

### Notification

```
{: .box-note}
**Note:** This is a notification box.
```

{: .box-note}
**Note:** This is a notification box.

### Warning

```
{: .box-warning}
**Warning:** This is a warning box.
```

{: .box-warning}
**Warning:** This is a warning box.

### Error

```
{: .box-error}
**Error:** This is an error box.
```

{: .box-error}
**Error:** This is an error box.

---


# MarkDown Syntax
> 마크다운(MarkDown)에 대해서

* 마크다운의 **`장점`**
  * 문법이 쉽다.
  * 관리가 쉽다.
  * 지원 가능한 플랫폼과 프로그램이 다양하다.
  * S/W 개발자라면... (무지성 따라쟁이 ^^)
   
* 마크다운의 **`단점`**
  * 표준이 없어 사용자마다 문법이 상이할 수 있다.
  * 모든 HTML 마크업을 대신하지 못한다.
  * 웹 브라우저 마다 변환에 차이가 있어서 html tag 도 일부 필요하다.

---

## 제목 (Header)
`<h1>`부터 `<h6>` 까지 제목을 표현할 수 있습니다.
```markdown
# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6
```
> # 제목 1
> ## 제목 2
> ### 제목 3
> #### 제목 4
> ##### 제목 5
> ###### 제목 6
***

## 강조 (Emphasis)
```markdown
이텔릭체는 *별표(asterisks)* 혹은 _언더바(underscore)_를 사용하세요.
두껍게는 **별표(asterisks)** 혹은 __언더바(underscore)__를 사용하세요.
**_이텔릭체_와 두껍게**를 같이 사용할 수 있습니다.
취소선은 ~~물결표시(tilde)~~를 사용하세요.
<u>밑줄</u>은 `<u></u>`를 사용하세요.
```
> 이텔릭체는 *별표(asterisks)* 혹은 _언더바(underscore)_를 사용하세요.  
> 두껍게는 **별표(asterisks)** 혹은 __언더바(underscore)__를 사용하세요.  
**_이텔릭체_와 두껍게**를 같이 사용할 수 있습니다.  
취소선은 ~~물결표시(tilde)~~를 사용하세요.  
<u>밑줄</u>은 `<u></u>`를 사용하세요.
***

## 목록 (List)
```markdown
1. 순서가 필요한 목록
2. 순서가 필요한 목록
    - 순서가 필요하지 않은 목록(서브)
    - 순서가 필요하지 않은 목록(서브)
3. 순서가 필요한 목록
    1. 순서가 필요한 목록(서브)
    2. 순서가 필요한 목록(서브)
4. 순서가 필요한 목록
    - 순서가 필요하지 않은 목록에 사용 가능한 기호
        - 대쉬(hyphen)
        * 별표(asterisks)
        + 더하기(plus sign)
```
1. 순서가 필요한 목록
2. 순서가 필요한 목록
   - 순서가 필요하지 않은 목록(서브)
   - 순서가 필요하지 않은 목록(서브)
3. 순서가 필요한 목록
   1. 순서가 필요한 목록(서브)
   2. 순서가 필요한 목록(서브)
4. 순서가 필요한 목록
   - 순서가 필요하지 않은 목록에 사용 가능한 기호
       - 대쉬(hyphen)
       * 별표(asterisks)
       + 더하기(plus sign)

## 링크(Links)
```markdown
[GOOGLE](https://google.com)    
[NAVER](https://naver.com "링크 설명(title)을 작성하세요.")  
[상대적 참조](../users/login)  
[Dribbble][Dribbble link]  
[GitHub][1]  
문서 안에서 [참조 링크]를 그대로 사용할 수도 있습니다.  
다음과 같이 문서 내 일반 URL이나 꺾쇠 괄호(`< >`, Angle Brackets)안의 URL은 자동으로 링크를 사용합니다.  
구글 홈페이지: https://google.com    
네이버 홈페이지: <https://naver.com>    

[Dribbble link]: https://dribbble.com
[1]: https://github.com  
[참조 링크]: https://naver.com "네이버로 이동합니다!" 
```
[GOOGLE](https://google.com)    
[NAVER](https://naver.com "링크 설명(title)을 작성하세요.")  
[상대적 참조](../users/login)  
[Dribbble][Dribbble link]  
[GitHub][1]  
문서 안에서 [참조 링크]를 그대로 사용할 수도 있습니다.  
다음과 같이 문서 내 일반 URL이나 꺾쇠 괄호(`< >`, Angle Brackets)안의 URL은 자동으로 링크를 사용합니다.  
구글 홈페이지: https://google.com    
네이버 홈페이지: <https://naver.com>    

[Dribbble link]: https://dribbble.com
[1]: https://github.com  
[참조 링크]: https://naver.com "네이버로 이동합니다!"  


## 코드(Code) 강조
> 숫자 1번 키 왼쪽에 있는 `(Grave)를 입력하세요

### 인라인(inline) 코드 강조

```markdown
`background`혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.
```

`background`혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

### 블록(block) 코드 강조
> `를 3번 이상 입력하고 코드 종류도 적습니다.  
> ex. html

```html
<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>
```

> ex. css

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

> ex. javascript

```javascript
function func() {
  var a = 'AAA';
  return a;
}
```

> ex. bash

```bash
$ vim ./~zshrc
```

> ex. python

```python
s = "Python syntax highlighting"
print s
```

> ex. None

```
No language indicated, so no syntax highlighting. 
But let's throw in a tag.
```

> ex. javascript via start with ~~~ 

~~~ javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

{: .box-error}
**Error:** And here is the same code yet again but with line numbers: `jekyll theme function` can't use "{ highlight javascript linenos }"


## 표(Table)
* `<table>` 태그로 변환됩니다.        
* 헤더 셀을 구분할 때 3개 이상의 -(hyphen/dash) 기호가 필요합니다.    
* 헤더 셀을 구분하면서 :(Colons) 기호로 셀(열/칸) 안에 내용을 정렬할 수 있습니다.  
* 가장 좌측과 가장 우측에 있는 |(vertical bar) 기호는 생략 가능합니다.

***

| 값 |           의미           | 기본값 |
|---|:----------------------:|---:|
| `static` |   유형(기준) 없음 / 배치 불가능   | `static` |
| `relative` |     요소 자신을 기준으로 배치     |  |
| `absolute` | 위치 상 부모(조상)요소를 기준으로 배치 |  |
| `fixed` |  **브라우저 창**을 기준으로 배치   |  |


Here's a useless table:

| Number | Next number | Previous number |
|:------ |:--- |:--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |


## 이미지 (Images)

```markdown
<img> 로 변환됩니다.  
링크과 비슷하지만 앞에 !가 붙습니다.

![대체 텍스트(alternative text)를 입력하세요!](http://www.gstatic.com/webp/gallery/5.jpg "링크 설명(title)을 작성하세요.")
![Kayak][logo]
[logo]: http://www.gstatic.com/webp/gallery/2.jpg "To go kayaking."
```

![대체 텍스트(alternative text)를 입력하세요!](http://www.gstatic.com/webp/gallery/5.jpg "링크 설명(title)을 작성하세요.")
![Kayak][logo]

[logo]: http://www.gstatic.com/webp/gallery/2.jpg "To go kayaking."

## 이미지에 링크
> 마크다운 이미지 코드를 링크 코드로 묶어 줍니다.

```markdown
[![MARK-II](/assets/img/avatar-icon-gunpla-mark-II.png)](https://gundam.fandom.com/wiki/RX-178_Gundam_Mk-II)
``` 

[![MARK-II](/assets/img/avatar-icon-gunpla-mark-II.png)]](https://gundam.fandom.com/wiki/RX-178_Gundam_Mk-II)


### w/o jekyll syntax

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

It can also be centered!

### w/ jekyll syntax - `.mx-auto.d-block`
``` markdown
![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg){: .mx-auto.d-block :}
```

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg){: .mx-auto.d-block :}