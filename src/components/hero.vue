<template>
  <section class="hero">
    <p class="hello">👋 Olá, eu sou</p>
    <h1>Rômulo Santos</h1>
    <h2>Desenvolvedor Front-end</h2>

    <p class="description">
      Crio interfaces modernas, responsivas e focadas em performance
      utilizando Vue.js e tecnologias web atuais.
    </p>

    <div class="actions">
      <a href="#projects" class="btn primary">Ver projetos</a>
      <a href="#contact" class="btn outline">Contato</a>
    </div>
  </section>
</template>

<script setup>
import profile from '../assets/IMG-20250407-WA0027.jpg'
</script>

  <img :src="profile" alt="Minha foto" />

<style scoped>
.hero {
  min-height: 100vh;
  padding: 40px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  gap: 16px;
}

h1 {
  font-size: 3rem;
}

h2 {
  font-weight: 400;
  color: #42b883;
}

.description {
  max-width: 600px;
}

.actions {
  display: flex;
  gap: 12px;
  margin-top: 16px;
}

.btn {
  padding: 10px 18px;
  border-radius: 6px;
  text-decoration: none;
  font-weight: 500;
}

.primary {
  background: #42b883;
  color: #fff;
}

.outline {
  border: 1px solid #42b883;
  color: #42b883;
}

</style>


