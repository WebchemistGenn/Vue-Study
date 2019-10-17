<template>
  <div id="app">
    <HeaderComponent title="Webchemist's Theme" />
    <h1>{{ welcome }}</h1>
    <FooterComponent />
  </div>
</template>

<script>
import HeaderComponent from "./components/Header";
import FooterComponent from "./components/Footer";

export default {
  name: "App",
  components: {
    HeaderComponent,
    FooterComponent
  },
  data: () => {
    return {
      welcome: `Welcome`
    };
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  padding-top: 50px;
}
</style>
