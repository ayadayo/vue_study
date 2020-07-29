<template>
	<div class="bar">
		<h1 class="header">これはbar.vue</h1>
		<foo class="header" />
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
		border: 1px solid #000;
		margin: 4px;
		padding: 4px;
	}
	.header {
		font-size: 14px;
	}
</style>
