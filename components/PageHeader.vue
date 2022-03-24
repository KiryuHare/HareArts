<template>
  <header>
    <img src="favicon.ico" />
    <div>HareArts</div>
  </header>
</template>

<script>
export default {
  name: "PageHeader",
};
</script>

<style scoped>
header {
  background-color: black;
  color: white;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 3rem;
  height: 7rem;
}
header img {
  height: 80%;
  width: auto;
  margin: 10px;
}
</style>