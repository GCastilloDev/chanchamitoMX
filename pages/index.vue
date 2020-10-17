<template>
  <div>
    <banner />
    <nosotros />
    <servicios />

    <section class="section">
      <h1>Bienvenido</h1>
    </section>
  </div>
</template>

<script>
export default {
  name: "HomePage",
  head: {
    titleTemplate: "Chanchamito MX",
  },
  components: {
    Banner: () => import("../components/Banner"),
    Nosotros: () => import("../components/Nosotros"),
    Servicios: () => import("../components/Servicios"),
  },
};
</script>

<style lang="css" scoped>
@import url("https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap");

* {
  font-family: "Poppins", sans-serif;
}
</style>
