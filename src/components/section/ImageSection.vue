<template>
     <section id="imageType" class="image__wrap section nexon">
      <h2>포트폴리오 구경하기</h2>
      <p>
        웹디자이너, 웹 퍼블리셔, 프론트앤드 개발자를 위한 강의 사이트입니다.
      </p>
      <div class="image__inner container">
        <ul class="image__box">
          <li class="image__imagecon">
            <div class="iamge_imagebox1"></div>
            <div class="image_text">
              <h3 class="image__title">김현정 포폴!</h3>
              <p class="image__desc">
                사이트를 만들기 위한 기초 강의입니다. 기본 코딩에 대한 감각을
                익히고, 웹 표준을 준수하면서......
              </p>
            </div>
          </li>
          <li class="image__imagecon">
            <div class="iamge_imagebox2"></div>
            <div class="image_text">
              <h3 class="image__title">장현정 포폴!</h3>
              <p class="image__desc">
                사이트를 만들기 위한 기초 강의입니다. 기본 코딩에 대한 감각을
                익히고, 웹 표준을 준수하면서......
              </p>
            </div>
          </li>
          <li class="image__imagecon">
            <div class="iamge_imagebox3"></div>
            <div class="image_text">
              <h3 class="image__title">박현정 포폴!</h3>
              <p class="image__desc">
                사이트를 만들기 위한 기초 강의입니다. 기본 코딩에 대한 감각을
                익히고, 웹 표준을 준수하면서......
              </p>
            </div>
          </li>
          <li class="image__imagecon">
            <div class="iamge_imagebox4"></div>
            <div class="image_text">
              <h3 class="image__title">송현정 포폴!</h3>
              <p class="image__desc">
                사이트를 만들기 위한 기초 강의입니다. 기본 코딩에 대한 감각을
                익히고, 웹 표준을 준수하면서......
              </p>
            </div>
          </li>
          <li class="image__imagecon">
            <div class="iamge_imagebox5"></div>
            <div class="image_text">
              <h3 class="image__title">이현정 포폴!</h3>
              <p class="image__desc">
                사이트를 만들기 위한 기초 강의입니다. 기본 코딩에 대한 감각을
                익히고, 웹 표준을 준수하면서......
              </p>
            </div>
          </li>
          <li class="image__imagecon">
            <div class="iamge_imagebox6"></div>
            <div class="image_text">
              <h3 class="image__title">마현정 포폴!</h3>
              <p class="image__desc">
                사이트를 만들기 위한 기초 강의입니다. 기본 코딩에 대한 감각을
                익히고, 웹 표준을 준수하면서......
              </p>
            </div>
          </li>
          <li class="image__imagecon">
            <div class="iamge_imagebox7"></div>
            <div class="image_text">
              <h3 class="image__title">우현정 포폴!</h3>
              <p class="image__desc">
                사이트를 만들기 위한 기초 강의입니다. 기본 코딩에 대한 감각을
                익히고, 웹 표준을 준수하면서......
              </p>
            </div>
          </li>
          <li class="image__imagecon">
            <div class="iamge_imagebox8"></div>
            <div class="image_text">
              <h3 class="image__title">최현정 포폴!</h3>
              <p class="image__desc">
                사이트를 만들기 위한 기초 강의입니다. 기본 코딩에 대한 감각을
                익히고, 웹 표준을 준수하면서......
              </p>
            </div>
          </li>
        </ul>
      </div>
    </section>
</template>

<style>
/* imageType */
#imageType h2 {
    font-family: 'GmarketSans';
    font-weight: 500;
    font-size: 50px;
}

.image__inner {
    display: flex;
    justify-content: space-between;
    font-family: 'GmarketSans';
}
.image__box {
    display: flex;
    justify-content: space-between;
    box-sizing: border-box;
    flex-direction: row;
    flex-wrap: wrap;
}

.image__imagecon {
    display: flex;
    flex-direction: column;
    align-content: space-between;
    width: 23%;
    height: 337px;
    margin-top: 30px;
}

.image__imagecon div {
    border-radius: 5%;
}

.iamge_imagebox1 {
    background: url(../../assets/img/image_bg01.jpg) no-repeat center;
    height: 100%;
}

.iamge_imagebox2 {
    background: url(../../assets/img/image_bg02.jpg) no-repeat center;
    height: 100%;
}

.iamge_imagebox3 {
    background: url(../../assets/img/image_bg03.jpg) no-repeat center;
    height: 100%;
}

.iamge_imagebox4 {
    background: url(../../assets/img/image_bg04.jpg) no-repeat center;
    height: 100%;
}

.iamge_imagebox5 {
    background: url(../../assets/img/image_bg05.jpg) no-repeat center;
    height: 100%;
}

.iamge_imagebox6 {
    background: url(../../assets/img/image_bg06.jpg) no-repeat center;
    height: 100%;
}

.iamge_imagebox7 {
    background: url(../../assets/img/image_bg07.jpg) no-repeat center;
    height: 100%;
}

.iamge_imagebox8 {
    background: url(../../assets/img/image_bg08.jpg) no-repeat center;
    height: 100%;
}


.image_text {
    display: block;
   
}

.image__title {
    font-size: 28px;
    margin-top: 15px;
    margin-bottom: 10px;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
}
.image__desc {
    font-size: 18px;
    margin-bottom: 20px;
    font-weight: 300;
    line-height: 1.5;
    text-overflow: ellipsis;
    -webkit-box-orient: vertical;
}
.image__btn {
    font-size: 16px;
    color: #fff;
    background-color: #b45a30;
    padding: 10px 20px;
    display: inline-block;
}
.image__btn.yellow {
    background-color: #b59140;
}

@media (max-width: 600px){
    .image__inner {
        flex-direction: column;
    }
    .image {
        width: 100%;
        padding: 210px 20px 20px 20px
    }
    .image:first-child {
        margin-bottom: 20px;
    }
    .image__title {
        font-size: 24px;
    }
}
</style>