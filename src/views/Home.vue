<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <CustomForm msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import CustomForm from '@/components/CustomForm.vue'

export default {
  name: 'Home',
  components: {
    CustomForm
  }
}
</script>
