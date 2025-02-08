<template>
  <header class="w-full border-b-[2px] border-[#F3F3F3]">
    <Container>
      <div class="w-full flex items-center justify-between py-3 sm:py-6">
        <div class="flex items-center">
          <!--logo section-->
          <NuxtLink to="/">
            <img
              src="../assets/images/logo.png"
              alt="sitelogo"
              class="w-[92px] h-[35px] sm:w-[130px] sm:h-[42px]"
            />
          </NuxtLink>
        </div>
        <div class="flex items-center">
          <!--menu section-->
          <Menu />
        </div>
        <div class="hidden sm:flex items-center gap-[25px]">
          <!--register-->
          <img src="../assets/icons/user.png" alt="user profile" />
          <img src="../assets/icons/bag-2.png" alt="hopping bag" />
        </div>
      </div>
    </Container>
  </header>
</template>

<script lang="ts" setup>
import Container from "~/layouts/Container.vue";
import Menu from "./Menu.vue";
</script>
