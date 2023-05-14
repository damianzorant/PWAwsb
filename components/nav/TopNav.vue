<template>
  <div class="nav">
    <div class="items title">
      <span>Galeria</span>
    </div>

    <div class="items">
      <span><NuxtLink to="/">Home</NuxtLink></span>
    </div>

    <div class="items">
      <span><NuxtLink to="/onas">About</NuxtLink></span>
    </div>
  </div>
</template>

<script></script>
<style scoped>
.nav {
  display: flex;
  /* flex-direction: column; */
  background: linear-gradient(
    to top,
    rgb(232, 89, 89),
    rgb(235, 160, 119),
    rgb(222, 184, 131)
  );
  border-bottom: 5px yellow solid;
  height: 50px;
  width: 100vw;
}

/* px, rem, em, vh, vw, % */
.items {
  display: flex;
  flex-direction: column;
  margin: 15px;
  text-transform: uppercase;
}

.title {
  border-right: 2px black solid;
  padding-right: 10px;
  color: black;
}
</style>
