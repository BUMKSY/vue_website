<template>
    <section
      id="imgTextType"
      class="imgText__wrap section gray nexon">
      <h2 class="blind">유용한 사이트 살펴보기</h2>
      <div class="imgText__inner container">
        <div class="imgText__txt">
          <span>FRONTEND</span>
          <h3>
            프론트엔드
            <br />
            전문과정
          </h3>
          <p>
            프론트앤드 개발자로 취업하기 위한
            <br />
            전문 과정입니다.
            <br />
            여러분들도 도전해보세요!
          </p>
        </div>
        <div class="imgText_text_Box">
          <div class="imgText_text t1">
            <h3 class="imgText_text__title">웹 디자인</h3>
            <p class="imgText_text__desc">
              웹디자이너가 포함된 웹 및 멀티미디어 디자이너는 다른 직업과
              비교하여 임금과 복리후생이 낮은 퍼블리싱은 웹 사이트를 제작할
            </p>
          </div>
          <div class="imgText_text t2">
            <h3 class="imgText_text__title">웹 퍼블리셔</h3>
            <p class="imgText_text__desc">
              퍼블리싱은 웹 사이트를 제작할 때, 웹 디자이너가 디자인한 것을 웹
              표준성과 접근성에 부합하도록 재정하였다.
            </p>
          </div>
          <div class="imgText_text t3">
            <h3 class="imgText_text__title">프론트엔드 개발자</h3>
            <p class="imgText_text__desc">
              사이트와 상호작용하는 모든 부분에 대한 개발, 관리, 유지 보수를
              하는 것 솔루션의 프로세스를 개발합니다.
            </p>
          </div>
          <div class="imgText_text t4">
            <h3 class="imgText_text__title">백엔드 개발자</h3>
            <p class="imgText_text__desc">
              용어 자체에서 알 수 있듯이, 백엔드는 웹사이트나 웹 애플리케이션
              또는 모바일 솔루션의 프로세스와 관련된입니다.
            </p>
          </div>
        </div>
      </div>
    </section>
</template>

<style>
.imgText__inner {
    display: flex;
    justify-content: space-between;
    align-content: space-between;
    font-family: 'GmarketSans';
    padding: 0;
}

.imgText__txt {
    display: block;
    white-space:nowrap;
    padding-right: 100px;
}


.imgText__txt span {
    font-size: 16px;
    color: #fff;
    background-color: #FF3344;
    padding: 5px 30px 5px 30px;
    text-align: center;
    display: inline-block;
    border-radius: 15px;
    font-weight: 400;
}

.imgText__txt h3 {
    font-size: 50px;
    font-weight: 500;
    margin-top: 18px;
    margin-bottom: 20px;
    font-family: 'GmarketSansBold';
}

.imgText__txt p {
    font-size: 18px;
    font-weight: 400;
    line-height: 1.5;
    color: #111;
    margin-bottom: 10px;
}

.imgText_text_Box {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    box-sizing: border-box;
}

.imgText_text {
    width: 48%;

}


.imgText_text__title::before {
    content: '';
    position: absolute;
    left: 0;
    top: 0;
    width: 60px;
    height: 60px;
    background: url(../../assets/img/text_icon.svg);
}
.imgText_text_Box .t1 .imgText_text__title::before {
    background-position: -180px 0;
}
.imgText_text_Box .t2 .imgText_text__title::before {
    background-position: -240px 0;
}
.imgText_text_Box .t3 .imgText_text__title::before {
    background-position: -300px 0;
}
.imgText_text_Box .t4 .imgText_text__title::before {
    background-position: -60px 0;
}

.imgText_text__title {
    font-size: 24px;
    line-height: 1;
    white-space: nowrap;
    text-overflow: ellipsis;
    position: relative;
    padding-top: 80px;
    font-weight: 500;
}

.imgText_text__desc {
    font-size: 18px;
    font-weight: 300;
    line-height: 1.4;
    overflow: hidden;
    text-overflow: ellipsis;
    display: -webkit-box;
    -webkit-line-clamp: 3; 
    -webkit-box-orient: vertical;
    color: #666;
    margin-bottom: 27px;
    margin-top: 27px;
}


@media (max-width: 960px){
    .imgText__inner {
        flex-wrap: wrap;
    }
    .imgText__txt h3 {
        font-size: 40px;
    }
    .imgText__txt p {
        margin-bottom: 60px;
    }
    .imgText__inner > div.imgText__txt {
        width: 100%;
        height: auto;
        text-align: center;
    }
    .imgText__inner > div.imgText__txt ul {
        display: none;
    }
    .imgText__inner > div.imgText__img {
        width: 49%;
    }
}
@media (max-width: 600px){ 
    .imgText__txt span {
        font-size: 14px;
        margin-bottom: 10px;
    }
    .imgText__txt h3 {
        font-size: 30px;
    }
    .imgText__txt p {
        margin-bottom: 50px;
        font-size: 16px;
    }
    .imgText__inner > div.imgText__img {
        width: 100%;
        height: 200px;
    }
    .imgText__inner > div.imgText__img.img1 {
        margin-bottom: 20px;
    }
    .imgText__img a {
        left: 20px;
        bottom: 20px;
    }
}
</style>