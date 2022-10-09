<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    7788
    <button type="button"
            @click="getData">
      23
    </button>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  },
  methods: {
    // getData () {
    //   const api = 'https://min-api.cryptocompare.com/data/pricemulti?fsyms=BTC,ETH,LINK&tsyms=CNY,USD'
    //   this.$http.get(api)
    //     .then((res) => {
    //       console.log(res)         
    //     })
    // },
    // getProducts () {
    //   const url = `https://vue3-course-api.hexschool.io/api/kelvinlin9/products/all`
    //   this.$http.get(url)
    //     .then((res) => {
    //       console.log(res)
    //     })
    // },
  }
}
</script>
