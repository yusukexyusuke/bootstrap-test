<template>
  <div id="app">
    <p>{{ message }}</p>
    <button class="btn btn-primary">test</button>
    <button class="btn btn-primary" data-toggle="popover" title="hoge" data-trigger="hover">test</button>
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

<style scoped>
p {
  font-size: 2em;
  text-align: center;
}
</style>
