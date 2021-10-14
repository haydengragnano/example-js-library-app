<template>
  <div class="home">
    <h1>{{ message }}</h1>
    <h2>Dark mode is much much cooler and easier on the eyes...</h2>
    <img
      src="https://www.indiewire.com/wp-content/uploads/2017/03/screen-shot-2017-03-28-at-8-24-02-am.png?w=780"
      alt=""
    />
  </div>
</template>

<style></style>

<script>
export default {
  data: function () {
    return {
      message: "Welcome to Vue.js!",
    };
  },
  created: function () {},
  methods: {},
};
</script>
