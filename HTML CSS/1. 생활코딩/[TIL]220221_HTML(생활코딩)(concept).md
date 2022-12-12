# HTML

* '웹 페이지'가 모여 있으면 '웹 사이트'라고 합니다.
  * 웹 페이지 ( 웹 문서 ) => 웹 사이트 - 출판 (publish)

* WEB : PUBLIC DOMAIN
* https://advancedwebranking.com/html/
  * 전 세계에 있는 웹페이지들이 몇 종류의 태그로 이루어져 있는지를 보여주고 있습니다.
    이에 따르면 26개 정도의 태그를 사용하는 사이트가 제일 많다.

```html
<!DOCTYPE html>
<html>
<head>
	<title></title>    
    <meat charset="utf-8"></meat>
</head>
<body>
	<h1> ~ <h6>
	<strong></strong>    
	<u></u>
	<p></p>  vs  <br>
	<img>
	<ol><ul>    
		<li></li>
		<li></li>    
	</ol></ul>
    <a href="https://www.w3.org/TR/html5/" target="_blank" title="html5 specification">
</body>
</html>
```

> 검색 엔진은 tag를 근거를 해서 정리한다.
>
> 즉, <h1> ~ <h6> tag를 사용한 제목이 있어야 검색엔진이 제목을 빠르게 인지하고, 상위노출을 시키려고 한다.

> parent, child tag : <ol><ul><li>

* <a> : HTML의 시작이자 정체성으로 메인 tag이다.





---



인터넷 > 웹

* 1960 : 인터넷 등장 - 미국 핵 공포

* 1990 : 웹 등장 - 유럽 입자 연구소 CERN
  * 팀 버너스리 : 문서 관리
  * 웹의 메소포타미아 : http://info.cern.ch
  
  
  
  
  
  **웹**
  
  * Web Browser ( client ) / Web Server ( server ) 
    * 2개의 컴퓨터는 인터넷으로 연결되어 있다.
    * Web Server : 하드디스크에는 index.html 이 있다.
  * clint pc가 server pc에 정보를 요청(request)하면
    server pc는 응답(response)하여 clint pc에 index.html 파일을 넘기게 된다.



* 호스트 : 인터넷에 연결된 컴퓨터 하나 하나를 말한다.
* 호스팅 : 이런 컴퓨터를 빌려주는 사업
  * 웹서버를 전문적으로 빌려주는 비즈니스를 **웹호스팅 업체**라고 부릅니다.
* 





* [웹호스팅 github pages (2022년 수정판)](https://opentutorials.org/course/3084/18891)
* [웹서버 운영하기 (2022년 수정판)](https://opentutorials.org/course/3084/31144)

* 무한 실습 - 한계 봉착 - 다음 것 공부하기
* [부록 : 코드의 힘 - 동영상 삽입](https://opentutorials.org/course/3084/18453)
* [부록 : 코드의 힘 - 댓글 기능 추가](https://opentutorials.org/course/3084/18594)
* [부록 : 코드의 힘 - 채팅 기능 추가](https://opentutorials.org/course/3084/18597)
* [부록 : 코드의 힘 - 방문자 분석기](https://opentutorials.org/course/3084/18899)



### head 태그

```html
<!DOCTYPE html>
<meta charset = "UTF-8">
<a href = "naver.com/html" target="_blank" title="무슨 링크인지 알려줌"></a>
```

1. DOCTYPE
   - DOCTYPE은 문서의 유형을 정의하기 위해 사용하는 선언문(DTD / Document Type Definition)이다. 웹 문서의 시작을 알려주며 `<html>` 태그보다 먼저 선언한다. DOCTYPE은 웹 브라우저에서 처리할 문서가 HTML이며 어떠한 버전으로 사용하였으니 해당 방식대로 해석하라는 의미를 갖는다.
2. meta charset = "UTF-8"
   * 인코딩 방식을 알려주는 태그이다. 
     웹 브라우저나 컴퓨터가 HTML파일을 웹브라우저에서 표시될 수 있도록 변환하는 인코딩 작업을 해야한다. 
   
3. target = "_blank"
   * 새 창 띄우기

<br>

### 기타

HTML => 4년후 => CSS
                5년 후 => JavaScript

<br>

<br>

## (실습) 개인 웹사이트 완성하기

1. index.html **(필수)**
2. html.html
3. css.html
4. javascript.html

* 지금까지 배운 내용을 활용하여 개인 컴퓨터에서 작동하는 웹사이트를 만든다.

<br>

<br>

### 인터넷 연결하기

1. 실제 사이트 ( index.html )
2. 웹 브라우저 ( 클라이언트 )
   - request - 요청
3. 웹 서버 ( 서버 ) or 웹 호스팅
   * response - 응답







