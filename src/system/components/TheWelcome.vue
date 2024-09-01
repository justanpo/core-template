<script setup>
import WelcomeItem from './WelcomeItem.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      1
    </template>
    <template #heading>One</template>

    text
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      2
    </template>
    <template #heading>Two</template>

    text text
  </WelcomeItem>
</template>
