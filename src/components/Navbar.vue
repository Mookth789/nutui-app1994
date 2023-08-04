<template>
<div id="nav" >
<div class="back">
<svg class="nut-icon nut-icon-left" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1024 1024" role="presentation">
<path d="M642.973 1005.542 321.912 587.098a123.278 123.278 0 0 1 0-150.17l321.06-418.443a47.182 47.182 0 0 1 74.83 57.422l-321.088 418.47a28.994 28.994 0 0 0 0 35.3l321.088 418.47a47.155 47.155 0 0 1-74.83 57.395" fill="currentColor" fill-opacity="0.9">
</path>
</svg>
</div>
<font style="vertical-align: inherit;">
<font style="vertical-align: inherit;">แถบนำทาง</font>
</font>
<div class="translate">
<img src="https://img14.360buyimg.com/imagetools/jfs/t1/135168/8/21387/6193/625fa81aEe07cc347/55ad5bc2580c53a6.png">
</div>
</div>


</template>

<script setup>
import { Notice } from '@nutui/icons-vue';
const back = () => {
  console.log('Click Back');
};
const title = () => {
  console.log('Click Title');
};
const rightClick = () => {
  console.log('Click Right');
};
const icon = () => {
  console.log('Click Icon');
};
</script>

<style>
  .nut-badge {
    margin-right: 10px;
  }
.nav {
    position: fixed;
    z-index: 100;
    left: 0;
    right: 0;
    height: 57px;
    line-height: 57px;
    text-align: center;
    background: #ff3991;
    font-weight: 700;
    font-size: 18px;
    color: #fff;
    -webkit-box-shadow: 0px 4px 10px 0px rgba(0,0,0,.07);
    box-shadow: 0 4px 10px rgba(0,0,0,.07);
}
</style>

