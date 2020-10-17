<template>
  <section class="section servicios__section">
    <div class="columns">
      <div class="column servicios has-text-right has-text-weight-semibold">
        Servicios
      </div>
      <div class="column servicios__content">
        <Menu @change="component = $event" />
        <component :is="component"></component>
      </div>
    </div>
  </section>
</template>

<script>
import Menu from "../components/servicios/Menu";
import Marketing from "../components/servicios/Marketing";
import IT from "../components/servicios/IT";

export default {
  data: () => ({
    component: "Marketing",
  }),
  components: {
    Menu,
    Marketing,
    IT,
  },
};
</script>

<style>
.servicios {
  color:  rgba(255, 255, 255, 0.2);
  background-color: #2b0447;
  font-size: 6rem;
  position: relative;
  top: 4.5rem;
  display: flex;
  justify-content: flex-end;
  align-items: center;
}

.servicios__section {
  padding-top: 0;
  background-color: rgba(43, 4, 71, 0.2);
}
</style>