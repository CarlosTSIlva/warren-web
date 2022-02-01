<template>
    <button :style="{backgroundColor: color}" @click="onClick">{{ texto }}</button>
</template>

<script>
export default {
  name: 'Button',
  props: {
    texto: String,
    color: String,
    onClick: Function
  }
}
</script>

<style scoped>
button {
    background: #EE2E5D;
}
</style>
