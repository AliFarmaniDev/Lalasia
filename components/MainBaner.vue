<template>
  <div class="w-full mt-[35px] sm:mt-[60px]">
    <Container>
      <div class="w-full flex flex-col items-center">
        <div class="flex items-center justify-center sm:w-[644px] w-full">
          <h2 class="flex text-wrap text-title-1 font-bold capitalize text-[26px] sm:text-[50px] text-center">discover furniture with high quality wood</h2>
          <img src="../assets/images/stars.png" alt="stars" class="relative sm:top-[40px] sm:right-[55px] h-[24px] w-[24px] sm:w-[51px] sm:h-[51px] top-[23px] right-[38px]">
        </div>
        <div class="flex justify-center items-center w-full sm:w-[644px] my-3 sm:my-4">
          <img src="../assets/images/Vector.png" alt="vector image" class=" relative sm:right-[40px] w-[47px] h-[44px] sm:w-[49px] sm:h-[131px]">
          <p class="text-wrap text-center text-pragraph-1 flex justify-center items-center sm:w-[640px]">Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquam expedita ut magnam! Debitis labore, iure blanditiis omnis similique magni enim.</p>
        </div>
      </div>
    </Container>
  </div>
</template>

<script lang="ts" setup>
import Container from '~/layouts/Container.vue';
import SearchBox from './SearchBox.vue';
</script>