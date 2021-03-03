<template>
  <header>
      <p class="intro intro-anim">{{intro}}</p>
  </header>
</template>
<style lang="scss">
@import '../assets/scss/style.scss'
</style>
<script>
import { Options, Vue } from 'vue-class-component';

@Options({
  props: {
   intro: String
  }
})
export default class Header extends Vue {}
</script>