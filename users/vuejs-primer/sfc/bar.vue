<template>
<div class="bar">
	<h1 class="header">これはbarです</h1>
	<p>fooを読み込む</p>
	<foo />
</div>
</template>
<script>
import Foo from './foo'
export default {
	components: {
		Foo
	}
}
</script>
<style scoped>
.bar {
	border: 1px solid green;
	margin: 5px;
	padding: 5px;
}
.header {
	color: green;
	font-size: 26px;
}
</style>
