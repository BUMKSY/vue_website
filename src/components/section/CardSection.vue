<template>
     <section id="cardType" class="card__wrap section">
      <h2>웹쓰 스터디 멤버</h2>
      <p>웹디자이너, 웹 퍼블리셔, 프론트앤드 개발자 멤버를 소개합니다.</p>
      <div class="card__inner container">
        <article class="card">
          <figure class="card__header">
            <img src="assets/img/card_bg01_01.jpg" alt="얼굴사진1" />
          </figure>
          <div class="card__body box1">
            <h3 class="tit">웹쓰 24기 전현정</h3>
            <a class="btn" href="/">
              자세히 보기
            </a>
          </div>
        </article>
        <article class="card">
          <figure class="card__header">
            <img src="assets/img/card_bg01_02.jpg" alt="얼굴사진2" />
          </figure>
          <div class="card__body box2">
            <h3 class="tit">웹쓰 14기 황현정</h3>
            <a class="btn" href="/">
              자세히 보기
            </a>
          </div>
        </article>
        <article class="card">
          <figure class="card__header">
            <img src="assets/img/card_bg01_03.jpg" alt="얼굴사진3" />
          </figure>
          <div class="card__body box3">
            <h3 class="tit">웹쓰 20기 김현정</h3>
            <a class="btn" href="/">
              자세히 보기
            </a>
          </div>
        </article>
      </div>
    </section>
</template>

<style>
/* cartType */
#cardType h2 {
    font-family: 'GmarketSans';
    font-weight: 500;
    font-size: 50px;
}

.card__inner {
    display: flex;
    justify-content: space-between;
    font-family: 'GmarketSans';
}
.card {
    width: 32%;
    position: relative;
}
.card__body {
    position: absolute;
    bottom: 0;
    width: 86.5%;
    padding: 24px;
    text-align: center;
}

.card__body.box1 {
    background: rgba(0, 0, 0, 0.7);
    color: #fff;
}

.card__body.box2 {
    background: rgba(160, 124, 56, 0.7);
    color: #fff;
}

.card__body.box3 {
    background: rgba(155,146, 137, 0.7);
    color: #fff;
}

.card__body .tit {
    font-size: 24px;
    margin-bottom: 10px;
    overflow: hidden;
    white-space: nowrap;
    text-overflow: ellipsis;
 
}
.card__body a {
    text-align: center;
    text-decoration: none;
    color: #fff;
}

.card__body a:hover {
    border-bottom: 1px solid #fff;
}


@media (max-width: 960px){
    .card__inner {
        flex-wrap: wrap;
    }
    .card {
        width: 49%;
    }
    .card:last-child {
        display: none;
    }
}
@media (max-width: 600px){
    .card {
        width: 100%;
    }
    .card:first-child {
        margin-bottom: 20px;
    }
    .card__body {
        padding: 20px;
    }
    .card__body .desc {
        font-size: 16px;
    }
}
</style>