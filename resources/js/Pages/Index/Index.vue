<script setup>
import MainLayout from '../Layouts/MainLayout.vue';
defineProps({
	message: String
})
</script>

<script>
import MainLayout from '../Layouts/MainLayout.vue'

export default {
	layout: MainLayout
}
</script>

<template>
		<div>Index</div>
		{{ message }}
</template>