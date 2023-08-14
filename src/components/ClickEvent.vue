@
<template>
  <div>
    <h1>Click Event</h1>
    <button v-on:click="count++">You clicked me {{ count }} times.</button>
  </div>
</template>

<script>
export default {
  name: 'ClickEvent',

  data () {
    return {
      count: 0
    }
  }
}
</script>

<style scoped></style>
