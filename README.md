# 3-1 HTML과 첫 만남
#### - 태그 : 어느 부분이 제목, 텍스트 또는 표인지 구별할 수 있게 하는 꼬리표
#### - html, head, body
```
<html>~</html> : 웹 문서의 시작과 끝을 나타내는 태그
<head>~</head> : 웹 브라우저가 웹 문서를 해석하는 데 필요한 정보를 입력하는 부분
<body>~</body> : 실제로 웹 브라우저가 웹 문서를 해석하는 데 필요한 정보를 입력하는 부분
```
# 3-4 웹 문서 구조를 만드는 시맨틱 태그
#### - 시맨틱 태그 : 이름만 봐도 의미를 알 수 있는 태그
```
<header> : 헤더영역, 주로 맨 위쪽이나 왼쪽, 검색 창이나 사이트 메뉴
<nav> : 같은 웹 문서 안에서 다른 위치로 연결하거나 다른 웹 문서로 연결하는 링크
<main> : 웹 문서에서 핵심이 되는 내용
<section> : 웹 문서에서 콘텐츠 영역
<footer> : 웹 문서에서 맨 아래쪽, 사이트제작정보 및 저작권 정보와 연락처 등
<div> : 영역을 구별하거나 스타일로 문서를 꾸밈
```
# 4-1 텍스트 입력하기
#### - br, strong, b, u
```
<br> : 줄바꿈, 단독으로 사용하므로 닫는 태그가 필요없다.
<strong> : 굵게 강조할 텍스트
<b> : 굵게 표시할 텍스트
<u> : 텍스트에 단순히 밑줄 긋기
```
# 4-2 목록만들기
#### - ol and li : 순서 있는 목록 
```
<ol>
    <li>항목1</li>
    <li>항목2</li>
</ol>
```

<ol>
    <li>항목1</li>
    <li>항목2</li>
</ol>

#### - ul and li : 순서 없는 목록 
```
<ul>
    <li>항목1</li>
    <li>항목2</li>
</ul>
```

<ul>
    <li>항목1</li>
    <li>항목2</li>
</ul>

# 4-3 표 만들기
#### - table, caption

```
<table>~</table> : 표
<caption>~</caption> : 표 제목
```

#### - tr, td, th
<table>
    <tr>
      <td>1행 1열</td>
      <td>1행 2열</td>
    </tr>
    <tr>
      <td>2행 1열</td>
      <td>2행 2열</td>
    </tr>
</table>
  
```
<tr> : 행
<td> : 셀
<th> : 요소별 제목
```
