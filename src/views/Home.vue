<template>
  <div class="home">
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <div id="nav">
      <router-link to="/about">跳转about路由</router-link>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld
  },
  beforeMount() {
    // window.addEventListener("load", () => {
    //   console.log("this is window onload event");
    // });
  }
};
</script>
