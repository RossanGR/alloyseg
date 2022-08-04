<script>
import MenuHeader from './components/MenuHeader.vue'
import MenuContainer from './components/MenuContainer.vue'
import QuemSomos from './components/QuemSomos.vue'
import AreaSolucoes from './components/AreaSolucoes.vue'
import SectionServicos from './components/SectionServicos.vue'
import AreaForm from './components/AreaForm.vue'
import AreaFaq from './components/AreaFaq.vue'
import AreaFooter from './components/AreaFooter.vue'

export default {
  name: 'App',
  components: {
    MenuHeader,
    MenuContainer,
    QuemSomos,
    AreaSolucoes,
    SectionServicos,
    AreaForm,
    AreaFaq,
    AreaFooter
  }
}
</script>

<template>
  <div id="app">
    <header class="background--header">
      <MenuHeader />
      <MenuContainer />
    </header>
    <main>
      <QuemSomos />
      <AreaSolucoes />
      <SectionServicos />
      <AreaForm />
      <AreaFaq />
      <AreaFooter />
    </main>
  </div>
</template>

<style>
.background--header {
  background-image: url(./assets/home_desk.png);
  background-position: center bottom;
  background-repeat: no-repeat;
}


#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

.menu__container__h1--arrow,.arrow {
  position: relative;
  animation-name: animation;
  animation-duration: .75s;
  animation-direction: alternate-reverse;
  animation-iteration-count: infinite;
}
@keyframes animation {
  0%   { left:0px; bottom:0px;}
  100% { left:0px; bottom:20px;}
}

</style>
