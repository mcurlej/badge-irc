<template>
  <div class="col-md-2 left-pane" id="left-pane">
    {{leftPane}}


  </div>
</template>

<script>
export default {
  name: 'left-pane',
  data () {
    return {
      leftPane: 'left-pane'
    }
  }
}
</script>

<style>
.left-pane {
  height: inherit;
}
</style>
