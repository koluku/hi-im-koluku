<template>
  <div id="title" class="card">
    <h1>Hi im koluku</h1>
  </div>
</template>

<script>
export default {
  name: "Title"
};
</script>

<style lang="scss">
#title {
  h1 {
    position: relative;
    margin: 0 auto;
    padding: 150px 0;

    &::before {
      position: absolute;
      bottom: 102px;
      left: 10px;
      content: "";
      width: 200px;
      height: 150px;
      background: url("../assets/gopher.png")
    }

    &::after {
      position: absolute;
      bottom: 102px;
      right: 10px;
      content: "";
      width: 200px;
      height: 150px;
      background: url("../assets/python.png")
    }
  }
}
</style>
