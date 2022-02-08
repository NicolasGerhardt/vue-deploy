<script>
export default {
  data() {
    return {
      count: 0,
    };
  },
  methods: {
    increment() {
      this.count++;
    },
  },
  mounted() {
    console.log(`the inital count is: ${this.count}`);
  },
};
</script>

<template>
  <h1>This is my Vue site testing gh-pages</h1>
  <h2>
    <img src="./assets/me.png" alt="profile" />
    By: Nic G
  </h2>
  <button @click="increment">Count is: {{ count }}</button>
</template>

<style>
button {
  font-size: 2em;
  font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
    "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
}

img {
  width: 100px;
  height: 100px;
}
</style>