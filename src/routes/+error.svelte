<script lang="ts">
	import { page } from '$app/state';
	import MainPanel from '$lib/components/MainPanel.svelte';
</script>

<MainPanel title="ERROR.md">
	{#if page.status === 404}
		<div class="border-b border-b-border py-2 text-2xl font-bold">error: 404</div>
		<div class="py-2 text-text-soft">page not found, sorry!</div>
	{:else}
		<div class="border-b border-b-border py-2 text-2xl font-bold">error: ${page.status}</div>
		<div class="py-2 text-text-soft">{page.error?.message}</div>
	{/if}
</MainPanel>
