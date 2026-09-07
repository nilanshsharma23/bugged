<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';
	import Navbar from '$lib/components/Navbar.svelte';

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>
<Navbar />

<div class="mx-8 mb-8 flex flex-col gap-4 sm:mx-24 md:mx-32 md:flex-row md:gap-6 lg:mx-40">
	{@render children()}
</div>
