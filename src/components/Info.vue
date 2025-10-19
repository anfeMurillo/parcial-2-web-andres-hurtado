<template>
  <section id="info" class="content-section">
    <h2>Información</h2>
    <ul>
      <li><strong>Email:</strong> usuario@example.com</li>
      <li><strong>Teléfono:</strong> +123 456 7890</li>
      <li><strong>Intereses:</strong> Programación, diseño web, café.</li>
      <li><strong>Situación sentimental:</strong> Es complicado.</li>
    </ul>
  </section>
</template>

<script>
export default {
  name: 'Info'
}
</script>

<style scoped>
.content-section {
  display: none;
}

.content-section.active {
  display: block;
}

#info ul {
  list-style: none;
  padding: 0;
}

#info li {
  padding: 8px 0;
}
</style>