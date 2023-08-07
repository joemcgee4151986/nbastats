<template>
<div id="app">
    <div class="container">
      <div class="box" v-for="(color, index) in boxes" :key="index" :style="{ backgroundColor: color }">
        <img src= "@/assets/player.jpg" style = "max-width: 50% ">
      </div>
      <div class="box2" v-for="(color, index) in boxes2" :key="index" :style="{ backgroundColor: color }">
        <img src= "@/assets/player.jpg" style = "max-width: 50% ">
      </div>
      <div class="box3" v-for="(color, index) in boxes3" :key="index" :style="{ backgroundColor: color }">
        <img src= "@/assets/player.jpg" style = "max-width: 50% ">
      </div>
      <div class="box4" v-for="(color, index) in boxes4" :key="index" :style="{ backgroundColor: color }">
        <img src= "@/assets/player.jpg" style = "max-width: 50% ">
      </div>
    </div>
</div>
    </template>

<script>
export default {
  name: 'App',
  data() {
    return {
      boxes:['white'],boxes2:['white'],boxes3:['white'],boxes4:['white']
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
.box2 {
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  max-width:25%;
min-height:150px;
  display: flex;
  align-items: center;
  justify-content: center;
  flex: 1;
}

.box3{
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

.box4{

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
.container {
  display: flex;
  flex-direction: row;
}
</style>