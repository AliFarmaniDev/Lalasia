<template>
  <Container>
    <div class="w-full bg-[url(/assets/images/searchbg.png)] bg-cover h-[140px] sm:h-[480px] my-4 sm:my-10">
      <div class="flex items-center justify-between w-full sm:w-[810px] sm:h-[70px] bg-[#FFFFFF] relative sm:left-[190px] top-[-50px] sm:top-[-40px] px-2 my-[80px] sm:my-[40px]">
        <!--search box-->
        <img src="../assets/icons/search-normal.png" alt="search" />
        <input type="search" value="search here"  class="w-full h-full px-3 text-title-3"/>
        <button class="capitalize flex justify-center items-center text-white sm:w-[170px] sm:h-[54px] bg-primary-1 font-medium w-[100px] h-[38px]">search</button>
      </div>
    </div>
  </Container>
</template>

<script lang="ts" setup>
import Container from "~/layouts/Container.vue";
</script>
