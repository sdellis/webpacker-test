<template>
  <div id="app">
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      message: "Hello Vue!"
    }
  }
}
</script>

<style>
body {
  background-color: red;
}
p {
  font-size: 2em;
  text-align: center;
  color: red;
}
</style>
