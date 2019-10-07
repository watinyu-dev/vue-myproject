<template>
  <div>
    <MyHeader></MyHeader>
    <div class="content">
    <b-jumbotron header="BootstrapVue" lead="Bootstrap v4 Components for Vue.js 2">
    <p>For more information visit website</p>
    <b-button variant="primary" href="#">More Info</b-button>
    </b-jumbotron>
    </div>
    <MyFooter></MyFooter>
  </div>
</template>

<script>
import MyHeader from './MyHeader'
import MyFooter from './MyFooter'

export default {
  name: 'HelloWorld',
  components: {
    MyHeader,MyFooter
  },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.main {
  margin-top: 0 !important;
}
</style>
