<template>
  <div class="homeheader">
  	<div class="left">返回</div>
  	<input type="text" placeholder="请输入搜索内容">
  	<div class="right">城市</div>
  </div>
</template>

<script>
export default {
  name: 'homeHeader',
  data () {
    return {
      
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
.homeheader {
	height: .86rem;
	display:flex;
	background:#00bcd4;
		.left {
			width:.84rem;
			float:left;
			line-height:.84rem;
			text-align:center;
		}
		input {
			flex:1;
			line-height:.64rem;
		}
		.right {
			float:right;
			width:1.12rem;
			line-height:.84rem;
			text-align:center;
		}
}
</style>
