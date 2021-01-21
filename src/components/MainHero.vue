

<template>
  <div>
  <h1 :class="$style['page-title']">Vue Your Todo </h1>
  <p :class="$style.subtitle">A Todo app powered by Vue.js 3</p>
  </div>
</template>

<style module>
.page-title {
  font-family: 'DM Serif Display', serif;
  font-size: 44px;
  letter-spacing: 1.84px;
  color: #2d2d2d;
  margin-top: 104px;
  margin-bottom: 0;
}

.subtitle {
  font-size: 1rem;
  font-weight: bold;
  color: #6b6b6b;
  margin-top: 0;
  letter-spacing: 0.67px;
  margin-left: 6px;
}

</style>