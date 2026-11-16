<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    
    <!-- 1. Твоя шапка -->
    <HeaderComponent />
    
    <!-- 2. Твої попередні повідомлення з пропсами -->
    <MesagComponent title="привіт" mesag="Я Вмію створювати компонент з записом даних у vue" />
    <MesagComponent title="Що ділі?" mesag="Я можу передавати дані у компоненти через props" />

    <!-- 3. Нові візитки за поточним завданням -->
    <BusinessCard 
      name="Michael Kaiser" 
      phone="+38 (099) 123-45-67" 
      email="mihacers@gmail.com" 
    />
  </div>
</template>

<script>
import HeaderComponent from './components/header.vue'
import MesagComponent from './components/MesageComponent.vue'
import BusinessCard from './components/BusinessCard.vue'

export default {
  name: 'App',
  components: {
    HeaderComponent,
    MesagComponent,
    BusinessCard
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  padding-bottom: 50px;
}
</style>