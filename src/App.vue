<template>
  <!-- <p v-if="show" class="text">{{text}}</p>
    <button @click="showText" class="showBtn">show</button> -->
  <SignupForm></SignupForm>
</template>

<script>
import SignupForm from './components/Signup-form.vue'

export default {
  name: 'App',
  components: { SignupForm },
  data() {
    return {
      // text: 'Hello World',
      // show: false
    }
  },

  methods: {
    // showText() {
    //   this.show = !this.show
    //   // console.log(this.show)
    // }
  }
}
</script>

<style scoped></style>
