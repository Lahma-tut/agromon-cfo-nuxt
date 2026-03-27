<script setup lang="ts">
const data = [
  {
    id: 1,
    title: "Агроконсалтинг",
    image: "/assets/image/comments-solid.svg",
    description:
      "Поможем оптимизировать агрономические процессы, уйти от «ненужных» операций и сохранить урожай.",
  },
  {
    id: 2,
    title: "Диагностика и анализ",
    image: "/assets/image/vial-circle-check-solid.svg",
    description:
      "Для точного и правильного диагностирования, необходим качественный анализ почвы. ",
  },
  {
    id: 3,
    title: "Составление схем питания и защиты",
    image: "/assets/image/layer-group-solid.svg",
    description:
      "Рынок пестицидов и агрохимикатов предлагает огромное количество решений, как комплексного так и точечного характера.",
  },
  {
    id: 4,
    title: "Проведение полевых испытаний",
    image: "/assets/image/tractor-solid.svg",
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
          <h1>Услуги Агрономов Черноземья</h1>
          <p>
            Поможем оптимизировать агрономические процессы, уйти от «ненужных» операций и сохранить
            урожай.
          </p>
        </div>
        <ul class="service-items">
          <li v-for="item in data" :key="item.id" class="service-item">
            <div class="service-heading">
              <div class="service-heading-image">
                <img src="/assets/image/vial-circle-check-solid.svg" alt="" width="36px" />
              </div>
              <div class="service-heading-content">
                <h3>{{ item.title }}</h3>
                <p>
                  {{ item.description }}
                </p>
                <a href="#" class="item-link">Подробнее</a>
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
  color: #f4c133;
}

.service-items {
  display: flex;
  flex-wrap: wrap;
  gap: 36px;
}

.service-item {
  flex: 1 1 356px;
  background-color: #f4c133;
  padding: 20px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.service-item:hover {
  background-color: #f4c133d1;
}

.service-heading {
  display: grid;
  grid-template-columns: 50px 1fr;
  gap: 21px;
}

.service-heading-image {
  justify-self: center;
  filter: invert(-20);
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
