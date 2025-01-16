<script setup>
import MainLayout from '../Layouts/MainLayout.vue';
defineProps({
	message: String
})
</script>

<template>
	<MainLayout>
		<div>Index</div>
		{{ message }}
	</MainLayout>
</template>