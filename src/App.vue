<template>
  <Header intro="I am Ishan, a Full-Stack Developer"></Header>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';
import Header from './components/header.vue';
//import { auth, db } from './firebase';
//console.log(auth)
@Options({
  components: {
    Header,
  },
})

export default class App extends Vue {}
</script>
<style type="text/css" media="all">
 /* * {
    box-sizing: border-box;
    padding: 0;
    margin: 0;
  }*/
</style>