<template>
	<div id="root">
		<h1>rootコンポーネント</h1>
		<p>rootコンポーネントです</p>
		<foo class="test" />
		<bar class="test" />
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
		margin: 4px;
		padding:4px
	}
</style>
