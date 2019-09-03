tag | 의미 설명
----------|-----------------
`<u></u>` | underline, 밑줄
`<strong></strong>` | bold, 굵게  
`<h1></h1> ~ <h6></h6>` | heading, 제목. 자동 줄바꿈됨 
`<!-- content -->` | 주석 처리  
`<i></i> or <em></em>` | 기울림 처리  
`<p></p>` | paragraph, 문단 구분  
`<br>` | break, 줄바꿈  
`<img src="image.jpg" width="% or value">` | image, 사진 첨부 / src = source, 출처
`<li></li>` | list, 목차  
`<ul></ul>` | unordered list, \<li>를 묶는 태그  
`<ol></ol>` | ordered list, 1. 2. 3. … 식으로 순서를 매겨줌  

```HTML
<ul>    //또는 <ol> 을 사용
	<li>text1</li>  
	<li>text2</li>  
	<li>text3</li>  
</ul>  //또는 </ol> 을 사용
```

<br><br>

tag|의미 설명
-----------------|--------------------  
`<title></title?` | 브라우저에서 보이는 제목  
`<meta charset=”utf-8”>` | utf-8방식으로 저장  
`<head></head>`| 본문을 설명  
`<body></body>`| 본문  
`<html></html>`| \<head>와 \<body>를 감쌈  
`<!doctype html>` | html 파일임을 표시 

```HTML
<!DOCTYPE html>  
<html>  
<head>  
   <title>서울시</title>  
  <meta charset="utf-8">  
</head>  
<body>  
    <h1>지리 정보</h1>  
    마포도서관 <strong><u>건대입구</u>홍대입구</strong>  
    <p style="margin-top|40px;">가나다라마바사</p>  
    <img src="C|\Users\BillCollection\Desktop\111.PNG" width="30%">  
    <ol>Class  
        <li>HTML</li>  
        <li>CSS</li>  
        <li>JavaScript</li>  
    </ol>  
</body>  
</html>  
```

<br><br>

tag | 의미 설명
----------|-----------------
`<a></a>` | anchor, 닻 -> 링크를 달 때 사용  
 `href` | hypertext reference, 링크  
 `target="_blank"` | 새 탭에서 열기  
 `title` | 커서를 가져다 댔을 때 보이는 텍스트  
```HTML
<a href="https|//mpllc.sen.go.kr/" target="_blank" title="마포도서관 홈페이지">마포도서관</a>
```

<br><br>
 
추가기능 | 설명  
---------|-----------------------  
WAMP(Windows Apache MySQL PHP) | Apache 서버 구축     
댓글 기능 추가 | disqus / LiveRe  
채팅 기능 추가 | tawk  

**아래 추가기능은 \<head>에 삽입해야함**  

추가기능 |  설명  
---------|--------------  
웹 분석 | Google Analytics  
광고 추가 | Google AdSense  
