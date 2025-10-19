<template>
  <section id="muro" class="content-section active">
    <div class="post-creator">
      <textarea placeholder="Pon algo aquí..."></textarea>
      <button>Compartir</button>
    </div>
    <div class="post">
      <p><strong>Nombre</strong> - Lunes a las 8:45pm</p>
      <p>Este es un ejemplo de una publicación en el muro. ¡Hola mundo!</p>
    </div>
    <div class="post">
      <p><strong>Nombre</strong> - Domingo a las 11:46pm</p>
      <p>Otra publicación para simular el feed de noticias.</p>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Muro'
}
</script>

<style scoped>
.content-section {
  display: none;
}

.content-section.active {
  display: block;
}

.post-creator {
  margin-bottom: 20px;
}

.post-creator textarea {
  width: 100%;
  height: 60px;
  padding: 10px;
  border: 1px solid #ddd;
  border-radius: 5px;
  box-sizing: border-box;
}

.post {
  border: 1px solid #ddd;
  padding: 15px;
  border-radius: 5px;
  margin-top: 15px;
}
</style>