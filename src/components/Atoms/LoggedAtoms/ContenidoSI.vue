<template>
    <div class="contenidoSI">
        <div class="cajaInvertir">
            <h1 class="tituloInvertir">Invertir</h1>
            <h1 class="tituloProgreso">Progreso</h1>
        </div>
    </div>
    <div class="cajaProgreso">
        
    </div>
</template>
<style scoped>
    .contenidoSI {
    position: absolute;
    width: 812px;
    height: 700px;
    left: 277px;
    top: 152px;
    background: #FFFFFF;
    box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.25);
    border-radius: 5px;
    }
    .cajaProgreso {
    position: absolute;
    width: 772px;
    height: 390px;
    left: 297px;
    top: 387px;

    background: #5F84F7;
    opacity: 0.1;
    border-radius: 5px;
    }

    .tituloInvertir {
    position: absolute;
    left: 31px;
    top: -11px;
    color: linear-gradient(180deg, #2850C7 20.31%, rgba(40, 80, 199, 0) 34.67%);
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    background: -webkit-linear-gradient(rgba(40, 80, 199, 1) 60%, rgba(40, 80, 199, 0) 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    font-weight: 700;
    text-shadow: 0px 4px 21px rgba(255,255,255,0.5);
    font-size: 40px;

    }

    .tituloProgreso {
        position: absolute;
    left: 31px;
    top: 212px;
    color: linear-gradient(180deg, #2850C7 20.31%, rgba(40, 80, 199, 0) 34.67%);
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    background: -webkit-linear-gradient(rgba(40, 80, 199, 1) 60%, rgba(40, 80, 199, 0) 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    font-weight: 700;
    text-shadow: 0px 4px 21px rgba(255,255,255,0.5);
    font-size: 40px;
    }
</style>