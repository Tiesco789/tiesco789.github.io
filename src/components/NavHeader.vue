<script setup lang="ts">
import 'remixicon/fonts/remixicon.css'
</script>
<template>
  <header>
    <div>
      <img src="@/assets/logo.svg" width="120" alt="" srcset="" />
    </div>

    <div class="links">
      <a href="">Portifolio</a>
      <a href="">Prints</a>
      <a href="">Draws</a>
      <a href="">Tattoo</a>
      <a href="">Tapes</a>
    </div>

    <div class="buttons">
      <a href="https://www.linkedin.com/in/franccesco-bordon" target="_blank">
        <i class="ri-linkedin-fill"></i>
      </a>
      <a href="https://www.behance.com/franccescoantonio" target="_blank">
        <i class="ri-behance-fill"></i>
      </a>
      <a href="https://www.dribbble.com/Franccesco" target="_blank">
        <i class="ri-dribbble-fill"></i>
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
    color: #A8A8B3;
    font: 800 1rem 'Nunito Sans';
    align-self: center;

    a {
      color: #A8A8B3;
      text-decoration: none;
      margin: 2.25rem;

      &:hover {
        color: darkviolet;
      }
    }
  }
  .buttons {
    a {
      text-decoration: none;
      color: white;
      padding: 8px;
      background-color: #1F2729;
      font-size: 1.5rem;
      border-radius: 4px;
      margin: 8px;

      &:hover {
        background-color: darkviolet;
        transition: .2s background-color ease-in;
      }
    }
  }
}
</style>
