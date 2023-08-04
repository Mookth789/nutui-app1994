<template>
  <nut-navbar @on-click-back="back" @on-click-title="title" title="หน้าหลัก">
    <template #left>
      <div>กลับ</div>
    </template>
    <template #right>
    <nut-badge dot>
      <Notice width="14px" color="#000000" class="nut-icon-am-breathe nut-icon-am-infinite" />
    </nut-badge>
    </template>
  </nut-navbar>
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
</style>

