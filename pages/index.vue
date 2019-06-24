<template>
  <div class="container">
    <header id="header">
      <a href="https://twitter.com/koluku">
        <img id="logo" src="../static/koluku.png" alt="logo" />
      </a>
      <h1 id="title">koluku.com</h1>
    </header>
  </div>
</template>

<style lang="scss">
@import url('https://fonts.googleapis.com/css?family=Patua+One&display=swap');

#header {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 100%;
}

#logo {
  width: 200px;
  height: 200px;
  background: #fff;
  border-radius: 50%;
  border: solid 5px #fff;
}

#title {
  color: #fff;
  font-size: 3.5rem;
  font-family: 'Patua One', cursive;
  margin: 0;
}
</style>
