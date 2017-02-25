<template>
  <div class="col-md-12 message-box" id="message-box">
    {{messageBox}}
    <div class="form-group">
      <label for="message"></label>
      <textarea class="form-control" id="message" name="text" placeholder="Type in your message" rows="5"></textarea>
    </div>
  </div>
</template>

<script>
export default {
  name: 'message-box',
  data () {
    return {
      messageBox: 'message-box'
    }
  }
}
</script>

<style>
</style>
