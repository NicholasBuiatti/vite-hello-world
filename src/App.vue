<script>
import HelloWorld from './components/HelloWorld.vue'
// import TheWelcome from './components/TheWelcome.vue'
export default {
  components: {
    HelloWorld
  },
  // data() {
  //   return {
  //     nomeApplicazione: "VitEsempio 0.1"
  //   }
  // },
  // methods: {
  //   //vanno qui, al solito
  // },
  // mounted() {
  //   console.log("App montata");
  // }
}

</script>



<template>
  <header>
    <HelloWorld />
  </header>

  <main>
    <TheWelcome />
  </main>
</template>

<style scoped>

</style>
