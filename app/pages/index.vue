<template>
  <div class="home">
    <section class="slider">
      <div class="slider__container container">
        <div class="slider__body">
          <div class="slider__text">Сайт компании ООО "Агрономы Черноземья"</div>
          <h1 class="slider__title">Почвенный анализ, диагностика и агроконсалтинг</h1>
        </div>
      </div>
      <div class="slider__img _ibg">
        <img src="/assets/image/image-slider-793.jpg" alt="image-slider-793" />
      </div>
    </section>
    <section class="white-block">
      <div class="container">
        <div class="white-body">
          <div class="heading">Агрономия</div>
          <h3>Рабочий день начинается с восходом солнца!</h3>
          <div class="white-block-content">
            <p>
              — Достаточно ли времени у Вас или Вашего агронома, для систематического и стабильного
              осмотра полей?
            </p>
            <p>
              — У Вас есть уверенность, что достаточно опыта и знаний для правильного
              диагностирования?
            </p>
            <p>— Соблюдаете методику осмотра или это стандартный маршрут по дороге вдоль поля?</p>
            <p>
              — Бывало, что приезжая на чужое поле, ошибки бросаются в глаза сразу, а на своём
              присутствует эффект «замыленных глаз»?
            </p>
            <p>
              — У кого опыта больше — агроном который каждый день видит 50 одних и тех же полей, или
              каждый день 10 новых полей?
            </p>
          </div>
        </div>
      </div>
    </section>
    <section class="services">
      <div class="container">
        <div class="services-box">
          <div class="services-desc">
            <div class="heading">Агрономы черноземья помогут</div>
            <p>
              У Вас есть уверенность, что достаточно опыта и знаний для правильного
              диагностирования?
            </p>
          </div>
          <ul class="services-list">
            <li class="services-list-item">
              <div class="service-heading">
                <img src="/assets/image/comments-solid.svg" alt="" width="36px" />
                <h3>Агроконсалтинг</h3>
              </div>
            </li>
            <li class="services-list-item">
              <div class="service-heading">
                <img src="/assets/image/vial-circle-check-solid.svg" alt="" width="36px" />
                <h3>Диагностика и анализ почв</h3>
              </div>
            </li>
            <li class="services-list-item">
              <div class="service-heading">
                <img src="/assets/image/layer-group-solid.svg" alt="" width="36px" />
                <h3>Составление схем питания и защиты</h3>
              </div>
            </li>
            <li class="services-list-item">
              <div class="service-heading">
                <img src="/assets/image/tractor-solid.svg" alt="" width="36px" />
                <h3>Проведение полевых испытаний</h3>
              </div>
            </li>
          </ul>
        </div>
      </div>
    </section>
    <section class="education">
      <div class="container">
        <div class="education-box">
          <div class="education-heading">
            <div class="heading">Блог АЧ</div>
            <div class="education-desc">
              <p>Первый развлекательно - познавательный контент о сельском хозяйств.</p>
              <p>
                Команда независимых агрономов-консультантов покажет свою повседневную деятельность.
              </p>
            </div>
          </div>
          <div class="education-video">
            <div class="video-box">
              <iframe
                width="100%"
                height="100%"
                src="https://www.youtube.com/embed/Ki_7ELdsWwE?si=vihvmZUZuMFIdKUG&amp;controls=0&amp;start=12"
                title="YouTube video player"
                frameborder="0"
                allow="
                  accelerometer;
                  autoplay;
                  clipboard-write;
                  encrypted-media;
                  gyroscope;
                  picture-in-picture;
                  web-share;
                "
                referrerpolicy="strict-origin-when-cross-origin"
                allowfullscreen
              ></iframe>
            </div>

            <div class="video-box">
              <iframe
                height="100%"
                width="100%"
                src="https://www.youtube.com/embed/hrYtpzma8FA?si=Ri4DXPdu_WuYpDuX"
                title="YouTube video player"
                frameborder="0"
                allow="
                  accelerometer;
                  autoplay;
                  clipboard-write;
                  encrypted-media;
                  gyroscope;
                  picture-in-picture;
                  web-share;
                "
                referrerpolicy="strict-origin-when-cross-origin"
                allowfullscreen
              ></iframe>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
.slider {
  position: relative;
}

.slider-body {
  padding: 160px 0px 160px 0px;
  position: relative;
  z-index: 2;
  width: 800px;
  margin: auto;
  text-align: center;
}

.slider-title {
  font-weight: 700;
  line-height: 1.3;
  letter-spacing: 2px;
  text-transform: uppercase;
  color: #fff;
}

@media (width > 768px) {
  .slider-title {
    font-size: 60px;
  }
}

.slider-img {
  position: absolute;
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
}

.slider-img img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.slider-text {
  font-size: 18px;
  font-weight: 400;
  color: #fff;
}

._ibg img {
  position: absolute;
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  object-fit: cover;
}

/*------------------------slider----------------------*/

.slider {
    position: relative;
}

.slider__body {
    padding: 160px 0px 160px 0px;
    position: relative;
    z-index: 2;
    margin: auto;
    text-align: center;
}

.slider__title {
    font-size: 60px;
    font-weight: 700;
    line-height: 1.3;
    letter-spacing: 2px;
    text-transform: uppercase;
    color: #fff;
}

@media (max-width: 880px) {
    .slider__title {
        font-size: 50px;
    }
}

@media (max-width: 425px) {
    .slider__title {
        font-size: 30px;
    }
    .slider__body {
        width: 360px;
    }
}
.slider__text {
    font-size: 18px;
    font-weight: 500;
    line-height: 1.5;
    color: #fff;
    margin: 0px 0px 15px 0px;
}

@media (max-width: 425px) {
    .slider__text {
        font-size: 16px;
    }
}

.slider__img {
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
}

/*--- wite-block ---*/

.white-block {
  background-color: #fff;
}

.white-body {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 66px 36px;
}

.white-body h3 {
  line-height: 2;
}

.white-block-content {
  width: 100%;
  text-align: center;
}

.white-block-content p {
  font-size: 16px;
  line-height: 2;
}

.heading {
  font-size: 16px;
  color: #1f1f1f;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 1.1px;
  margin: 9px 0;
  text-align: center;
}

h3 {
  font-size: 27px;
  font-weight: 700;
  color: #1f1f1f;
}

/*--- services ---*/

.services {
  background-color: #f4c133;
}

.services-box {
  padding: 66px 36px;
}

.services-desc {
  text-align: center;
  font-size: 16px;
  line-height: 1.6;
  text-wrap: balance;
}

.service-content p {
  font-size: 16px;
  line-height: 1.6;
  text-wrap: balance;
}

.services-list {
  display: flex;
  gap: 16px;
  padding: 36px 0;
  overflow-x: auto;
  padding-bottom: 10px;
  /* Плавная прокрутка на мобильных */
  -webkit-overflow-scrolling: touch;
  /* Прилипание карточек (по желанию) */
  scroll-snap-type: x mandatory;
}

.services-list::-webkit-scrollbar {
  height: 5px;
  background-color: transparent;
}

.services-list::-webkit-scrollbar-thumb {
  background-color: rgba(0, 0, 0, 0.2);
  border-radius: 10px;
}

.services-list::-webkit-scrollbar-thumb:hover {
  background-color: rgba(0, 0, 0, 0.4);
}

.services-list {
  scrollbar-width: thin;
  scrollbar-color: rgba(0, 0, 0, 0.2) transparent;
}

.services-list-item {
  padding: 12px;
  border: 1px solid #1f1f1f;
  flex: 0 0 300px;
  scroll-snap-align: start;
}

.service-heading {
  text-align: center;
}

.service-heading h3 {
  margin: 9px 0;
}

.service-link {
  display: inline-block;
  padding: 9px;
  border: 1px solid #000;
  color: #000;
  transition: 0.3s ease;
}

.service-link:hover {
  background-color: #000;
  color: #fff;
}

/*-- education-block --*/

.education {
  background-color: #fff;
}

.education-box {
  padding: 66px 36px;
}

.education-desc {
  text-align: center;
  font-size: 16px;
  line-height: 2;
}

.education-video {
  display: flex;
  flex-wrap: wrap;
  gap: 36px;
  padding: 36px 0;
}

.video-box {
  min-height: 336px;
  flex: 1 0 auto;
  border: 1px solid #29a04d;
  padding: 6px;
}

.video-box iframe {
  display: block;
}

/* .black-block__body {
  flex: 1 1 50%;
}
.white-style {
  color: #fff;
}

.black-block__video {
  flex: 1 1 50%;
  position: relative;
  padding: 0 0 29% 0;
}

@media (max-width: 900px) {
  .black-block__video {
    padding: 29% 0 29% 0;
  }
}

.black-block__video iframe {
  object-fit: cover;
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border-radius: 2px;
}

.black-heading {
  font-size: 16px;
  color: #fff;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 1.1px;
  margin: 9px 0;
}

.black-h3 {
  color: #fff;
  margin: 9px 0;
}

.black-content {
  font-size: 16px;
  color: #fff;
  line-height: 1.6;
} */
</style>
