<template>
  <div>
    <h1>Test1</h1>

    <cc-intro></cc-intro>
  </div>

</template>

<script>
import CcIntro from './intro.vue'

export default {
  components: {
    CcIntro
  }
}

</script>


<style scoped>
  h1{
    font-size: 50px;
    font-weight: bold;
    color: #f00;
  }

</style>
