<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/icon.svg';
	import Navbar from '$lib/components/Navbar.svelte';
	import Footer from '$lib/components/Footer.svelte';

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>
<Navbar />

<div class="mx-4 mb-8 flex flex-col gap-4 sm:mx-24 md:mx-32 md:flex-row md:gap-6 lg:mx-40">
	{@render children()}
</div>

<Footer />
