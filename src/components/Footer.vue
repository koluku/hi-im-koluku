<template>
  <div class="card">
    <img src="../assets/qr.png" alt="">
    <small class="copyright"><span class="mark">©</span> 2019 <a href="https://twitter.com/koluku">koluku</a></small>
  </div>
</template>

<script>
export default {
  name: "Footer"
};
</script>

<style lang="scss">
.copyright {
  display: block;
  font-size: 0.9rem;
  text-align: center;

  a {
    color: #222;
    text-decoration: none;
  }
}

.mark {
  font-size: 1.5rem;
}
</style>
