<template>
  <div>
    <div
      style="border: 2px solid #ccc; margin: 0rem auto 2rem auto; width: 77%;"
      class="round nav w-mar-bottom grid_1-5"
    >
      <div
        v-for="tab in tabs"
        :key="tab"
        :class="['tab-button', { active: currentTab === tab }]"
        @click="currentTab = tab"
      >
        <h6 class="nav-title">
          {{ tab }}
        </h6>
      </div>
    </div>
    <component :is="currentTabComponent" class="tab fade-in"></component>
  </div>
</template>
<script>
import Services from "./Services";
import Contact from "./Contact";
import Work from "./Work";
import About from "./About";
import Rates from "./Rates";

export default {
  components: {
    Contact,
    Work,
    Services,
    About,
    Rates,
  },
  data() {
    return {
      currentTab: "Contact",
      tabs: ["Contact", "About", "Work", "Services", "Rates"],
    };
  },
  computed: {
    currentTabComponent: function() {
      return this.currentTab;
    },
  },
};
</script>
<style scoped lang="scss">
h6 {
  margin: auto;
  margin-top: 1rem !important;
  &:hover {
    background-color: $color-2;
  }
}
.active > h6 {
  width: min-content;
  background-color: $color-3;
  color: $white;
}
</style>
