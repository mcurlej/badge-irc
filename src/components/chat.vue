<template>
  <div class="col-md-10 chat" id="chat">
    <div class="row chat-window">
      <chat-window></chat-window>
      <user-list></user-list>
    </div>
    <div class="row message-box">
      <message-box></message-box>
    </div>
  </div>
</template>

<script>
import chatWindow from "./chat-window.vue";
import messageBox from "./message-box.vue";
import userList from "./user-list.vue";

export default {
  name: 'chat',
  components: {
    "chat-window": chatWindow,
    "message-box": messageBox,
    "user-list": userList
  },
  data () {
    return {
      chat: 'chat'
    }
  }
}
</script>

<style>
.chat {
  display: flex;
  flex-direction: column;
  height: inherit;
}

.chat-window {
  flex: 1 1 auto;
  height: inherit;
}

.message-box {
  flex: 0 1 50px;
}
</style>
