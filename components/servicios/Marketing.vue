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

<style lang="css" scoped>
.is-list {
  padding-left: 2rem;
}
</style>
