<template>
  <div id="header">
    <b-nav tabs>
      <b-nav-item disabled><strong> Vue Quiz app</strong></b-nav-item>
      <b-nav-item disabled
        >Counter: {{ numCorrect }}/{{ numTotal }}
      </b-nav-item>
    </b-nav>
  </div>
</template>

<script>
export default {
  props: ["numCorrect", "numTotal"],
};
</script>

<style>
#header {
  font-family: "Montserrat", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  background: #343a40;
}
</style>
