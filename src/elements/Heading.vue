<template>
  <h1>
    <slot/>
  </h1>
</template>

<script>
  export default {
    name: 'Heading'
  }
</script>

<style lang="scss" scoped>
  h1 {
    line-height: $line-height-heading;
    color: $color-primary-rich-black;
    font-size: $font-size-xx-large;
    font-family: $font-primary;
    margin: 0 0 $space-small;
    letter-spacing: -1px;
    font-style: normal;
    font-weight: 700;
  }
</style>

<docs>
  ```jsx
  <heading>The quick brown fox</heading>
  ```
</docs>