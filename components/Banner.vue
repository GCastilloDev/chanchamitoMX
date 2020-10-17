<template>
  <div class="banner__img">
    <section class="hero is-large banner__content">
      <div class="hero-body ">
        <div class="container">
          <h1 class="title has-text-centered has-text-weight-bold is-size-1 has-text-white">
            CREANDO CAMPAÑAS PARA TUS CLIENTES
          </h1>
          <h2 class="subtitle has-text-centered has-text-weight-semibold has-text-white">
            #AGENCIA #MARKETING #DIGITAL
          </h2>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "BannerComponent",
};
</script>

<style lang="css">
.banner__img {
  background-image: url("../assets/banner.jpg");
  background-image: no-repeat;
  background-image: fixed;
  background-image: center;
  background-size: cover;
}

.banner__content {
  background-color: rgba(130, 90, 221, 0.2);
}
</style>