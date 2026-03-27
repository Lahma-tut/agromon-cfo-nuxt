<script setup lang="ts"></script>

<template>
  <footer class="footer">
    <div class="container">
      <div class="footer-box">
        <div class="contacts">
          <div>
            <p>ООО "АГРОНОМЫ ЧЕРНОЗЕМЬЯ"</p>
          </div>

          <div class="address">
            <p class="heading">Адрес офиса</p>
            <p>г. Воронеж, Московский проспект, 128</p>
          </div>
          <div class="working">
            <p class="heading">Время работы</p>
            <p>СЕЗОН (апрель-сентябрь): 24/7</p>
            <p>Пн. – Пт. (октябрь-март) с 9:00 – 18:00</p>
          </div>
        </div>
        <div class="services">
          <p class="heading">Услуги</p>
          <ul>
            <li>Агроконсалтин</li>
            <li>Диагностика и анализ</li>
            <li>Cхемы питания и защиты</li>
            <li>Проведение полевых испытаний</li>
            <li>Агромаркетинговая поддержка</li>
          </ul>
        </div>
        <div class="footer-about">
          <div class="logo">
            <img src="/assets/image/agronom-cfo-w.png" alt="logo-agronom-cfo" />
          </div>
          <div class="about">
            <div class="social">
              <p class="heading">Мы онлайн</p>
              <p>Telegram, MAX, +7 (992) 050-55-33</p>
            </div>
            <p class="about-desc">
              Наша команда сотрудничает с передовыми, коммерческими лабораториями агрохимического
              анализа, а отбор проб проводит исключительно своими руками по утверждённым методикам.
            </p>
          </div>
        </div>
      </div>
      <div class="copyright"></div>
    </div>
  </footer>
</template>

<style scoped>
.footer {
  display: flex;
  flex-direction: column;
  background-color: #29a04d;
}

.footer-box {
  width: 100%;
  height: 100%;
  min-height: 216px;
  padding: 66px 12px;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  gap: 18px;
}

.footer-about {
  flex: 1 0 30%;
}

.services {
  flex: 1 0 30%;
}

.contacts {
  flex: 1 0 30%;
  display: flex;
  flex-direction: column;
  gap: 9px;
  
}

.logo {
  margin-bottom: 6px;
}

.logo img {
  height: 100%;
  max-width: 144px;
}

.working {
  text-wrap: balance;
}

.about-desc {
  margin-bottom: 6px;
}

.copyright {
}

p,
ul {
  font-size: 15px;
  color: #fff;
  line-height: 1.8;
}

.heading {
  margin-bottom: 6px;
  text-decoration-line: underline;
  text-decoration-thickness: 1px;
  text-underline-offset: 6px;
  text-decoration-color: #ffffff78;
  -webkit-text-decoration-thickness: 1px;
  -webkit-text-decoration-color: #ffffff78;
}
</style>
