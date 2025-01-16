<script setup>
import { Link } from '@inertiajs/vue3'
</script>

<template>
	<Link href="/">Main Page</Link> <br>
	<Link href="/hello">Show Page</Link>
	<slot>Default</slot>
</template>