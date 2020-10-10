<template>
  <div>
    <globalNavigation></globalNavigation>
    <restaurantWindow></restaurantWindow>
    <globalFooter></globalFooter>
  </div>
</template>

<script>
//Component Imports
import globalNavigation from "./components/globalNavigation.vue";
import globalFooter from "./components/globalFooter";
import restaurantWindow from "./components/restaurantWindow";

//vue export to index.html
export default {
  name: "app",
  data() {
    return {};
  },
  components: {
    globalNavigation,
    globalFooter,
    restaurantWindow
  }
};
</script>
