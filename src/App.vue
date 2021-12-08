<template>
  <div class="container">
    <OrderSummary />
  </div>
</template>

<script>
import OrderSummary from "./components/OrderSummary.vue";

export default {
  name: "App",
  components: {
    OrderSummary,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Red+Hat+Display:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap");

html,
body {
  margin: 0;
  padding: 0;
  height: 100%;
  width: 100%;
}

#app {
  height: 100vh;
  width: 100vw;
}

.container {
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #e0e8ff;
  background-image: url("./assets/images/pattern-background-desktop.svg");
  background-size: contain;
  background-repeat: no-repeat;
  font-family: 'Red Hat Display', sans-serif;
}

@media only screen and (max-width: 600px) {
  .container {
      background-image: url("./assets/images/pattern-background-mobile.svg");
  }
}
</style>
