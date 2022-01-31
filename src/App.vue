<template>
  <!-- <div id="app">
    <font-awesome-icon icon="user-secret" />
  </div> -->
  <div id="cajaPrincipal" class="cajaPrincipal">
    <HeaderSI />
    <FooterSI />
    <NavBarSI />
    <SideBarSI />
    <ContenidoSI />
  </div>
</template>

<script>
import NavBarSI from "./components/Atoms/LoggedAtoms/NavBarSI.vue";
import SideBarSI from "./components/Atoms/LoggedAtoms/SideBarSI.vue";
import ContenidoSI from "./components/Atoms/LoggedAtoms/ContenidoSI.vue"

export default {
  name: "App",
  components: {
    NavBarSI,
    SideBarSI,
    ContenidoSI,
  },
};

</script>

<style scoped>
  .cajaPrincipal{
    position: relative;
    background: radial-gradient(70.48% 113.47% at -13.27% 72.72%, #1461F6 0%, #011537 54.66%);
    position: relative;
    width: 1366px;
    height: 958px;
  }

</style>