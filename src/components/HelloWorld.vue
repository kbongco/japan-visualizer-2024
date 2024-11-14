<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h3>
      Hello this is a mini project I created with Vue! I wanted to get some Vue practice in since that is what I am currently learning and I just got back from a trip in Japan so I decided to create this.<br/>
      <div class="social-links">
      <a href="http://github.com/kbongco" target="_blank" rel="noopener">Github</a> +
      <a href="https://www.linkedin.com/in/kathleen-bongco-11843197/" target="_blank" rel="noopener">LinkedIn</a>
      </div>
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: left;
}

.social-links {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
