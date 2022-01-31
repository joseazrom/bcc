<template>
     <div id="navbarsi" class="navBarSI">
        <div>
            <img src="../../../assets/logos/BCCLogoSI.png" alt="" class="BCCLogoSI" />
        </div>
        <div id="cajaNotificaciones" class="cajaNotificaciones">
            <img
              src="../../../assets/iconos/ajustesNBSI.png"
              alt=""
              class="ajustesNBSI"
            />
            <img
              src="../../../assets/iconos/notificacionesNBSIpng.png"
              alt=""
              class="notificacionesNBSI"
            />
            <img
              src="../../../assets/iconos/powerNBSI.png"
              alt=""
              class="powerNBSI"
            />
        </div>
        <div id="cajaCentralNBSI" class="cajaCentralNBSI">
            <img src="../../../assets/iconos/logoBCCNB.png" alt="" class="logoBCCNB">
            <img src="../../../assets/iconos/playNBSI.png" alt="" class="playNBSI">

            <div id="bienvenidaNBSI" class="bienvenidaNBSI">
                <h1 id="textoBienvenida" class="textoBienvenidaNBSI">¡Bienvenido José Castilla!</h1>
            </div>
        </div>
     </div>
    <NavBarNotificaciones></NavBarNotificaciones>
    <BotonIdiomas></BotonIdiomas>
</template>

<script>
    import BotonIdiomas from "./BotonIdiomas.vue"

    export default {
        name: "App",
        components: {
            BotonIdiomas,
        },
    };
</script>

<style scoped>

.navBarSI{
    position: absolute;
    width: 1230px;
    height: 63px;
    left: 69px;
    top: 37px;
}

.BCCLogoSI {
    position: absolute;
    width: 185px;
    height: 63px;
    left: 0px;
    top: 0px;
}

.cajaCentralNBSI {
    position: absolute;
    width: 811px;
    height: 63px;
    left: 208px;
    top: 0px;
    border-radius: 5px;
    background: linear-gradient(163.7deg, #5F84F7 10.47%, #144DF6 88.69%);
    filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.25));
}

.logoBCCNB {
    position: absolute;
    width: 36px;
    height: 36px;
    left: 16px;
    top: 13px;
}

.playNBSI {
    position: absolute;
    width: 42px;
    height: 42px;
    left: 63px;
    top: 9px;
}

.bienvenidaNBSI {
    position: absolute;
    width: 187px;
    height: 37px;
    left: 336px;
    top: 21px;
}

.textoBienvenidaNBSI {
    position: absolute;
    left: -210px;
    top: -10px;
    font-family: 'Inter', sans-serif;
    font-style: normal;
    font-weight: 600;
    font-size: 15px;
    line-height: 19px;
    /* or 127% */
    text-align: right;
    color: #FFFFFF;
}

.cajaNotificaciones {
   position: absolute;
   width: 185px;
   height: 63px;
   left: 1044px;
   top: 0px;
   border-radius: 5px;
   background: linear-gradient(163.7deg, #5F84F7 10.47%, #144DF6 88.69%);
}

.ajustesNBSI {
   position: absolute;
   width: 23px;
   height: 23px;
   left: 20px;
   top: 20px;
}

.notificacionesNBSI {
   position: absolute;
   width: 28px;
   height: 27.24px;
   left: 80px;
   top: 16px;
}

.powerNBSI {
  position: absolute;
  width: 26px;
  height: 26px;
  left: 140px;
  top: 19px;
}
</style>