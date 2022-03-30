<template>
  <div>
    <page-header></page-header>
    <nav></nav>
    <main>
      <about class="section"></about>
      <articles class="section"></articles>
      <works class="section"></works>
      <contact-me class="section"></contact-me>
    </main>
    <page-footer></page-footer>
  </div>
</template>

<script>
import ContactMe from "../components/ContactMe.vue";
import PageFooter from "../components/PageFooter.vue";
import PageHeader from "../components/PageHeader.vue";
import SectionTitle from "../components/SectionTitle.vue";
export default {
  components: { ContactMe, PageFooter, PageHeader, SectionTitle },
  name: "IndexPage",
};
</script>

<style>
body {
  margin: 0px;
}
</style>

<style scoped>
.section {
  margin: 50px 0px;
}
</style>