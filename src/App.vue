<template>
  <div id="app">
    <Menu />
    <HeaderVue />
    <ContenedorVue/>
    <PieVue/>
  </div>
</template>

<script>
import Menu from './components/Menu'
import HeaderVue from './components/HeaderVue'
import ContenedorVue from './components/ContenedorVue'
import PieVue from './components/PieVue'

export default {
  name: 'App',
  components: {
    Menu,
    HeaderVue,
    ContenedorVue,
    PieVue,
  }
}
</script>

