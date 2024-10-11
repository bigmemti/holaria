<script setup lang="ts"></script>

<template lang="pug">
  div
    header
      nav(class="flex justify-between")
        ColorModeButton
        ul(class="flex")
          li 
            UButton(to="/" variant='guest' size="xl") home
          li 
            UButton(to="/" variant='guest' size="xl") login
          li 
            UButton(to="/" variant='guest' size="xl") sign up
          li 
            UButton(to="/" variant='guest' size="xl") dashboard
    slot
</template>

<style scoped lang="scss">

</style>
