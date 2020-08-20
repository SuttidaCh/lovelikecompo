<template>
  <div id="app">
    
    <img
      src="https://pbs.twimg.com/profile_images/1294650535702753282/n0jc9pBg_400x400.jpg"
      class="rounded-circle"
      width="20%"
    />
    <p>
      <br />
    </p>
    <HelloWorld msg="LOVE LIKE YOU" />
    <br />
    <div class="row">
      <div class="col-4">
        <img
          src="https://pbs.twimg.com/profile_images/1292843792710676482/NebuzRYw_400x400.jpg"
          class="rounded-circle"
          width="50%"
        />
        <p>
          <br />
        </p>
        <Button />
      </div>
      <div class="col-4">
        <img
          src="https://pbs.twimg.com/profile_images/1292844473622421505/HUFG4PeZ_400x400.jpg"
          class="rounded-circle"
          width="50%"
        />
        <p>
          <br />
        </p>
        <Button />
      </div>
      <div class="col-4">
        <img
          src="https://pbs.twimg.com/profile_images/1293181369665744897/hFU3cZPa_400x400.jpg"
          class="rounded-circle"
          width="50%"
          
        />
        <p>
          <br />
        </p>
        <Button />
      </div>
    </div>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Button from "./components/Button.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    Button,
  },

};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
