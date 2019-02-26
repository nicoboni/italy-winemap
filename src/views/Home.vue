<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <Italy/>
  </div>
</template>

<script>
// @ is an alias to /src
import Italy from '@/components/Italy.vue'

export default {
  name: 'home',
  components: {
    Italy
  }
}
</script>
