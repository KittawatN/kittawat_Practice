<template>
  <div>
    <h1>V-On</h1>
    <h2>{{ message }}</h2>
    <botton v-on:click="add()">Add</botton>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: 0,
    };
  },
  methods: {
    add() {
      this.message = this.message + 1;
    },
  },
};
</script>
