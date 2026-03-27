<script setup lang="ts"></script>

<template>
  <header class="header">
    <div class="container">
      <div class="header-box">
        <div class="logo-box">
          <div class="logo">
            <a href="/">
              <img src="/assets/image/agronom-cfo-w.png" alt="logo-agronom-cfo" />
            </a>
          </div>
          <div class="slogan">
            <p>Жди не дождя и грома, а жди агронома!</p>
          </div>
        </div>
        <div class="content-box">
          <div class="address desktop">
            <p class="heading">Адрес офиса</p>
            <p>г. Воронеж, Московский проспект, 128</p>
          </div>
          <div class="working desktop">
            <p class="heading">Время работы</p>
            <p>СЕЗОН (апрель-сентябрь): 24/7</p>
            <p>Пн. – Пт. (октябрь-март) с 9:00 – 18:00</p>
          </div>
          <div class="social desktop">
            <p class="heading">Мы онлайн</p>
            <p>Telegram, MAX</p>
            <p>+7 992 050-55-33</p>
          </div>
        </div>
      </div>
      <hr />
      <nav class="nav">
        <ul class="menu-desktop">
          <li>
            <a
              href="/services"
              class="menu-link"
              :class="[$route.path === '/services' ? 'menu-link-active' : '']"
            >
              Услуги
            </a>
          </li>
          <li>
            <a
              href="/products"
              class="menu-link"
              :class="[$route.path === '/products' ? 'menu-link-active' : '']"
            >
              Портфель товаров
            </a>
          </li>
          <li>Акции и скидки</li>
          <li>
            <a
              href="/blog"
              class="menu-link"
              :class="[$route.path === '/blog' ? 'menu-link-active' : '']"
            >
              Блог АЧ
            </a>
          </li>
          <li>О компании</li>
          <li>Контакты</li>
        </ul>
        <ul></ul>
      </nav>
    </div>
  </header>
</template>

<style scoped>
.header {
  height: 100%;
  min-height: 186px;
  background-color: #29a04d;
  position: relative;
}

.header-box {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 36px;
  padding: 27px 6px;
}

.content-box {
  display: flex;
  gap: 36px;
}
@media (width < 1080px) {
  .desktop {
    display: none;
  }

  .header-box {
    display: flex;
    justify-content: center;
    padding: 27px 0;
  }
}

p,
ul {
  font-size: 14px;
  color: #fff;
  line-height: 1.6;
  text-wrap: balance;
}

.logo-box {
  display: flex;
  align-items: center;
  gap: 6px;
}

.logo-box img {
  height: 100%;
  max-width: 218px;
}

.slogan {
  width: 128px;
}

.slogan p {
  font-size: 15px;
  color: #fff;
  line-height: 1.4;
}

.heading {
  text-transform: uppercase;
  letter-spacing: 1.1px;
  font-weight: 600;
  /* margin-bottom: 6px; */
  /* text-decoration-line: underline;
  text-decoration-thickness: 1px;
  text-underline-offset: 6px;
  text-decoration-color: #ffffff78;
  -webkit-text-decoration-thickness: 1px;
  -webkit-text-decoration-color: #ffffff78; */
}

hr {
  position: absolute;
  bottom: 47px;
  right: 0;
  border: none;
  background-color: #ffffff78;
  height: 1px;
  width: 100%;
}

.nav {
  /* border-top: 1px solid #ffffff78; */
  padding: 12px 6px;
}

@media (width < 1080px) {
  .menu-modile {
    display: flex;
  }

  .menu-desktop {
    display: none;
  }
}

@media (width > 1080px) {
  .menu-desktop {
    display: flex;
    justify-content: space-between;
    gap: 18px;
  }

  .menu-modile {
    display: none;
  }
}

.menu-link {
  color: #fff;
  transition: 0.3s ease;
}

.menu-link:hover {
  font-weight: 500;
}

.menu-link-active {
  font-weight: 500;
  margin-bottom: 6px;
  text-decoration-line: underline;
  text-decoration-thickness: 1px;
  text-underline-offset: 6px;
  text-decoration-color: #ffffff78;
  -webkit-text-decoration-thickness: 1px;
  -webkit-text-decoration-color: #ffffff78;
}
</style>
