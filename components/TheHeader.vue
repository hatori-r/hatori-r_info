<template>
  <v-app>
    <v-navigation-drawer app v-model="drawer" clipped>
      <ul>
        <li>
          <nuxt-link to="/">top</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/about">about</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/works">works</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/contact">contact</nuxt-link>
        </li>
      </ul>
    </v-navigation-drawer>
    <v-app-bar color="blue-grey lighten-5" app clipped-left>
      <v-app-bar-nav-icon @click="drawer=!drawer"></v-app-bar-nav-icon>
      <v-toolbar-title>hatori</v-toolbar-title>
    </v-app-bar>
  </v-app>
</template>

<script>
export default {
  data() {
    return {
      drawer: null
    }
  }
}
</script>