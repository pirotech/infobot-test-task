<template>
  <div class="app">
    <router-view/>
  </div>
</template>

<style lang="scss">
// reset styles
.app {
  width: 100%;
  min-height: 100vh;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}

html,
body,
div,
header,
main,
ul,
li,
ol,
p,
span,
h1,
h2,
h3,
h4,
h5,
h6,
button,
input,
textarea {
  margin: 0;
  padding: 0;
  list-style: none;
  box-sizing: border-box;
  outline: none;
}
</style>
