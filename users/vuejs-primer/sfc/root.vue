<template>
	<div id="root">
		<h1>rootコンポーネント</h1>
		<p>rootコンポーネントです</p>
		<foo/>
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
<style>
	#root {
		border: 1px solid #000;
		margin: 4px;
		padding:4px
	}
</style>
