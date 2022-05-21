<template>
  <div class="header">
    <NavModule :tabs_ls="tabs_ls" @nav_click="nav_click"></NavModule>
    <component :is="current_component.com"></component>
  </div>
</template>

<script setup lang="ts">
import { shallowReactive, shallowRef } from "vue";
import NavModule from "@/components/NavModule/NavModule.vue"; // @ is an alias to /src
import ClubModule from "@/components/ClubModule/ClubModule.vue";
import BarcaTeam from "@/components/BarcaTeam/BarcaTeam.vue";
import CulersModule from "@/components/CulersModule/CulersModule.vue";
import ShopModule from "@/components/ShopModule/ShopModule.vue";
import TicketsModule from "@/components/TicketsModule/TicketsModule.vue";
import FirstTeam from "@/components/FirstTeam/FirstTeam.vue";

// export default defineComponent({
//   name: 'HomeView',
//   components: {
//     NavModule,
// },
// });

type el = {
  items: string;
};

type tab_el = {
  title: string;
  id: number;
  com: any;
  subitems: el[];
};
let tabs_ls = shallowReactive<tab_el[]>([
  {
    title: "FIRST TEAM",
    id: 1,
    com: FirstTeam,
    subitems: [{ items: "Latest" }, { items: "Schedule" }, { items: "Result" }],
  },
  {
    title: "TICKETS & MUSEUM",
    id: 2,
    com: TicketsModule,
    subitems: [
      { items: "Footsall" },
      { items: "Icerink" },
      { items: "Hockey" },
    ],
  },
  {
    title: "SHOP",
    id: 3,
    com: ShopModule,
    subitems: [
      { items: "Subscribel" },
      { items: "Drawn" },
      { items: "Benefits" },
    ],
  },
  {
    title: "CULERS",
    id: 4,
    com: CulersModule,
    subitems: [
      { items: "Anythink" },
      { items: "Anythink" },
      { items: "Anythink" },
    ],
  },
  {
    title: "CLUB",
    id: 5,
    com: ClubModule,
    subitems: [
      { items: "Somethink" },
      { items: "Somethink" },
      { items: "Somethink" },
    ],
  },
  {
    title: "BARCA TEAMS",
    id: 6,
    com: BarcaTeam,
    subitems: [{ items: "Some" }, { items: "Some" }, { items: "Some" }],
  },
]);
let current_component = shallowRef<tab_el>(tabs_ls[0]);
const nav_click = (item: tab_el) => {
  current_component.value = item;
  console.log("MenuBar", item);
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
