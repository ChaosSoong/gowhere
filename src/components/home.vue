<template>
  <div>
  	<home-header></home-header>
  	<home-swiper></home-swiper>
  </div>
</template>

<script>
import homeHeader from './home/header.vue'
import homeSwiper from './home/swiper.vue'
export default {
  name: 'Home',
  components:{
  	homeHeader:homeHeader,
  	homeSwiper:homeSwiper
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
	
</style>
