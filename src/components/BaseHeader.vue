<script setup>
import { ref }from 'vue'
const titleName = ref('title')
</script>
<template>
    <div><h1 :class ="titleName">NBA.com/Stats<img id = logo src = "/src/assets/Header-image.JPG" ></h1></div>
</template>

<style>
.title{
    h1 {
        display: inline;
    }
   font-size: 80px;
   font-style: Helvetica Condensed Black;
}
#logo {
    display: flex;
   float:right;
}

</style>