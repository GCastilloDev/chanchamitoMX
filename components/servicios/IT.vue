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
      "Desarrollo de aplicaciones web",
      "App móviles",
      "Páginas web",
      "Desarrollo de software",
      "Consultoría en T.I.",
    ],
  }),
};
</script>

<style lang="css" scoped>
.is-list {
  padding-left: 2rem;
}
</style>
