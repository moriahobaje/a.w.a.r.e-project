<template>
 
  <Head>

  </Head>

  <body>
    <div class="sideCar">
      <HomePage></HomePage>
    </div>
    <div id="HomePage">
      <HelloWorld></HelloWorld>
    </div>
  </body>

  <footer>

  </footer>
</template>

<script>
import HomePage from './components/Pages/HomePage.vue';
import HelloWorld from './components/Pages/HelloWorld.vue';
export default {
  name: 'App',
  components: {
    HomePage,HelloWorld
  }
}
</script>