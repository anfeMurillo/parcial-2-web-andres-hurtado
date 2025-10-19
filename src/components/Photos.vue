<template>
  <section id="photos" class="content-section">
    <h2>Fotos</h2>
    <div class="photo-grid">
      <div class="photo-placeholder"></div>
      <div class="photo-placeholder"></div>
      <div class="photo-placeholder"></div>
      <div class="photo-placeholder"></div>
      <div class="photo-placeholder"></div>
      <div class="photo-placeholder"></div>
      <div class="photo-placeholder"></div>
      <div class="photo-placeholder"></div>
      <div class="photo-placeholder"></div>
      <div class="photo-placeholder"></div>
      <div class="photo-placeholder"></div>
      <div class="photo-placeholder"></div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Photos'
}
</script>

<style scoped>
.content-section {
  display: none;
}

.content-section.active {
  display: block;
}

.photo-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(120px, 1fr));
  gap: 10px;
}

.photo-placeholder {
  width: 100%;
  padding-top: 100%;
  background-color: #e0e0e0;
  border-radius: 8px;
}
</style>