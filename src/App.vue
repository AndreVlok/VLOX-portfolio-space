<template>
  <div id="app" style="background-color: #fdfdfd !important;">
    <img />
    <Home />
  </div>
</template>

<script>
import Home from "./views/Home.vue";

export default {
  name: "App",
  components: {
    Home,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
article {
  width: 100%;
  height: 100%;
  background-color: #fff !important;
  @include round();
}
.card-heading {
  margin-top: 0.5rem !important;
}
.carousel__pagination-button--active {
  background-color: #ff4c42;
}
.carousel__pagination-button {
  padding: 3px;
  margin: 3px;
  border-radius: 1rem;
  border: 2px solid #ff4c42;
  box-shadow: none;
}
.carousel__pagination {
  padding: 0;
}
.content-container {
  margin: 0 auto;
  max-width: 976px;
  width: 97%;
}
button{
  @include round();
}
</style>
