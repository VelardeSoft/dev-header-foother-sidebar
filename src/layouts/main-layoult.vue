<template>
  <div class="layout">
    <TheHeader />
    <div class="main-content">
      <the-sidebar />
    </div>
    <TheFooter />
  </div>
</template>

<script setup>
import TheHeader from "@/layouts/the-header.vue";
import TheFooter from "@/layouts/the-footer.vue";
import TheSidebar from "@/layouts/the-sidebar.vue";
</script>

<style scoped>
.layout {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}
.main-content {
  width: 100%;
  display: flex;
  flex: 1;
}
</style>