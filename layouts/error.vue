<template>
  <div class="pages">
    <section class="error-page">
      <h2>404</h2>
        <div class="error-text">
          <h3>sorry...</h3>
          <p>アクセスされたページは存在しないか、削除されています。</p>
        </div>
    </section>
  </div>
</template>

<script>

</script>

<style scoped lang="scss">
  .error-page {
    .error-text {
      width: 750px;
      margin: 0 auto;
      h3 {
        font-size: 30px;
        padding-left: 60px;
        margin: 0 0 20px;
        letter-spacing: 0.1em;
        font-weight: bold;
        font-family: 'Oswald', sans-serif;
      }
      p {
        text-align: center;
        font-size: 16px;
        letter-spacing: 0.1em;
        color: #757575;
        font-family: "M PLUS Rounded 1c";
      }
    }
  }
</style>
