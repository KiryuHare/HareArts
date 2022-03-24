<template>
  <div>
    <PageHeader></PageHeader>
    <main>
      <div>HareArtsは気流ハレによる個人ゲーム開発サークルです。</div>
      <div>
        <p>制作したゲーム:</p>
        <div class="games">
          <p class="games-title">-影-</p>
          <p>
            <a href="https://kiryuhare.github.io/silhouette/">公式サイト</a>
          </p>
        </div>
      </div>
      <div>
        <p>リンク:</p>
        <div class="links">
          <p><a href="https://twitter.com/kiryuhare">Twitter</a></p>
          <p><a href="https://www.youtube.com/channel/UCdjlHOEzIR-BjA-phDUEnAA">Youtube</a></p>

        </div>
      </div>
    </main>
    <PageFooter></PageFooter>
  </div>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>

<style>
body {
  margin: 0px;
}
</style>

<style scoped>
main {
  margin: 1rem 5%;
}
.games {
  margin: 0px 1rem;
  padding: 0px 5%;
  border-style: ridge;
  background-color: bisque;
}
.games-title {
  font-size: 1.3rem;
}
.links {
  margin: 0px 1rem;
  padding: 0px 5%;
}
</style>