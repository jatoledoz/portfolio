<template>
  <header>
    <p class="text-3xl">Jorge Zarpão</p>
    <p class="text-lg">Full stack developer</p>

  </header>
</template>

<script>
export default {

}
</script>

<style scoped>
  @keyframes slideInFromLeft {
    0% {
      transform: translateX(-100%);
    }
    100% {
      transform: translateX(0);
    }
  }
  header{
    @apply bg-slate-500 text-white p-4;
  }
  p{
    animation: slideInFromLeft 1.5s ease-in-out;
  }
</style>