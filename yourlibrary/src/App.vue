<template>
  <div id="app">
    <main class="container">
    <navbar />
    <div class="body">
      <router-view />
    </div>
    </main>
  </div>
</template>

<script>
import navbar from "./components/navbar";
export default {
  name: "App",
  components: {
    navbar
  }
};
</script>

<style>
* {
  margin: 0;
  padding: 0;

}


</style>
