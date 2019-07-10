<template>
	<div>
		hello ,info!
		<button type="button" @click="add()">添加</button>
	</div>
</template>

<script>
	import store from '@/store'
	export default{
		name:"Info",
		methods:{
			add (){
				console.log("111111");
				store.commit('increase')
			}
		}
	}
</script>

<style>
</style>
