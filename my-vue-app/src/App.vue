<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HeaderComponent />
  <MesagComponent title="привіт" mesag="Я Вмію створювати компонент з записом даних у vue" />
  <MesagComponent title="Що ділі?" mesag="Я можу передавати дані у компоненти через props" />
</template>

<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HeaderComponent />
    <MesagComponent title="привіт" mesag="Я Вмію створювати компонент з записом даних у vue" />
    <MesagComponent title="Що ділі?" mesag="Я можу передавати дані у компоненти через props" />
  </div>
</template>

<script>
import HeaderComponent from './components/header.vue'
import MesageComponent from './components/MesageComponent.vue';
export default {
  name: 'App',
  components: {
    HeaderComponent,
    MesageComponent
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
