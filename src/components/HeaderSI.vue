<template>
    <div id="header" class="header">
        <h1>Header</h1>
        <SideBarSI></SideBarSI>
    </div>
</template>

<script>
import SideBarSI from "./"


export default {
    el: "#header",

    components: { SideBarSI }
    computed: {

    }
}
</script>

<style scoped>
.header {
    background: black;
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
}
</style>