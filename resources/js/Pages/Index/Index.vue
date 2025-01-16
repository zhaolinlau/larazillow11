<script setup>
import MainLayout from '../Layouts/MainLayout.vue';
defineProps({
	message: String
})
</script>

<template>
		<div>Index</div>
		{{ message }}
</template>