<script>
export default {
  data() {
    return {
      newImg: "pexels-anaghan-km-11351621.jpg",
    };
  },
  methods: {
    getNewImg() {
      return new URL(`../assets/${this.newImg}`, import.meta, url).href;
    },
  },
};
</script>

<template>
  <img :src="getNewImg()" alt="" />
</template>

<style></style>
