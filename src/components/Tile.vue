<template>
	<div
		id="tile"
		:class="`h-20 w-20 ${type ? 'bg-yellow-950' : 'bg-slate-400'}`"
	></div>
</template>
<script setup lang="ts">
	defineProps<{
		type: number;
	}>();
</script>
