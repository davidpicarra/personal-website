<template>
  <div class="columns">
    <div class="column is-half is-offset-one-quarter is-dark">
      <div class="notification has-text-centered">
        <p class="title">David Piçarra</p>
        <p class="subtitle">Full stack developer</p>
        <figure>
          <img src="https://avatars2.githubusercontent.com/u/5445369?s=460&v=4">
        </figure>
        <div class="social">
          <a href="http://github.com/davidpicarra" target="_blank"><i class="fa fa-github-alt" aria-hidden="true"></i></a>
          <a href="http://linkedin.com/in/davidpicarra" target="_blank"><i class="fa fa-linkedin" aria-hidden="true"></i></a>
          <a href="mailto:daviddcp@gmail.com" target="_blank"><i class="fa fa-envelope" aria-hidden="true"></i></a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'hello'
}
</script>

<style lang="scss">
@import '~bulma';
img {
  border: 2px solid #fff;
  border-radius: 50%;
  background-color: #ecf0f1;
  box-shadow: 0 0px 3px 1px rgba(0,0,0,0.3);
  margin: 8px 0 8px 8px;
  outline: 0;
  width: 120px;
}
.social {
  border-top: 1px solid $dark;
}
.fa {
  font-size: 32px;
  margin: 10px;
  padding: 3px;
}
.fa-github-alt:hover { background-color: #221e1b; color: #fff; }
.fa-linkedin:hover { background-color: #3371b7; color: #fff; }
.fa-envelope:hover { background-color: #FF4136; color: #fff; }
</style>
