<template>
  <div id="app">
    <div class="container">
      <div class="box" v-for="(color, index) in boxes" :key="index" :style="{ backgroundColor: color }">
        Box {{ index + 1 }}
      </div>
      <div class="box2" v-for="(color, index) in boxes2" :key="index" :style="{ backgroundColor: color }">
        Box {{ index + 1 }}
      </div>
      <div class="box3" v-for="(color, index) in boxes3" :key="index" :style="{ backgroundColor: color }">
        Box {{ index + 1 }}
      </div>
      
    </div>
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      boxes: ['red'],boxes2:['blue'],boxes3:['black']
    };
  },
};

</script>





<style scoped>
.container {
  display: flex;
  flex-direction: column;
}

.box {
  width: 5%;
  height: 100px;
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
  font-weight: bold;
}
.box2 {
  width: 10%;
  height: 100px;
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
  font-weight: bold;
}
.box3 {
  width: 10%;
  height: 100px;
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
  font-weight: bold;
}
</style>