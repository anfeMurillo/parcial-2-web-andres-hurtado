<template>
  <div id="app">
    <Header />
    <div class="page-container">
      <LeftSidebar />
      <MainContent />
    </div>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import LeftSidebar from './components/LeftSidebar.vue'
import MainContent from './components/MainContent.vue'

export default {
  name: 'App',
  components: {
    Header,
    LeftSidebar,
    MainContent
  }
}
</script>

<style>
:root {
  --primary-color: #4267B2;
  --background-color: #F0F2F5;
  --white-color: #FFFFFF;
  --border-color: #ddd;
}

body {
  font-family: Arial, sans-serif;
  margin: 0;
  background-color: var(--background-color);
  color: #333;
}

.page-container {
  display: grid;
  grid-template-columns: 1fr 2.5fr;
  gap: 20px;
  padding: 20px;
  max-width: 1200px;
  margin: auto;
}
</style>