<template>
  <button > {{hello}}!!s </button>
</template>
<script>
export default{
  props: {
    hello: {
      required: true,
      type: String
    }
  }
}
</script>
<style>
button {
  padding:20px;
}
</style>