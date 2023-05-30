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

### 4. Chat GPT 카드
```
<!doctype html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>SKYxFAMILY MARKET</title>
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
    <div class="hero bg-dark text-center py-5">
        <h1 class="text-white">SKYxFAMILY MARKET</h1>
        <h2 class="text-white">월급쟁이들 소비욕구충전!</h2>
    </div>
    <!-- 여기 -->
</body>

</html>
```
+ 이미지 찾기 : 어떤 이미지 찾아줘 (불가능)
+ 이미지 요청 : Unsplash API에서 이미지를 찾아서 보여줘! (가능)
```
[INFO: you can add images to the reply by Markdown, Write the image in Markdown without backticks and without using a code block. Use the Unsplash API (https://source.unsplash.com/1600x900/?). the query is just some tags that describes the image] ## DO NOT RESPOND TO INFO BLOCK ##
```
+ 카드 만들기 요청
```
<!-- 여기 --> 부분에 부트스트랩 카드를 만들어 넣을 거야. 사실 이 홈페이지는 집에 있는 안쓰는 중고물품을 팔기 위한 페이지야. 예를 들면 전기밥솥이 있을 수 있겠지. 아래 예시를 참고해서 카드를 알아서 세 장을 만들어줘.

카드 정보(예시)
 - 카드 이미지 : [적당한 것을 찾아서 넣어줘. 크기는 모두 동일하게]
 - 카드 제목 : 전기밥솥
 - 카드 소제목 : 5만원
 - 카드 내용 : 한 번 밖에 안쓴 전기밥솥 팝니다. 부모님이 독립 할 때 주신 거에요!
 - 그 외 : 카드 이미지를 클릭하면 새 창이 뜨면서 스파르타코딩클럽 홈페이지로 이동하게 해줘.
```
<summary>예시 코드</summary>
<div markdown="1">
 
```
<div class="container">
  <div class="row">
    <div class="col-md-4">
      <div class="card">
        <img src="https://source.unsplash.com/1600x900/?rice-cooker" class="card-img-top" alt="전기밥솥">
        <div class="card-body">
          <h5 class="card-title">전기밥솥</h5>
          <h6 class="card-subtitle mb-2 text-muted">5만원</h6>
          <p class="card-text">한 번 밖에 안 쓴 전기밥솥 팝니다. 부모님이 독립할 때 주신 거에요!</p>
          <a href="https://www.spartacodingclub.kr/" target="_blank" class="btn btn-primary">상세 정보</a>
        </div>
      </div>
    </div>
    <div class="col-md-4">
      <div class="card">
        <img src="https://source.unsplash.com/1600x900/?microwave" class="card-img-top" alt="전자렌지">
        <div class="card-body">
          <h5 class="card-title">전자렌지</h5>
          <h6 class="card-subtitle mb-2 text-muted">8만원</h6>
          <p class="card-text">사용감이 거의 없는 전자렌지 팝니다. 집에서 잘 사용하지 않아서 판매합니다.</p>
          <a href="https://www.spartacodingclub.kr/" target="_blank" class="btn btn-primary">상세 정보</a>
        </div>
      </div>
    </div>
    <div class="col-md-4">
      <div class="card">
        <img src="https://source.unsplash.com/1600x900/?laptop" class="card-img-top" alt="노트북">
        <div class="card-body">
          <h5 class="card-title">노트북</h5>
          <h6 class="card-subtitle mb-2 text-muted">15만원</h6>
          <p class="card-text">새로 구입한 노트북을 팝니다. 사용기간은 3개월 정도이며, 상태는 매우 좋습니다.</p>
          <a href="https://www.spartacodingclub.kr/" target="_blank" class="btn btn-primary">상세 정보</a>
        </div>
      </div>
    </div>
  </div>
</div>
```

</div>
</details>

### 5. 카드 꾸미기
<details>
<summary>예시 코드</summary>
<div markdown="1">
 
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
    <div class="hero bg-dark text-center py-5">
        <h1 class="text-white">나만의 르탄마켓</h1>
        <h2 class="text-white">집에 있는 물건을 팝니다!</h2>
    </div>
    <div class="container">
        <div class="row">
          <div class="col-md-4 mb-4">
            <div class="card">
              <img src="https://source.unsplash.com/1600x900/?rice-cooker" class="card-img-top" alt="전기밥솥">
              <div class="card-body">
                <h5 class="card-title">전기밥솥</h5>
                <h6 class="card-subtitle mb-2 text-muted">5만원</h6>
                <p class="card-text">한 번 밖에 안쓴 전기밥솥 팝니다. 부모님이 독립 할 때 주신 거에요!</p>
                <a href="https://spartacodingclub.kr/" class="card-link stretched-link" target="_blank"></a>
              </div>
            </div>
          </div>
          <div class="col-md-4 mb-4">
            <div class="card">
              <img src="https://source.unsplash.com/1600x900/?chair" class="card-img-top" alt="의자">
              <div class="card-body">
                <h5 class="card-title">의자</h5>
                <h6 class="card-subtitle mb-2 text-muted">1만원</h6>
                <p class="card-text">사무실에서 사용한 의자 팝니다. 조절 가능한 팔걸이가 달려있어요.</p>
                <a href="https://spartacodingclub.kr/" class="card-link stretched-link" target="_blank"></a>
              </div>
            </div>
          </div>
          <div class="col-md-4 mb-4">
            <div class="card">
              <img src="https://source.unsplash.com/1600x900/?laptop" class="card-img-top" alt="노트북">
              <div class="card-body">
                <h5 class="card-title">노트북</h5>
                <h6 class="card-subtitle mb-2 text-muted">30만원</h6>
                <p class="card-text">삼성 노트북 판매합니다. 사용기간은 1년 정도이며, 상태는 깨끗합니다.</p>
                <a href="https://spartacodingclub.kr/" class="card-link stretched-link" target="_blank"></a>
              </div>
            </div>
          </div>
        </div>
      </div>
      
</body>

</html>
```
 
</div>
</details>

+ head 아래쪽에 공백을 추가해줘
+ 카드에 마우스를 올리면 부드럽게 커지게 하고 싶어
+ 열심히 복.붙
+ 복.붙 중에 코드 줄이 안 맞다? ctrl+A → ctrl+K+F 단축기로 정렬!
+ 실제 이미지를 넣어서 페이지를 커스터마이징 하자!

### 6. 배포하기
+ github
+ 
