<template>
    <section id="bannerType" class="banner__wrap nexon">
      <h2 class="blind">배너 영역</h2>
      <div class="banner__inner">
        <div class="banner_text container">
          <h3 class="title">유튜버 웹보이</h3>
          <p class="desc">
            더 다양한 강의는 유튜브를 통해 제공하고 있습니다.
            <br />
            구독과 좋아요! 부탁드립니다.
          </p>
          <span class="small">
            <a href="/">바로가기</a>
          </span>
        </div>
      </div>
    </section>
</template>

<style>
.banner__inner {
    background-image: url(../../assets/img/banner_bg01.jpg);
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
    padding: 120px 0;
    color: #fff;
    font-family: 'GmarketSans';
}


.banner__inner .title {
    font-size: 50px;
    line-height: 1;
    font-weight: 500;
    margin-bottom: 40px;
}
.banner__inner .desc {
    font-size: 24px;
    line-height: 1.5;
    font-weight: 300;
    margin-bottom: 70px;
}
.banner__inner .desc a {
    color: #fff;
    display: block;
}
.banner__inner .desc a:hover {
    text-decoration: underline;
}
.banner__inner .small {
    display: inline-block;
    background: #FF3344;
    font-size: 16px;
    padding: 15px 65px 15px 65px;
}

.banner__inner .small a {
    color: #fff;
    text-decoration: none;
}

@media (max-width: 960px){
    .banner__inner {
        padding: 100px 0;
    }
}

@media (max-width: 600px){
    .banner__inner {
        padding: 80px 0;
    }
    .banner__inner .title {
        font-size: 30px;
        margin-bottom: 20px;
    }
    .banner__inner .desc {
        font-size: 16px;
        margin-bottom: 40px;
    }
}
</style>