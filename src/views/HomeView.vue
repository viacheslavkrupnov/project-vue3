<template>
  <div class="header">
    <NavModule :tabs_ls="tabs_ls" @nav_click="nav_click"></NavModule>
    <component :is="current_component.com"></component>
  </div>
</template>

<script setup lang="ts">
import { shallowReactive, shallowRef } from 'vue';
import NavModule from '@/components/NavModule/NavModule.vue'; // @ is an alias to /src
import ClubModule from '@/components/ClubModule/ClubModule.vue';
import BarcaTeam from '@/components/BarcaTeam/BarcaTeam.vue';
import CulersModule from '@/components/CulersModule/CulersModule.vue';
import ShopModule from '@/components/ShopModule/ShopModule.vue';
import TicketsModule from '@/components/TicketsModule/TicketsModule.vue'
import FirstTeam from '@/components/FirstTeam/FirstTeam.vue';

// export default defineComponent({
//   name: 'HomeView',
//   components: {
//     NavModule,
// },
// });

type tab_el = {
  title: string;
  id: number;
  com: any;
};
let tabs_ls = shallowReactive<tab_el[]>([
  {
    title: "FIRST TEAM",
    id: 1,
    com: FirstTeam,
  },
  {
    title: "TICKETS & MUSEUM",
    id: 2,
    com: TicketsModule,
  },
  {
    title: "SHOP",
    id: 3,
    com: ShopModule,
  },
  {
    title: "CULERS",
    id: 4,
    com: CulersModule,
  },
  {
    title: "CLUB",
    id: 5,
    com: ClubModule,
  },
  {
    title: "BARCA TEAMS",
    id: 6,
    com: BarcaTeam,
  },
]);
let current_component = shallowRef<tab_el>(tabs_ls[0]);
const nav_click = (item: tab_el) => {
  current_component.value = item;
  console.log("父组件", item);
};
</script>

<style lang="less" scoped>
 .header {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    background-color: #181733;
    z-index: 100;
    
  }

</style>
