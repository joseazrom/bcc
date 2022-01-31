<template>
  <div id="sideBarSI" class="sideBarSI">
    
    <div id="cajaInversiones" class="cajaInversiones">
      
     
      <img src="../../../assets/iconos/flechaInversionesSI.png" alt="" class="flechaInversionesSI">
      <h1 class="tituloInversiones">Inversiones</h1>
      <router-link to="/wallet" class="linkWallet">Wallet</router-link>
      <h1></h1>
      <router-link to="/plazos" class="linkPlazos">Plazos</router-link>
      <h1></h1>
      <router-link to="/simulador" class="linkSimulador">Simulador</router-link>
      <h1></h1>
      <router-link to="/miscontratos" class="linkMisContratos">Mis Contratos</router-link>
    
    </div>

    <div id="cajaRedes" class="cajaRedes">
      <div
        id="lineaCajaInversioneSI"
        class="lineaCajaInversionesSI"
      ></div>
      <img
        src="../../../assets/logos/logoINSI.png"
        alt="INSI"
        class="logoINSI"
      />
      <img
        src="../../../assets/logos/logoFBSI.png"
        alt="FBSI"
        class="logoFBSI"
      />
      <img
        src="../../../assets/logos/logoIGSI.png"
        alt="IGSI"
        class="logoIGSI"
      />
    </div>

    <div id="cajaOpciones" class="cajaOpciones">
      <router-link to="/contactanos" class="linkContactanos">Contáctanos</router-link> <h1></h1>
      <router-link to="/simulador" class="linkAyuda">Ayuda (FAQ)</router-link> <h1></h1>
      <router-link to="/cerrar-sesion" class="linkCerrarSesion">Cerrar Sesión</router-link>
    </div>

  </div>
</template>

<script>

export default {
  name: "app",

  data () {
    return {
      name: '',
    }
  }
}

</script>

<style scoped>

.link{
  color: var(--secondary-color);
  text-decoration: none;
  list-style: none;
  margin: 0px 25px;
  font-size: 15px;
  font-weight: 400;
     }
    li{
       margin: 20px 0px;
      }


.sideBarSI{
  position: absolute;
  width: 198px;
  height: 375px;
  left: 68px;
  top: 152px;
}

.cajaInversiones {
  position: absolute;
  width: 198px;
  height: 167.49px;
  left: 0px;
  top: 0px;
}

.flechaInversionesSI {
  position: absolute;
  width: 53px;
  height: 53px;
  left: -13px;
  top: -17px;
  box-shadow: 0px 0px 0px rgba(152, 180, 250, 0.75);
}

.tituloInversiones {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
    Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  font-weight: 700;
  font-style: normal;
  font-size: 20px;
  line-height: 19px;
  position: absolute;
  width: 134.02px;
  height: 27px;
  left: 30px;
  top: -12px;
  text-decoration: none;
  color: #ffffff;
}

.linkWallet {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
    Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  position: absolute;
  width: 134.02px;
  height: 12.83px;
  left: 30px;
  top: 35px;

  font-style: normal;
  font-weight: 300;
  font-size: 16px;
  line-height: 19px;
  
  /* or 119% */

  color: #FFFFFF;
}

.linkPlazos {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
    Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  position: absolute;
  width: 134.02px;
  height: 12.83px;
  left: 30px;
  top: 75px;

  font-style: normal;
  font-weight: 300;
  font-size: 16px;
  line-height: 19px;
  text-decoration: none;
/* or 119% */
  color: #FFFFFF;
}

.linkSimulador {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
    Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  position: absolute;
  width: 134.02px;
  height: 12.83px;
  left: 30px;
  top: 115px;

  font-style: normal;
  font-weight: 300;
  font-size: 16px;
  line-height: 19px;
/* or 119% */

  color: #FFFFFF;
}

.linkMisContratos {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
    Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  position: absolute;
  width: 169px;
  height: 13px;
  left: 30px;
  top: 155px;

  font-style: normal;
  font-weight: 300;
  font-size: 16px;
  line-height: 19px;
  color: #FFFFFF;
}

.linkContactanos {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
    Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  position: absolute;
  width: 164px;
  height: 8px;
  left: 0px;
  top: 36px;

  font-style: normal;
  font-weight: 300;
  font-size: 14px;
  line-height: 19px;
  /* or 136% */

  color: #FFFFFF;
}

.linkAyuda {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
    Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  position: absolute;
  width: 164px;
  height: 8px;
  left: 0px;
  top: 75px;

  font-style: normal;
  font-weight: 300;
  font-size: 14px;
  line-height: 19px;
  /* or 136% */

  color: #FFFFFF;
}

.linkCerrarSesion {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  position: absolute;
  width: 165.38px;
  height: 11.6px;
  left: 0px;
  top: 114px;

  font-style: normal;
  font-weight: 300;
  font-size: 14px;
  line-height: 19px;

  color: #FFFFFF;
}

.lineaCajaInversionesSI {
  position: absolute;
  width: 163px;
  height: 0px;
  left: 0px;
  top: 228px;

  border: 0.5px solid #ffffff;
}

.cajaRedes {
  position: absolute;
  width: 163px;
  height: 31px;
  left: 0px;
  top: 0px;

}


.logoINSI {
  position: absolute;
  width: 20px;
height: 19.33px;
left: 5px;
top: 238px;
}

.logoFBSI {
  position: absolute;
  width: 20px;
  height: 20px;
  left: 73px;
  top: 238px;
}

.logoIGSI {
  position: absolute;
  width: 20px;
  height: 20px;
  left: 140px;
  top: 238px;
}


.cajaOpciones {
  position: absolute;
  width: 165.38px;
  height: 90px;
  left: 0px;
  top: 250px;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  font-style: normal;
  font-weight: 300;
  font-size: 14px;
  line-height: 19px;
/* or 136% */
  color: #FFFFFF;
}
</style>
