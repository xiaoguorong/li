<template>
	<div class="index">
		<section></section>
		<div class="add_btn"></div>
	</div>
</template>

<script>
export default {
  name: 'Index',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style scoped>
section{
	background:url('./../../image/banner.png');
	background-size:100% 100%;
	width:100vw;
	height:102.906vw;
}
.add_btn{
	width:25vw;
	height:25vw;
	border-radius: 50%;
	border:2px solid #CDCAD0;
	position:fixed;
	bottom:25px;
	left:0;
	right:0;
	margin:auto;
	background:#D7D3DB;
}
</style>
