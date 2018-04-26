<template>
  <section class="section">
    <div class="container">
      <router-view></router-view>
    </div>
  </section>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style lang="scss">
@import '~bulma';
$fa-font-path: '~fork-awesome/fonts';
@import '~fork-awesome/scss/fork-awesome.scss';
</style>
