<script setup>

</script>



<template>

<v-card class = "column-one" id = "boxes">
  <template v-slot:title>
   League Leaders
  </template> 
</v-card>

  
 

  


<v-card id = "box1">
  <template v-slot:title>
   POINTS PER GAME
  
</template>

</v-card>



<v-card id = "box1">
  <template v-slot:title>
   REBOUNDS PER GAME
  </template> 

</v-card>

<v-card id = "box1">
  <template v-slot:title>
   ASSISTS PER GAME
  </template> 

</v-card>

<v-card id = "box1">
  <template v-slot:title>
  STEALS PER GAME
  </template> 

</v-card>




  
 


  
  
  
  
  
  
</template> 
<style>


#boxes{
    display: flex;
    color: white;
    background-color:blue;
    width:100%;
    justify-content: space-between;
  }
  #box1{
    display: inline-flex;
  flex-direction: column;
  flex: 1 0 auto;
  width: 25%;
  background-color:GREY;
  }
  #box2{
    display: flex;
    flex-wrap:wrap;
    margin-right: 20px;
    flex: 1;
    color: white;
    background-color:GREY;
    width: 100%;
    justify-content: space-between;
  }
</style>