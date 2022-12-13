<template>
     <footer id="footerType" class="footer__wrap section nexon">
      <h2 class="blind">푸터 영역</h2>
      <div class="footer__inner container">
        <div class="footer__menu">
          <div class="footer_leftbox">
            <h3>Webstoryboy</h3>
            <p>
              안녕하세요!
              <br />더 다양한 정보 확인
              <br />
              webstoryboy@naver.com
            </p>
            <ul class="footer_iconbox">
              <li class="footer_icon">
                <a href="/">
                  <img src="assets/img/foot_icon1.png" alt="푸터아이콘1" />
                </a>
              </li>
              <li class="footer_icon">
                <a href="/">
                  <img src="assets/img/foot_icon2.png" alt="푸터아이콘2" />
                </a>
              </li>
              <li class="footer_icon">
                <a href="/">
                  <img src="assets/img/foot_icon3.png" alt="푸터아이콘3" />
                </a>
              </li>
              <li class="footer_icon">
                <a href="/">
                  <img src="assets/img/foot_icon4.png" alt="푸터아이콘4" />
                </a>
              </li>
              <li class="footer_icon">
                <a href="/">
                  <img src="assets/img/foot_icon5.png" alt="푸터아이콘5" />
                </a>
              </li>
            </ul>
          </div>
          <div class="footer_rightbox">
            <div>
              <h3>사이트</h3>
              <ul>
                <li>
                  <a href="/">웹표준 사이트</a>
                </li>
                <li>
                  <a href="/">반응형 사이트</a>
                </li>
                <li>
                  <a href="/">패럴랙스 사이트</a>
                </li>
                <li>
                  <a href="/">포트폴리오 사이트</a>
                </li>
              </ul>
            </div>
            <div>
              <h3>유형</h3>
              <ul>
                <li>
                  <a href="/">이미지 유형</a>
                </li>
                <li>
                  <a href="/">카드 유형</a>
                </li>
                <li>
                  <a href="/">이미지/텍스트 유형</a>
                </li>
                <li>
                  <a href="/">배너 유형</a>
                </li>
                <li>
                  <a href="/">텍스트 유형</a>
                </li>
                <li>
                  <a href="/">푸터 유형</a>
                </li>
              </ul>
            </div>
            <div>
              <h3>스크립트</h3>
              <ul>
                <li>
                  <a href="/">검색 이벤트</a>
                </li>
                <li>
                  <a href="/">퀴즈 이펙트</a>
                </li>
                <li>
                  <a href="/">마우스 이펙트</a>
                </li>
                <li>
                  <a href="/">슬라이드 이펙트</a>
                </li>
                <li>
                  <a href="/">패럴랙스 이펙트</a>
                </li>
                <li>
                  <a href="/">게임 이펙트</a>
                </li>
              </ul>
            </div>
            <div>
              <h3>레퍼런스</h3>
              <ul>
                <li>
                  <a href="/">CSS</a>
                </li>
                <li>
                  <a href="/">FONTS</a>
                </li>
                <li>
                  <a href="/">BLOG</a>
                </li>
                <li>
                  <a href="/">REFERENCE</a>
                </li>
                <li>
                  <a href="/">TUTORIAL</a>
                </li>
              </ul>
            </div>
          </div>
        </div>
        <div class="footer__right">
          Copyright 2022. All Rights Reserved. - Designed by Webstoryboy
        </div>
      </div>
    </footer>
</template>

<style>
.footer__menu {
    display: flex;
    padding-bottom: 100px;

}

.footer__menu h3 {
    font-size: 18px;
    margin-bottom: 20px;
    font-weight: bold;
    color: #222;
}
.footer__menu li a {
    font-size: 14px;
    color: #666;
    margin-bottom: 10px;
    display: block;
}
.footer__right {
    border-top: 1px solid #d9d9d9;
    text-align: center;
    padding-top: 40px;
    color: #888;
    line-height: 1.5;
}

.footer_leftbox {
    width: 35%;
}

.footer_leftbox p {
    font-size: 14px;
    color: #666;
    line-height: 1.7;
    font-weight: 500;
}

.footer_rightbox {
    width: 60%;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    flex-direction: row;
}

.footer_iconbox {
    display: flex;
    flex-direction: row;
    margin-top: 20px;
}

.footer_icon {
    width: 12%;
    padding-right: 15px;
}


@media (max-width: 960px){
    .footer__menu {
        display: none;
    }
    .footer__right {
        padding-top: 0;
        border-top: 0;
    }
    .footer__wrap {
        padding: 40px 0;
    }
}
</style>