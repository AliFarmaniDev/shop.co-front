<script setup>
import Container from "@/layouts/Container.vue";
</script>

<template>
  <header class="w-full">
    <div class="w-full h-[36px] bg-black flex items-center justify-center">
      <span class="text-white text-[12px] md:text-[14px] font-medium"
        >Sign up and get 20% off to your first order. Sign Up Now</span
      >
    </div>
    <Container>
      <div class="w-full flex justify-between">
        <div class="flex items-center">
          <!--logo section-->
          <RouterLink to="/">
            <img src="../assets/images/logo.png" alt="site logo" class="" />
          </RouterLink>
        </div>
        <div class="flex items-center">
          <!--men u sections-->
        </div>
        <div class="">
          <!--search box-->
        </div>
        <div class="">
          <!--register box-->
        </div>
      </div>
    </Container>
  </header>
</template>
