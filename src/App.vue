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
$navbar-item-img-max-height: 3.75rem;
$primary: #2c3e50;
@import '~bulma';
$fa-font-path: '~font-awesome/fonts';
@import '~font-awesome/scss/font-awesome.scss';
</style>
