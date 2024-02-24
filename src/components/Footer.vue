<template>
  <footer id="footer">
    <p>Make Your Burger &copy; 2023</p>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
#footer {
  height: 200px;
  background-color: #222;
  border-top: solid 4px #111;
  color: #fcba03;
  display: flex;
  align-items: center;
  justify-content: center;
  position: absolute;

  width: 100%;
}
</style>