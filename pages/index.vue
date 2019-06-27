<template>
  <div class="container">
    <header id="header">
      <img id="logo" src="../static/koluku.png" alt="logo" />
      <h1 id="title">koluku.com</h1>
      <ul id="social">
        <a href="https://twitter.com/koluku">
          <li>
            <font-awesome-icon :icon="['fab', 'twitter']" />
          </li>
        </a>
        <a href="https://github.com/koluku">
          <li>
            <font-awesome-icon :icon="['fab', 'github']" />
          </li>
        </a>
        <a href="https://koluku.hateblo.jp">
          <li>
            <font-awesome-icon icon="rss" />
          </li>
        </a>
      </ul>
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
  margin: 20px 0;
}

#social {
  margin: 0;
  margin-top: 10px;
  padding: 0;
  list-style: none;

  li {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 5rem;
    height: 5rem;
    margin: 0 1em;
    float: left;
    background: #fff;
    border-radius: 50%;
  }

  svg {
    color: #0097e6;
    font-size: 2.5rem;
  }
}
</style>
