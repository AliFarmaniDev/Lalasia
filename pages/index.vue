<template>
  <div>
    <MainBaner />
  </div>
  <div>
    <SearchBox />
  </div>
</template>

<script lang="ts" setup>
//import components
import MainBaner from '~/components/MainBaner.vue';
import SearchBox from '~/components/SearchBox.vue';
//seo
useSeoMeta({
  title: "home page",
  description: "this is home page"
});
</script>
