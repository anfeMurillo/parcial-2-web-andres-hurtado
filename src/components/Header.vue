<template>
  <header class="main-header">
    <div class="logo"><img src="../assets/logo.png" alt="Logo" style="height:40px;"></div>
    <div class="search-bar">
      <input type="text" placeholder="Buscar...">
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style scoped>
.main-header {
  background-color: #4267B2;
  color: #FFFFFF;
  padding: 10px 20px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.main-header .logo {
  font-size: 24px;
  font-weight: bold;
}

.main-header .search-bar input {
  width: 250px;
  padding: 8px;
  border: none;
  border-radius: 5px;
}
</style>