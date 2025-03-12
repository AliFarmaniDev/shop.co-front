<script setup>
import { ref } from "vue";
let isActive = ref("home");
let drowMenu = ref(false);
</script>

<template>
  <div>
    <div class="flex sm:hidden">
      <!--mobile menu-->
      <button></button>
      <nav class=""></nav>
    </div>
    <div class="hidden sm:flex items-center justify-between">
      <!--desctop menu-->
      <nav class="flex items-center gap-[23px]">
        <RouterLink to=""></RouterLink>
      </nav>
    </div>
  </div>
</template>
