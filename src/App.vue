<template>
  <v-app>
    <div>
      <Header />
    </div>
    <Menubar />
    <v-content>
      <Income />
    </v-content>
  </v-app>
</template>

<script>
import Header from "./components/Header";
import Menubar from "./components/Menubar";
import Income from "./components/Income";
export default {
  name: "App",

  components: {
    Header,
    Menubar,
    Income
  },

  data: () => ({
    //
  })
};
</script>
