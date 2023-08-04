<template>
  <nut-tabbar bottom safe-area-inset-bottom placeholder>
    <nut-tabbar-item v-for="(item,index) in List" :tab-title="item.title" :icon="item.icon"> </nut-tabbar-item>
  </nut-tabbar>
</template>
<script>
  import { h } from 'vue';
  import { Home, Category, Find, Message, My } from '@nutui/icons-vue';
  export default {
    components: { Home, Category, Find, Message, My },
    setup() {
      const List = [
        {
          title: 'หน้าหลัก',
          icon: h(Home)
        },
        {
          title: 'ภารกิจ',
          icon: h(Category)
        },
        {
          title: 'มาใหม่',
          icon: h(Find)
        },
        {
          title: 'แชท',
          icon: h(Message)
        },
        {
          title: 'ข้อมูล',
          icon: h(My)
        }
      ];
      return {
        List
      };
    }
  };
</script>
