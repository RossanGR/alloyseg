<script>
import MenuHeader from './components/MenuHeader.vue'
import MenuContainer from './components/MenuContainer.vue'

export default {
  name: 'App',
  components: {
    MenuHeader,
    MenuContainer
  }
}
</script>

<template>
  <div id="app">
    <header>
      <MenuHeader />
        <MenuContainer />
    </header>
    <main>
      
    </main>
  </div>
</template>

<style>
header {
  background-image: url(@/assets/media/home_desk.png);
  background-position: center top;
  background-repeat: no-repeat;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
