<template>
<div id="app">
    <div class="container">
      <div class="box" v-for="(color, index) in boxes" :key="index" :style="{ backgroundColor: color }">
       <p class = "p1"></p>
      </div>
    </div>
</div>
    </template>

<script>
export default {
  name: 'App',
  data() {
    return {
      boxes:['white']
    };
  },
};

</script>

<style scoped>
.box {
    box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  max-width:25%;
  flex: 1;
  flex-direction:row;
min-height:150px;
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
  font-weight: bold;
}
</style>