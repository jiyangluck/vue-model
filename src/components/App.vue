<template>
	<div>	
		<h1>单文件组件</h1>
		<myform></myform>
		<list></list>
	</div>
	
</template>

<script>
	import list from './list.vue';
	import myform from './myform.vue';
	export default {
		components:{list,myform}
	}
</script>