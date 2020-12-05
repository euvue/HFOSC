<template>
  <h1>{{ msg }}</h1>
  <p>About Us</p>
  <p>.</p>
</template>

<script>
export default {
  name: 'About_Us',
  props: {
    msg: String
  },
  data() {
    return {
      count: 0
    }
  }
}
</script>
