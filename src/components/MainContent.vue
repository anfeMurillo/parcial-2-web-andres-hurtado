<template>
  <main class="main-content">
    <nav class="profile-nav">
      <ul>
        <li><router-link to="/" class="nav-link">Muro</router-link></li>
        <li><router-link to="/info" class="nav-link">Info</router-link></li>
        <li><router-link to="/photos" class="nav-link">Photos</router-link></li>
        <li><router-link to="/boxes" class="nav-link">Boxes</router-link></li>
      </ul>
    </nav>
    <div class="content-sections">
      <router-view></router-view>
    </div>
  </main>
</template>

<script>
export default {
  name: 'MainContent'
}
</script>

<style scoped>
.main-content {
  background-color: #FFFFFF;
  padding: 20px;
  border-radius: 8px;
}

.profile-nav ul {
  list-style: none;
  padding: 0;
  margin: 0 0 20px 0;
  display: flex;
  border-bottom: 1px solid #ddd;
}

.profile-nav li a {
  text-decoration: none;
  color: #4267B2;
  padding: 10px 20px;
  display: block;
  font-weight: bold;
}

.profile-nav li a.router-link-exact-active {
  border-bottom: 3px solid #4267B2;
  color: #333;
}
</style>