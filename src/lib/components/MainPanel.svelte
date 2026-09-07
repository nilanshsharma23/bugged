<script lang="ts">
	let { title, children } = $props();
</script>

<div class="flex h-full w-full flex-col rounded-lg border border-border bg-panel">
	<div class="border-b border-b-border px-4 py-2 font-mono text-text-soft">{title}</div>

	<div class="flex flex-col px-6 py-4">
		{@render children?.()}
	</div>
</div>
