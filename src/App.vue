<script>
import AppTitle from "./components/AppTitle.vue";
import AppBonus from "./components/AppBonus.vue";
// export default {
//   data() {
//     return {
//       key: "Ciao",
//     };
//   },
//   components: {
//     AppTitle,
//     AppBonus,
//   },
// };
</script>

<template>
  <AppBonus />
  <div>
    {{ key }}
  </div>
  <AppTitle />
</template>

<style scoped></style>
