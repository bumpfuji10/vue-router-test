<template>
  <!--header-->
  <TheHeader text="Yo's Portfolio Site" />

  <!--ルーティング-->
  <router-view></router-view>
</template>

<script>
import TheHeader from "./components/TheHeader.vue";

export default {
  components: {
    TheHeader,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Arial, Helvetica, sans-serif;
  color: #2c3e50;
}
</style>
