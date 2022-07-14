<template>
  <aside>
    <nav>
      <ul>
        <li>
          <a href="/">Home</a>
        </li>
        <li>
          <a href="#about">About</a>
        </li>
        <li>
          <a href="#projects">Projects</a>
        </li>
        <li>
          <a href="#technologies">Technologies</a>
        </li>
        <li>
          <a href="#contact">Contact me</a>
        </li>
      </ul>
    </nav>
  </aside>
</template>


<style scoped>
  @keyframes slideInFromLeft {
    0% {
      transform: translateX(-100%);
    }
    100% {
      transform: translateX(0);
    }
  }

  aside{
    @apply rounded-3xl z-10 overflow-y-auto p-5 fixed top-1/2 left-10 flex-col items-center justify-center gap-6;

    animation: slideInFromLeft 1.5s ease-in-out;
  }

  li > a{
    @apply text-lg font-semibold uppercase;
  }
</style>