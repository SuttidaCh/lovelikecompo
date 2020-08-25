<template>
  <div id="app">
    
    <img
      src="img\p.jpg"
      class="rounded-circle"
      width="20%"
    />
    <p>
      <br />
    </p>
    <HelloWorld msg="LOVE LIKE DYNAMITE" />
    <br />
    <div class="row">
      <div class="col-4">
        <img
          src="img/v.jpg"
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
          src="img/jh.jpg"
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
          src="img/rm.jpg"
          class="rounded-circle"
          width="50%"
          
        />
        <p>
          <br />
        </p>
        <Button />
      </div>
    </div>
   <p>
      <br />
    </p>
     <div class="row">
      <div class="col-4">
        <img
          src="img/yg.jpg"
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
          src="img/j.jpg"
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
          src="img/jk.jpg"
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
