<template>
  <h1>{{ msg }}</h1>
  <p>Nyob Zoo, This project is open for Pull Requests and Collaboration.</p>
</template>

<script>
export default {
  name: 'HelloWorld',
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
