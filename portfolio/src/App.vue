<template>
  <MyHero></MyHero>
  <navbar></navbar>
  <MyProjects></MyProjects>
</template>

<script>
import MyHero from './components/home/MyHero.vue'
import navbar from './components/navbar.vue'
import MyProjects from './components/home/MyProjects.vue'


export default {

  name: 'App',
  components: { MyHero , navbar , MyProjects,  }
}
</script>

<style>



</style>
