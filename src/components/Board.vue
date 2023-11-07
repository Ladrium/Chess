<template>
	<main class="flex">
		<div v-for="i in 8" class="flex-row">
			<Tile v-for="j in 8" :type="(i + j) % 2" :key="i" />
		</div>
	</main>
</template>
<script setup lang="ts"></script>
<style></style>
