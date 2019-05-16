<template>
  <div class="App">
    <header></header>
    <nav></nav>
    <main>
      <nuxt />
    </main>
    <aside></aside>
    <footer></footer>
  </div>
</template>

<style lang="scss">
@import './holy-grail.scss';

html {
  background-color: theme('colors.white');
  font-family: theme('fontFamily.sans');
}
</style>
