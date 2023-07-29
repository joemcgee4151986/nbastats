<template>

<v-card id = "stats1">
  <template v-slot:title>
  
</template>

</v-card>

<v-card id = "stats1">
  <template v-slot:title>
  
</template>

</v-card>

<v-card id = "stats1">
  <template v-slot:title>
  
</template>

</v-card>

<v-card id = "stats1">
  <template v-slot:title>
  
</template>

</v-card>

<v-card id = "stats-number">
  <template v-slot:title>
  2
</template>

</v-card>
<v-card id = "stats-player">
  
  <img src="@/assets/hardenpic.jpeg" id = "player-pics">


</v-card>
<v-card id = "stats-names">
  <template v-slot:title>
  James Harden
  </template>
</v-card>

</template>

<style>
#stats1{
    display: inline-flex;
  flex-direction: column;
  width: 25%;
  height: 150px;
  background-color:white;
  }

  #stats-number{
    display: inline-flex;
  flex-direction: column;
  width: 3%;
  height: 80px;
  background-color:white;
  }
  #stats-player{
    display: inline-flex;
  flex-direction: column;
  width: 6%;
  height: 100px;
  background-color:white;
  }
  #stats-names{
    display: inline-flex;
  flex-direction: column;
  width: 16%;
  height: 80px;
  background-color:white;
  border: solid;
  }
  #player-pics{
    width: 100px;
  height: 90px;
  }
</style>