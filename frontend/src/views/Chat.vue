<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <top-bar>CHAT.VUE CHAT SELECCIONADO</top-bar>
    <chat-list />
    <!-- <new-chat /> -->
  </div>
</template>

<script>
// @ is an alias to /src
import TopBar from '@/components/TopBar.vue';
import ChatList from '@/components/ChatList.vue';

export default {
  name: 'home',
  components: {
    TopBar,
    ChatList,
  },
};
</script>
