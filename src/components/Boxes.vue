<template>
  <section id="boxes" class="content-section">
    <h2>Boxes</h2>
    <div class="boxes-container">
      <article class="box">
        <h3>🎵 Música Favorita</h3>
        <ul>
          <li>Daft Punk - Random Access Memories</li>
          <li>The Strokes - Is This It</li>
          <li>Gorillaz - Demon Days</li>
        </ul>
      </article>
      <article class="box">
        <h3>🎬 Películas Recientes</h3>
        <ul>
          <li>Dune: Part Two</li>
          <li>Oppenheimer</li>
          <li>Past Lives</li>
        </ul>
      </article>
      <article class="box">
        <h3>📝 Notas</h3>
        <p>Un breve pensamiento sobre el desarrollo web: la simplicidad es la máxima sofisticación. Usar las herramientas adecuadas para cada trabajo es clave.</p>
        <a href="#">Leer más</a>
      </article>
      <article class="box">
        <h3>🎮 Videojuegos</h3>
        <p>Actualmente jugando a The Legend of Zelda: Tears of the Kingdom y Baldur's Gate 3.</p>
      </article>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Boxes'
}
</script>

<style scoped>
.content-section {
  display: none;
}

.content-section.active {
  display: block;
}

.boxes-container {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
  gap: 20px;
}

.box {
  border: 1px solid #ddd;
  border-radius: 8px;
  padding: 20px;
  background-color: #f9f9f9;
  box-shadow: 0 1px 3px rgba(0, 0, 0, 0.05);
}

.box h3 {
  margin-top: 0;
  font-size: 16px;
  color: #4267B2;
  border-bottom: 1px solid #eee;
  padding-bottom: 10px;
  margin-bottom: 15px;
}

.box ul {
  list-style: none;
  padding: 0;
  margin: 0;
  font-size: 14px;
}

.box ul li {
  padding: 5px 0;
}

.box p {
  font-size: 14px;
  line-height: 1.5;
}

.box a {
  color: #4267B2;
  text-decoration: none;
  font-weight: bold;
  font-size: 14px;
}

.box a:hover {
  text-decoration: underline;
}
</style>