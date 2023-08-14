@
<template>
  <div>
    this is child props
    {{ parentmsg }}

    <p>hom nay la ngay: {{ dateProps }}</p>
  </div>
</template>

<script>
export default {
  name: 'ChildComponent',
  props: ['parentmsg', 'dateProps']
}
</script>

<style lang="scss" scoped></style>
