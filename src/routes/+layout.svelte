<script lang="ts">
	import '../app.css';
	import Navbar from '$lib/components/navbar.svelte';
	let { children } = $props();
</script>

<Navbar />

<style>
	:global(body) {
		background-color: #cbe0a6;
		font-family: Verdana, Geneva, Tahoma, sans-serif
	}
</style>


{@render children()}

