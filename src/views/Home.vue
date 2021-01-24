<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <my-button :msg="msg"></my-button>
  </div>
</template>

<script>
// @ is an alias to /src
import MyButton from '@/components/MyButton.vue'

export default {
  name: 'Home',
  components: {
    MyButton
  },
  data() {
    return {
      msg: 'test'
    }
  }
}
</script>
