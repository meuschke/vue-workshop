<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <Todos />
  </div>
</template>

<script>
// @ is an alias to /src
import Todos from '@/components/Todos.vue'

export default {
  name: 'home',
  components: {
    Todos
  }
}
</script>
