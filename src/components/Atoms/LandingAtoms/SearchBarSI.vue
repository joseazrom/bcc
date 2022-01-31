<template>
  <div class="searchContainerSI">
    <img src="../../../assets/iconos/lupaSearchBarSI.png" alt="" class="lupaSearchBarSI">
    <input
      type="text"
      class="lupaSearchBarSI"
      placeholder="Buscar"
    />
  </div>
</template>

<script></script>

<style scoped>

.searchContainerSI {
  position: absolute;
  width: 209px;
  height: 34px;
  left: 744px;
  top: 14px;
  background: #04b8d8;
  mix-blend-mode: normal;
  opacity: 0.2;
  border-radius: 5px;
  font-family: Inter;
  font-style: normal;
  font-weight: 300;
  font-size: 15px;
  line-height: 19px;
  /* or 127% */
  display: flex;
  align-items: center;
  padding: 0px 10px;
}
.lupaSearchBarSI {
  border: 1;
}
.lupaSearchBarSI:focus {
  outline: none;
  position: relative;
}
</style>