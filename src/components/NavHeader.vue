<script setup lang="ts">
import 'remixicon/fonts/remixicon.css'
</script>
<template>
  <header>
    <div>
      <img src="@/assets/logo.svg" width="120" alt="" srcset="" />
    </div>

    <div class="links">
      <a href="https://www.github.com/Tiesco789" target="_blank">
        <i class="ri-github-fill"></i>
      </a>
      <a href="https://www.dribbble.com/Franccesco" target="_blank">
        <i class="ri-dribbble-fill"></i>
      </a>
      <a href="https://www.linkedin.com/in/franccesco-bordon" target="_blank">
        <i class="ri-linkedin-fill"></i>
      </a>
      <a href="https://www.behance.com/franccescoantonio" target="_blank">
        <i class="ri-behance-fill"></i>
      </a>
    </div>
  </header>
</template>

<style scoped lang="scss">
header {
  padding: 40px 96px;
  display: flex;
  flex-direction: row;
  justify-content: space-between;

  .links {
    a {
      text-decoration: none;
      color: white;
      padding: 4px;
      background-color: #27272a;
      font-size: 2.5rem;
      border-radius: 4px;
      margin: 8px;

      &:hover {
        background-color: lighten($color: #27272a, $amount: 4);
        transition: .2s;
      }
    }
  }
}
</style>
