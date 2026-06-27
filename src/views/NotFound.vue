<template>
  <div class="not-found">
    <header>
      <h1>404</h1>
    </header>
    <p>Page Not Found.</p>
    <p>
      <router-link to="/">Return to the main page</router-link>
    </p>
  </div>
</template>

<script>
export default {
  name: 'NotFound'
}
</script>

<style scoped>
.not-found {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
  padding: 40px 20px;
  background: #f8f9fb;
  color: #222;
}
.not-found h1 {
  font-size: 5rem;
  margin: 0 0 20px;
}
.not-found a {
  color: #1a73e8;
  text-decoration: none;
}
.not-found a:hover {
  text-decoration: underline;
}
</style>
