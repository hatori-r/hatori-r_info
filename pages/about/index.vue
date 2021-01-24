<template>
  <div class="pages">
    <section class="about-page">
      <h2>about</h2>
      <div class="about-text">
        <h3>name</h3>
        <hr>
          <p class="my-name">Hattori Reiya</p>
        <h3>engineer history</h3>
        <hr>
          <table>
            <tr>
              <td>2020.1 ~</td><td>独学にて学習をはじめました。</td>
            </tr>
            <tr>
              <td>2020.5 ~ 7</td><td>プログラミングスクール（TECH CAMP）で学習を行いました。</td>
            </tr>
          </table>
        <h3>skills</h3>
        <hr>
        <v-container>
          <v-row justify="center">
            <v-col
            cols="12" sm="3" md="2" lg="2"
            >
              <v-card>
                <v-img
                  :src="require('@/static/html.png')">
                </v-img>
                <v-card-title>
                  html
                </v-card-title>
              </v-card>
            </v-col>
            <v-col
            cols="12" sm="3" md="2" lg="2"
            >
              <v-card>
                <v-img
                  :src="require('@/static/css.png')">
                </v-img>
                <v-card-title>
                  css
                </v-card-title>
              </v-card>
            </v-col>
            <v-col
            cols="12" sm="3" md="2" lg="2"
            >
              <v-card>
                <v-img
                  :src="require('@/static/javascript.png')">
                </v-img>
                <v-card-title>
                  javascript
                </v-card-title>
              </v-card>
            </v-col>
            <v-col
            cols="12" sm="3" md="2" lg="2"
            >
              <v-card>
                <v-img
                  :src="require('@/static/jquery.png')">
                </v-img>
                <v-card-title>
                  jQuery
                </v-card-title>
              </v-card>
            </v-col>
            <v-col
            cols="12" sm="3" md="2" lg="2"
            >
              <v-card>
                <v-img
                  :src="require('@/static/haml.png')">
                </v-img>
                <v-card-title>
                  haml
                </v-card-title>
              </v-card>
            </v-col>
            <v-col
            cols="12" sm="3" md="2" lg="2"
            >
              <v-card>
                <v-img
                  :src="require('@/static/sass.png')">
                </v-img>
                <v-card-title>
                  sass
                </v-card-title>
              </v-card>
            </v-col>
            <v-col
            cols="12" sm="3" md="2" lg="2"
            >
              <v-card>
                <v-img
                  :src="require('@/static/ruby.png')">
                </v-img>
                <v-card-title>
                  ruby
                </v-card-title>
              </v-card>
            </v-col>
            <v-col
            cols="12" sm="3" md="2" lg="2"
            >
              <v-card>
                <v-img
                  :src="require('@/static/rails.png')">
                </v-img>
                <v-card-title>
                  rails
                </v-card-title>
              </v-card>
            </v-col>
            <v-col
            cols="12" sm="3" md="2" lg="2"
            >
              <v-card>
                <v-img
                  :src="require('@/static/vue.png')">
                </v-img>
                <v-card-title>
                  vue.js
                </v-card-title>
              </v-card>
            </v-col>
            <v-col
            cols="12" sm="3" md="2" lg="2"
            >
              <v-card>
                <v-img
                  :src="require('@/static/nuxt.png')">
                </v-img>
                <v-card-title>
                  nuxt.js
                </v-card-title>
              </v-card>
            </v-col>
            <v-col
            cols="12" sm="3" md="2" lg="2"
            >
              <v-card>
                <v-img
                  :src="require('@/static/php.png')">
                </v-img>
                <v-card-title>
                  php
                </v-card-title>
              </v-card>
            </v-col>
            <v-col
            cols="12" sm="3" md="2" lg="2"
            >
              <v-card>
                <v-img
                  :src="require('@/static/wordpress.png')">
                </v-img>
                <v-card-title>
                  wordpress
                </v-card-title>
              </v-card>
            </v-col>
            <v-col
            cols="12" sm="3" md="2" lg="2"
            >
              <v-card>
                <v-img
                  :src="require('@/static/mysql.png')">
                </v-img>
                <v-card-title>
                  MySQL
                </v-card-title>
              </v-card>
            </v-col>
            <v-col
            cols="12" sm="3" md="2" lg="2"
            >
              <v-card>
                <v-img
                  :src="require('@/static/aws.png')">
                </v-img>
                <v-card-title>
                  aws
                </v-card-title>
              </v-card>
            </v-col>
            <v-col
            cols="12" sm="3" md="2" lg="2"
            >
              <v-card>
                <v-img
                  :src="require('@/static/github.png')">
                </v-img>
                <v-card-title>
                  GitHub
                </v-card-title>
              </v-card>
            </v-col>
            <v-col
            cols="12" sm="3" md="2" lg="2"
            >
              <v-card>
                <v-img
                  :src="require('@/static/zoom.png')">
                </v-img>
                <v-card-title>
                  ZOOM
                </v-card-title>
              </v-card>
            </v-col>
            <v-col
            cols="12" sm="3" md="2" lg="2"
            >
              <v-card>
                <v-img
                  :src="require('@/static/slack.png')">
                </v-img>
                <v-card-title>
                  slack
                </v-card-title>
              </v-card>
            </v-col>
            <v-col
            cols="12" sm="3" md="2" lg="2"
            >
              <v-card>
                <v-img
                  :src="require('@/static/trello.png')">
                </v-img>
                <v-card-title>
                  trello
                </v-card-title>
              </v-card>
            </v-col>
          </v-row>
        </v-container>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  
}
</script>

<style scoped lang="scss">
  .about-text {
    margin: 0 auto;
    width: 85%;
    h3 {
      padding-left: 30px;
      font-size: 24px;
    }
    p {
      padding: 0 50px;
      margin: 30px 0 130px;
    }
    .my-name {
      font-size: 30px;
    }
    table {
      margin: 30px auto 130px;
      tr {
        td {
          padding: 20px 40px;
        }
      }
    }
    v-row {
      margin: 30px 0;
    }
    v-col {
    }
    .v-card {
      padding: 10px 0 0;
    }
    .v-image {
      height: 60px;
      width: 60px;
      margin: 0 auto;
    }
    .v-card__title {
      font-weight: bold;
      font-size: 16px;
    }
  }
</style>