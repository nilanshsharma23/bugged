<script lang="ts">
	import flag from '$lib/assets/flag.svg';
	import Button from '$lib/components/Button.svelte';

	const rsvpButton = () => {
		window.open('https://rsvp.hackclub.community/bugged', '_black')?.focus();
	};
</script>

<nav class="flex flex-row items-center justify-between px-8">
	<img src={flag} class="w-40" alt="" />
	<Button onclick={rsvpButton}>RSVP</Button>
</nav>
