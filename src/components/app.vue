<template>
  <div id="app" class="container-fluid app">
    <div class="row app">
      <left-pane></left-pane>
      <chat></chat> 
    </div>
  </div>
</template>

<script>
import leftPane from "./left-pane.vue";
import chat from "./chat.vue";

export default {
  name: 'app',
  components: {
    "left-pane": leftPane,
    "chat": chat
  },
  data () {
    return {
      title: 'badge-irc'
    }
  }
}
</script>

<style>
* {
  border-color: red;
  border-width: 5px;
}
html, body {
  height: 100%;
}

.app {
  height: inherit;
}
</style>
