<template>
	<div id="app">
		<h1 class="greeting">{{msg}}</h1>
		<span>挨拶</span>
	</div>
</template>
<script>
// import Mymodel from 'my-model.vue'

export default {
 data:function(){
		return {
			msg:'hello'
	}
 }
}
</script>
<style scoped>
.greeting {
	color: #000000;
}
</style>
<style>
.greeting + span {
	background: red;
}
</style>
