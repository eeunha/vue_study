<!-- Tabs.vue -->
<template>
  <div id="tabs">
    <button
      v-for="(tab, index) in tabs"
      v-bind:key="index"
      :class="{ active: currentTab === index }"
      @click="currentTab = index"
    >
      {{ tab }}
    </button>
    <div class="tab-content">
      <div v-show="currentTab === 0">tab content1</div>
      <div v-show="currentTab === 1">tab content2</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Tabtab_",
  data() {
    return {
      currentTab: 0,
      tabs: ["tab title1", "tab title2"],
    };
  },
};
</script>

<style>
/* 필요한 스타일 */
</style>
