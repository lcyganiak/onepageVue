<template>
  <v-app>
    <v-container>
      <div id="app">
        <Menu/>
        <div class="container">
          <router-view></router-view>
        </div>
      </div>
    </v-container>
  </v-app>
</template>

<script>
import Menu from "./components/menu/Menu";

export default {
  name: "App",
  components: {
    Menu
  },
  data() {
    return {
      //
    };
  }
};
</script>
