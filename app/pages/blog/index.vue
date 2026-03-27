<script setup lang="ts">
const data = [
  {
    id: 1,
    title: "«СовЭкон» повысил прогноз экспорта пшеницы",
    image: "/image/f2405d1c162.jpg",
    description:
      "В то же время Казахстан ввел запрет на импорт российского зерна из-за эпизоотической ситуации.",
  },
  {
    id: 2,
    title: "Весенний сев стартовал в благоприятных условиях",
    image: "/image/c62e6bafc44.jpg",
    description:
      "Сельхозпроизводители юга оптимистично настроены относительно урожая этого года.",
  },
  {
    id: 3,
    title: "Составление схем питания и защиты",
    image: "/image/c62e6bafc44.jpg",
    description:
      "Рынок пестицидов и агрохимикатов предлагает огромное количество решений, как комплексного так и точечного характера.",
  },
  {
    id: 4,
    title: "Проведение полевых испытаний",
    image: "/image/f2405d1c162.jpg",
    description:
      "Одним из наших любимых направлений, в котором мы не просто чувствуем свою экспертность, но и легко составляем конкуренцию научно исследовательским институтам, является проведение опытов.",
  },
];
</script>

<template>
  <div class="services">
    <div class="container">
      <div class="services-box">
        <div>
          <span class="services-breadcrumbs">Главная >> Услуги</span>
          <h1>Блог Агрономов Черноземья</h1>
          <p>
            Поможем оптимизировать агрономические процессы, уйти от «ненужных» операций и сохранить
            урожай.
          </p>
        </div>
        <ul class="service-items">
          <li v-for="item in data" :key="item.id" class="service-item">
            <div class="service-heading">
              <div class="service-heading-image">
                <img :src="String(item.image)" alt="" />
              </div>
              <div class="service-heading-content">
                <h3>{{ item.title }}</h3>
                <p>
                  {{ item.description }}
                </p>
                <a :href="`/blog/${item.id}`" class="item-link">Подробнее</a>
              </div>
            </div>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<style scoped>
h3 {
}

.services {
}

.services-box {
  padding: 27px;
  display: flex;
  flex-direction: column;
  gap: 18px;
}

.services-breadcrumbs {
  display: block;
  margin-bottom: 9px;
  color: #29a04d;
}

.service-items {
  display: flex;
  flex-wrap: wrap;
  gap: 36px;
}

.service-item {
  flex: 1 1 356px;
  /* background-color: #f4c133; */
  border: 1px solid #f4c133;
  padding: 20px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.service-item:hover {
  background-color: #f4c133d1;
}

.service-heading {
  display: flex;
  flex-direction: column;
  gap: 21px;
}

.service-heading-image {
  width: 100%;
  height: 100%;
  justify-self: center;
}

.service-heading-content {
  display: flex;
  flex-direction: column;
  gap: 18px;
}

.item-link {
  display: block;
  letter-spacing: 0.6px;
  color: #1d221d;
  text-decoration-line: underline;
  text-decoration-thickness: 1px;
  text-underline-offset: 6px;
  text-decoration-color: #ffffff78;
  -webkit-text-decoration-thickness: 1px;
  -webkit-text-decoration-color: #ffffff78;
}
</style>
