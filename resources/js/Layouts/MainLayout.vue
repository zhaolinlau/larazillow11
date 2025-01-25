<script setup>
import { Link, usePage } from '@inertiajs/vue3'
import { computed } from 'vue'

const page = usePage()

const flashSuccess = computed(() => {
	return page.props.flash.success
})

// const x = ref(0)
// const y = computed(() => x.value * 2)
// import { ref } from 'vue'

// const timer = ref(0)

// setInterval(() => timer.value++, 1000)
</script>

<template>
	<Link href="/">Main Page</Link> <br>
	<Link href="/hello">Show Page</Link>
	<!-- <div>The page with time {{ timer }}</div> -->
	<div v-if="flashSuccess" class="success">
		{{ flashSuccess }}
	</div>

	<div>
		{{ y }}
	</div>
	<slot>Default</slot>
</template>

<style scoped>
.success {
	background-color: green;
	color: white;
}
</style>