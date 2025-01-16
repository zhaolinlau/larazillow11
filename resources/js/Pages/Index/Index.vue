<script setup>
import { Link } from '@inertiajs/vue3'
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