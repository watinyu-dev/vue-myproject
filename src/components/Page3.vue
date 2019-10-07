<template>
  <div>
    <b-container class="bv-example-row">
    <MyHeader></MyHeader>
    {{ msg }}
    <MyFooter></MyFooter>
    </b-container>
  </div>
</template>

<script>
import MyHeader from './MyHeader'
import MyFooter from './MyFooter'

export default {
  name: 'Page3',
  components: {
    MyHeader,MyFooter
  },
  data () {
    return {
      msg: 'Page 3'
    }
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
