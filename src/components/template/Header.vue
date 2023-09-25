<script setup lang="ts">
import HeaderIcon from '../organism/Header/HeaderIcon.vue'
import HeaderActionItemBox from '../organism/Header/HeaderActionItemBox.vue'
import HeaderMenu from '../organism/Header/HeaderMenu.vue'
</script>

<template>
  <div class="md:container md:mx-auto flex space-x-4">
    <HeaderIcon></HeaderIcon>
    <div class="md:container md:mx-auto flex">
      <HeaderActionItemBox></HeaderActionItemBox>
    </div>
    <div class="md:container md:mx-auto flex space-x-4">
      <HeaderMenu></HeaderMenu>
    </div>
  </div>
</template>

<style scoped></style>
