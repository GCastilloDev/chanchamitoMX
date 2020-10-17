<template>
  <!-- <section class="hero is-large">
    <div class="nosotros__fondo has-text-centered has-text-weight-bold">
      NOSOTROS
    </div>
    <div
      class="nosotros__contenido has-text-weight-bold is-size-5 hero is-large"
    >
      PLAN DE CONTENIDO / GESTIÓN DE REDES SOCIALES / CAMPAÑA REDES SOCIALES /
      ESTRATEGIAS DIGITALES / CONSULTORIA MARKETING DIGITAL / DESARROLLO DE
      APLICACIONES WEB Y MOVILES / PAGINAS WEB / DESARROLLO DE SOFTWARE /
      CONSULTARIA EN T.I.
    </div>
  </section> -->
  <section class="nosotros__seccion">
    <div class="nosotros">
      PLAN DE CONTENIDO / GESTIÓN DE REDES SOCIALES / CAMPAÑA REDES SOCIALES /
      ESTRATEGIAS DIGITALES / CONSULTORIA MARKETING DIGITAL / DESARROLLO DE
      APLICACIONES WEB Y MOVILES / PAGINAS WEB / DESARROLLO DE SOFTWARE /
      CONSULTARIA EN T.I.
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style lang="css" >
.nosotros__seccion {
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  height: 40vh;
}

.nosotros {
  position: relative;
  font-size: 1.2rem;
  font-weight: 600;
}
.nosotros::before {
  content: "NOSOTROS";
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
  font-size: 14rem;
  font-weight: 700;
  opacity: 0.1;
}

.nosotros__fondo {
  z-index: -1;
  position: relative;
  font-size: 15rem;
  color: #f7f5f8;
  border: 1px solid blue;
}

.nosotros__contenido {
  position: absolute;
  width: 100%;
  height: 43vh;
  display: flex;
  text-align: center;
  align-items: center;
  justify-content: center;
  border: 1px solid red;
}
</style>