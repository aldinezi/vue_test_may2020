<template>
  <div id="app">
    <h3>Vue test, May 2020 - Spark - {{imeiprezime}}</h3>
    <hr />
    <!-- Ispod ove linije implmentirajte vaše rješenje -->
  </div>
</template>

<script>

export default {
  name: 'App',
  data() {
    return {
      imeiprezime: 'unesite vaše ime i prezime',
    };
  },
  components: {
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
