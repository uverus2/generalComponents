<template>
  <button > {{hello}} </button>
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