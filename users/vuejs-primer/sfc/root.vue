<template>
	<div id="root">
		<h1 class="header">Rootです</h1>
		<p>fooとbarを読み込む</p>
		<bar/>
		<foo/>
	</div>
</template>
<script>
import Foo from './foo'
import Bar from './bar'
export default {
	components: {
		Foo,
		Bar
	}
}
</script>
<style>
#root {
	border: 1px solid #000;
	margin: 5px;
	padding: 5px;
}
.header {
	font-size: 30px;
}
p {
	text-decoration: underline;
}
</style>
