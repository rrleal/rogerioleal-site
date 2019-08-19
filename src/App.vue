<template>
      <div id="app">
            <Home></Home>
      </div>
</template>

<script>

import Home from './components/Home.vue'

export default {
    name: 'app',
    components: {
        Home
    }
}
</script>

<style>

    #app {
      margin: 20px 60px;
    }
</style>
