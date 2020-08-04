<template>
  <v-content>
    <v-navigation-drawer app v-model="drawer" clipped>
      <v-container>
        <v-list-item>
          <v-list-item-content>
            <v-list-item-title
              class="list-title title text-center gray--text text--darken-2"
              @click="drawer=!drawer"
              >
                hatori info
              </v-list-item-title>
          </v-list-item-content>
        </v-list-item>
        <v-divider></v-divider>
      </v-container>
        <ul class="half-window">
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
    <v-app-bar color="grey lighten-5" app clipped-left>
      <v-app-bar-nav-icon @click="drawer=!drawer"></v-app-bar-nav-icon>
      <v-toolbar-title>
        <h1>
          hatori info
        </h1>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <ul class="full-window">
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
    </v-app-bar>
  </v-content>
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

<style scoped lang="scss">
.v-app-bar {
  padding-top: 10px;
  padding-bottom: 70px;
}

.list-title {
  padding-bottom: 14px;
  line-height: 30px;
  cursor: pointer;
}

h1 {
  font-size: 35px;
  color: #3f3f3f;
  font-weight: bold;
  letter-spacing: 0.02em;
}

.half-window {
  li {
    display: block;
    padding: 22px 0 22px 25px;
    font-weight: bold;
    letter-spacing: 0.03em;
    transition: all 0.2s;
    &:hover {
      transition: all 0.2s;
      text-shadow: 0 0 5px #abcdd3;
    }
  }
}

.full-window {
  display: flex;
  li {
    padding-left: 40px;
    font-weight: bold;
    letter-spacing: 0.03em;
    transition: all 0.2s;
    &:hover {
      transition: all 0.2s;
      text-shadow: 0 0 5px #abcdd3;
    }
    &:last-child {
      padding-right: 120px;
    }
  }
}

  @media screen and (min-width: 860px) {
    nav.v-navigation-drawer {
      display: none!important;
    }
    .v-app-bar__nav-icon {
      display: none!important;
    }
  }

  @media screen and (max-width: 860px) {
    .full-window {
      display: none;
    }
  }
</style>