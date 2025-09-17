<template>
  <div id="app">
    <nav class="nav"></nav>

    <main class="hero">
      <h1 class="hero-title">We will coming soon!</h1>
      <p class="hero-subtitle">
        如果你有任何疑问或者希望投稿可以在项目提交issue或者发送相关信息到管理员邮箱
      </p>
    </main>

    <footer class="footer"></footer>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
}

.nav {
  height: 60px;
  background-color: #f8f9fa;
}

.hero {
  flex: 1;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 2rem;
}

.hero-title {
  font-size: 3rem;
  font-weight: bold;
  margin-bottom: 1rem;
  color: #333;
}

.hero-subtitle {
  font-size: 1.2rem;
  color: #666;
  max-width: 600px;
  line-height: 1.6;
}

.footer {
  height: 60px;
  background-color: #f8f9fa;
}
</style>