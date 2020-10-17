<template>
  <div class="columns">
    <div class="column is-list">
      <li v-for="(item, index) in items" :key="index">
        {{ item }}
      </li>
    </div>
  </div>
</template>

<script>
export default {
  data: () => ({
    items: [
      "Plan de contenido",
      "Gestión de redes sociales",
      "Campaña redes sociales",
      "Estrategias digitales",
      "Consultoria de marketing digital",
    ],
  }),
};
</script>

<style lang="css">
li {
  font-weight: 500;
  color: #000000;
}
</style>
