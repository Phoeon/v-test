<template>
   <div class="content-zone">
   		<h2>{{msg}}</h2>
	   <div class="logo-wrap">
	   		<img src="../../assets/logo.png">
	   </div>
   </div>
</template>
<script>
	export default {
		name : "Hello",
		data(){
			return {
				msg : "Hello world !",
				logo : ""
			}
		}
	}
</script>

<style lang="less">
	.content-zone{
		text-align: center;
	}
</style>