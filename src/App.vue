<template>
  <div id="container">
    <header id="header">
      <Title/>
    </header>
    <main id="main">
      <Profile/>
      <Works/>
    </main>
    <footer id="footer">
      <Footer/>
    </footer>
  </div>
</template>

<script>
import Title from "./components/Title.vue";
import Profile from "./components/Profile.vue";
import Works from "./components/Works.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "app",
  components: {
    Title,
    Profile,
    Works,
    Footer,
  },
};
</script>

<style lang="scss">
html, body {
  background: url("./assets/qbkls.png");
  color: #222;
  font-size: 16px;
}

#container {
  display: flex;
  flex-direction: column;
  max-width: 900px;
  margin: 0 auto;
}

.card {
  box-sizing: border-box;
  margin: 1rem 0;
  padding: 1rem;
  background: #fff;
  border: solid 1px #ddd;
  border-radius: 3px;
 
  h1, h2 {
    @import url('https://fonts.googleapis.com/css?family=Forum');
    font-family: 'Forum', cursive;
    text-align: center;
  }

  h1 {
    font-size: 3rem;
  }

  h2 {
    font-size: 2rem;
  }
}
</style>
