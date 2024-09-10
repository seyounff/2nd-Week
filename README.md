<h1>2주차 수업 정리</h1>

<h2>1. HTML 기본 구조</h2>

VS Code에서 !를 입력하고 Tab을 누르면 기본 HTML 문서 구조가 자동으로 생성됩니다.

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>    
</body>
</html>
```

<em>코드 자동 정렬: Shift + Alt + F를 사용하여 가능합니다.</em>

<h2>2. 텍스트 관련 태그</h2>
   
`<h1>` ~ `<h6>`: 글자의 크기를 조절하는 태그입니다. `<h1>`이 가장 크고, `<h6>`이 가장 작습니다.

`<br>`: 줄바꿈을 위한 태그.               

`<hr>`: 가로선을 표시하는 태그.            

`<p>`: 단락을 나누는 태그.                

<h3>텍스트 꾸미기</h3>

`<b>`: 텍스트를 진하게 표시.                

`<i>`: 텍스트를 이탤릭체로 표시.              

`<strong>`: 중요한 텍스트를 진하게 표시.       

`<em>`: 텍스트를 강조하여 이탤릭체로 표시.   

`<small>`: 한 단계 작은 문자로 표시.            

`<del>`: 삭제된 텍스트를 표시.

`<ins>`: 추가된 텍스트를 표시.

`<sup>`: 윗첨자 표시.

`<sub>`: 아래첨자 표시.

`<mark>`: 텍스트를 하이라이팅.

<h2>3. 블록 및 인라인 태그</h2>

`<div>`: 블록 요소로, 항상 새 라인에서 시작하여 출력됩니다.

`<span>`: 인라인 요소로, 블록 속에 삽입되어 블록의 일부로 출력됩니다.

<h2>4. 메타 데이터 관련 태그</h2>

`<meta>`: 웹 페이지의 저작자, 내용, 키워드 등을 표현하여 검색 엔진이 페이지를 더 잘 이해할 수 있게 합니다.

`<link>`: 외부 자원을 연결할 때 사용됩니다.

<h2>5. 하이퍼링크</h2>
   
하이퍼링크를 생성하여 다른 페이지로 이동할 수 있습니다:

`<a href="http://www.naver.com">네이버</a>`

<em>링크의 색상은 기본적으로 처음 클릭 시 파란색, 방문 후 보라색, 누르고 있는 동안 빨간색으로 나타납니다. CSS를 사용하여 링크 색상을 변경할 수 있습니다. (보통 검정을 채택합니다)</em>

```
<head>
    <base href="http://www.mysite.com/">
</head>
<body>
    <a href="score/math.html">수학</a>
    <a href="score/science.html">과학</a>
</body>
```

<h2>6. 표 만들기</h2>
   
HTML 표는 데이터를 구조적으로 표시할 때 사용됩니다:

```
<table border="1">
    <caption>1학기 성적</caption>
    <thead>
        <tr><th>이름</th><th>HTML</th><th>CSS</th></tr>
    </thead>
    <tfoot>
        <tr><th>합계</th><th>225</th><th>230</th></tr>
    </tfoot>
    <tbody>
        <tr><td>황기태</td><td>80</td><td>70</td></tr>
        <tr><td>이재문</td><td>95</td><td>99</td></tr>
        <tr><td>이병은</td><td>40</td><td>61</td></tr>
    </tbody>
</table>
```


<h3>주요 태그 설명</h3>

`<table>`: 표 전체를 감싸는 컨테이너.

`<caption>`: 표의 제목을 지정.

`<thead>`: 표의 헤더 셀 그룹.

`<tfoot>`: 표의 바닥 셀 그룹.

`<tbody>`: 표의 데이터 셀 그룹.

`<tr>`: 행(row)을 정의.

`<th>`: 열 제목 셀.

`<td>`: 데이터 셀.
    
<h2>7. 인라인 프레임</h2>

인라인 프레임은 HTML 페이지 내에 또 다른 HTML 페이지를 삽입할 때 사용됩니다:

`<iframe src="iframe1.html"></iframe>`

    
<h2>8. target 속성</h2>

링크를 클릭했을 때 링크가 열리는 위치를 지정할 수 있습니다.

`_blank`: 새로운 브라우저 창이나 탭에서 열림.

`_self`: 현재 창에서 열림 (기본값).

`_parent`: 부모 프레임에서 열림.

`_top`: 최상위 프레임에서 열림.

`윈도우 이름`: 지정된 이름의 윈도우에서 열림.







