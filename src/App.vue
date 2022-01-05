<template>
  <div id="app">
    <section class="hero is-info is-fullheight header-image text-shadow">
      <div class="hero-body">
        <div class="container has-text-centered">
          <h1 class="title big-title">Lucas Chang</h1>
          <p class="subtitle is-2">Student, Programmer, Runner</p>

          <a href="https://github.com/FairfieldBW" target="_blank"><b-icon class="mx-1" icon="github" size="is-large" href="https://diogotc.com/"></b-icon></a>
          <a href="https://twitter.com/FairfieldBW" target="_blank"><b-icon class="mx-1" icon="twitter" size="is-large"></b-icon></a>
          <a href="https://www.youtube.com/channel/UCHXhJzu4eN8CjcPpppsSk_g" target="_blank"><b-icon class="mx-1" icon="youtube" size="is-large"></b-icon></a>
          <a href="https://www.instagram.com/chucas.lang/" target="_blank"><b-icon class="mx-1" icon="instagram" size="is-large"></b-icon></a>
          <a @click="alert()"><b-icon class="mx-1" icon="discord" size="is-large"></b-icon></a>
          <a href="https://www.strava.com/athletes/LucasChang" target="_blank"><b-icon class="mx-1" icon="shoe-sneaker" size="is-large"></b-icon></a>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
  export default {
    methods: {
      alert() {
        this.$buefy.dialog.alert({
            message: `Fairfield#4104`,
            type: 'is-info',
        })
      }
    }
  }
</script>
<!-- <b-button class="mr-4" size="is-medium" type="is-info" rounded outlined inverted>Projects</b-button> -->