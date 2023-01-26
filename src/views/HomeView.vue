<template>
  <div>
    <page-header></page-header>
    <main-page></main-page>
  </div>
</template>

<script>
import MainPage from "@/components/MainPage.vue";
import PageHeader from "@/components/PageHeader.vue";

export default {
  components: {
    MainPage,
    PageHeader,
  },
};
</script>
