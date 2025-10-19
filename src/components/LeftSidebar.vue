<template>
  <aside class="left-sidebar">
    <div class="profile-intro">
      <div class="profile-pic-placeholder"></div>
      <h3>Nombre de Usuario</h3>
      <p>Información breve sobre el usuario.</p>
    </div>
    <div class="friends-box">
      <h4>Amigos</h4>
      <div class="friends-grid">
        <div class="friend-placeholder"></div>
        <div class="friend-placeholder"></div>
        <div class="friend-placeholder"></div>
        <div class="friend-placeholder"></div>
        <div class="friend-placeholder"></div>
        <div class="friend-placeholder"></div>
      </div>
    </div>
  </aside>
</template>

<script>
export default {
  name: 'LeftSidebar'
}
</script>

<style scoped>
.left-sidebar .profile-intro,
.left-sidebar .friends-box {
  background-color: #FFFFFF;
  padding: 15px;
  border-radius: 8px;
  margin-bottom: 20px;
}

.profile-pic-placeholder {
  width: 80px;
  height: 80px;
  background-color: #ccc;
  border-radius: 50%;
  margin: 0 auto 10px;
}

.friends-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 10px;
}

.friend-placeholder {
  width: 100%;
  height: 60px;
  background-color: #e0e0e0;
  border-radius: 8px;
}
</style>