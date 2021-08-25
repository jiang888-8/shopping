<template>
  <div id="app">
    <my-header/>
    <my-goods/>
    <my-footer/>
  </div>
</template>

<script>
import 'bootstrap/dist/css/bootstrap.css'
import MyHeader from './components/MyHeader.vue'
import MyGoods from './components/MyGoods.vue'
import MyFooter from './components/MyFooter.vue'
export default {
  data () {
    return {

    }
  },

  components: {
    MyHeader,
    MyGoods,
    MyFooter
  },

  created () {

  },

  methods: {

  }
}
</script>

<style scoped>
#app {
  padding-top: 60px;
}
</style>
