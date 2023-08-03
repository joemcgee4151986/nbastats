<template>
  <div id="app">
    <div class="container">
      <div class="box" v-for="(color, index) in boxes" :key="index" :style="{ backgroundColor: color }">
       2
      </div>
      <div class="box2" v-for="(color, index) in boxes2" :key="index" :style="{ backgroundColor: color }">
        <img src= "@/assets/hardenpic.jpeg" style = "min-width: 100% ">
      </div>
      <div class="box3" v-for="(color, index) in boxes3" :key="index" :style="{ backgroundColor: color }">
        James Harden 13 G / Hou
      </div>
      <div class="box3" v-for="(color, index) in boxes4" :key="index" :style="{ backgroundColor: color }">
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
      boxes: ['red'],boxes2:['white'],boxes3:['black'],boxes4:['green']
    };
  },
};

</script>





<style scoped>
.container {
  display: flex;
  flex-direction: row;
}

.box {
  max-width:3%;
  flex: 1;
  flex-direction:row;
min-height:100px;
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
  font-weight: bold;
}
.box2 {
  max-width:5%;
 flex:1;
 min-height:100%;
  flex-direction:row;
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
  font-weight: bold;
}
.box3 {
  color:blue;
  max-height:100%;
  flex:1;
  flex-direction:row;
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
  font-weight: bold;
}
.box4{
  flex: 1;
  flex-direction:row;
min-height:100px;
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
  font-weight: bold;
}
</style>