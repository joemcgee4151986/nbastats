<script setup>

</script>



<template class = "flex-container">

<v-card

id = "boxes">
  <template v-slot:title>
   League Leaders
  </template> 
  
  <v-card

id = "box1">
  <template v-slot:title>
   League Leaders
  </template> 
  
 
</v-card>
  
</v-card>





  
 


  
  
  
  
  
  
</template>
<style>
#flex-container > template{
  justify-content: space-between;
}
#boxes{
    display: flex;
    color: white;
    background-color:blue;
    width:25%;
    justify-content: space-between;
  }
  #box1{
    display: flex;
    flex-wrap:wrap;
    margin-right: 20px;
    color: white;
    background-color:GREY;
    width: 25%;
    
  }
  #box2{
    display: flex;
    flex-wrap:wrap;
    margin-right: 20px;
    flex: 1;
    color: white;
    background-color:GREY;
    width: 25%;
    justify-content: space-between;
  }
</style>