<template>
  <div class="pages">
    <section class="works-page">
      <h2>works</h2>
      <v-container>
        <v-row>
          <v-col cols="12" sm="6" md="4" lg="3">
            <v-card max-width="380">
              <v-img
                :src="require('@/static/hatoriblog.png')"
                height="250"
                class="white--text align-end"
                >
                </v-img>
                <v-card-title class="headline">
                  our task
                </v-card-title>
              <v-card-text>
                自分のタスクを投稿し、他のユーザーに
                <br>
                共有することが出来るアプリです。
              </v-card-text>
            </v-card>
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