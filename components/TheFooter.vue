<template>
  <v-footer color="blue-grey darken-3" dark app>
    <v-col
      class="text-center"
      >
        {{ new Date().getFullYear() }} - <strong>©hatori info</strong>
      </v-col>
  </v-footer>
</template>

<style scoped lang="scss">
  .text-center,
  strong {
    font-size: 14px;
    letter-spacing: 0.05em;
  }
</style>