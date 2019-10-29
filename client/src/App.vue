<template>
  <div id="app">
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
      <a id="main_title" class="navbar-brand" href="#/">Community Message Board</a>
    </nav>
    <router-view class="container"/>
  </div>
</template>

<style scoped>
#main_title{
  font-size: 6vw;
  font-family: cursive;
  color: mediumseagreen;
}
</style>
