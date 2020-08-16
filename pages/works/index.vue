<template>
  <div class="pages">
    <section class="works-page">
      <h2>works</h2>
      <v-container>
        <v-row justify="center">
          <v-col cols="12" sm="4" md="4" lg="4">
            <a href="https://hatori-r.info/">
              <v-card max-width="380">
                <v-img
                  :src="require('@/static/hatoriblog.png')"
                  class="white--text align-end hatoriblog"
                  >
                  </v-img>
                  <v-card-title class="headline">
                    hatori info
                  </v-card-title>
                <v-card-text>
                  当サイトです。
                </v-card-text>
              </v-card>
            </a>
          </v-col>
          <v-col cols="12" sm="4" md="4" lg="4">
            <a href="https://hatoriblog.com/">
              <v-card max-width="380">
                <v-img
                  :src="require('@/static/hatoriblog.png')"
                  class="white--text align-end hatoriblog"
                  >
                  </v-img>
                  <v-card-title class="headline">
                    hatoriblog
                  </v-card-title>
                <v-card-text>
                  ブログサイトを運営しております。
                </v-card-text>
              </v-card>
            </a>
          </v-col>
          <v-col cols="12" sm="4" md="4" lg="4">
            <a href="http://ourtask.tokyo/">
              <v-card max-width="380">
                <v-img
                  :src="require('@/static/ourtask.png')"
                  height="200px"
                  width="100%"
                  class="white--text align-end ourtask"
                  >
                  </v-img>
                  <v-card-title class="headline">
                    our task
                  </v-card-title>
                <v-card-text>
                  自分のタスクを投稿し、他のユーザーに共有することが出来るアプリです。
                </v-card-text>
              </v-card>
            </a>
          </v-col>
        </v-row>
      </v-container>
    </section>
  </div>
</template>

<script>
export default {
  
}
</script>

<style scoped lang="scss">
  v-container {
    display: grid;
    place-items: center;
  }
</style>

<style scoped lang="scss">
.v-card {
  min-height: 380px;
}
  .hatoriblog {
    margin: 20px auto 0;
    max-height: 200px;
    max-width: 200px;
  }
  .ourtask {
    margin: 20px auto 0;
    max-height: 200px;
    .v-image__image {
      margin-top: 90px;
    }
  }
</style>