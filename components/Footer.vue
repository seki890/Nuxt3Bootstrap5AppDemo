<template>
  <header>
    <nav>
      <ul>
        <li><nuxt-link to="/">ホーム</nuxt-link></li>
        <li><nuxt-link to="/about">About</nuxt-link></li>
        <li><nuxt-link to="/a">Contact</nuxt-link></li>
        <a href="/about">Aboutページへ</a>

      </ul>
    </nav>
  </header>
</template>

<script>
// コンポーネントのロジックやデータがあればここに記述
export default {
  // コンポーネントのプロパティやメソッドなど
};
</script>

<style scoped>
/* ヘッダーのスタイリングがあればここに記述 */
header {
  background-color: #333;
  color: white;
  padding: 10px;
}

.logo img {
  max-width: 100px; /* ロゴの最大幅を指定 */
}

nav ul {
  list-style: none;
  display: flex;
}

nav li {
  margin-right: 20px;
}

nav a {
  text-decoration: none;
  color: white;
}
</style>
