<template>
  <div class="center">
    <h1>Hello {{ value }}!</h1>
    <h3>Integrantes:</h3>
    <h4>- Mariana</h4>
    <h4>- Carolina</h4>
    <h4>- Alex</h4>
    <h4>- Santos</h4>
  </div>
  
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      value: "Profesor"
    };
  }
};
</script>
<style scoped>
  div{
    justify-content: center;
  }
  .center {
  text-align: center;
  border: 3px solid green;
}
</style>
