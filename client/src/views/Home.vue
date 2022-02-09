<template>
  <div class="home">
    <Welcome msg="結婚式スライドショーアプリ"/>
    <img alt="Vue logo" src="../assets/marriage.png">
  </div>
</template>

<script>
// @ is an alias to /src
import Welcome from '@/components/Welcome.vue'

export default {
  name: 'Home',
  components: {
    Welcome
  }
}
</script>
