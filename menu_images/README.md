# 급식 메뉴 사진 미리보기

<style>
  /* README.md 내에서 사용할 인라인 스타일 */
  .image-grid {
    display: flex; /* flexbox를 사용하여 유연한 레이아웃 */
    flex-wrap: wrap; /* 내용이 넘칠 경우 다음 줄로 넘어감 */
    gap: 10px; /* 이미지 사이의 간격 */
    justify-content: flex-start; /* 이미지를 왼쪽부터 정렬 */
    align-items: flex-start; /* 이미지를 상단부터 정렬 */
  }
  .image-grid-item {
    flex: 1 1 calc(33.333% - 10px); /* 3개 열, gap 포함 계산 */
    box-sizing: border-box; /* padding, border가 width에 포함되도록 */
    text-align: center; /* 이미지와 캡션 중앙 정렬 */
    max-width: calc(33.333% - 10px); /* 최대 너비를 3분의 1로 제한 */
    min-width: 150px; /* 너무 작아지지 않도록 최소 너비 설정 */
    margin-bottom: 10px; /* 아이템 하단 간격 */
  }
  .image-grid-item img {
    max-width: 100%; /* 부모 요소 너비에 맞춤 */
    height: auto; /* 비율 유지 */
    display: block; /* 이미지 아래 공백 제거 */
    margin: 0 auto; /* 이미지 중앙 정렬 */
    border: 1px solid #eee; /* 이미지 테두리 추가 */
    border-radius: 4px; /* 테두리 둥글게 */
  }
  .image-grid-item p {
    margin-top: 5px;
    font-size: 0.9em;
    color: #555;
  }
</style>


## 1. 밥

<div class="image-grid">
  <div class="image-grid-item">
    <img src="밥/곤드레밥.webp" alt="곤드레밥">
    <p>곤드레밥</p>
  </div>
  <div class="image-grid-item">
    <img src="밥/기장밥.webp" alt="기장밥">
    <p>기장밥</p>
  </div>
  <div class="image-grid-item">
    <img src="밥/김치볶음밥.webp" alt="김치볶음밥">
    <p>김치볶음밥</p>
  </div>
  <div class="image-grid-item">
    <img src="밥/날치알밥.webp" alt="날치알밥">
    <p>날치알밥</p>
  </div>
  </div>

## 2. 국

<div class="image-grid">
  <div class="image-grid-item">
    <img src="국/미역국.webp" alt="미역국">
    <p>미역국</p>
  </div>
  <div class="image-grid-item">
    <img src="국/북엇국.webp" alt="북엇국">
    <p>북엇국</p>
  </div>
  <div class="image-grid-item">
    <img src="국/닭개장.webp" alt="닭개장">
    <p>닭개장</p>
  </div>
  <div class="image-grid-item">
    <img src="국/콩나물국.webp" alt="콩나물국">
    <p>콩나물국</p>
  </div>
  </div>
