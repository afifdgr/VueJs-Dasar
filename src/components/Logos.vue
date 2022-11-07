<template>
  <div class="logos-wrapper">
    <h2 class="title-header">Find Best Logo</h2>

    <div class="item-logos">
      <img class="logo" alt="Forest logo" src="../assets/forest.png" />
    </div>
    <div class="item-logos">
      <img class="logo" alt="CP logo" src="../assets/crystal_palace.png" />
    </div>
    <div class="item-logos">
      <img class="logo" alt="AV logo" src="../assets/aston_villa.png" />
    </div>
    <div class="item-logos">
      <img class="logo" alt="Forest logo" src="../assets/forest.png" />
    </div>
    <div class="item-logos">
      <img class="logo" alt="CP logo" src="../assets/crystal_palace.png" />
    </div>
    <div class="item-logos">
      <img class="logo" alt="AV logo" src="../assets/aston_villa.png" />
    </div>
    <div class="item-logos">
      <img class="logo" alt="Forest logo" src="../assets/forest.png" />
    </div>
    <div class="item-logos">
      <img class="logo" alt="CP logo" src="../assets/crystal_palace.png" />
    </div>
  </div>
</template>

<script>
export default {
  name: "Logos",
};
</script>

<style scoped>
.title-header {
  margin-bottom: 80px;
  text-align: left;
}
.logos-wrapper {
  width: 62%;
  height: hidden;
  margin: auto;
}

.item-logos {
  float: left;
  margin-right: 70px;
  margin-bottom: 70px;
  width: 150px;
  height: 150px;
}
.item-logos .logo {
  width: 150px;
  height: 150px;
}
</style>
