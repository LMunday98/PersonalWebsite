<template>
  <div>
    <head>
		<title>Identity by HTML5 UP</title>
		<meta charset="utf-8" />
	</head>

  <LandingPage/>
  </div>
</template>

<script>
import LandingPage from './pages/LandingPage.vue'

export default {
  name: 'App',
  components: {
    LandingPage
  },
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
}
</style>
