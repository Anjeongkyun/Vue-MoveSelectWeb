<template>
  <div id = "app">
    <SignUpHeader></SignUpHeader>
    <SignUpInput></SignUpInput>
    <SignUpFooter></SignUpFooter>
  </div>
</template>

<script>
import SignUpHeader from './components/signup/SignUpHeader.vue'
import SignUpInput from './components/signup/SignUpInput.vue'
import SignUpFooter from './components/signup/SignUpFooter.vue'

export default {
    components: {
    'SignUpHeader' : SignUpHeader,
    'SignUpInput' : SignUpInput,
    'SignUpFooter' : SignUpFooter,
  }
}
</script>


<style scoped>

</style>