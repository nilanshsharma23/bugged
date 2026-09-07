<script lang="ts">
	import flag from '$lib/assets/flag.svg';
	import NavbarLink from './NavbarLink.svelte';
</script>

<nav class="flex flex-row items-center justify-between border-b border-b-border bg-panel px-32">
	<a href="http://hackclub.com" target="_blank" rel="noopener noreferrer">
		<img src={flag} alt="A Hack Club YSWS" class="h-18" /></a
	>
	<div class="flex flex-row"></div>
	<a
		href="https://rsvp.hackclub.community/bugged"
		target="_blank"
		rel="noopener noreferrer"
		class="cursor-pointer rounded bg-text px-3 py-1 text-panel">RSVP</a
	>
</nav>
<div class="mx-8 my-8 flex flex-col sm:mx-32 md:mx-40 lg:mx-48">
	<div class="flex flex-row gap-2 text-2xl">
		<div class="font-bold">hack-club</div>
		<div class="text-text-soft">/</div>
		<div class="font-bold">bugged</div>
	</div>
	<div class="text-md text-text-soft">
		A YSWS for bugs nobody's fixing, intentionally. Public. Read-write. Never Fixed.
	</div>
	<div class="text-md flex flex-row gap-4 border-b border-b-border py-4">
		<div class="flex flex-row gap-1">
			<div class="font-bold">128</div>
			<div class="text-text-soft">shipped</div>
		</div>
		<div class="flex flex-row gap-1">
			<div class="font-bold">0</div>
			<div class="text-text-soft">fixed (by design)</div>
		</div>
		<div class="flex flex-row gap-1">
			<div class="text-text-soft">just the</div>
			<div class="font-bold">2</div>
			<div class="text-text-soft">of us</div>
		</div>
	</div>
	<div class="flex flex-row gap-4 border-b border-b-border pt-4">
		<NavbarLink route="/">README</NavbarLink>
		<NavbarLink route="/ships">Pull Requests</NavbarLink>
		<NavbarLink route="/shipping-guide">Shipping Guide</NavbarLink>
		<NavbarLink route="/faq">FAQ</NavbarLink>
	</div>
</div>
