@
<template>
  <div>
    Parent component
    <ChildComponent :parentmsg="'xin chao'" :dateProps=date />
  </div>
</template>

<script>
import ChildComponent from './ChildComponent.vue'
export default {
  name: 'ParentComponent',
  components: {
    ChildComponent
  },
  props: {
    parentmsg: String,
    dateProps: Date
  },
  data () {
    return {
      date: new Date().toUTCString()
    }
  }
}
</script>

<style scoped></style>
