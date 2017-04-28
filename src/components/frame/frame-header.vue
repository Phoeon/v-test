<template>
	<header class="frame-header">
		<a :href="nav.text" v-for="nav in topNavs">{{nav.text}}</a>
	</header>
</template>
<script>
	export default {
		name : "FrameTop",
		data(){
			return {
				topNavs : [
				{
					link:"/",
					text:"首页"
				},
				{
					link:"/",
					text:"日记"
				},
				{
					link:"/",
					text:"圈子"
				},
				{
					link:"/",
					text:"安心购"
				},
				{
					link:"/",
					text:"项目"
				},
				{
					link:"/",
					text:"云诊所"
				},
				{
					link:"/",
					text:"App"
				}
			]
			}
		}
	}
</script>
<style scoped>
	.frame-header{
		background-color:#000;
	}
	a{
		color:#fff;
	}
</style>