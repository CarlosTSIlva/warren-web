<template>
    <button @click="onClick"><b>{{ texto }}</b></button>
</template>

<script>
  export default {
    name: 'Button',
    props: {
      texto: String,
      onClick: Function
    }
  }
</script>

<style scoped>
button {
  background: #EE2E5D;
  cursor: pointer;
}

.buttonBlack {
  background: #2F2F33;
}
</style>
