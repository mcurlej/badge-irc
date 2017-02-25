<template>
  <div class="col-md-2 user-list" id="user-list">
    {{userList}}
  </div>
</template>

<script>
export default {
  name: 'user-list',
  data () {
    return {
      userList: 'user-list'
    }
  }
}
</script>

<style>
.user-list {
  height: inherit;
}
</style>
