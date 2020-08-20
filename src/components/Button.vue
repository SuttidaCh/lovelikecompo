<template>
  <div>
    <button @click="likeFunction" class="btn btn-dark ml-2" title="Like">👍 </button>
    <button @click="loveFunction" class="btn btn-dark ml-2" title="Love">🧡</button>
    <button @click="hahaFunction" class="btn btn-dark ml-2" title="Haha">😆</button>
    <button @click="wowFunction" class="btn btn-dark ml-2" title="Wow">😮</button>
    <button @click="sadFunction" class="btn btn-dark ml-2" title="Sad">😢</button>
    <button @click="angryFunction" class="btn btn-dark ml-2" title="Angry">😡</button>
    <button @click="resetFunction" class="btn btn-dark ml-2" title="Reset">reset</button>
    <p v-bind:style="{ fontSize: fsize + 'px' }">{{ button }}</p>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      button: 0,
      fsize: 40,
      
    };
  },

  props: {
    lable: String,
  },

  methods: {
    likeFunction: function () {
      this.button += 1;
    },
    loveFunction: function () {
      this.button += 10;
    },
    hahaFunction: function () {
      this.button += 5;
    },
    wowFunction: function () {
      this.button += 20;
    },
    sadFunction: function () {
      this.button -= 5;
    },
    angryFunction: function () {
      this.button -= 50;
    },
    resetFunction: function () {
      this.button = 0;
    },
  },
};
</script>

<style>
</style>

