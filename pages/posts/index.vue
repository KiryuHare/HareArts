<template>
  <article>
    <h1>{{ post.title }}</h1>
    <nuxt-content :document="post" />
  </article>
</template>

<script>
export default {
  async asyncData ({ $content }) {
    return {
      post: await $content('home').fetch()
    }
  }
}
</script>