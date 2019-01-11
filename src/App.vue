<template>
  <section class="hero is-fullheight">
    <div class="hero-body">
      <div class="container has-text-centered">
        <div class="box">
          <p class="title">
            David Piçarra
          </p>
          <p class="subtitle">
            Full stack developer
          </p>
          <figure>
            <img src="https://avatars2.githubusercontent.com/u/5445369?s=460&v=4">
          </figure>
          <div class="social">
            <a
              href="https://github.com/davidpicarra"
              target="_blank"
            >
              <i
                class="fa fa-github-alt"
                aria-hidden="true"
              />
            </a>
            <a
              href="https://linkedin.com/in/davidpicarra"
              target="_blank"
            >
              <i
                class="fa fa-linkedin"
                aria-hidden="true"
              />
            </a>
            <a
              href="https://keybase.io/davidpicarra"
              target="_blank"
            >
              <i
                class="fa fa-keybase"
                aria-hidden="true"
              />
            </a>
            <a
              href="mailto:daviddcp@gmail.com"
              target="_blank"
            >
              <i
                class="fa fa-envelope"
                aria-hidden="true"
              />
            </a>
          </div>
        </div>
      </div>
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
.box {
  width: 70%;
  margin-left: 15%;
}
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
  color: $dark;
}
.fa-github-alt:hover { background-color: #221e1b; color: #fff; }
.fa-linkedin:hover { background-color: #3371b7; color: #fff; }
.fa-keybase:hover { background-color: rgb(54, 99, 234); color: #fff; }
.fa-envelope:hover { background-color: #FF4136; color: #fff; }
</style>
