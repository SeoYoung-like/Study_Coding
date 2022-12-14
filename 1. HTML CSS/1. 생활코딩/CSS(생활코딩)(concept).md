# CSS

### CSS 이전

* 과거 html은 디자인을 대신 할 언어를 만드는 대신 <font> 태그를 사용했지만 그 의미와 효율성에 한계를 느끼고 css라는 언어를 만들게 된다. ( css 이전까지는 한번에 처리가 불가능한 구조로 비효율적인 작업을 했다. )

<br>

<br>

### CSS 탄생 이유

HTML에 정보에 집중하기 위해서 HTML에 있던 디자인 기능을 CSS라는 개념으로 분리시켜 디자인 기능을 더욱 강화시키고, 유지보수를 편리하게 만들었다.

1. 유지 보수
2. 디자인 집중
3. 자원 효율 ( 트래픽 절약 )

<br>

<br>

### CSS 배워야 하는 이유
* 디자인을 위한 도구와 기술을 통한 확장성
  * 논리적인 과정을 거쳐 만들어지는 것을 배워야 더 확장된 디자인을 만들 수 있다. 


* 협업 능력 향상
       - 디자이너, 프런트엔드 등

<br>

<br>

## 사용법

### CSS 사용하는 방법

* **[핵심] 선택자와 속성**

<br>

1. style tag ( 선택자 사용 ) - **html안의 사용 방식**

```css
<style>
	a {
		color:red;
		text-decoration:none;     <!--장식을 없앤다.(밑줄이 없어진다.)-->
	}
	h1{
            font-size:45px;
            text-align:center;
        }
</style>
```

| Selector        | 선택자 ( a{} )                |
| --------------- | ----------------------------- |
| **Declaration** | **선언, 효과 ( color:red; )** |
| **Property**    | **속성 ( color )**            |
| **Value**       | **값 ( red )**                |

<br>

2. style property - **html안의 사용 방식 : style 속성**

```html
<a href="a.html" style="color:red; text-decoration:underline">CSS</a>
```

* 세미콜론(;) 으로 구분해서 사용한다.

<br>

3. 검색 키워드
ex) css text size property

<br>

<br>

### 클래스 및 아이디

* 우선순위 : id > class > tag
  * 포괄적인 것보다 구체적인 것을 우선순위로 가진다. ( 제외를 위해 )
  * 클래스는 2개 까지도 지정할 수 있지만 사용을 권장하지 않는다.
  * 그 외에 위치 상 body 코드와 가장 가까이에 있는 코드가 우선순위를 가진다.
* 검색 키워드
  ex) css selector

```html
<style>
            #active {
                color:red;
            }
            .saw {
                color:gray;
            }
            a {
                color:black;
                text-decoration: none;
            }
            h1 {
                font-size:45px;
                text-align:center;
            }
</style>
```

```html
<a href="SquidGame.html" class="saw"><li>오징어게임</li></a>
<a href="HELLBOUND.html" class="saw" id="active"><li>지옥</li></a>
```

* '.saw'가 아닌 'saw'를 지정할 경우 클래스 saw가 아닌 태그 saw를 지정하게 되니 주의하자. 





### 블록 모델

* block element : <h1>
  * 화면 전체

* inline element : <a>
  * 자기 크기만큼 가짐

* margin, border, padding
* width, height

* display : flex 





### 그리드 Grid

```css
#grid{
	...
	display:grid;
	grid-template-columns: 150px 1fr;
	...
}
```



* [참고]
  caniuse 홈페이지 - https://caniuse.com/
  - 얼마나 많은 컴퓨터에 호환이 되고 있는지 숫자 퍼센트로 확인할 수 있는 사이트이다.







### 미디어 쿼리

* 반응형 웹 디자인의 핵심 부분으로 뷰포트의 크기에 따라 서로 다른 레이아웃을 생성할 수 있다.

**(예시) width 값이 800px 아래로 내려가면 작동된다.**

```css
@media(max-width:800px){
	div{
		display:none;
	}
}
```




