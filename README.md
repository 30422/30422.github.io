<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <title>콘텐츠 태그 뽑기</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <h1>복수 장르 모두 포함 콘텐츠 랜덤 추천</h1>

  <!-- 소설/웹툰 선택 -->
  <div id="typeSelector">
    <label><input type="radio" name="contentType" value="novels" checked> 소설</label>
    <label><input type="radio" name="contentType" value="webtoons"> 웹툰</label>
  </div>

  <div id="genreCheckboxes">콘텐츠 목록 불러오는 중...</div>

  <button id="recommendBtn" disabled>추천하기</button>

  <div id="resultWrapper">
    <div id="result">추천 결과가 여기에 표시됩니다.</div>
    <button id="copyBtn" title="복사하기">제목 복사</button>
  </div>

  <!-- 추가 텍스트 링크 -->
  <div id="addNovelWrapper">
    <a id="addNovelLink" href="https://github.com/30422/s30422/tree/main" target="_blank" rel="noopener noreferrer">
      목록 추가하러 가기
    </a>
  </div>

  <script src="recommend.js"></script>
</body>
</html>
