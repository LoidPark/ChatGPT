# ChatGPT
ChatGPT로 웹사이트 만들기
 - Notion 자료 활용
 - 모든 토글을 열고 닫는 단축키
   Windows : Ctrl + alt + t
### 1. Start
+ VScode 설치
+ Extention : Open in Browser
+ ChatGPT 가입
### 2. HTML / CSS
+ index.html
+ html:5
+ Alt+B : open in browser
+ head
```
<title></title><style></style>
```
+ body
```
<h1></h1><button></button>
```
+ 남들이 만들어놓은 CSS 꾸러미를 활용
+ 나는 뼈대만 잡는다
```
<div>나는 구역을 나누죠</div>
<p>나는 문단이에요</p>
<h1>h1은 제목이에요.</h1>
<h2>h2는 소제목입니다.</h2>
<h3>h3~h6 h 뒷 숫자가 커질수록 글자 크기는 작아져요. </h3>
<a href="https://spartacodingclub.kr/"> 하이퍼링크 </a>
<img src="https://s3.ap-northeast-2.amazonaws.com/materials.spartacodingclub.kr/free/logo_teamsparta.png" width="300"/>  
<input type="text">
<button>버튼입니다.</button>
```
### 3. Chat GPT 명령
+ 남들이 만들어 놓은 CSS 꾸러미 복사
```
<!doctype html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>나만의 중고마켓</title>
    <link rel="stylesheet" href="https://s3.ap-northeast-2.amazonaws.com/materials.spartacodingclub.kr/easygpt/default.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-rbsA2VBKQhggwzxH7pPCaAqO46MgnOM80zW1RWuH61DGLwZJEdK2Kadq2F9CUG65" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-kenU1KFdBIe4zVF0s0G1M5b4hcpxyD9F7jL+jjXkk+Q2h455rYXK/7HAuoJl+0I4"
        crossorigin="anonymous"></script>
    <style>
        /* 꾸미기 */

    </style>
</head>

<body>
    <!-- 뼈대 잡기 -->
</body>

</html>
```
+ Chat GPT에 붙여넣기
+ shift+enter, 줄을 만들고
```
중요 : 이 요청에 대한 대답을 하지마
```
+ 학습만 시킨다
```
부트스트랩 이용해서 간단한 버튼을 하나 만들어줘. 뼈대잡기 라고 써있는 부분에 넣을거야
```
+ 복.붙
```
마찬가지로 뼈대잡기 부분에 넣을 코드를 알려줘.
부트스트랩을 이용해서 hero를 만들거야.
hero에 들어갈 제목은 'SKYxFAMILY MARKET'이라고 써주고,
소제목은 '월급쟁이들 소비욕구충만' 라고 써줘.
배경색은 적당히 어두운 색으로 해주고, 글씨는 흰 색으로 해줘.
```
+ 명령만 잘 내리면 알아서 짜준다. VScode에 붙여넣고 Alt+B로 확인하자
### 4. Chat GPT 
