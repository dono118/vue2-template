<template>
  <div id="app"
    class="audio">
    <aplayer :audio="audio" />
  </div>
</template>

<script>
export default {
  data() {
    return {
      audio: {
        name: '',
        artist: '',
        url: 'https://files.51voa.cn/202205/scientists-grow-plants-in-dirt-from-moon.mp3',
        cover: 'https://p1.music.126.net/5zs7IvmLv7KahY3BFzUmrg==/109951163635241613.jpg?param=300y300' // prettier-ignore
      }
    }
  }
}
</script>

<style scoped>
.audio {
  margin-top: 50px;
  width: 600px;
}
</style>